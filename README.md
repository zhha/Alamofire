在[Alamofire 4.0.1](https://github.com/Alamofire/Alamofire)的版本中去掉了一些iOS 9的新特性，可以在`iOS 8.x`，`swift 3.0`环境下运行。

具体去掉的内容可在工程中搜索`// MARK: 适配iOS 8`查看。

使用时在Podfile中添加即可：
`pod 'Alamofire', :git => 'https://github.com/zhha/Alamofire'`
