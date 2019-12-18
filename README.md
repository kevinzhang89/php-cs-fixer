## 背景

一个编码团队,假如每个人写的代码规范都不一致,会导致很多不好的问题,比如不愿意阅读他人的代码,甚至打架斗殴的现象;
一个团队的凝聚力来源于,有很多共同点,代码规范一致是必须的,代码就相当于我们的子弹,我们使用的枪和子弹必须是一个型号的,这样也更容易切换角色,由此引出了php-cs-fixer

## 安装(以下只介绍ubuntu系统, 其它系统请阅读参考资料)

- wget http://get.sensiolabs.org/php-cs-fixer.phar -O php-cs-fixer
- sudo chmod a+x php-cs-fixer
- sudo mv php-cs-fixer /usr/local/bin/php-cs-fixer

## 使用

- 格式化文件 php-cs-fixer fix xx.php

## 参考资料

- https://segmentfault.com/a/1190000004162229?_ea=531240
- https://github.com/FriendsOfPHP/PHP-CS-Fixer
