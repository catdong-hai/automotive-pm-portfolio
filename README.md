# 新能源汽车项目管理：求职成果展示页（静态网站）

本项目页面是可离线打开、可部署到 GitHub Pages 的 **个人模拟项目展示页**。不代表真实车企实习经历，业务数字除205件真实案例背景外均为教学模拟。

## 本地查看

直接双击 `index.html`。若图片或下载链接未显示，请确认 `assets/` 和 `files/` 文件夹与 `index.html` 位于同一目录。

## 发布为公开可分享链接（GitHub Pages）

1. 登录GitHub，新建一个**公开**仓库，例如 `automotive-pm-portfolio`。
2. 将本压缩包解压后的 `index.html`、`assets/`、`files/` 上传到该仓库**根目录**，而不是再套一层中文文件夹。`README.md` 可一起上传。
3. 打开仓库 `Settings` → `Pages`，选择 **Deploy from a branch**，分支 `main`、目录 `/(root)`，保存。
4. 发布成功后，典型公开地址为 `https://你的用户名.github.io/automotive-pm-portfolio/`。实际网址以GitHub Pages显示为准。
5. 浏览器打开公开地址，检查预览图和3个下载链接，确认无密钥或敏感信息后再填入简历。

注意：GitHub Pages 页面托管的是**静态作品集**，不会托管或运行 Streamlit Python 服务。需要展示实时交互应用，需额外部署 Streamlit 并配置数据与凭证保护。简历可以先使用静态公开作品集链接。

## 文件目录

- `index.html`：可展示的响应式网页。
- `assets/dashboard_preview.png`：已有模拟项目看板预览图。
- `files/project_workbook.xlsx`：前五课管理工作簿。
- `files/ai_assistant_source.zip`：第六课代码、样例CSV、测试、README。
- `files/sample_weekly_report.md`：示范项目周报。

## 参考资料

公开案例：Sustainability 2020, 12(21), 9245，https://doi.org/10.3390/su12219245

## 限制

- 项目中的流程、规则和日期为教学简化方案，不能声称是蔚来内部真实制度。
- 不要提交企业保密资料、个人信息和 API 密钥到公开仓库。
- AI部分需要本人拥有的API凭证才能使用；静态页面本身不提供AI功能。
