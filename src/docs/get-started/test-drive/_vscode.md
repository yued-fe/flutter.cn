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

以上步骤

{% include_relative _main-code-note.md  %}

## Run the app

 1. Locate the VS Code status bar (the blue bar at the bottom of the
    window):<br> ![status bar][]{:width="450px"}
 1. Select a device from the **Device Selector** area.
    For details, see [Quickly switching between Flutter devices][].
    - If no device is available and you want to use a device simulator,
      click **No Devices** and launch a simulator.
    - To setup a real device, follow the device-specific instructions on the
      [Install][] page for your OS.
 1. Invoke **Debug > Start Debugging** or press <kbd>F5</kbd>.
 1. Wait for the app to launch &mdash; progress is printed
    in the **Debug Console** view.

{% capture save_changes -%}
  : invoke **File > Save All**,
  or click **Hot Reload** (the green circular arrow button).
{% endcapture %}

{% include_relative _try-hot-reload.md save_changes=save_changes %}

[Install]: /docs/get-started/install
[Material Components]: https://material.io/guidelines
[Quickly switching between Flutter devices]: https://dartcode.org/docs/quickly-switching-between-flutter-devices
[status bar]: {% asset tools/vs-code/device_status_bar.png @path %}

</div>
