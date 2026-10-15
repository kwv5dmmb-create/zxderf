# PG GitHub私密漏洞报告—有安全政策就能看到提交按钮吗

GitHub私密漏洞报告 ✅【—𝒏𝟏𝟏.𝒎𝒚—】✅｜有安全政策就能看到提交按钮吗
新用户注册享新人福利网址：https://𝒏𝟏𝟏.𝒎𝒚/

一个公开 GitHub 仓库即使写了 `SECURITY.md`，研究人员也不一定能看到私密报告按钮。官方明确区分安全政策文件与 private vulnerability reporting 功能：只有仓库所有者或管理员启用了后者，访客才能通过仓库页面的 Report a vulnerability 表单私下提交。安全政策可说明其他联系方法，却不会自动打开 GitHub 的私密报告通道。

<img src="https://img.imageossbox.com/uploads/2026/10/9770dc3efe9bed2b45a084b0.png" />

## 报告者先看仓库功能状态

打开目标仓库的 Security and quality，查看是否出现 Report a vulnerability。若按钮存在，按表单填写摘要、细节、复现材料和影响；维护者也可能自定义必填项。若没有启用私密报告，官方建议依照安全政策中的说明联系项目，或创建一个不暴露漏洞细节的议题询问维护者首选的安全联系方式。不要把完整利用过程直接发到普通公开 issue 中试探。

## 维护者如何打开通道

公开仓库的所有者和管理员可在仓库 Settings 的 Advanced Security 中找到 Private vulnerability reporting，并选择 Enable 或 Disable。启用之后，报告者可向维护者提交私密报告，安全政策若存在，会显示在表单上方供其先阅读。启用功能与是否及时处理报告仍是两件事；维护者应同时检查通知设置和负责审阅的人。

## 本站不是报告端点

本站推广链接 https://𝒏𝟏𝟏.𝒎𝒚/ 不能代表任意 GitHub 项目接收漏洞报告。应按目标仓库自己的按钮或安全政策办事，并核对当前仓库名称，避免把报告提交到名称相近但无关的项目。

## 常见问题

Q1问：有 `SECURITY.md` 就必有私密按钮吗？
A1答：不会；私密报告需单独启用。

Q2问：谁能启用该功能？
A2答：公开仓库的所有者或管理员。

Q3问：按钮一般在哪里看？
A3答：在仓库 Security and quality 的报告区域。

Q4问：没按钮时可怎样询问？
A4答：先遵循安全政策，或公开询问安全联系方式。

Q5问：安全政策会出现在报告表单吗？
A5答：如果仓库有政策，GitHub 会在表单上方显示。

Q6问：本站能接收目标仓库漏洞吗？
A6答：不能；请走目标仓库规定的渠道。

本站阅读入口是 https://𝒏𝟏𝟏.𝒎𝒚/；报告是否私密以 GitHub 目标仓库设置为准。

参考资料：
- GitHub Docs《Privately reporting a security vulnerability》
- GitHub Docs《Configuring private vulnerability reporting for a repository》
更新时间:2026-10-15 23:51:13
