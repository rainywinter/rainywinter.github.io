+++
title = 'Python Matplotlib'
date = 2024-05-09T10:30:23+08:00
draft = true
tags=['python']
+++


## 中文乱码（显示框框）

直接使用matplotlib的情况，添加一下代码即可  
```python
plt.rcParams['font.sans-serif'] = ['Arial Unicode MS']
```

使用mplfinance库时需要添加一下代码
```python
my_style = mpf.make_mpf_style(rc={'font.sans-serif' :'Arial Unicode MS'})
mpf.plot(dataframe, style=my_style)

```