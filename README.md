# Kevin Zou Personal Homepage

这是 `Kevin Zou` 的静态个人主页，适合直接通过 GitHub Pages 发布。

## 本地文件

- `index.html`
- `styles.css`
- `script.js`

## GitHub Pages 发布方式

这个仓库已经是独立 Git 仓库，远程地址为：

`git@github.com:KevinnZou/kevinzou-index.git`

默认分支：

`main`

### 第一次发布

1. 确认当前文件都已经保存
2. 在项目目录执行：

```bash
cd /Users/kevinnzou/Documents/升学规划/kevin-zou
git add .
git commit -m "publish personal homepage"
git push origin main
```

3. 打开 GitHub 仓库页面：

`https://github.com/KevinnZou/kevinzou-index`

4. 进入：

`Settings` -> `Pages`

5. 在 `Build and deployment` 里选择：

- `Source`: `Deploy from a branch`
- `Branch`: `main`
- `Folder`: `/ (root)`

6. 点击 `Save`

7. 等待几十秒到几分钟，GitHub Pages 会生成站点链接。

通常链接会是：

`https://kevinnzou.github.io/kevinzou-index/`

## 后续更新

每次你改完页面后，只需要重新执行：

```bash
cd /Users/kevinnzou/Documents/升学规划/kevin-zou
git add .
git commit -m "update homepage"
git push origin main
```

GitHub Pages 会自动重新发布。

## 常见问题

### 页面没更新

- 等 1 到 3 分钟再刷新
- 强制刷新浏览器
- 去 GitHub 仓库的 `Actions` 或 `Pages` 看是否还在部署

### 链接打不开

- 先确认 `Settings -> Pages` 已经启用
- 确认分支选的是 `main`
- 确认目录选的是 `/ (root)`

### 自定义域名

如果以后你要绑定自己的域名，可以在 `Settings -> Pages` 里继续配置。
