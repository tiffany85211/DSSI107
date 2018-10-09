# Policy
* R語言教學部份共包含6至7次的作業。每項作業2~3分不等，著重在練習、複習、不刁難。因此請按時完成作業。
* 作業繳交時間統一為次週上課前一天晚上23:59，逾期分數乘以80%。**逾期一週該項以零分記，不得補交**。

# Assigment #1 (2 points) No later than 09/30 23:59

* 繳交方式：請上傳完成Datacamp introduction to R的screenshop，或者上傳你完成期初R能力測驗的docx檔。
* 先用[期初R能力測驗](https://docs.google.com/document/d/1EFIz1LrYt2d4ExcZXj1VPGPSJHvgUvs1c8yusAZAbsk/edit?usp=sharing)測測看你到底會不會R，完成不了就請把[datacamp: Introduction to R](https://github.com/R4CSS/Assignments/blob/master/01DataCamp.md)做完，下週上課前請上傳其中一項。
* 申請一個datacamp帳號，並將自己的Datacamp帳號填入[這個問卷](https://goo.gl/forms/sfTBquz3tWldyVCU2)**（問卷會在三天內關閉，務必一下課馬上申請）**。 

# Assignment #2 No later than 10/07 23:59 (3 points)

* 繳交方式：統一上傳.rmd檔案與.rmd檔案所generate出來的.nb.html或.html兩個檔案（務必成功generate出其中一種.html檔）。將兩個檔案壓縮後上傳。如果不會操作R markdown可以參考這個[影片說明](https://youtu.be/xVXUZShYfEI)。
* 完成課堂R01_2 vector.Rmd與R01_4 dataframe tp theft.Rmd最末的練習。請務必用R notebook或R Markdown編寫，助教屆時將會優先看.html檔，沒有成功編譯成.html檔的會扣分。
* 下載R01_5prac load and summarize tweet data.Rmd，練習完，並嘗試對這筆資料做點分析，並提出你的發現。
```{r}
x.a <- rnorm(1000, 1, 10)
# 1.1 Filter out extreme values out of two standard deviations
a1 <- x.a[!abs(x.a - mean(x.a)) > 2*sd(x.a)]

# 1.2 Plotting the distribution of the remaining vector x.a
# 1.3 Calculate the 25% 50% and 75% quantile of vector x.a. You may google "quantile r"
# 1.4 Get the number between 25% to 75% and assign to x.a1
# 1.5 Plotting x.a1
x.b <- c("a", "b", "c", "d", "e", "f", "g", "h", "i", "j", "k")
# 2.1 Get only elements at odd positions and assign to x.b1
x.b1 <- x.b[(1:length(x.b)) %% 2 == 1]

# 2.2 Truncate the first 2 elements and the last 2 elements and assign to x.b2
```
# Assignment #3 No later than 10/14 23:59 (3 points)

請在下列三題中選兩題做：
* 第一題：在Paid maternity leave的練習中，我們繪製了最後調查年代為level 5的兩張不同國家長條圖。請嘗試修改程式碼，畫出level 4的那兩張長條圖。
* 第二題：下載或直接讀取[空氣品質資料](https://taqm.epa.gov.tw/taqm/aqs.ashx?lang=tw&act=aqi-epa&ts=1538931940046)，並依照**R02_3 read json ubike.Rmd** 的方法繪製空氣品質地圖。上色應依照空氣品質監測網的上色方式。
* 第三題：讀取以下資料集中的任一個並轉成Data.frame（當然是json檔，不然csv編錯還得了）
  * 違規藥品廣告資料(https://data.gov.tw/dataset/14196)
  * 違規化妝品廣告資料（https://data.gov.tw/dataset/14198）
  * 健康食品資料集（https://data.gov.tw/dataset/6951)

