# GeneralUtilDeps
常用工具库

### Model

[AFNetworking]( https://github.com/AFNetworking/AFNetworking)  网络

[MJExtension](https://github.com/CoderMJLee/MJExtension)  数模转换

[ReactiveObjC](https://github.com/ReactiveCocoa/ReactiveObjC) 响应式编程

### UI

[LookinServer](https://github.com/QMUI/LookinServer)  UI调试工具

 pod 'LookinServer', :configurations => ['Debug']

```objective-c
pod 'LookinServer', :configurations => ['Debug']
```

[Masonry](https://github.com/SnapKit/Masonry) 自动布局

[IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) 键盘

[DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) 列表空数据显示

[MJRefresh](https://github.com/CoderMJLee/MJRefresh) 上下拉刷新

[SDCycleScrollView](https://github.com/gsdios/SDCycleScrollView) 轮播

[SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) 提示信息

[MBProgressHUD](https://github.com/jdg/MBProgressHUD) 提示信息

[TZImagePickerController](https://github.com/banchichen/TZImagePickerController) 图片选择器

[TOCropViewController](https://github.com/TimOliver/TOCropViewController) 图片剪辑

[WeScan](https://github.com/WeTransfer/WeScan)  文档轮廓扫描识别

### Utils

[YYKit](https://github.com/ibireme/YYKit)



#### Podfile 汇总

```objective-c
source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '11.0'
inhibit_all_warnings!
install! 'cocoapods', :disable_input_output_paths => true
#use_frameworks!

target 'xxx' do
  # 视图调试工具
  pod 'LookinServer', :configurations => ['Debug']
  
  pod 'AFNetworking'
  pod 'MJExtension'
  pod 'IQKeyboardManager'
  pod 'DZNEmptyDataSet'
  pod 'MJRefresh'
  pod 'YYKit'

  pod 'SDCycleScrollView'
  pod 'SVProgressHUD'
  pod 'TZImagePickerController', '~> 3.5.2'
  pod 'TOCropViewController'
  pod 'Masonry'
  
#  pod 'ReactiveCocoa', '~> 10.1'
  pod 'ReactiveObjC'
end
```

