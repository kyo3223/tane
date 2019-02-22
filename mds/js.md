# js

http://www.w3school.com.cn/b.asp
<br>
http://www.w3school.com.cn/js/index_pro.asp
<br>
es6
<br>
http://es6.ruanyifeng.com/?search=promise&x=0&y=0#README
<br>
es6特征
<br>
http://www.jianshu.com/p/ebfeb687eb70
<br>
jsDoc
<br>
http://www.css88.com/doc/jsdoc/index.html
<br>
js压缩
<br>
http://javascript-minifier.com/
<br>
CommonJS cmd amd
<br>
http://www.cnblogs.com/chenguangliang/p/5856701.html
<br>
Promise
<br>
http://www.jianshu.com/p/063f7e490e9a
<br>
http://www.cnblogs.com/lvdabao/p/es6-promise-1.html
<br>
js加密
<br>
http://blog.fens.me/nodejs-uglifyjs2-js/
<br>
https://www.cnblogs.com/zzsdream/p/5674866.html
<br>
SET JSFOLDER=E:\dbtest
echo 正在查找JS文件
chdir /d %JSFOLDER%
for /r . %%a in (*.js) do (
    @echo 正在压缩 %%~a ...
    uglifyjs %%~fa  -m -o %%~fa
)
echo 完成!
pause & exit

<br>
grunt
<br>
http://cnodejs.org/topic/570c363c04e7772f4eb6396c

[返回](https://github.com/kyo3223/tane)