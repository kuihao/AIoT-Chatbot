Node:
1. Dialogflow: Google 提供的語意分析整合平台，
2. Open Source Database: 提供 api 可以發 request 索取所需資訊
3. Node.js: Javascript Server 將 JavaScript 轉變為後端程式
4. ngrok/ Heroku: DNS Web Server (for Node.js)，使 Node.js 可以對外連線
5. LineChatbot: Line 平台的溝通介面

Communicaton:
- Dialogflow 建立後端語義分析，可以分析 client 輸入的文字訊息，解析其意思，並根據解析出的意義給予對應的回應腳本、發送索取api
- Client <-> Line <-> Dialogflow <-> Node.js <-> Open Source Database (The Movie DB)

Ref.:
1. https://www.slideshare.net/Slideshare/what-to-upload?next_slideshow=1
2. https://ppt.cc/fb3Cbx