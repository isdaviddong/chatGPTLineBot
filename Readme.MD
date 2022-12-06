chatGPLineBot
===
1. 於底下位置申請 openAPI key:
https://beta.openai.com/account/api-keys

請置換程式碼中的key與token即可，分別位於:  
/Controllers/ChatGPT.cs 22行(使用 openAPI key)  
![](https://i.imgur.com/N5k9bNt.png)

/Controllers/LineWebHookController.cs 16,21行 (使用你應該很熟的 LINE Bot Token)  
![](https://i.imgur.com/mynmuCV.png)

執行結果:  
![](https://i.imgur.com/v6Shjgk.png)

### OpenAI參考文件:  
https://beta.openai.com/docs/api-reference/completions/create
