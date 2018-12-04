# pull-down-banner
a pull down translate the banner script.

## use like this:
```javascript
var pull = new pullDownBanner({
    dragger: '.main',
    banner: '.banner-img'
});
pull.on('refresh', function () {
    console.log('pull begin');
    setTimeout(function () {
        pull.emit('success');
    }, 100)
});
```

## preview
> * [click here](https://yangyuji.github.io/pull-down-banner/demo.html)
> * ![qrcode](https://github.com/yangyuji/pull-down-banner/blob/master/qrcode.png)

## License
> * copyright(c) 2018 oujizeng Licensed under MIT license.
