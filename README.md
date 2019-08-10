# static-files-host

> Static files host for [gooreplacer](https://github.com/jiacai2050/gooreplacer)

## Redirect rules

### Domains

| Source | Destination | Enabled |
| ------ | ----------- | ------- |
| www.google.com | www.google.cn | `false` |
| developers.google.com | developers.google.cn | `true` |
| developer.android.com | developer.android.google.cn | `true` |
| source.android.com | source.android.google.cn | `true` |
| golang.org | golang.google.cn | `true` |
| tensorflow.org | tensorflow.google.cn | `true` |
| maps.google.com | ditu.google.cn | `true` |
| translate.google.com | translate.google.cn | `true` |
| www.gstatic.com | www.gstatic.cn | `true` |
| clients1.google.com | clients1.google.cn | `true` |
| ajax.googleapis.com | ajax.proxy.ustclug.org | `false` |

### Files

| Source | Destination | Enabled |
| ------ | ----------- | ------- |
| www.google.com/js/google.js | www.google.cn/js/google.js | `true` |
| www.google.com/recaptcha/api.js | recaptcha.net/recaptcha/api.js | `true` |
| apis.google.com/js/api.js | cdn.jsdelivr.net/npm/static-files-host/public/apis.google.com/js/api.js | `true` |
| apis.google.com/js/platform.js | cdn.jsdelivr.net/npm/static-files-host/public/apis.google.com/js/platform.js | `true` |
| apis.google.com/js/plusone.js | cdn.jsdelivr.net/npm/static-files-host/public/apis.google.com/js/plusone.js | `true` |
| platform.twitter.com/oct.js | cdn.jsdelivr.net/npm/static-files-host/public/platform.twitter.com/oct.js | `true` |
| platform.twitter.com/widgets.js | cdn.jsdelivr.net/npm/static-files-host/public/platform.twitter.com/widgets.js | `true` |
| labs.mysql.com/common/js/site-20180426.min.js | cdn.jsdelivr.net/npm/static-files-host/public/labs.mysql.com/common/js/site-20180426.min.js | `true` |

## License

MIT
