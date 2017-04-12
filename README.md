# CodeSnippet
Xcode自定义代码块，让开发更加效率

### 你可以在Xcode中自定义自己的代码块，设置自己习惯的shorcut

### 书写自己的代码片段
```objc
//属性
@property (nonatomic, <#type#>) <#class#> * <#propertyName#>;
//interface
@interface <#class#> : <#superClass#>
{

}
//implementation
@implementation <#class#>
{

}
//prototol
@protocol <#protocol name#> <#superClass#>

<#methods#>

@end
//可以根据自己的喜好设置各种代码段。
```

### 将自己写好的代码段拖拽到Code Snippet Library
1. 点击Xcode->View->Utilities->Show Code Sinppet Library，可以快速定位到Code Snippet Libray。<br/>
2. 会弹出一个Code Snippet,你可以设置一个标题（可以写中文😯）、语言、平台、快捷键。

### 设置完成后可以在Xcode中立即使用。

### 代码段备份位置
```swift
Xcode中的代码片段默认放在下面的目录中：

~/Library/Developer/Xcode/UserData/CodeSnippets

我们可以将目录中的代码片段备份，也可以将其直接拷出来放在不同的电脑上使用，因此多台电脑之间的协作也毫无压力。
```
### 我的宗旨，无论事无巨细，好记性不如烂笔头！
