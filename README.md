# 网页版文件管理器
![Icon](./favicon.png)
使用AI合成的文件管理器，浏览你分享的文件，让单个连接合并起来。不再麻烦。
### 使用方式
只需要把它放在你的服务器就可以分享你的文件。
### 功能
- [x] UI美观
- [x] 哈希路径支持
- [x] 音乐播放器
### 编辑文件列表
只需要在``files.json``编辑它
```json
{
    "files": [
        {
            "name": "Folder",
            "type": "folder",
            "children": [
                {
                    "name": "files.txt",
                    "type": "file",
                    "size": "1. B",
                    "url": "https://example.com/path/of/your/files.txt"
                },
                // 其他文件
                
            ]
        },
        // 其他文件或文件夹
    ]
}
```

