### 1.目录结构约定

```
--config                # webpack等配置文件
--script                # 项目需要的脚本
--public                # 静态资源, 模板文件
--src                   # 源代码
   |--app               # 业务开发目录
     |--demo            # 具体模块
       |--config.ts     # 配置, 权限等
       |--index.tsx     # 模块入口文件
       |--interface.ts  # 接口定义
       |--model.ts      # 数据模型
       |--service.ts    # 服务及接口
       |--store.ts      # 数据存储
   |--asset             # 静态资源文件, 字体, 图片等
     |--font
     |--icon
   |--common            # 公共资源
     |--BussUtil        # 业务强关联工具类
       |--__test        # 测试用例
     |--Model           # 公用的数据模型
     |--PlainUtil       # 纯粹的工具类
       |--__test        # 测试用例
     |--Service         # 公共的服务及接口
     |--Style           # 公共的样式
   |--component         # 业务强关联组件
   |--constant
     |--const.ts        # 常量
     |--enum.ts         # 枚举
     |--tracker.ts      # 埋点信息
   |--widget            # 纯粹的基础组件
--project.config.js     # 项目配置文件(代理, 环境变量等)
```

### 2.名词解释

```
+ model:     数据模型
+ store:     数据储存
+ buss :     business缩写, 业务
+ plain:     简单, 单纯
```

### 3.开发约定

```
+ 1.BussUtil/PlainUtil下的工具类, 编写测试用例
```
