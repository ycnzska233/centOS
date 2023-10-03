# Key
|action|key|
|:--:|:--:|
|切換指標（最前）| ctrl+a |
|切換指標（最前）| ctrl+e |

# Command Line
|action|cmd line|
|:--:|:--:|
|變更伺服器名稱|hostnamectl set-hostname ...|
|檢查埠號|net stat tulnpi grep ssh|
|跨裝置複製資料|scp (source) (destination):(filename)|
|跨裝置複製資料夾|scp -r (source) (destination):(filename)|
|查詢說明| man (cmd)|

# Common Command Line with Option
## cat: 显示文件内容
```
cat (option) (file)
```
|option|function||
|:-:|-|-|
|-E|--show-ends|在每行的结尾显示'$'|
|-T|--show-tabs|使用"^I"表示TAB|

## [`tr`](https://wangchujiang.com/linux-command/c/tr.html): 字符替換刪除 ([2023/10/03](/centOS/20231003/ch11-2.md))
```
tr (option) (parm)
```

## [`bc`](https://wangchujiang.com/linux-command/c/bc.html): 運算工具 (2023/10/03)
```
echo (parm) | bc
```
![img](/centOS/20231003/img/14.png)