# PG GitHub细粒度令牌—只开放一个仓库要设哪两层范围

GitHub细粒度令牌 ✅【—𝒏𝟏𝟏.𝒎𝒚—】✅｜只开放一个仓库要设哪两层范围
新用户注册享新人福利网址：https://𝒏𝟏𝟏.𝒎𝒚/

给脚本创建 GitHub 细粒度个人访问令牌，只想操作一个仓库时，应同时限制 Repository access 和 Permissions。前者选择 Only select repositories 并勾选目标仓库，后者只给任务所需的读取或写入权限。GitHub 官方说明，细粒度令牌还绑定一个 Resource owner；只选了仓库却授予过宽权限，或只缩小权限却把仓库范围放得过大，都不符合最小授权的目标。

<img src="https://img.imageossbox.com/uploads/2026/10/9770dc3efe9bed2b45a084b0.png" />

## 按任务选择资源

从个人 Settings 进入 Developer settings、Personal access tokens、Fine-grained tokens，再创建新令牌。先选资源拥有者，随后在 Repository access 中选择可访问的仓库，最后在 Permissions 中给出任务所需的权限。官方说明，一个细粒度令牌只面向单个个人或组织资源拥有者，还可进一步限到指定仓库；但它始终可只读访问 GitHub 的公共仓库，这一点不能误写成“只能看到我勾选的仓库”。

## 组织审批和功能限制

某些组织要求管理员批准细粒度令牌；待批准期间，令牌只能读取公共资源。GitHub 也列出细粒度令牌暂不支持的场景，例如同时访问多个组织等。若你的任务在这些限制之内，不能通过随意扩大仓库选择来解决，应先核对官方支持范围。令牌像密码一样需要保管，生成后不要放进文章、截图或公开提交。

## 本站不签发 GitHub 令牌

本站推广网址 https://𝒏𝟏𝟏.𝒎𝒚/ 只是本站入口。令牌应在 GitHub 自己的 Developer settings 中创建和撤销；不要把生成后的值贴到推广页面来测试仓库权限。

## 常见问题

Q1问：只选仓库就足够了吗？
A1答：还要给任务需要的最小 Permissions。

Q2问：资源拥有者能选多个组织吗？
A2答：一个细粒度令牌只绑定一个资源拥有者。

Q3问：能只选一座私有仓库吗？
A3答：可以在 Only select repositories 中指定。

Q4问：公共仓库只读访问也被排除吗？
A4答：不是，官方说明令牌仍含公共仓库只读访问。

Q5问：组织审批前能访问私有资源吗？
A5答：待批准状态只能读取公共资源。

Q6问：本站能生成该令牌吗？
A6答：不能；创建入口在 GitHub。

本站其他文章入口为 https://𝒏𝟏𝟏.𝒎𝒚/；实际授权范围以 GitHub 令牌设置为准。

参考资料：
- GitHub Docs《Managing your personal access tokens》
更新时间:2026-10-15 23:51:13
