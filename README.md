# Why this repository
所有的一切都源自一篇博客 http://it-consultis.com/blog/5-redmine-plugins-will-change-way-you-work。
当我安装这些插件的时候，发现一个一个寻找它们时一件蛮费的，更何况 http://www.redminecrm.com/ （一个最大redmine资源的站点 ） 还被墙了；所以，我决定将我常用的一些插件和皮肤汇总在这里，方便有需求的朋友使用。

ps：所有插件均成功跑在 redmine 3.0版本之上

# How to use 
#####1. plugins 和 public/thmemes 的文件拷贝到你的 redmine 项目对应目录中。
#####2. 依次执行命令
```ruby
bundle install --without development test
bundle exec rake redmine:plugins NAME=redmine_checklists RAILS_ENV=production
bundle exec rake redmine:plugins NAME=redmine_agile RAILS_ENV=production
```
##### 3. 重启 reminde，进入 ～/admin/plugins 和 ~/settings?tab=display 页面设置插件和皮肤。
