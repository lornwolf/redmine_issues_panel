# Redmine Issues Panel

This is a plugin for Redmine to display issues by statuses and change it's status by DnD.

## Features

* Filter and group issues with custom queries
* Drag and drop to change status
* Update issues via the context menu

## Install

#### Place the plugin source at Redmine plugins directory.

`git clone` or copy an unarchived plugin to
`plugins/redmine_issues_panel` on your Redmine installation path.

```
$ git clone https://github.com/lornwolf/redmine_issues_panel.git /path/to/redmine/plugins/redmine_issues_panel
```

本插件只适用于Redmine4.1版，在Redmine4.0下运行时会出错。
如果要在4.0下运行，需要手动添加一些4.1版才有的类和函数。目前在我的Redmine4.0环境下已成功运行。

## Uninstall

#### Remove the plugin directory.

```
$ cd /path/to/redmine
$ rm -rf plugins/redmine_issues_panel
```

## Licence

This plugin is licensed under the GNU General Public License, version 2 (GPLv2)

## Author

[Takenori Takaki (Far End Technologies)](https://www.farend.co.jp)
