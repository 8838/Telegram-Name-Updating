# Telegram-Name-Updating(Telegram名字实时显示时间)

Update (first/last/user) name of Telegram user every 30 seconds. (每30秒更新一次Telegram用户（第一个/最后一个/用户）名称。)

参考文档：<a href="https://telethon.readthedocs.io/en/stable/">Telethon</a>

lastname实时更新效果：<a href="https://t.me/JiuMeng">旧梦</a>

## 0. 准备

运行环境：VPS，python3，python3-pip

创建应用：<a href="https://my.telegram.org/">https://my.telegram.org/</a>。只要填App title和Short name即可。获得api_id和api_hash。

## 1. 下载Demo小程序到VPS上

<code>git clone https://github.com/8838/Telegram-Name-Updating.git</code>\
<code>cd Telegram-Name-Updating</code>

## 2. 安装telethon

<code>pip3 install -r requirements.txt</code>

## 3. 运行Demo小程序

<code>python3 tg_username_update.py</code>

## 4. api认证和用户登陆

根据提示输入api_id和api_hash。接着输入手机号和验证码，如果账号开启了二次验，证根据提示再输入二次验证的密码。最后看到 It works! 表明成功了。 默认的是每30秒钟按照一定概率更新一次lastname到特定模式。
