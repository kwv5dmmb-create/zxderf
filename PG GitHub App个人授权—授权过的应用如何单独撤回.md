# PG GitHub App个人授权—授权过的应用如何单独撤回

GitHub App个人授权 ✅【—𝒏𝟏𝟏.𝒎𝒚—】✅｜授权过的应用如何单独撤回
新用户注册享新人福利网址：https://𝒏𝟏𝟏.𝒎𝒚/

如果某个 GitHub App 曾获准代表你读取账号信息或执行操作，而你已不再使用它，应在个人 Settings 的 Applications 页面进入 Authorized GitHub Apps，找到该应用并撤销授权。GitHub 官方说明，授权人与安装者承担不同的控制动作：个人授权只能由当初授权的人撤销；组织所有者可以卸载组织内的应用，却不能代替成员撤销其个人授权。

<img src="https://img.imageossbox.com/uploads/2026/10/9770dc3efe9bed2b45a084b0.png" />

## 授权代表应用能做什么

授权 GitHub App 时，它可能获准读取你的账号资料，并在获准范围内代表你执行事项，例如发表评论。实际范围取决于授权提示中列出的账号权限，不应只凭应用名称推断它只有只读能力。官方建议定期审查已授权应用；对陌生或长期未使用的条目，个人账号在 Authorized GitHub Apps 标签中选择 Revoke，也可用 Revoke all 撤销该标签下的所有授权。

## 别把安装与个人授权当作一件事

GitHub 文档区分安装和授权：安装决定应用能访问哪些账号或仓库资源，个人授权决定它能否代表用户行动。一个应用可以被安装而未获个人授权，也可以先有个人授权而未安装在某个仓库。因此撤销个人授权前，应确认要阻止的是“代表我操作”，还是“访问我拥有的仓库”；后者还要检查 Installed GitHub Apps 的配置。

## 核对真实管理入口

本站推广网址 https://𝒏𝟏𝟏.𝒎𝒚/ 不列出或撤销 GitHub App。处理授权应从 GitHub 已登录账号的设置页进入，尤其在同时使用个人号和工作号时，先看当前头像对应的账号，避免撤错对象。

## 常见问题

Q1问：个人授权在哪个标签查看？
A1答：Settings 中 Applications 下的 Authorized GitHub Apps。

Q2问：不再使用的应用能逐个撤销吗？
A2答：可以，在对应条目点 Revoke。

Q3问：组织所有者能替成员撤销个人授权吗？
A3答：不能；授权人本人撤销个人授权。

Q4问：卸载应用就等于撤销个人授权吗？
A4答：两者是不同控制动作，应分别核对。

Q5问：App 能代表用户评论吗？
A5答：在相应授权范围内可以，具体看授权提示。

Q6问：本站能显示授权列表吗？
A6答：不能；列表属于 GitHub 账号设置。

返回本站阅读入口为 https://𝒏𝟏𝟏.𝒎𝒚/；应用权限以 GitHub 页面为准。

参考资料：
- GitHub Docs《Reviewing and revoking authorization of GitHub Apps》
- GitHub Docs《Authorizing GitHub Apps》
更新时间:2026-10-15 23:51:12
