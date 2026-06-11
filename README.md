## Socket.IO-Client-Swift  16.1.1   

**当前分支从tag：16.1.1创建，替换内部 Starscream 的 repositoryURL 指向 MSport 的替换库 [MSport-Starscream](https://github.com/Eason-Saber/MSport-Starscream/tree/Replace-TCPTransport)，不能从其他分支合并代码！
**

##Cocoapods集成
**Podfile 里定制的 Starscream要写在它前面**

```Podfile
#定制的 Starscream https://github.com/Eason-Saber/MSport-Starscream   
  pod 'Starscream',
      :git => 'https://github.com/Eason-Saber/MSport-Starscream.git',
      :branch => 'Replace-TCPTransport'
  #https://github.com/Eason-Saber/MSport-Socket.IO-Client-Swift
  pod 'Socket.IO-Client-Swift',
      :git => 'https://github.com/Eason-Saber/MSport-Socket.IO-Client-Swift.git',
      :branch => 'Link-MSport-Starscream'
```
##SPM集成
<img height="260" src="Usage Docs/PROJECT_SPM.png" />