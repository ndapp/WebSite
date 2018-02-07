## 自助添加 NEO dApp 的步骤

1. Fork 这个项目到自己的 GitHub 仓库，相当于拷贝一份到自己的 GitHub 账户下
2. 将自己的库 Pull 下来（这时候 Origin 是自己的地址，不是公共地址）
3. 创建子分支并修改本地 WebSite\wwwroot 目录下的 index.html 文件
4. 提交修改（Commit）
5. Push 到自己的 GitHub，也就是当前的 Origin 地址
6. 在 GitHub 上提交 Pull request（neo-project ← Your GitHub）

## 快速添加的方法
如果你对网站前端十分熟练，可以使用此方法快速添加dApp
1. 打开 [https://github.com/ndapp/WebSite/tree/master/WebSite/wwwroot/images](https://github.com/ndapp/WebSite/tree/master/WebSite/wwwroot/images) 点击 Upload files 上传 dApp 的 LOGO，然后点击 Commit changes.
2. 打开 [https://github.com/ndapp/WebSite/blob/master/WebSite/wwwroot/index.html](https://github.com/ndapp/WebSite/blob/master/WebSite/wwwroot/index.html) 点击编辑按钮，在列表最后添加项目信息，后点击 Commit changes.

提交 Pull request 后，管理员审核通过后，就会合并到主分支中，并且发布到官网。若有疑问，可以发邮件到 [chenzhitong12@hotmail.com](mailto:chenzhitong12@hotmail.com)

### dApp 要求

- 所添加的 dApp 必需已在 main net 或 test net 上发布
- 需要添加完善的 dApp 信息，如封面图片、名称、作者、dApp描述、邮箱、GitHub、ScriptHash
- 封面图片上传至 WebSite\wwwroot\images 文件夹中
- 新添加的项目应该添加到项目列表的最后，否则审核不会通过。

## How to add a dApp

The overall process is as follows:

1. Fork this project to your own GitHub repository (so you have a copy on your own GitHub account).
2. Create a branch in your own repository (this time the origin will be your own fork, not the public one).
3. Modify the site code locally and complete the tests.
4. Commit the changes to your branch.
5. Push the changes to your main branch.
6. Create a Pull Request (PR) on GitHub (neo-project ← your own GitHub).

## Quick Add method
If you are familiar with the front-end of the site, you can use this method to quickly add Dapp.
1. Open [Https://github.com/ndapp/WebSite/tree/master/WebSite/wwwroot/images](https://github.com/ndapp/WebSite/ tree/master/website/wwwroot/images) Click Upload files Upload dApp LOGO and click Commit Changes.
2. Open [https://github.com/ndapp/WebSite/blob/master/WebSite/wwwroot/index.html](https://github.com/ndapp/WebSite /blob/master/website/wwwroot/index.html) Click the Edit button to add item information at the end of the list and click Commit Changes.

When the PR is submitted, it will be reviewed and, if accepted, merged into the main branch, after which it is published to the official website.If you have any questions, you can send an e-mail to [chenzhitong12@hotmail.com](mailto:chenzhitong12@hotmail.com).

### dApp Requests

- The added dApp must be published on main net or test net.
- You need to add crucial dApp information, such as cover pictures, name, author, dApp description, mailbox, GitHub, ScriptHash.
- The cover image is uploaded to the WebSite\wwwroot\images folder.
- The newly added item should be added to the end of the dApps list, otherwise the audit will not pass.
