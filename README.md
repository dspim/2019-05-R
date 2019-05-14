
## 課程大綱

1. [環境與基本語法](R-Installation-Basic/R-Installation-Basic.html)
2. 資料處理-非結構化
3. 資料處理-半結構化
4. 資料處理-結構化
5. 資料處理-整合
6. 視覺化-1
7. 視覺化-2
8. 報表製作

## 行前通知

本次活動包含專題講座與個人實務操作，為了讓各位可以順利學習R語言，請各位參加準備下列工具：

(1) 自備可以無線上網的筆記型電腦，建議使用下列作業系統：

- Windows 7 或以上，並且使用者名稱或家目錄的路徑不包含中文
    - 否則Rstudio會無法運作
    - 可以在R 中輸入 `tempdir()` 檢查有無亂碼或中文。若有，則Rstudio會無法運作。
    - 如果使用者有包含中文，可以：
        1. 建立不包含中文的新帳號
        2. 參考 <https://github.com/wush978/DataScienceAndR/wiki/Windows%E4%B8%AD%E6%96%87%E4%BD%BF%E7%94%A8%E8%80%85%E8%88%87Rstudio%E7%9A%84%E7%92%B0%E5%A2%83%E8%AE%8A%E6%95%B8%E8%AA%BF%E6%A0%A1> 做環境變數的修改。（較不建議，可能對其他程式造成影響）
- Mac OS X 10.9 或以上
- Ubuntu 14.04 或以上

(2) 在課程開始前下載並安裝 R (R-3.4.2 版本，Windows 上不建議安裝最新版，會遇到RSQLite套件在中文上的bug)

- 下載網址:
    - Windows: <https://mran.revolutionanalytics.com/snapshot/2017-10-12/bin/windows/base/R-3.4.2-win.exe>
    - Mac OS X: <https://mran.revolutionanalytics.com/snapshot/2017-10-12/bin/macosx/R-3.4.2.pkg>
    - Linux: <https://cran.r-project.org/bin/linux>

(3) 在課程開始前下載並安裝 RStudio (1.1.383 以上版本)
    下載網址:
    <https://www.rstudio.com/products/rstudio/download/#download>

(4) 參考 R語言翻轉教室 的安裝說明 <https://datascienceandr.org/install> ，利用以下的指令安裝 R語言翻轉教室

```r
source("https://wush978.github.io/R/init-swirl.R")
```

- 安裝後可以自行嘗試完成 `DataScienceAndR` 課程的 `00-Hello-DataScienceAndR` 單元。如有錯誤可以在上課當天詢問講師或教練。

(4) 本次課程的投影片網址：

<https://dspim.github.io/2019-05-R/>

![](qrcode.png)

目前還在建置中，投影片還未開放下載
