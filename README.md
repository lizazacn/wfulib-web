# wfulib-web
# 更新v2.0
该脚本支持Chrome浏览器（其它浏览器没试，不知道）
谷歌浏览器需要修改以下配置：
    在浏览器地址栏中输入：chrome://flags/
    将SameSite by default cookies和Cookies without SameSite must be secure修改为Disabled。
    然后点击Relaunch重启浏览器
demo:https://lizazacn.github.io/wfulib-wdb/v2.0
# 注意：该脚本有一丢丢不讲武德，可能会导致预约系统崩溃，请各位慎用！！！！
# 简介
该脚本采用HTML+JavaScript+jQuery编写，可直接在浏览器中打开使用（该版本仅支持火狐浏览器），脚本通过form表单想服务器发送post请求，通过删除对图标、图片等数据的加载，降低对网速的需求。
# 环境要求
    目前仅支持火狐浏览器（旧版本）
# 获取座位id的方法
    使用谷歌浏览器打开预约界面-->找到想要预约的座位-->鼠标右击该座位-->选择检查
    例如：
     <div id=“517” ......>187</div>
     101A 187座位对应的座位id为517
