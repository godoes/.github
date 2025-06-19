---
name: 🐛  Report a bug 报告错误
about: Your issue may already be reported! please search before creating one. 您的问题可能已被报告！请在创建之前进行搜索。 🥳
labels: type:bug
assignees: iTanken

---

<!-- DON'T CHANGE THE TEMPLATE 请勿修改模板 -->

## Description 问题说明

<!-- Describe the issue 详细描述一下产生的问题 -->

## Environment 环境

<!-- Please replace X with the actual value 请将 X 替换为实际值 -->

- [`go`](https://github.com/golang/go/tags) version：`goX.X.X`
- `os`: `XXX`
- `arch`: `XXX`

<!-- 非数据库驱动问题可删除当前节点的以下内容 -->

**驱动问题请务必填写数据库和驱动相关版本，以及相关 Go 和 SQL 示例代码！**

- [ ] **Oracle**

- [**`oracle database`**](https://endoflife.date/oracle-database) veresion: `XXx`
- [**`gorm-oracle`**](https://github.com/godoes/gorm-oracle/tags) version：`vX.X.X`
- [`go-gorm`](https://github.com/go-gorm/gorm/tags) version：`vX.X.X`

- [ ] **DM**

- [**`dameng database`**](https://eco.dameng.com/download/) veresion: `XXx`
- [**`gorm-dameng`**](https://github.com/godoes/gorm-dameng/tags) version：`vX.X.X`
- [`go-gorm`](https://github.com/go-gorm/gorm/tags) version：`vX.X.X`

## Code 示例代码

<!-- Write the relevant code where the error occurs here 在这里编写发生错误的相关代码，数据库驱动相关问题请补充 SQL 示例 -->

```go
// 发生错误的 Go 代码

```

<!-- 非数据库驱动问题可删除以下代码块 -->

```sql
-- 发生错误的 SQL

```
