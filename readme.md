# BIT 校园网用户认证

上网不涉密，涉密不上网

login:
```python
srun_login(username, password)
```

logout:
```python
srun_login(username, action="logout")
```


# 注意
这里包含3个.py文件, 三个版本功能一致

其中"srun_login_req.py", 使用了requests, py2/py3环境下均可使用

对于某些无法使用requests的环境(例如路由器), 替代方案为使用urllib的"srun_login_py3.py"或"srun_login_py2.py"