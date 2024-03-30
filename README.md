Typecho Blogging Platform
=========================

Typecho is a PHP-based blog software and is designed to be the most powerful blog engine in the world.
Typecho is released under the GNU General Public License 2.0.

个人自用 typecho 的一些魔改，也方便同步官方

## sync

1.   添加原项目的映射：`git remote add src https://github.com/typecho/typecho.git`
2.   获取更新：`git fetch src`
3.   本地合并：`git merge src/slave`，手动解决冲突
4.   合并完成后重新 push：`git push origin slave`

或者使用 fork 的 update：

1.   `git checkout master`
2.   `git pull`
3.   `git checkout slave`，`git merge master`，解决冲突
4.   `git push origin slave`

## 几个好用的 plugin

1.   [kokororin/typecho-plugin-Access](https://github.com/kokororin/typecho-plugin-Access.git)
2.   [DT27/EditorMD](https://github.com/DT27/EditorMD.git)
3.   [handsome](https://www.ihewro.com/archives/489/)

## Main Features

* Multiple databases support (MySQL, SQLite, PostgreSQL)
* Markdown Support
* Plugin Support
* Theme Support
* Custom Fields
* Custom Pages

## Requirements

* PHP 7.2.0 or higher
* Database (MySQL, SQLite, PostgreSQL)
  * MySQL 5.5.3 or higher
  * SQLite 3.7.11 or higher
  * PostgreSQL 9.1 or higher

## Screenshots

![Typecho](https://typecho.org/usr/themes/bluecode/img/screenshot/st1.png)

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.
