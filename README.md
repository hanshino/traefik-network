此專案用於快速架設 `nginx_proxy` ，並且使 `LetsEncrypt` 提供服務，提供自己快速進行憑證簽定，並且將 `domain` 導引至此服務，再進行服務分流

# 安裝方式

## 初始化(第一次執行)
```bash
bash init.sh
```

## 啟動
```bash
docker-compose up -d
```