# webdriver client for go

## About

貌似原作者不再维护，故此`fork`次仓库，以支持`chrome devtools procotol`的操作.
感谢原作者花费时间及精力贡献此组件包.

[cdp-example](./example_test.go)

## About

This is a [WebDriver][selenium] client for [Go][go]. It supports the
[WebDriver protocol][webdriver] and has been tested with various versions of
[Selenium WebDriver][selenium], Firefox and [Geckodriver][geckodriver], and
Chrome and [ChromeDriver][chromedriver],

`selenium` is currently maintained by Eric Garrido ([@minusnine][minusnine]).

[selenium]: http://seleniumhq.org/
[webdriver]: https://www.w3.org/TR/webdriver/
[go]: http://golang.org/
[server]: http://seleniumhq.org/download/
[geckodriver]: https://github.com/mozilla/geckodriver
[chromedriver]: https://sites.google.com/a/chromium.org/chromedriver/
[minusnine]: http://github.com/minusnine

## Installing

Run

    go get -t -d github.com/stitch-june/selenium

to fetch the package.

The package requires a working WebDriver installation, which can include recent
versions of a web browser being driven by Selenium WebDriver.


## License

This project is licensed under the [MIT][mit] license.

[mit]: https://raw.githubusercontent.com/tebeka/selenium/master/LICENSE
