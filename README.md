# OBSCLOCK
https://cdn.jsdelivr.net/gh/ChengJenLi/OBSCLOCK/clock.html
https://cdn.jsdelivr.net/gh/user/repo@version/file




###  說明
A script for OBS Studio (https://obsproject.com/) to embed a current date and timestamp. No other softwares and plugins are needed. Just OBS Studio and the built-in Browser Source input.

這代碼是為了在OBS Studio中嵌入現在的日期和時間而寫的。而且不需要安裝其他軟件或插件即可使用，只需要OBS Studio和原生的Browser Source輸入。

For usage, please see this video:
具體用法請參看這短片:
https://youtu.be/wVbP8GQTLG8

### 範例

- Vanilla

`[https://cdn.rawgit.com/sam0737/a0ee8ca253fc5c84b2aa2ac018f7b8ad/raw/108196e17c2c9d79ff60ed3bf788973ab94da9af/clock.html](https://cdn.jsdelivr.net/gh/ChengJenLi/OBSCLOCK/clock.html)`

- White text
`[https://cdn.rawgit.com/sam0737/a0ee8ca253fc5c84b2aa2ac018f7b8ad/raw/108196e17c2c9d79ff60ed3bf788973ab94da9af/clock.html](https://cdn.jsdelivr.net/gh/ChengJenLi/OBSCLOCK/clock.html)?style=font:bold 30px monospace; color: white;`

- Rounded rectangle
`[https://cdn.rawgit.com/sam0737/a0ee8ca253fc5c84b2aa2ac018f7b8ad/raw/108196e17c2c9d79ff60ed3bf788973ab94da9af/clock.html](https://cdn.jsdelivr.net/gh/ChengJenLi/OBSCLOCK/clock.html)?style=font: bold 30px monospace; color: lightgray; display: inline-block; border-radius: 5px; padding: 2px 5px; background-color: rgba(0, 0, 0, 0.5);`

- With US date formatting
`[https://cdn.rawgit.com/sam0737/a0ee8ca253fc5c84b2aa2ac018f7b8ad/raw/108196e17c2c9d79ff60ed3bf788973ab94da9af/clock.html](https://cdn.jsdelivr.net/gh/ChengJenLi/OBSCLOCK/clock.html)?style=font: bold 30px monospace; color: lightgray; display: inline-block; border-radius: 5px; padding: 2px 5px; background-color: rgba(0, 0, 0, 0.5)&format=MMM DD YYYY HH:mm:ss;`

### 參數
Use style to add more style to the output element
While bodyStyle for the style to the body element
Use format to control the date format. For the syntax, see https://momentjs.com/docs/#/displaying/format/

原作者：https://gist.github.com/sam0737/a0ee8ca253fc5c84b2aa2ac018f7b8ad
