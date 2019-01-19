After the app build completes, you'll see the starter app on your device.

当 app 构建完成之后，你将会看到 app 运行在你所选择的运行设备上。

{% include app-figure.md img-class="site-mobile-screenshot border"
    path-prefix="get-started" platform="iOS" image="starter-app.png"
    caption="Starter app" %}

## Try hot reload

## 尝试 hot reload

Flutter offers a fast development cycle with _hot reload_, the ability to reload
the code of a live running app without restarting or losing app state.
Make a change to app source, tell your IDE or command-line tool that you
want to hot reload, and see the change in your simulator, emulator, or device.

Flutter 提供了 _hot reload_ 快速开发特性，这能够让你无需重新打开 app 而且能保持当前 app 运行状态来加载代码的能力。
在对项目代码进行修改之后，通过 IDE 或者命令行进行 hot reload ，你将马上看到你的修改展示在你所选择的运行设备上。

 1. Open `lib/main.dart`.
 
    打开 `lib/main.dart` 。
 1. Change the string
    <code class="text-nowrap">
    'You have <del>pushed</del> the button this many times'
    </code>
    to
    <code class="text-nowrap">
      'You have <ins>clicked</ins> the button this many times'
    </code>.
    
    将
    <code class="text-nowrap">
    'You have <del>pushed</del> the button this many times'
    </code>
    修改为
    <code class="text-nowrap">
      'You have <ins>clicked</ins> the button this many times'
    </code> 。

    {{site.alert.important}}
      Do _not_ stop your app. Let your app run.
    {{site.alert.end}}
    
    {{site.alert.important}}
      _不需_停止运行中的 app 。
    {{site.alert.end}}

 1. Save your changes{{include.save_changes}}
    保存你所做的修改。

You'll see the updated string in the running app almost immediately.

你将马上看到运行中的 app 做出更新。

