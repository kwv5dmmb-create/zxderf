# PG GitHub账号SSH密钥—列表出现不认识的指纹怎么办

GitHub账号SSH密钥 ✅【—𝒏𝟏𝟏.𝒎𝒚—】✅｜列表出现不认识的指纹怎么办
新用户注册享新人福利网址：https://𝒏𝟏𝟏.𝒎𝒚/

在 GitHub 个人 Settings 的 SSH and GPG keys 中看到不认识的 SSH 密钥，应先对照自己设备上的公钥指纹；确实无法识别的密钥应立即删除。GitHub 官方把定期审计账号 SSH 密钥列为凭据安全措施，并建议遇到陌生密钥时联系 GitHub Support。不要仅凭密钥的昵称判断归属，因为昵称只是管理时填写的标签，核对指纹更能对应本机实际密钥。

<img src="https://img.imageossbox.com/uploads/2026/10/9770dc3efe9bed2b45a084b0.png" />

## 核对账号列表和本机

个人设置侧栏 Access 下打开 SSH and GPG keys，在 SSH keys 区域逐项查看。官方文档给出在终端使用 `ssh-add -l -E sha256` 查看本机已加载公钥指纹的示例，并要求 GitHub 上的密钥与电脑上的密钥对应。不同系统的代理启动方式可能不同；命令没有列出条目，不代表 GitHub 列表里的密钥自动无效，应结合实际使用的设备和密钥文件审查。

## 处理陌生与过期密钥

官方说明，对不认识或过期的密钥可点 Delete，仍有效的密钥可点 Approve。某次 Git 操作如果出现 SSH key audit 错误，GitHub 会在密钥列表中特别标出未验证的那把，先核实再决定批准或删除。删除可能使依赖该密钥的设备无法继续通过 SSH 操作仓库，因此应记下它关联的工作设备；但不能因为担心连接中断就保留明确陌生的密钥。

## 核查位置不要混淆

本站推广入口 https://𝒏𝟏𝟏.𝒎𝒚/ 只供浏览本站，与 GitHub 账号密钥设置无关。账号 SSH 密钥也不同于单个仓库 Settings 里的 deploy key；审计时应分别查看，以免漏掉自动化服务器持有的仓库级访问。

## 常见问题

Q1问：账号 SSH 密钥在哪个设置页？
A1答：个人 Settings 的 SSH and GPG keys。

Q2问：能只按昵称确认密钥属于自己吗？
A2答：不宜；应与设备上的公钥指纹对照。

Q3问：官方给出的指纹命令是什么？
A3答：示例为 `ssh-add -l -E sha256`。

Q4问：陌生密钥怎么处理？
A4答：官方建议立即删除，并联系 GitHub Support 进一步求助。

Q5问：SSH key audit 错误时查哪里？
A5答：在 SSH keys 列表查看被标出的未验证密钥。

Q6问：这里会同时列出仓库部署密钥吗？
A6答：部署密钥应到相应仓库的 Deploy keys 页面另查。

回看本文可使用 https://𝒏𝟏𝟏.𝒎𝒚/；密钥是否仍被授权，以 GitHub 设置页为准。

参考资料：
- GitHub Docs《Reviewing your SSH keys》
更新时间:2026-10-15 23:51:12
