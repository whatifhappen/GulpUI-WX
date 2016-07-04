### Autoprefixer

#### 介绍

[PostCSS](https://github.com/postcss/postcss)插件之一，用于解析CSS，并根据Can I Use的CSS规范补全前缀。Google推荐使用，Twitter和淘宝已经应用在项目中。

#### 编写标准化CSS

只需要根据W3C规范写CSS，Autoprefixer会自动补全旧浏览器的代码。

//默认使用webkit兼容（Android 2.3, ios 6.0), 可更换成IE兼容
```css
a {
    display: flex;
}
```

```css
a {
  display: -webkit-box;
  display: -webkit-flex;
  display: flex;
}
```

### Browsersync

####省时的浏览器同步测试工具

Browsersync能让浏览器实时、快速响应您的文件更改（html、js、css、sass、less等）并自动刷新页面。更重要的是 **Browsersync可以同时在PC、平板、手机等设备下进项调试**。您可以想象一下：“假设您的桌子上有pc、ipad、iphone、android等设备，同时打开了您需要调试的页面，当您使用browsersync后，您的任何一次代码保存，以上的设备都会同时显示您的改动”。无论您是前端还是后端工程师，使用它将提高您30%的工作效率。（节选自[Browsersync中文网](http://www.browsersync.cn/))）

![sync-demo](../images/sync-demo.gif)

### babel

Babel是一个转换编译器，它能将ES6转换成可以在浏览器中运行的向后兼容的js代码

```js
// ES6
// Expression bodies
var odds = evens.map(v => v + 1);
var nums = evens.map((v, i) => v + i);

// Statement bodies
nums.forEach(v => {
  if (v % 5 === 0)
    fives.push(v);
});
```

```js
//babel编译后
// Expression bodies
var odds = evens.map(function (v) {
  return v + 1;
});
var nums = evens.map(function (v, i) {
  return v + i;
});

// Statement bodies
nums.forEach(function (v) {
  if (v % 5 === 0) fives.push(v);
});
```

### csswring
[PostCSS](https://github.com/postcss/postcss)插件之一, 用于压缩CSS代码

### gulp-cached
[gulp-cached](https://www.npmjs.com/package/gulp-cached)一个简单的缓存文件机制。

### gulp-concat
[gulp-concat](https://www.npmjs.com/package/gulp-concat)合并文件

### del
[del](https://www.npmjs.com/package/del)删除文件/目录，用于编译目录的时候清理


### gulp-file-include
[gulp-file-include](https://www.npmjs.com/package/gulp-file-include)引用文件


### gulp-if
[gulp-if](https://www.npmjs.com/package/gulp-if)判断


### gulp-ignore
[gulp-ignore](https://www.npmjs.com/package/gulp-ignore)忽略文件


### gulp-imagemin
[gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin) 图片压缩


### imagemin-mozjpeg
[imagemin-mozjpeg](https://www.npmjs.com/package/imagemin-mozjpeg) mozjpeg插件


### imagemin-pngquant
[imagemin-pngquant](https://www.npmjs.com/package/imagemin-pngquant) pngquant插件


### imagemin-svgo
[imagemin-svgo](https://www.npmjs.com/package/imagemin-svgo) svgo插件


### gulp-jshint
[gulp-jshint](https://www.npmjs.com/package/gulp-jshint) jshint代码检测插件


### gulp-plumber
[gulp-plumber](https://www.npmjs.com/package/gulp-plumber) 发生错误不会中断流程

### gulp-postcss
[gulp-postcss](https://www.npmjs.com/package/gulp-postcss)
[PostCSS](https://github.com/postcss/postcss)处理css多个流程，但只编译css一次


### gulp-prettify
[gulp-prettify](https://www.npmjs.com/package/gulp-prettify)代码格式化插件

### run-sequence
[run-sequence](https://www.npmjs.com/package/run-sequence) 用于运行一系列排序任务


### gulp-rename
[gulp-rename](https://www.npmjs.com/package/gulp-rename) 用于重命名文件，可用作修改根目录位置

### gulp-replace
[gulp-replace](https://www.npmjs.com/package/gulp-replace) 正则匹配替换插件

### stream-combiner2
[stream-combiner2](https://www.npmjs.com/package/stream-combiner2) 运行多个任务时，合并错误提示，延后输出

### gulp-sourcemaps
[gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps) 用于解析编译后的文件并提供源码文件对应的地址


### gulp-size
[gulp-size](https://www.npmjs.com/package/gulp-size) 输出文件大小

### gulp.spritesmith
[gulp.spritesmith](https://www.npmjs.com/package/gulp.spritesmith) 雪碧图插件


### gulp-uglify
[gulp-uglify](https://www.npmjs.com/package/gulp-uglify) js代码压缩插件

### gulp-using
[gulp-using](https://www.npmjs.com/package/gulp-using) 插件依赖

### gulp-util
[gulp-util](https://www.npmjs.com/package/gulp-util)


### gulp-watch
[gulp-watch](https://www.npmjs.com/package/gulp-watch) 文件监听插件（增删改），不主动中断.




















