# 删除 Visual Studio | Microsoft Docs
-   2019/12/19

### 本文内容

1.  [运行 InstallCleanup.exe](#run-installcleanupexe)

如果遇到灾难性错误，并且无法修复或卸载 Visual Studio，可运行 `InstallCleanup.exe` 工具，以删除 Visual Studio 2017 或 Visual Studio 2019 的所有已安装实例的安装文件和产品信息。If you experience a catastrophic error and can't repair or uninstall Visual Studio, you can run the `InstallCleanup.exe` tool to remove installation files and product information for all installed instances of Visual Studio 2017 or Visual Studio 2019.

警告

InstallCleanup 工具仅作为修复或卸载失败时在不得已情况下采用的一种方法 。Use the InstallCleanup tool **only as a last resort** if repair or uninstall fail. 此工具可能会从其他 Visual Studio 安装或其他产品中卸载功能，可能还需要修复或重新安装这些功能。This tool might uninstall features from other Visual Studio installations or other products, which then might also need to be repaired or reinstalled.

## [](#run-installcleanupexe)运行 InstallCleanup.exeRun InstallCleanup.exe

可以将以下任一命令行开关与 `InstallCleanup.exe` 工具结合使用：You can use either of the following command-line switches with the `InstallCleanup.exe` tool:

以下是运行 `InstallCleanup.exe` 工具的方法：Here's how to run the `InstallCleanup.exe` tool:

1.  关闭 Visual Studio 安装程序。Close the Visual Studio Installer.
2.  打开管理员命令提示符。Open an administrator command prompt. 要打开管理员命令提示符，请执行以下步骤：To open an administrator command prompt, follow these steps:

    -   在 “在此键入进行搜索” 框中键入“cmd” 。Type **cmd** in the "Type here to search" box.
    -   右键单击 “命令提示符” ，然后选择 “以管理员身份运行” 。Right-click **Command Prompt**, and then choose **Run as administrator**.
3.  输入 `InstallCleanup.exe` 工具的完整路径，并添加所需的命令行开关。Enter the full path of the `InstallCleanup.exe` tool and add the command-line switch you prefer. 默认情况下，此工具的路径如下所示。By default, the path of the tool is as follows. 使用双引号将包含空格的命令括起来：The double quotes enclose a command containing spaces:

        "C:\Program Files (x86)\Microsoft Visual Studio\Installer\resources\app\layout\InstallCleanup.exe" 

    备注

    如果在 Visual Studio 安装程序目录下找不到 `InstallCleanup.exe`，而该目录始终位于 `%ProgramFiles(x86)%\Microsoft Visual Studio`，则接下来要执行以下操作。If you can't find `InstallCleanup.exe` under the Visual Studio Installer directory, which is always located at `%ProgramFiles(x86)%\Microsoft Visual Studio`, here's what to do next. 按照指示来[安装 Visual Studio](https://docs.microsoft.com/zh-cn/visualstudio/install/install-visual-studio?view=vs-2019)。Follow the instructions to [install Visual Studio](https://docs.microsoft.com/zh-cn/visualstudio/install/install-visual-studio?view=vs-2019). 然后，在显示工作负载选择屏幕时，关闭窗口并再次执行此页上的步骤。Then, when the workload selection screen is displayed, close the window and follow the steps on this page again.

 [https://docs.microsoft.com/zh-cn/visualstudio/install/remove-visual-studio?view=vs-2019](https://docs.microsoft.com/zh-cn/visualstudio/install/remove-visual-studio?view=vs-2019)
