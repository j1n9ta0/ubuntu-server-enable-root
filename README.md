Ubuntu 24 的自动安装（automatic‑ubiquity）已不再支持 preseed；

要启用 root 并禁止其他用户创建，关键在于省略 identity、同步写 user-data；

只创建 root、清空 users 列表、设置 SSH 密码允许登录和 debconf 强制允许 root 登录；

同时务必要评估安全性，并在生产环境慎用。
