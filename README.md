# Whistle 搭配 SwitchyOmega

## 安裝 [Whistle](https://github.com/avwo/whistle) (需安裝 node.js)

```bash
npm install -g whistle
```

## 主要指令

- Run (ctrl + C 停止運行)

```bash
w2 run
```

- Start

```bash
w2 start
```

- Stop

```bash
w2 stop
```

## 安裝[SwitchyOmega](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif?hl=zh-TW)

## 執行步驟

- 配置 SwitchyOmega
- 新增一個情境模式
- 瀏覽器代理到 Whistle

| 網址協議 | 代理協議 | 代理伺服器 | 連接埠 |
| -------- | -------- | -------- | -------- |
| (預設) | HTTP | 127.0.0.1 | 8899 |

- 執行 `w2 start`
- 在 Rules 按下 Create 新增一個規則
- 設定規則
- 【替換地址】【被替換的地址】

```
https://github.com https://google.com
```

- Chrome 右上角 plugin SwitchyOmega 選取剛剛新增的情境
