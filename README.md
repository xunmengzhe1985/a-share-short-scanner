# A股短线选股系统 GitHub Pages 部署

这个目录用于 GitHub Pages 静态部署。

- `index.html` 是加密解锁页，不包含明文业务网页源码。
- 访问者输入正确访问密码后，浏览器本地使用 PBKDF2 + AES-GCM 解密网页。
- GitHub Pages 是静态托管，不提供服务端密码校验；不要把任何账号登录密码当作访问密码。
