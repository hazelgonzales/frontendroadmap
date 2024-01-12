https://www.bfa.com.tw/blog/color-palettes-for-powerful-slides-1

Avoid enormous network payloads 

Serve static assets with an efficient cache policy 

Ensure text remains visible during webfont load

Page prevented back/forward cache restoration

Minimize main-thread work 

Avoid an excessive DOM size 

Reduce JavaScript execution time 

https://developer.chrome.com/docs/lighthouse/performance/unused-javascript/?utm_source=lighthouse&utm_medium=devtools
輔助完善前端項目交接流程
模擬交接: 
制定交接進程安排計畫表 
列舉交接进度核对表细项 
編寫交接考核題目 
確定流程方案: 
制定前端新人培養方案 
資料整理: 
 採用階段式進階學習模式
 附以多格式資料文檔參考
 通過作業形式檢驗學習成果
2021年开始一直在ReportEase项目组进行前端开发，
2022年初开始着手设计品质项目，与其他三位前端开发多人协作的模式。接着担任ReportEase的前端DRI
主要完成根据需求进行并实现UI、交互设计，
到了2022年底 
業務梳理  
2023RD HC 
Vue2 升级Vue3 
代碼 優化 

當前APP 跨團隊 擴展 合作 
ReportEase 性能优化
數據體量大
 頁面卡頓並報錯
引發數據丟失 
耗时⻓、
耗时波动性较大
重點優化
合并超大量數
據時一直卡頓
合并文件后偶爾 出現數據丟失 


在逻辑优化方面主要采取了ECRS分析法，例如取消，排查到PASS数据占了大部分内存，由于不是PASS中所有内容都是有用的，所以对PASS信息进行整合，减少了PASS数据在系统占用的大部分内存。

* 优化了CSS和JavaScript文件，压缩合并减少请求次数
* 引入CDN加速静态资源，减轻服务器负担
* 通过优化代码逻辑，减少重绘和重排，提升用户体验
* 实施前端缓存策略，减少数据请求频率
* 压缩和合并CSS和JavaScript文件
* 实施前端缓存策略
启用文本 gzip打包 压缩 

整合 ReportEase UI、交互到 IPA ，並行進行新功能開發 
使用 IPA studio 開發平台並適應雙線模式開發流程 用戶能在 IPA 平台生成目前的報告格式 每個季度匯報功能整合百分比，每天英語學習打卡 
推動並落地部門項目管理系統
參考 PingCode 的 Ship、Project、Testhub、Goals 板塊 覆蓋研發管理全流程，提高各種可視化報表 每個月完成一個模塊 
https://xqg5v9.aitianhu1.top/#/chat/1002
