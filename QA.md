# R notebook無法儲存

R Notebook 要存檔的時候檔名絕對不要有空白，若有空白就用底線_代替，否則Notebook寫到一半會無法預覽下半部的程式並出現錯誤訊息。若仍然無法儲存或出現錯誤訊息，應該只要開另外一個R Notebook檔案，複製程式碼即可。

# Mac: 開啟RStudio遇到以下警告訊息
During startup - Warning messages:
1: Setting LC_CTYPE failed, using "C"
2: Setting LC_COLLATE failed, using "C"
3: Setting LC_TIME failed, using "C"
4: Setting LC_MESSAGES failed, using "C"
5: Setting LC_PAPER failed, using "C"
[R.app GUI 1.50 (6126) x86_64-apple-darwin9.8.0]

WARNING: You're using a non-UTF8 locale, therefore only ASCII characters will work. Please read R for Mac OS X FAQ (see Help) section 9 and adjust your system preferences accordingly. [History restored from /Users/nemo/.Rapp.history]
解決方法參考：https://stackoverflow.com/questions/9689104/installing-r-on-mac-warning-messages-setting-lc-ctype-failed-using-c
Open Terminal
Write or paste in: defaults write org.R-project.R force.LANG en_US.UTF-8
Close Terminal
Start R	
在RStudio的View會看見中文亂碼。 
Sys.setlocale(category = "LC_ALL", locale = "UTF-8")
Sys.setlocale(category = "LC_ALL", locale = "cht")
如果讀取到資料有中文的話，可能會看到以下的情形。此時，你只需要指定locale為cht，然後重開該data.frame就可以解決該問題。

Sys.setlocale(category = "LC_ALL", locale = "cht")
但你在寫程式剖析HTML時若使用了rvest這個套件，有可能在html_node()函式時會因為編碼而產生問題，此時你會需要把locale改為C。這個C指的是C語言的C。
Sys.setlocale(category = "LC_ALL", locale = "C")
參考連結：http://psmethods.postach.io/post/ru-he-geng-gai-rde-yu-she-yu-xi
參考連結：https://stat.ethz.ch/R-manual/R-devel/library/base/html/locales.html
The locale describes aspects of the internationalization of a program. Initially most aspects of the locale of R are set to "C" (which is the default for the C language and reflects North-American usage)
