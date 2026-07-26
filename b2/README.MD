## alist-b2-proxy.js

针对私有的B2桶，无需绑卡

环境变量: 

- **ALLOW_LIST_BUCKET** = false
- **B2_APPLICATION_KEY** = 应用秘钥 applicationKey
- **B2_APPLICATION_KEY_ID** = 应用 keyID
- **B2_ENDPOINT** = 端点地址（如 s3.us-west-004.backblazeb2.com）
- **BUCKET_NAME** = 桶名（如 123abc）
- **PATH_PREFIX** = alist前缀名（如 /B2）
- **ALIST_TOKEN** = alist TOKEN

部署到CF workers后填入`Alist-存储-设置-下载代理网址`
