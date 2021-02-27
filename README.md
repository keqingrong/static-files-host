# static-files-host

[![npm version](https://img.shields.io/npm/v/static-files-host.svg)](https://www.npmjs.com/package/static-files-host)

> Static files host for [gooreplacer](https://github.com/jiacai2050/gooreplacer)

Online rules at [jsDelivr](https://cdn.jsdelivr.net/npm/static-files-host/json/gooreplacer.json)

## Redirect rules

### Domains

| Source | Destination | Enabled |
| ------ | ----------- | ------- |
| www.google.com | www.google.cn | `false` |
| maps.google.com | ditu.google.cn | `false` |
| translate.google.com | translate.google.cn | `true` |
| clients1.google.com | clients1.google.cn | `true` |
| developers.google.com | developers.google.cn | `true` |
| developer.android.com | developer.android.google.cn | `true` |
| source.android.com | source.android.google.cn | `true` |
| golang.org | golang.google.cn | `true` |
| tensorflow.org | tensorflow.google.cn | `true` |
| www.gstatic.com | www.gstatic.cn | `true` |
| fonts.gstatic.com | fonts-gstatic.lug.ustc.edu.cn | `false` |
| ajax.googleapis.com | ajax.proxy.ustclug.org | `false` |
| fonts.googleapis.com | fonts.lug.ustc.edu.cn | `false` |
| themes.googleusercontent.com | google-themes.lug.ustc.edu.cn | `false` |

### Files

| Source | Destination | Enabled |
| ------ | ----------- | ------- |
| www.google.com/js/google.js | www.google.cn/js/google.js | `true` |
| www.google.com/recaptcha/api.js | recaptcha.net/recaptcha/api.js | `true` |
| ajax.googleapis.com/ajax/libs/webfont/1/webfont.js | cdn.jsdelivr.net/npm/webfontloader@1/webfontloader.js | `true` |
| apis.google.com/js/api.js | cdn.jsdelivr.net/npm/static-files-host/public/apis.google.com/js/api.js | `true` |
| apis.google.com/js/platform.js | cdn.jsdelivr.net/npm/static-files-host/public/apis.google.com/js/platform.js | `true` |
| apis.google.com/js/plusone.js | cdn.jsdelivr.net/npm/static-files-host/public/apis.google.com/js/plusone.js | `true` |
| platform.twitter.com/oct.js | cdn.jsdelivr.net/npm/static-files-host/public/platform.twitter.com/oct.js | `true` |
| platform.twitter.com/widgets.js | cdn.jsdelivr.net/npm/static-files-host/public/platform.twitter.com/widgets.js | `true` |
| labs.mysql.com/common/js/site-20180426.min.js | cdn.jsdelivr.net/npm/static-files-host/public/labs.mysql.com/common/js/site-20180426.min.js | `true` |

## License

MIT
