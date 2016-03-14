#sublime使用笔记

##常用插件

* Emmet 快速便捷html+css [使用教程](http://www.w3cplus.com/tools/emmet-cheat-sheet.html)
* TortoiseSVN 在sublime提交svn，配置：`Preferences->Package Settings->TortoiseSVN->Settings - User` 输入以下内容

        ```json
            {
            // Auto close update dialog when no errors, conflicts and merges
            "autoCloseUpdateDialog": false,
            "tortoiseproc_path": "D:\\SVN\\bin\\TortoiseProc.exe" //svn路径
        }
        ```
    使用快捷方式：
    
    [alt+c] : commit current file.
    [alt+u] : update current file.
    [alt+r] : revert current file.
* jsFormat 格式化js 快捷键 `ctrl+Alt+f`