# ETF_Crawler
## 目的
> 從證交所爬取ETF每日歷史資料，包括開盤價、收盤價、高點、低點、成交量。
## 工具
> `python` `BeautifulSoup`
## 程式
> get_webmsg (year, month , day) : 發送request來取得回應，並做data的預先處理。  
> write_csv(directory,filename,smt) : 將data寫入CSV檔。  
> makedirs (year, month) : 檢查是否有對應的資料夾存放檔案，若無則創建。  
> random_time() : 產生time.sleep需要的隨機時間。  
