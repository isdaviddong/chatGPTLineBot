ChatGP LINE Bot
===
1. 於底下位置申請 openAPI key:
https://beta.openai.com/account/api-keys

請置換程式碼中的key與token即可，分別位於:  
/Controllers/ChatGPT.cs 22行(使用 openAPI key)  
![](https://i.imgur.com/N5k9bNt.png)

/Controllers/LineWebHookController.cs 16,21行 (使用你應該很熟的 LINE Bot Token, 如果不熟, 請參考 https://github.com/isdaviddong/HOL-LineBotSDK )  
![](https://i.imgur.com/mynmuCV.png)

2. 建置後使用 NGROK 測試 或 佈署到正式網站
3. 配置 LINE WebHook

執行結果:  
![](https://i.imgur.com/v6Shjgk.png)

### OpenAI參考文件:  
https://beta.openai.com/docs/api-reference/completions/create
