# online.net special sales monitor
It is a script for online special sales.</br>
To use it, you have to install python2.x and crontab.</br>
<br>
### tutorial
1. You need to get a wechat push key from https://sc.ftqq.com/, and put it into online.py.
2. Use crontab to run the online.py automaticly.
3. If you want to monitor other sales, you can just change those:
```
prices = ['6.99', '16.99', '19.99']
driver.get('https://www.online.net/en/summer-2017/sales')
```

BUY! BUY! BUY!
