# Docker for PHP + Nginx + Mysql5.7

## 設定步驟

1. 將資料夾內容複製到要run的專案
```
$ cp -r <下載路徑>/docker-php-nginx-mysql5.7/ <你的專案路徑>
```

2. 將 `docker-compose.yml` 和 `./php-nginx/nginx/conf.d/nginx.conf` 中的必要參數帶入

3. 執行Container
```
$ docker-compose up -d
```

## 參考資料
https://www.pascallandau.com/blog/structuring-the-docker-setup-for-php-projects/