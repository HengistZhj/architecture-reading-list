# 建筑书单 / Architecture Reading List

[打开书单网页 / Open the reading list](https://hengistzhj.github.io/architecture-reading-list/)

面向手机与电脑的中英双语建筑阅读档案，包含61本书，可按书名、作者、主题、分类和阅读状态搜索筛选。
A bilingual architecture reading archive with 61 books, searchable by title, author and topic, with category and reading-status filters.

## 语言约定 / Language conventions

中文和英文同时显示；英文保留原书名，中文为便于检索的参考译名，不代表特定中文版或正式出版译名。
Chinese and English appear together; English titles retain their original wording, while Chinese titles are reference translations rather than claims about published Chinese editions.

分类、书单类型和状态的英文数据值保留，另加中文显示字段；原有阅读状态、优先级和课程来源不变。
Canonical English category, list and status values are retained alongside Chinese display fields; reading progress, priorities and course sources are preserved.

## 更新资料 / Update readings

阅读数据保存在`books.json`，网站自动读取；修改条目时同时维护`title`/`title_zh`与`notes`/`notes_zh`。
The site loads `books.json`; maintain both `title`/`title_zh` and `notes`/`notes_zh` when editing an entry.

缺失作者或年份保持空值，页面显示“待补”；链接失效不影响收录，不要求逐个验证。
Leave unknown authors or years empty; the page shows a missing-data label, and unavailable links do not prevent inclusion or require individual verification.

## 课程资料 / Course resources

- [重合书籍与章节 / Overlapping books and chapters](COURSE-READING-OVERLAPS.md)
- [新增28本课程书籍 / 28 additional course books](COURSE-READING-ADDITIONS.md)
- [维护规则 / Maintenance rules](AGENTS.md)

## GitHub Pages 发布 / GitHub Pages publishing

仓库 Settings → Pages → Deploy from a branch，选择 main 和 /(root)，保存。
In repository Settings → Pages → Deploy from a branch, choose main and /(root), then save.

提交后页面可能需等待部署和浏览器缓存更新；可刷新查看。
After a commit, allow time for deployment and browser caches to update, then refresh.
