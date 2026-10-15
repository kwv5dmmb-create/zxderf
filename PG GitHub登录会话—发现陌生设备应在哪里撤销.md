# PG GitHub登录会话—发现陌生设备应在哪里撤销

GitHub登录会话 ✅【—𝒏𝟏𝟏.𝒎𝒚—】✅｜发现陌生设备应在哪里撤销
新用户注册享新人福利网址：https://𝒏𝟏𝟏.𝒎𝒚/

怀疑 GitHub 账号仍在陌生设备上登录时，应进入个人 Settings 的 Sessions，先分清 Web sessions 与 GitHub Mobile sessions，再针对不认识的会话执行撤销。官方文档把这两类登录设备列在同一设置页；网页会话可展开详情后点 Revoke session，移动端会话在概览中点 Revoke。撤销的是指定登录会话，不等于已经检查了 SSH 密钥、访问令牌或第三方应用授权。

<img src="https://img.imageossbox.com/uploads/2026/10/9770dc3efe9bed2b45a084b0.png" />

## 先辨认会话的类型

从 GitHub 页面右上角头像进入 Settings，在侧栏 Access 区域打开 Sessions。Web sessions 显示网页登录会话，GitHub Mobile sessions 显示通过移动应用登录的设备。核对设备时不要仅凭一个地名或浏览器名称断言盗号；可把近期自己使用的电脑、手机和登录时间逐一对照。对于拿不准的条目，先查看页面提供的详情，再决定是否撤销。

## 撤销后还要查什么

网页会话需要在对应条目下点 See more，再选择 Revoke session；移动应用会话可在 Sessions 概览中撤销。官方特别说明，撤销移动端会话会让该设备上的 GitHub Mobile 退出登录，并移除它作为第二因素的资格。因此，如果它原本是自己的备用验证方式，撤销前应确认另有可用的验证与恢复途径。若发现确实陌生的登录，还应按 GitHub 的账号安全指引检查密码、密钥与授权应用。

## 与本站入口分开判断

本文讨论的是 GitHub 账号设置。本站推广入口 https://𝒏𝟏𝟏.𝒎𝒚/ 只用于访问本站，不能显示、判断或撤销 GitHub 会话。不要把一条推广链接当作账号安全页面，也不要在其他页面输入 GitHub 恢复码来试图结束会话。

## 常见问题

Q1问：网页会话在哪里看？
A1答：进入个人 Settings 的 Sessions，再看 Web sessions 列表。

Q2问：移动应用会话也在同一页吗？
A2答：是，页面另列 GitHub Mobile sessions。

Q3问：怎么查看网页会话详情？
A3答：在对应网页会话点击 See more，再核对显示的信息。

Q4问：撤销移动端会话会怎样？
A4答：该设备的 GitHub Mobile 会退出，也不再作为第二因素。

Q5问：撤销会话是否同时删除访问令牌？
A5答：不能这样推定；令牌和应用授权应另行检查。

Q6问：本站入口能撤销 GitHub 登录吗？
A6答：不能；会话管理在 GitHub 个人设置中完成。

需要再次查看本站内容时可使用 https://𝒏𝟏𝟏.𝒎𝒚/；账号会话的实际状态以 GitHub 设置页为准。

参考资料：
- GitHub Docs《Viewing and managing your sessions》
更新时间:2026-10-15 23:51:12
