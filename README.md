# bilibili-parse

> bilibili 视频解析 API

## Descriptions

| 参数名 |     含义     | 默认  |       可选       |
| :----: | :----------: | :---: | :--------------: |
|   av   | 视频 av 编号 |       |        -         |
|   bv   | 视频 bv 编号 |       |        -         |
|   ep   |   剧集编号   |       |        -         |
|   p    |   视频集数   |   1   |       >=1        |
|   q    |  视频清晰度  |  32   |   16/32/64/80    |
|  type  |   视频类型   | video |  video/bangumi   |
| format |   视频格式   |  flv  |   flv/dash/mp4   |
| otype  |   输出格式   | json  | json/url/dplayer |

## Demo

- [https://api.injahow.cn/bparse/?av=14661594&p=1&q=64&otype=json](https://api.injahow.cn/bparse/?av=14661594&p=1&q=64&otype=json)
- [https://api.injahow.cn/bparse/?av=14661594&p=2&q=32&otype=url](https://api.injahow.cn/bparse/?av=14661594&p=2&q=32&otype=url)
- [https://api.injahow.cn/bparse/?av=14661594&p=1&format=mp4&otype=json](https://api.injahow.cn/bparse/?av=14661594&p=1&format=mp4&otype=json)
- [https://api.injahow.cn/bparse/?av=14661594&p=1&otype=dplayer](https://api.injahow.cn/bparse/?av=14661594&p=1&otype=dplayer)

## Tools

- [bilibili-parse-download](https://github.com/injahow/user.js/tree/main/bilibili-parse-download)

## Requirement

PHP 5.4+ and Curl, OpenSSL extension installed.

## License

[MIT](https://github.com/injahow/bilibili-parse/blob/master/LICENSE) license.

Copyright (c) 2019 injahow
