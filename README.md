# mima.py
可以使用Python的random模块和字符串的ascii_letters属性来生成随机密码。
import random
import string

password = ''.join(random.choices(string.ascii_letters, k=18))
print(password)
这个代码生成一个由18个大小写字母随机组成的密码，并将其打印在控制台上。
