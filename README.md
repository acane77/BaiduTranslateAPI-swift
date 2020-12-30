# Baidu Translate General API in Swift

## Usage

Copy `BaiduTranslate.swift` to your project directory, and call like this.

```swift
translateUsingBaiduTranslateAPIAsync(
    textToTranslate: "Hello world!", 
    langFrom: "auto", 
    langTo: "zh", 
    appID: "<Your AppID>", 
    appKey: "<Your AppKey>",
    onComplete:  { (ret: String) in 
        print('Result: \(ret)')
        // do other stuffs
    }
)
```

For more information, see [offical API document](https://fanyi-api.baidu.com/doc/21).