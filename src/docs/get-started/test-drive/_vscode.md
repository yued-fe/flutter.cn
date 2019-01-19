<div class="tab-pane" id="vscode" role="tabpanel" aria-labelledby="vscode-tab" markdown="1">

## Create the app

## 创建应用

  1. Invoke **View > Command Palette**.
  
     在菜单中选择 **View > Command Palette**。
  1. Type "flutter", and select the **Flutter: New Project**.
  
     在输入框中输入「flutter」，然后点击选择 **Flutter: New Project**。
  1. Enter a project name, such as `myapp`, and press **Enter**.
  
     输入新建项目名，例如「myapp」，然后按 **回车键**。
  1. Create or select the parent directory for the new project folder.
  
     选择已有文件夹或是新建文件夹作为项目代码存放的根目录。
  1. Wait for project creation to complete and the `main.dart`
     file to appear.
     
     等待项目创建完成以及编辑器自动打开「main.dart」。

The above commands create a Flutter project directory called `myapp` that
contains a simple demo app that uses [Material Components][].

以上步骤将创建一个名为「myapp」的 Flutter 项目，其中包含一个使用 [Material Components][] 构建的简单 app 。  

{% include_relative _main-code-note.md  %}

## Run the app

## 运行 app 

 1. Locate the VS Code status bar (the blue bar at the bottom of the
    window):<br> ![status bar][]{:width="450px"}
    
    找到 VS Code 的状态栏（打开窗口底部的蓝色工具栏）:<br> ![status bar][]{:width="450px"}
 1. Select a device from the **Device Selector** area.
    For details, see [Quickly switching between Flutter devices][].
    
    在 **Device Selector** 栏目中选择运行设备。更多详情请查看 [Quickly switching between Flutter devices][] 。
    - If no device is available and you want to use a device simulator,
      click **No Devices** and launch a simulator.
      
      如果没有可用的运行设备，而且您想要使用模拟器来运行项目代码，点击 **No Devices** 来运行模拟器。
    - To setup a real device, follow the device-specific instructions on the
      [Install][] page for your OS.
      
      根据 [Install][] 页面中的教程来设置可用设备，使你的项目代码运行在您的手机设备上。
 1. Invoke **Debug > Start Debugging** or press <kbd>F5</kbd>.
 
    在菜单栏中选择 **Debug > Start Debugging** 或者直接按下 <kbd>F5</kbd> 。 
 1. Wait for the app to launch &mdash; progress is printed
    in the **Debug Console** view.
    
    等待 app 运行 &mdash; 运行进度将显示在 **Debug Console** 上。

{% capture save_changes -%}
  : invoke **File > Save All**,
  or click **Hot Reload** (the green circular arrow button).
{% endcapture %}

{% capture save_changes -%}
  : 在菜单栏中选择 **File > Save All**,
  或者直接点击 **Hot Reload** （那个绿色的圆形按钮）。
{% endcapture %}

{% include_relative _try-hot-reload.md save_changes=save_changes %}

[Install]: /docs/get-started/install
[Material Components]: https://material.io/guidelines
[Quickly switching between Flutter devices]: https://dartcode.org/docs/quickly-switching-between-flutter-devices
[status bar]: {% asset tools/vs-code/device_status_bar.png @path %}

</div>
