# HWScreenRecord
集成到APP里面，可以录制手机屏幕同时录制音频
用法很简单
1、将HWScreenRecord.h和HWScreenRecord.m拖入自己的项目中
#import "HWScreenShow.h"
2、调用
[[将HWScreenRecord shareInterface] prepareForRecording];
准备就绪
3、调用
[[将HWScreenRecord shareInterface] startRecording];
开始录制屏幕
4、调用
[[将HWScreenRecord shareInterface] stopRecording];
结束录制

如果需要手势支持请添加
KTouchPointerWindow
https://github.com/itok/KTouchPointerWindow
