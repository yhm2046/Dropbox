* 提供一个给系统应用导出dropbox日志的通用工具类
* 因为需要READ_LOGS权限，所该改方式只适合系统应用。
## 使用方式
```
DropboxLogcatExporter.getInstance().output(context, outputPath, bufferMaxBytes);
```