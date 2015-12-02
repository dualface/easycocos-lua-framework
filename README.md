# EasyCocos Lua Framework for Cocos2d-x Lua

这是一个专为 Cocos2d-x Lua 设计的游戏框架。

核心目标如下：

-   提供易学易用的 API，显著降低 Cocos2d-x Lua 的使用门槛
-   完全模块化和组件化
-   完善的文档和示例
-   配套的自动化工具

主要组成部分：

-   `framework` 包含框架核心模块
-   packages/`ui` 高级 UI 库，实现 100% 纯 Lua 的游戏内 UI
-   packages/`res` 资源管理库，实现资源的统一管理和流水线操作
-   packages/`behavior` 名为 Behavior 的游戏逻辑库，帮助开发者模块化游戏逻辑代码

未来，可能增加更多模块。

> 与 Cocos2d-x Lua 引擎的兼容性问题
>
> 为了支持 `ui` 和 `res` 两个库，Cocos2d-x Lua 引擎会增加一些支持代码。这些支持代码将合并到 Cocos2d-x Lua 引擎中。用户不用担心未来的 Cocos2d-x Lua 引擎升级时导致 EasyCocos Lua Framework 存在兼容性问题。

\-EOF\-
