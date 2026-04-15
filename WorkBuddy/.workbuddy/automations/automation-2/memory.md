# 游戏客户端面经自动化执行记录

## 已覆盖主题清单

### 第 1 期（2026-04-14 晚间）
- 多线程与异步编程（UE4 TaskGraph、Unity Job System、C++ std::thread/async）
- 设计模式在游戏中的应用（组件模式、观察者模式、状态模式、命令模式）

### 第 2 期（2026-04-14 晚间2）
- 渲染管线（前向渲染 vs 延迟渲染、UE5 Nanite、Unity URP/HDRP、Draw Call 优化）
- C++ 核心（智能指针 shared_ptr/unique_ptr/weak_ptr、移动语义、右值引用、MoveTemp）

### 第 3 期（2026-04-15 上午）— Tavily 深度搜索增强版
- 动画系统（UE 分层架构、AnimMontage 内部实现、Inertialization 惯性融合原理、Playable API/Animancer、Motion Matching 算法流程/Pose Search KD-Tree PCA/前瞻模拟/3A落地经验、URO 降频优化）
- Lua 语言深入（元表 __index/__newindex/__call 与脏标记、OOP 继承原型链、协程消灭回调地狱、Lua-C++ 交互瓶颈分析/腾讯面试优化方案、GC 调优三策略、LuaJIT FFI/table优化、内存泄漏排查四板斧）
- 信息来源：Epic 官方文档、UWA 侑虎科技、Hika/Lynx 博客、GDC 2016-2024、Lua 官方 Performance Tips、Luau 性能文档、腾讯面试题解析、Defold 社区、Animancer 作者分享

## 待覆盖主题（未来计划）
- 网络同步（状态同步 vs 帧同步、UE Replication、RPC 机制）
- 游戏 AI（行为树、EQS、GOAP、FSM/HFSM）
- 内存管理与性能优化（UE GC、Unity GC、对象池、Profiling 方法论）
- Shader 编程（HLSL/GLSL、PBR 光照模型、常见效果实现）
- UI 系统（UMG/Slate vs UGUI/UI Toolkit、MVC/MVVM 架构）
- 物理系统（PhysX、碰撞检测优化、物理同步）
- 资源管理（AssetManager、Addressables、热更新）
- C# 核心（GC 机制、值类型 vs 引用类型、async/await、Span<T>）
- 跨语言交互（C++/Lua 绑定、C#/C++ 互调、IL2CPP）
- 导航与寻路（NavMesh、A* 算法、动态避障 RVO）
- 粒子与特效（UE Niagara vs Unity VFX Graph、GPU 粒子、Overdraw 优化）
- 热更新方案（Lua 热更、HybridCLR、AB 包更新流程）
- 数据结构与算法（空间划分、碰撞检测算法、序列化）
- 移动端优化（iOS/Android 差异、内存限制、发热控制）
- GPU 编程与优化（Compute Shader、GPU Instancing、GPU Driven Pipeline）
- 游戏玩法系统（GAS、战斗系统、背包系统、Buff 系统）
- 构建与部署（Cook/Package、Build Pipeline、CI/CD）
- 调试技巧（UE Insights、Unity Profiler、RenderDoc）
