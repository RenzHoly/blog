#Android 中的设计模式
##创建型模式
###Builder 生成器
将一个复杂对象的构建与它的表示分离，使得同样的构建过程可以创建不同的表示。
>[AlertDialog.Builder](http://developer.android.com/reference/android/app/AlertDialog.Builder.html)

###Factory Method 工厂方法
定义一个用于创建对象的接口，让子类决定实例化哪一个类。Factory Method 使一个类的实例化延迟到其子类。
>[BitmapFactory](http://developer.android.com/reference/android/graphics/BitmapFactory.html)

###Singleton 单件
保证一个类仅有一个实例，并提供一个访问他的全局访问点。
>[LayoutInflater](http://developer.android.com/reference/android/view/LayoutInflater.html)

##结构型模式
###Adapter 适配器
将一个类的接口转换成客户端希望的另外一个接口。Adapter 模式使得原本由于接口不兼容而不能一起工作的那些类可以一起工作。
>[RecyclerView.Adapter](http://developer.android.com/reference/android/support/v7/widget/RecyclerView.Adapter.html)

###Bridge 桥接
将抽象部分与它的实现部分分离，使它们都可以独立地变化。
>[AppCompatDelegate](http://developer.android.com/reference/android/support/v7/app/AppCompatDelegate.html)

###Composite 组成
将对象组合成树形结构以表示“部分－整体”的层次结构。Composite 使得用户对单个对象核组合对象的使用具有一致性。
>[View](http://developer.android.com/reference/android/view/View.html)

###Decorator 装饰
动态地给对象添加一些额外的职责。就增加功能来说，Decorator 模式相比生成子类更为灵活。
>[RecyclerView.ItemDecoration](http://developer.android.com/reference/android/support/v7/widget/RecyclerView.ItemDecoration.html)

###Facade 外观
为子系统中的一组接口提供一个一致的界面，Facade 模式定义了一个高层接口，这个接口使得这一子系统更加容易使用。
>[ContextImpl](https://android.googlesource.com/platform/frameworks/base/+/android-6.0.1_r16/core/java/android/app/ContextImpl.java)

###Flyweight 享元
运用共享技术有效地支持大量细粒度的对象。
>[RecyclerView.RecycledViewPool](http://developer.android.com/reference/android/support/v7/widget/RecyclerView.RecycledViewPool.html)

###Proxy 代理
为其它对象提供一种代理以控制对这个对象的访问。
>[ContextWrapper](http://developer.android.com/reference/android/content/ContextWrapper.html)

##行为模式
###Strategy 策略
定义一系列的算法，把它们一个个封装起来，并且使它们可互相替换。本模式使得算法可独立于使用它的客户而变化。
>[RecyclerView.LayoutManager](http://developer.android.com/reference/android/support/v7/widget/RecyclerView.LayoutManager.html)