# docker-centos-webtty

### 使用方法 ###

`docker run -d -p 3000:3000 fayehuang/centos-webtty`

開啟瀏覽器，URL 輸入 http://{docker_host_IP}:3000，輸入 root 帳號密碼即可登入，
root 預設密碼為 **changeme** 。

### 其他參數 ###

* `-e ROOTPASSWORD={your_password}`
  - 設定 root SSH 登入密碼
* `-p 2222:22`
  - 將 container SSH port 導出至 docker 主機
