# From Looking to Making · 陶艺研习室

静态陶艺教学网站，包含七项技法视频，可部署到 GitHub Pages，无需安装依赖或构建。

## 首次部署
1. 在 GitHub 新建 Public 仓库，建议名称 from-looking-to-making。
2. 解压本压缩包。将里面的 index.html、style.css、app.js、courses.js、images 文件夹、videos 文件夹及 .nojekyll 上传到仓库根目录。不要上传 ZIP 本身，也不要多包一层目录。
3. 点击 Commit changes。若视频上传较慢，可分批上传，但保持 videos 文件夹结构。
4. Settings → Pages → Build and deployment：Source 选择 Deploy from a branch；Branch 选择 main；Folder 选择 /(root)，点击 Save。
5. 等部署完成，在 Pages 页面点击 Visit site。请使用这里显示的实际网址，不要使用 github.com 的仓库地址作为作品集网站链接。
6. 用无痕窗口打开网站，检查首页、七个视频和手机显示后，再放入作品集。

## 文件
- index.html：页面入口
- style.css：样式
- app.js：页面与交互
- courses.js：技法标题、步骤、材料、常见问题和视频地址
- images/：陶板案例图片
- videos/：七个 MP4 与对应封面

## 后续更新
修改文件后上传到同一路径并 Commit changes，GitHub Pages 会重新发布。更新时使用同名文件可保留原链接。所有资源使用相对路径，适配项目子目录。

## 视频对应
knead.mp4：揉泥
slab.mp4：拍泥板
pinch.mp4：捏杯子
handle.mp4：杯子粘把手
mountains.mp4：山石概括制作
relief.mp4：浮雕细节塑造
glaze.mp4：上釉

学习记录保存在当前浏览器，不跨设备同步。烧制由教师或专业人员负责。
