---
layout:post
title:'ubuntu 搭建 Jekyll环境 '
category: 日志
tags: ubuntu Jekyll
---

#Step 1.Ruby安装#

    $sudo apt-get install ruby

    查看是否安装成功：

    $ ruby -v

      ruby 1.8.7 (2010-01-10 patchlevel 249) [i486-linux]

# Step 2. RubyGems安装（管理ruby包） #
    $ wget http://production.cf.rubygems.org/rubygems/rubygems-2.1.6.tgz

    $ tar xvf rubygems-2.1.6.tgz
    
    $ cd rubygems-2.1.6

    $ sudo ruby setup.rb

    $ sudo ln -s /usr/bin/gem1.8 /usr/bin/gem

    $ gem update –system

    $ sudo gem install jekyll

