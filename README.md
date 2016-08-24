##

## 警示框
```html
<div class="alert alert--success|alert--error|alert--info">
    <h4 class="alert__title"></h4>
    <p class="alert__content"></p>
    <button class="btn-close" data-js="close">&times;</button>
</div>
```
## 徽章
```html
<span class="badge badge--success|badge--error|badge--warning|badge--info"></span>
```
## 标签
```html
<span class="label label--success|label--error|label--warning|label--info"></span>
```
## 按钮
```html
<a class="btn btn--success|btn--error|btn--warning|btn--info" href="javascript:;"></a>
<button class="btn btn--success|btn--error|btn--warning|btn--info"></button>
```
## 进度条
```html
<div class="progress progress--mini">
    <div class="progress__bar progress--info|progress--success|progress--warning|progress--error" style="width: 20%"></div>
</div>
```
## 表单
```html
<form class="form" action="about:blank" method="get|post" autocomplete="on|off" novalidate accept-charset="utf-8">
    <div class="form__group">
        <label>用户名：</label>
        <input type="text" placeholder="用户名">
        <span class="form__help--inline">用户名是你的注册邮箱地址</span>
    </div>
    <div class="form-group">
        <label>密码：</label>
        <input type="password" placeholder="请输入密码">
        <span class="form__help--block">密码输入错误，请重新输入</span>
    </div>
    <div class="form__action">
        <select name="">
            <option value="">请选择</option>
        </select>
    </div>
    <div class="form__action">
        <label class="remeber">
            <input type="checkbox">记住我
        </label>
    </div>
    <div class="form__action">
        <button class="btn-submit" data-js="submit">提交</button>
    </div>
</form>
```
## 盒子
```html
<div class="box">
    <div class="box__hd">
        <i class="box__icon"></i>
        <h3 class="box__title">标题</h3>
        <div class="box__act">
            <a href="#">更多&raquo;</a>
        </div>
    </div>
    <div class="box__bd">

    </div>
    <div class="box__ft">

    </div>
</div>
```
## 图片列表
```html
<ul class="list list--picture">
    <li>
        <a href="#">
            <img alt="" src="http://art.yypm.com/130x90">
            <em></em>
            <i class="icon-play"></i>
        </a>
    </li>
</ul>
```
## 文章列表
```html
<ul class="list list--article">
    <li>
        <a href="#"></a>
        <time></time>
    </li>
</ul>
```
