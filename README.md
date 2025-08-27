
# MDViewer  |  MDViewer

一个基于 AutoHotkey 为 Windows 编写的轻量级、高速 Markdown 查看器。  
A fast and lightweight markdown viewer for Windows written in AutoHotkey.

## 安装  |  Installation

你可以直接下载已编译好的可执行文件，或克隆本仓库自行构建。  
You can download the compiled app from here, or you can clone the repo.

## 使用  |  Usage

### 打开 Markdown 文件  |  Opening a Markdown File

- 将 Markdown 文件拖拽到 `MDViewer.exe` 或 `MDViewer.ahk` 上即可打开；  
  Drag and drop a markdown file onto the executable/ahk file.

- 或者通过命令行传入文件路径作为第一个参数：  
  Or pass the file path as the first argument:

```bash
MDViewer.exe README.md
MDViewer.ahk README.md
```

### 设为默认 Markdown 查看器  |  Setting as Default Markdown Viewer

1. 在 Markdown 文件上点击右键；  
   Right-click on a markdown file.

2. 选择「打开方式」→「选择其他应用」；  
   Go to *Open With* → *Choose another app…*.

3. 点击「更多应用」→「在这台电脑上查找其他应用」；  
   Click *More apps* → *Look for another app on this PC…*.

4. 浏览并选中 `MDViewer.exe` 或 `MDViewer.ahk`；  
   Find and select `MDViewer.exe` or `MDViewer.ahk`.

5. 双击列表中的 MDViewer 即可设为默认。  
   Double-click MDViewer in the list.

## 自定义样式  |  Customization

如需自定义渲染样式，请将自制的 `style.css` 文件放置在 `MDViewer.exe` 或 `MDViewer.ahk` 同级目录下，程序启动时会自动加载该文件以替代默认样式。  
To customize the appearance of the rendered markdown, place a `style.css` file next to `MDViewer.exe` or `MDViewer.ahk`; it will be used instead of the default style.

## 许可证  |  License

MIT License  
Copyright (C) 2021 Luis Sanchez (luissanchezdev, LuisSanchez-Dev)  
Licensed under MIT Copyright (C) 2021 Luis Sanchez (luissanchezdev, LuisSanchez-Dev)
