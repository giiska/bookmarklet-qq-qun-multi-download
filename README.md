# 用法
一. 在 chrome 中打开 qq 群文件下载页面，打开 Develop Tools 的 Console ，粘贴以下代码。

```js
var a = document.getElementsByClassName('btn_c btn_c_h20');
for(var i in a) {
  if(a[i]) { 
    a[i].click(); 
    console.log('已完成：', i + 1); 
  } 
}
```

二. 按下 `Enter` 键，将执行以上代码，自动下载当前页面中的所有文件。

三. 翻页后需要再粘贴执行一次。
