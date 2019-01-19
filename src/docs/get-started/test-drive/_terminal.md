<div class="tab-pane" id="terminal" role="tabpanel" aria-labelledby="terminal-tab" markdown="1">

## Create the app

## 创建项目

Use the `flutter create` command to create a new project:

使用 `flutter create` 命令来创建一个新的项目：

```terminal
$ flutter create myapp
$ cd myapp
```

The command creates a Flutter project directory called `myapp` that
contains a simple demo app that uses
[Material Components](https://material.io/guidelines/).

以上步骤将创建一个名为「myapp」的 Flutter 项目，其中包含一个使用 [Material Components](https://material.io/guidelines/) 构建的简单 app 。

{% include_relative _main-code-note.md  %}

## Run the app

## 运行 app

 1. Check that an Android device is running. If none are shown, follow the
    device-specific instructions on the [Install][] page for your OS.
    
    检查 Android 设备是否正常运行中。若设备没有正常显示，查看 [Install][] 教程查看解决方法。 

    ```terminal
    $ flutter devices
    ```

 2. Run the app with the following command:
 
    使用一下命令来运行 app 。

    ```terminal
    $ flutter run
    ```

{% capture save_changes -%}
.
1. 在命令行中按 <kbd>r</kbd> 。 
{% endcapture %}

{% include_relative _try-hot-reload.md save_changes=save_changes %}

[Install]: /docs/get-started/install
</div>
