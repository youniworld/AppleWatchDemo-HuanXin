# AppleWatchDemo-HuanXin
此项目简单演示Apple Watch Kit 如何集成环信的SDK
current only few features were implemented but subject to be implemented more in future

##InterfaceController
Apple Watch App Extension bridge implementation，which is the bridge connecting to IOS App

##AppDelegate
###IOS App delegate
This is the interface which should be implemented to handle the request sent from Apple Watch Kit Extention

>func application(application: UIApplication!, handleWatchKitExtensionRequest userInfo: [NSObject : AnyObject]!, reply: (([NSObject : AnyObject]!) -> Void)!)

##HXSDKHelper
The helper class of HuanXin SDK in which only one sendTextMessage is implemented but more helper APIs will be implemented in this class.

>请重新导入环信 IM SDK(please reimport HuanXin IM SDK)
