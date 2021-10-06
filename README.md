# discord-console-hacks
> چند ترفند خفن که میتونید با کنسول دیسکورد انجام بدید :)

## 🚀 شروع

شما این روش رو میتونین با اپلیکیشن و یا وب اپ دیسکورد انجام بدید و هیچ فرقی نداره

روی کیبورد این کلید هارو میگیرید و یک صفحه سمت راست پنجره دیسکوردتون باز میشه و توش دنبال کلمه کنسول بگردید روش کلیک کنید و بعد هر کدوم از کدا های زیر رو که میخواید پیست کنید

<br />
<br />


<p>گرفتن برچسب سیستم دیسکورد</p>

```
var findModule = (item) => Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}}, [['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default[item]!==void 0).exports.default;
findModule('getCurrentUser').getCurrentUser().system = true;
```

<hr />

<p>عوض کردن نام برچسب</p>

```
var findModule = (item) => Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}}, [['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default[item]!==void 0).exports.default;
findModule('Messages').Messages.SYSTEM_DM_TAG_SYSTEM = 'New_Tag_Name';
```

<hr />

<p>گرفتن تمام بدج ها</p>

```
Object.values(webpackJsonp.push([[],{[''] :(_,e,r)=>{e.cache=r.c}},
[['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default.getCurrentUser!==void
0).exports.default.getCurrentUser().flags=-33
```

<hr />

<p>گرفتن برچسب ربات دیسکورد</p>

```
var findModule = (item) => Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}}, [['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default[item]!==void 0).exports.default;
findModule('getCurrentUser').getCurrentUser().bot = true;
```

<hr />

<p>گرفتن توکن اکانت</p>

```
   Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}},[['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default.getToken!==void 0).exports.default.getToken()
```

<hr />

<p>لاگین با توکن</p>

```
   function login(token) {
setInterval(() => {
document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
}, 50);
setTimeout(() => {
location.reload();
}, 200);
}
  login("TOKEN_HERE")
```

<hr />

<p>اسکرین شات فیک</p>

```
   document.designMode = 'on'
```

<hr />

<p>وریفای کردن سرور</p>

```
   Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}},[['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default.getGuilds!==void 0).exports.default.getGuild('SERVERID').features.add('VERIFIED')
```

<hr />


<p>پارتنر کردن سرور</p>

```
   Object.values(webpackJsonp.push([[],{['']:(_,e,r)=>{e.cache=r.c}},[['']]]).cache).find(m=>m.exports&&m.exports.default&&m.exports.default.getGuilds!==void 0).exports.default.getGuild('SERVERID').features.add('PARTNERED')
```


![DM me Discord](https://discord.c99.nl/widget/theme-1/488958506280550402.png)
