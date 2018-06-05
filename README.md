# JS_OC
计划整理的JS与OC调用的系列包括：
* 1.在JS 中做一次URL跳转，然后在OC中拦截跳转。（这里分为UIWebView 和 WKWebView两种，去年因为还要兼容iOS 6，所以没办法只能采用UIWebView来做。）
* 2.利用WKWebView 的MessageHandler。
* 3.利用系统库JavaScriptCore，来做相互调用。（iOS 7推出的）
* 4.利用第三方库WebViewJavascriptBridge。
* 5.利用第三方cordova库，以前叫PhoneGap。（这是一个库平台的库）
* 6.当下盛行的React Native。

## JS_OC_summary
是2015年中整理的两种调用方式,包括通过URL和JavaScriptCore来实现调用<br>
在最新的示例中都有做更新和优化。<br>

## JS_OC_URL
展示了UIWebView和WKWebView通过URL来实现JS调用原生OC的示例。
在JS_OC_summary的基础上有了点小小的优化。<br>
## JS_OC_MessageHandler
是利用WKWebView提供的新的API实现的JS调用原生OC,更简洁和方便。<br>
相关文章地址：<br>

## JS_OC_JavaScriptCore
是利用JavaScriptCore框架来实现JS与OC相互调用的示例。<br>

## JS_OC_WebViewJavascriptBridge
是通过第三方框架WebViewJavascriptBridge来实现JS与OC交互的示例。<br>
## JS_OC_Cordova
是通过第三方框架Cordova来实现JS与OC交互的示例。<br>



