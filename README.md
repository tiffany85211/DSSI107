# https://github.com/P4CSS/DSSI107

# DSSI107 R Part

* Instructor: Hsieh, Ji-Lung 謝吉隆, Graduate Institute of Journalism, NTU. jerryhsieh(@)ntu.edu.tw
* Course assistants:
* [Youtube Video for review](https://www.youtube.com/playlist?list=PLK0n8HKZQ_VfJcqBGlcAc0IKoY00mdF1B)
* [Q&A 如編碼相關問題](QA.md)
* [Interesting open data](https://github.com/P4CSS/p4css.github.io/blob/master/data.md)

# Announce
* [謝舒凱老師的投影片和ipynb](https://github.com/lopentu/BestPracticeInCorpusProgramming/tree/master/%E8%AA%9E%E6%96%99%E5%BA%AB%E9%96%8B%E6%94%BE%E6%A1%86%E6%9E%B6%E5%8F%8A%E4%B8%8A%E7%B7%9A%E9%83%A8%E7%BD%B2)

## Recommended books

* **[R for data science](http://r4ds.had.co.nz/introduction.html)**
* **[Text mining using r](http://tidytextmining.com/)**
* [Good jiebaR introduction](http://blog.fens.me/r-word-jiebar/)
* http://www.rdatamining.com/
* [Datacamp for R](https://www.datacamp.com/courses/tech:r)
* [Online books made by Bookdown](https://bookdown.org/)


# Announcement
* [A FB page for sharing interesting data science projects to you](https://www.facebook.com/p4css/)
* **HOT! [Open data conference](https://github.com/P4CSS/p4css.github.io/blob/master/img/competition.jpg) for you (Due: 11/30)**

* 因為老師習慣照課程進行更新程式碼或講義，所以**每週上課前務必重新下載或clone本repository**。
* 本門課的教學著重在「怎麼用」程式碼解決問題，所以會略過一些基本資料型態的繁瑣定義或說明。建議初學者務必熟做Datacamp上的練習，過去教學過程中證實相當多同學受益於上課內容和線上內容的對應。也可以自行找一本R的書籍，都是相當好的幫助。

# Calendar

## W2: 09/17 R Basic
* Slide: [Introducion to R for data science](https://docs.google.com/presentation/d/e/2PACX-1vTSSfrUAnwy-mlcA7I3YBj1NeCTZY6z8b--cuyOqtg-p7-GbMmF11JejhGb6sOoogBbaSKMxpYSLcem/pub?start=false&loop=false&delayms=3000)
* Slide: [Installing R and RStudio](https://docs.google.com/presentation/d/e/2PACX-1vSNj-P2-8cJptSy-eRMKXs4eSNgLgeaCHiF22THEDkmijIXaqFA8U67T3Lp-iR0ibXssD-NHUq5DEG2/pub?start=false&loop=false&delayms=3000&slide=id.g27addf16d4_0_67)
* Be sure to submit Assignment #1 to ceiba before the next class(No later than 10/01).

## W4: 10/01 Read CSV to data.frame
* [SlideR01 Basic](https://docs.google.com/presentation/d/1gvWK2qDZuwR7lRrCLfVwfzrMBt1Dw2yFcG8LeoNgLrA/edit?usp=sharing)
* [SlideR02 read_csv](https://docs.google.com/presentation/d/1vzJL2YU-kWKeM66bLxRFrdXLleWC_mbRFhXi-xkDuqM/edit?usp=sharing): Taipei theft, paid maternity leave, ...
* [Assignment #2](https://github.com/P4CSS/DSSI107/blob/master/Assignments.md#assignment-2-no-later-than-1007-2359-3-points)

## W5: 10/08 Read JSON
* [SlideR02 read_csv](https://docs.google.com/presentation/d/1vzJL2YU-kWKeM66bLxRFrdXLleWC_mbRFhXi-xkDuqM/edit?usp=sharing): from Taipie Theft to Paid maternity leave, ...
* [SlideR03. read json](https://docs.google.com/presentation/d/e/2PACX-1vSHPm_O02O1BQotytOXuL6GV4crFSt90Y3Q5AzJ_Od0_ay7WBZT-Wh8Erll-3EbbbsUmaj5LyqhkWek/pub?start=false&loop=false&delayms=3000)
* [Assignment #3](https://github.com/P4CSS/DSSI107/blob/master/Assignments.md#assignment-3-no-later-than-1014-2359-3-points)

## W6: 10/15
* [SlideCrawler01. crawler design](https://docs.google.com/presentation/d/e/2PACX-1vRW84XoB5sFRT1Eg-GrK4smX23qoNkFffz_h8oRU4AIvJAgrrxBn8059_0UeHv_pFBks_Z37vNbLGai/pub?start=false&loop=false&delayms=3000)
* [Assignment #4](https://github.com/P4CSS/DSSI107/blob/master/Assignments.md#assignment-4-try-to-scrape-10-pages-of-one-sites-listed-as-follows)

## W7: 10/22
* [SlideCrawler03. HTML Parser](https://docs.google.com/presentation/d/e/2PACX-1vSGeNG6BcEUNjhZjqo1obJ9bijuMjKJ0WhEva29-AuishNv779rSC0nDShfkR5HcWp4EdlRUBaaiG0M/pub?start=false&loop=false&delayms=3000)
* [Assignment #5](Assignments.md#assignment-5-scraping-news-report) Scraping news website.

## W8: 10/29
* [(Option) SlideR05. ggplot](https://docs.google.com/presentation/d/e/2PACX-1vR0MIoaDm9YaEvop3wYAYHnr5O-kCPtK2AlS9QR8zpgeoCBQCfJ39q55VrK4RvM_UJg18JDQa1I_pgJ/pub?start=false&loop=false&delayms=3000)
* [SlideTM06. dplyr_trump's tweet](https://docs.google.com/presentation/d/e/2PACX-1vRNLWSWiTePNA5tmAhFcbkFWEzfa0LFiG0FENhalVpxz2lG2Z1lZ8pJHacaKHWpnC1SYhR-qxQOnKb7/pub?start=false&loop=false&delayms=3000): Code [R04_2_trump_tweet.Rmd](R04_2_trump_tweet.Rmd)
* [Assignment #6](Assignments.md#assignment-6-challenge) No later than **11/11 23:59**

## W9: 11/05
* [SlideR06. Processing Chinese text](https://docs.google.com/presentation/d/1sdqhlHcFp-2L1Lt7c8NV1m-KX_2o-iSQykDpMlgWZrE/edit?usp=sharing): Code [TM01_demographic_typhoon.Rmd](TM01_demographic_typhoon.Rmd)
* [SlideML08-1: PCA](https://docs.google.com/presentation/d/1QEpBksIPI6jFXqdxGF2cXZnHbi48cP3oPdLJXQGqVFs/edit?usp=sharing): Code 1 [R08_1_PCA_iris.Rmd](R08_1_PCA_iris.Rmd), Code 2 [R08_2_PCA_marraige_equality.Rmd](R08_2_PCA_marraige_equality.Rmd), **Code 3 [R08_3_PCA_citizenMiaoKo.Rmd](R08_3_PCA_citizenMiaoKo.Rmd)**

## W10: 11/12
* [SlideML08-1: PCA](https://docs.google.com/presentation/d/e/2PACX-1vRhbsGGw0xYHisqd9IxqiOJ7iDYic0WjipPEwlI3J8LkaBYokP20oyOlKiGE7lyXBCAhBnBL4harpmV/pub?start=false&loop=false&delayms=3000): Code 3 [R08_3_PCA_citizenMiaoKo.Rmd](R08_3_PCA_citizenMiaoKo.Rmd)
* [Review and Self-learning resource](https://docs.google.com/presentation/d/e/2PACX-1vTlc2NcLyX9YJ_ghkPcB3quEC9FtGeBpDp3RoolUab4MXw6kCqYlJGo_J9H-zsWDApKXX1Y23yy4mqE/pub?start=false&loop=false&delayms=3000)
* [SlideML09: SVM](https://docs.google.com/presentation/d/1intnDw3NkuL3pJoO-qowkCUHUTk8CrF40f3KxOTMneQ/edit?usp=sharing)

# options
* [SlideTM07. Topic modeling](https://docs.google.com/presentation/d/e/2PACX-1vRTSSO_8JuLTK_1OyM9eDrogA-K2fhXQwlKxh1PpRvNavkurCCcKBNftv9MpKGYM6EDXtNnqZvPDdKy/pub?start=false&loop=false&delayms=3000)
* [SlideTM08: word2vec](https://docs.google.com/presentation/d/e/2PACX-1vSaDbagemtALMf0F5CJViNvLUI7U7cGJtelziV5IdKOridKI28DQ85sWWpVa1Y_1G3vH0bkKMAzW-XZ/pub?start=false&loop=false&delayms=3000)



# Images
![data.frame](img/dataframe.png)
---
![counting](img/counting.png)
---
![dplyr](img/dplyr.png)
