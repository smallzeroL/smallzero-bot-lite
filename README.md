# smallzero-bot-lite版本

不會Code,卻想要自己做一個Discord Bot然後跟朋友裝自己超牛?

這個Bot不失為一種好方案!

拿著Bot Token,點幾下滑鼠就能用!

說明都是中文,不怕看不懂!

不須寫一行代碼,只需要安裝環境!(附腳本安裝)

不在顯眼的地方插入自家標示,高度自訂性!

可以用工具顯示自訂狀態!

會依照版本更新越多的指令!


# 使用步驟
1.下載ZIP檔案

1.1.在Discord Developer Portal創建一個Bot(https://discord.com/developers/applications)

1.2.在Bot選項中把Presence Intent、Server Members Intent、Message Content Intent 開啟

3.安裝Python3.12.5(ZIP裡有)

4.配置Token.env檔案(以記事本等文本編輯器開啟)

4.1.Token.env看起來應該像這樣:DISCORD_TOKEN=MTI5OTYzMjEwMDQwNzkwNjMzNQ00000000000000000000000

5.安裝Bot需要的環境配置,用Windows鍵+R跳出執行窗口,在裡面輸入cmd

6.在跳出的窗口中輸入如下的指令

pip install discord

pip install doenv

pip install datetime

pip install hashlib

pip install asyncio

(別問我怎麼那麼多,我編譯後我才發現我import多了💀)


然後打開就可以用了w
