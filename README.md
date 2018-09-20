# xuanhuan

xuanhuan is a **modern css framework** based on [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes).

## install

```
npm install xuanhuan
```

## usage

### importing precompiled sass

To enjoy the full potential of xuanhuan and customize it to your needs, use the source files as a part of your project's bundling process.

First, create your own \_custom.scss and use it to override the [built-in custom variables](https://github.com/otfngo/xuanhuan/blob/master/scss/_variables.scss). Then, use your main sass file to import your custom variables, followed by xuanhuan:

```
@import 'custom';
@import '~xuanhuan/scss/xuanhuan';
```

### importing compiled css

Alternatively, you may use xuanhuan's ready-to-use CSS by simply adding this line to your project's entry point:

```
import 'xuanhuan/dist/xuanhuan.min.css'
```

## browser support

xuanhuan uses [autoprefixer](https://github.com/postcss/autoprefixer) to makr(most) Flexbox features compatible with earlier browser versions. According to [Can I use](https://caniuse.com/#feat=flexbox), xuanhuan is compatible with **recent** versions of:

- Chrome
- Edge
- Firefox
- Opera
- Safari

Internet Explorer(10+) is only partially supported.

## copyright and license

Code copyright 2018 otfngo. Code released under [the MIT license](https://github.com/otfngo/xuanhuan/blob/master/LICENSE).
