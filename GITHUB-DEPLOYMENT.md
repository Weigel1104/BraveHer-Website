# GitHub Pages 部署指南

## 部署步骤

1. **创建GitHub仓库**
   - 登录GitHub账户
   - 创建名为 `BraveHer-Website` 的新仓库
   - 建议设置为公开仓库

2. **上传网站文件**
   - 将所有文件上传到仓库
   - 确保根目录包含 `index.html` 和 `.nojekyll` 文件
   - 可以使用GitHub网页界面上传或使用Git命令

3. **配置GitHub Pages**
   - 前往仓库设置(Settings)
   - 在左侧菜单找到 "Pages"
   - Source部分选择 "Deploy from a branch"
   - Branch部分选择 "main" 分支和 "/ (root)" 文件夹
   - 点击 "Save"

4. **验证部署**
   - 等待几分钟让GitHub完成部署
   - 访问 `https://您的用户名.github.io/BraveHer-Website/`
   - 验证网站是否正常显示

## 常见问题排查

如果网站无法正常显示，请检查以下几点：

1. **404错误**
   - 确认网址是否正确
   - 检查仓库设置中的Pages配置
   - 验证index.html文件是否存在于正确位置

2. **样式/图片无法加载**
   - 检查浏览器控制台是否有资源加载错误
   - 确认所有路径是否正确
   - 确保网络连接正常(图片依赖在线服务)

3. **页面跳转问题**
   - 确认所有导航链接使用相对路径
   - 检查文件名大小写(GitHub Pages区分大小写)

## 更新网站

要更新已部署的网站:

1. 修改本地文件
2. 上传新文件到GitHub仓库
3. GitHub Pages会自动重新部署网站

## 自定义域名(可选)

如需使用自定义域名:

1. 在Pages设置中添加您的域名
2. 按照GitHub提供的说明配置DNS
3. 等待DNS传播(可能需要24小时) 