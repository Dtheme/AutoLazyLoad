# Xcode-AutoLazyLoad


## Xcode-AutoLazyLoad使用

打开Xcode工程，选中指定需要懒加载的那一行，在系统上面的toolbar中选中选择edit-AutoLazyLoad，执行指定的插件指令，或者在xcode的偏好设置中添加你喜欢的快捷键，选中需要懒加载的属性那一行快捷键生成属性的懒加载代码。

Xcode 8的插件是以扩展的形式使用的，类似于sifari插件的形式。
，在mac中以.app的形式安装，在系统偏好设置-扩展中-选中已经安装的

#### 安装

1. 使用你自己的证书签名AutoLazyLoad
2. build工程
3. 拷贝`products`目录中的`AutoLazyLoad.app`到你的应用程序中。
4. 打开`AutoLazyLoad.app`,再关掉。只有首次安装需要这个操作。
5. 打开系统的`偏好设置-扩展`，勾选上`lazyload`。
6. 重启xcode就可以使用啦。
7. 如果有需要可以去xcode的偏好设置中设置快捷键，我是用`option+'`作为快捷键
8. 选中你要生成懒加载的属性，按下`option+'`就好啦。

#### 移除

如果不想使用了，在系统的应用程序中删除`lazyLoad.app`，就可以了.



#### usage：

1. Setup Code Signing for Target `AutoLazyLoad` by applying your own Team
2. Build Target `AutoLazyLoad`
3. Copy `AutoLazyLoad.app` from `Products` to your `Applications` folder
4. Open `AutoLazyLoad.app` then close it
5. Open `Preference - Extension` of macOS, make sure `lazyLoad` is selected as Xcode Source Editor
6. Restart Xcode and enjoy it.
7. add shortcuts if you like, I'm using `option+'`as the shortcuts.
8. Select the property you want to generate lazy-load code and press `option+'`,done.

#### remove：

If you don't need it anymore, Just remove  `AutoLazyLoad.app` from the `../Applications/` folder.