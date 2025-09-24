# Changelog


## [v1.3.16](https://github.com/faiz-Liu/soybean-admin/compare/undefined...v1.3.16) (2025-09-24)

### &nbsp;&nbsp;&nbsp;🚨 Breaking Changes

- **projects**:
  - refactor global menu & support `reversed-horizontal-mix-menu`. close #365 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/365 [<samp>(087e5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/087e5326)
  - don't reset active menu of vertical-mix layout when it is mixSiderFixed &nbsp;-&nbsp; by @soybeanjs [<samp>(939c5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/939c512f)
  - update scss config &nbsp;-&nbsp; by @soybeanjs [<samp>(24e9e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/24e9e57a)
  - refactor route cache & support reset route cache strategy &nbsp;-&nbsp; by @soybeanjs [<samp>(b667e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b667eab7)

### &nbsp;&nbsp;&nbsp;🚀 Features

- setting 页面新增 是否显示footer的开关 &nbsp;-&nbsp; by **zuihou** [<samp>(d064f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d064f628)
- 新增 affix 属性，用于将其固定在tab卡 &nbsp;-&nbsp; by **zuihou** [<samp>(e772f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e772ff05)
- internationalized menu search &nbsp;-&nbsp; by **Kori** [<samp>(9e115)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9e115dae)
- **auth**:
  - 防止多次刷新token &nbsp;-&nbsp; by **liwei** [<samp>(0eaa3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0eaa327d)
- **component**:
  - 增加剪贴板示例 &nbsp;-&nbsp; by **Yanbowen** [<samp>(f1cd9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f1cd9955)
- **components**:
  - 添加主题配置抽屉，添加暗黑主题 &nbsp;-&nbsp; by **Soybean** [<samp>(a8759)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a87593f5)
  - 添加面包屑 &nbsp;-&nbsp; by **Soybean** [<samp>(c1cdc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c1cdc3a9)
  - 添加vertical-mix的导航模式下的菜单 &nbsp;-&nbsp; by **Soybean** [<samp>(f24ec)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f24ec1c5)
  - 添加图片验证码 &nbsp;-&nbsp; by **Soybean** [<samp>(336c7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/336c7766)
  - 添加多页签Tab点击后自动往中间滚动 &nbsp;-&nbsp; by **Soybean** [<samp>(8ce62)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8ce627a3)
  - svgIcon,添加type,调整size方案 &nbsp;-&nbsp; by **Lsq128** [<samp>(ce4e0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ce4e039f)
  - Add tree related component instances &nbsp;-&nbsp; by **small_happy** [<samp>(d203a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d203a358)
  - Add routing data related to tree components and page display optimization &nbsp;-&nbsp; by **small_happy** [<samp>(a0f55)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a0f55aca)
  - enhance the custom strength of the 'TableHeaderOperation' component &nbsp;-&nbsp; by **tnt group** [<samp>(fdf64)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fdf64f71)
  - add GlobalSearch components &nbsp;-&nbsp; by **燕博文** [<samp>(9ea87)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9ea87891)
- **docs**:
  - add GitCode star badge to README files &nbsp;-&nbsp; by @soybeanjs [<samp>(05dc1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/05dc11e2)
  - add DartNode sponsorship badge to README files &nbsp;-&nbsp; by @soybeanjs [<samp>(2ed0b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2ed0b648)
- **hooks**:
  - add useNaiveTable &nbsp;-&nbsp; by **Soybean** [<samp>(cc13f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cc13fcc8)
  - add useHookTable &nbsp;-&nbsp; by @soybeanjs [<samp>(b3ae7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b3ae7605)
  - add use-echarts &nbsp;-&nbsp; by @soybeanjs [<samp>(726ab)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/726abe42)
  - deleting the route export of useRoutePush, use vue-router &nbsp;-&nbsp; by @paynezhuang [<samp>(c6648)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c6648b6c)
  - add state hooks: useRef, useState, useSignal &nbsp;-&nbsp; by @soybeanjs [<samp>(09f64)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/09f64646)
  - add setOptions for useEcharts &nbsp;-&nbsp; by @soybeanjs [<samp>(e4d53)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e4d53aa7)
- **layouts**:
  - 添加侧边栏/头部的反转模式来增加对比度 &nbsp;-&nbsp; by **元家怿** [<samp>(3c8dd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3c8dd772)
  - 添加侧边栏/头部的反转模式来增加对比度 &nbsp;-&nbsp; by **元家怿** [<samp>(861c8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/861c8b98)
- **packages**:
  - @sa/scripts: add new commit type `optimize` and commit scope `packages` &nbsp;-&nbsp; by @soybeanjs [<samp>(fbc2e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fbc2e61f)
  - `@sa/scripts`: command `gitCommit` support chinese &nbsp;-&nbsp; by @mmdapl in https://github.com/faiz-Liu/soybean-admin/issues/548 [<samp>(06971)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/06971f39)
  - @sa/axios: replace CancelTokenSource by AbortController. close #530, close #532 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/530 and https://github.com/faiz-Liu/soybean-admin/issues/532 [<samp>(527fd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/527fd79d)
  - @sa/scripts: add ignore pattern list for command `gitCommitVerify`. close #504 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/504 [<samp>(958d0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/958d0baf)
  - @sa/axios: add response to flatRequest when success &nbsp;-&nbsp; by @soybeanjs [<samp>(c4e16)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c4e16102)
  - add subpackage `@sa/alova` &nbsp;-&nbsp; by @JOU-amjs in https://github.com/faiz-Liu/soybean-admin/issues/640 [<samp>(2072f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2072f585)
  - optimistic subpackage `@sa/alova` &nbsp;-&nbsp; by @JOU-amjs in https://github.com/faiz-Liu/soybean-admin/issues/646 [<samp>(4b3ac)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4b3ac11b)
- **projects**:
  - 项目初始化搭建，集成eslint规范，集成代码提交规范 &nbsp;-&nbsp; by **Soybean** [<samp>(6754d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6754da4d)
  - 新增主题配置 &nbsp;-&nbsp; by **Soybean** [<samp>(ed67b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ed67b797)
  - 布局调整 &nbsp;-&nbsp; by **Soybean** [<samp>(eda87)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/eda87f04)
  - 新增主题颜色配置 &nbsp;-&nbsp; by **Soybean** [<samp>(d9349)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d93493b9)
  - 新增导航模式配置 &nbsp;-&nbsp; by **Soybean** [<samp>(49c2d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/49c2dc4f)
  - 导航栏模式配置：界面实现及主题配置布局调整 &nbsp;-&nbsp; by **Soybean** [<samp>(f0021)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f002124e)
  - 新增主题配置：页面功能 &nbsp;-&nbsp; by **Soybean** [<samp>(8601c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8601ce2e)
  - 主题配置：页面功能和页面显示 &nbsp;-&nbsp; by **Soybean** [<samp>(a0392)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a0392b3d)
  - 添加全屏显示 &nbsp;-&nbsp; by **Soybean** [<samp>(0a171)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0a1711d5)
  - 四种基本布局完成 &nbsp;-&nbsp; by **Soybean** [<samp>(86d4a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/86d4a207)
  - 添加固定路由 &nbsp;-&nbsp; by **Soybean** [<samp>(ff4a0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ff4a09c4)
  - 添加exception页面：403，404，500 &nbsp;-&nbsp; by **Soybean** [<samp>(d012c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d012c4ec)
  - 首页更新 &nbsp;-&nbsp; by **Soybean** [<samp>(5c010)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5c010063)
  - 登录页面实现 &nbsp;-&nbsp; by **Soybean** [<samp>(f1e7c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f1e7cf60)
  - 菜单数据及组件接入 &nbsp;-&nbsp; by **Soybean** [<samp>(3226a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3226a724)
  - 头部添加菜单折叠按钮和github地址 &nbsp;-&nbsp; by **Soybean** [<samp>(3ec1f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3ec1fc8f)
  - 添加multiTab标签页 &nbsp;-&nbsp; by **Soybean** [<samp>(eec0b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/eec0b36f)
  - 多页签绑定路由 &nbsp;-&nbsp; by **Soybean** [<samp>(f29bc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f29bc05d)
  - 添加reload context &nbsp;-&nbsp; by **Soybean** [<samp>(03ebd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/03ebd49c)
  - 添加多页签风格：按钮和浏览器两种风格 &nbsp;-&nbsp; by **Soybean** [<samp>(3cfa0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3cfa0f10)
  - 添加多页签右键菜单 &nbsp;-&nbsp; by **Soybean** [<samp>(d6f52)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d6f5237c)
  - 添加环境文件env对应的类型 &nbsp;-&nbsp; by **Soybean** [<samp>(4f050)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4f050953)
  - 新增顶部菜单 &nbsp;-&nbsp; by **Soybean** [<samp>(221d2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/221d2cc0)
  - vertical-mix的导航模式的二级菜单显示 &nbsp;-&nbsp; by **Soybean** [<samp>(736f3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/736f3146)
  - 添加多级菜单页面 &nbsp;-&nbsp; by **Soybean** [<samp>(3f49d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3f49d6db)
  - 添加svg logo自适应主题颜色 &nbsp;-&nbsp; by **Soybean** [<samp>(e1e55)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e1e5579e)
  - 添加项目配置拷贝 &nbsp;-&nbsp; by **Soybean** [<samp>(2d9d5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2d9d5c03)
  - 新增文档页面 &nbsp;-&nbsp; by **Soybean** [<samp>(7654b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7654b2ad)
  - 工作台页面布局 &nbsp;-&nbsp; by **Soybean** [<samp>(4c855)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4c85569b)
  - 分析页更新，添加关于页面 &nbsp;-&nbsp; by **Soybean** [<samp>(8e182)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8e182181)
  - 添加富文本和markdown编辑器插件及示例页面 &nbsp;-&nbsp; by **Soybean** [<samp>(60c20)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/60c20647)
  - 添加百度地图插件 &nbsp;-&nbsp; by **Soybean** [<samp>(6abe0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6abe094f)
  - 新增高德地图插件 &nbsp;-&nbsp; by **Soybean** [<samp>(ea82e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ea82edc1)
  - 新增腾讯地图插件 &nbsp;-&nbsp; by **Soybean** [<samp>(3f02c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3f02c215)
  - 新增视频插件 &nbsp;-&nbsp; by **Soybean** [<samp>(6a692)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6a692d4f)
  - 工作台页面：添加技术栈官网链接 &nbsp;-&nbsp; by **Soybean** [<samp>(364c6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/364c64b4)
  - 添加判断是否是移动端的hooks &nbsp;-&nbsp; by **Soybean** [<samp>(0a9fb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0a9fba90)
  - 添加swiper插件 &nbsp;-&nbsp; by **Soybean** [<samp>(27f60)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/27f600c4)
  - 增加Icon以及打印功能示例 &nbsp;-&nbsp; by **Yanbowen** [<samp>(d5bce)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d5bce264)
  - 新增多页签缓存功能 &nbsp;-&nbsp; by **Soybean** [<samp>(d86f8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d86f891c)
  - 新增网址导航页面 &nbsp;-&nbsp; by **Soybean** [<samp>(32aa5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/32aa5ee7)
  - 新增组件页面：按钮、卡片示例 &nbsp;-&nbsp; by **Soybean** [<samp>(bdc39)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bdc39aff)
  - 添加路由跳转浏览器新标签 &nbsp;-&nbsp; by **Soybean** [<samp>(987ce)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/987cef33)
  - 添加常用组件、composables函数 &nbsp;-&nbsp; by **Soybean** [<samp>(230a5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/230a50a4)
  - 添加表格页面示例 &nbsp;-&nbsp; by **Soybean** [<samp>(51c74)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/51c744c8)
  - 增加Icon选择器组件 &nbsp;-&nbsp; by **Yanbowen** [<samp>(9472b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9472b518)
  - 图标选择器增加扩展树形 &nbsp;-&nbsp; by **Yanbowen** [<samp>(04101)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/041012b3)
  - 增加项目文档外链 &nbsp;-&nbsp; by **Yanbowen** [<samp>(1901a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1901a0bf)
  - 引入mockjs &nbsp;-&nbsp; by **Soybean** [<samp>(9bc68)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9bc682da)
  - 增加全局搜索菜单功能 &nbsp;-&nbsp; by **Yanbowen** [<samp>(b9ce6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b9ce6913)
  - 菜单搜索增加大小写转换 &nbsp;-&nbsp; by **Yanbowen** [<samp>(29078)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/29078689)
  - 添加cryptojs，对本地缓存数据进行加密 &nbsp;-&nbsp; by **Soybean** [<samp>(7a064)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7a0648db)
  - 路由页面跳转权限完成 &nbsp;-&nbsp; by **Soybean** [<samp>(0d2a5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0d2a5629)
  - 集成naiveUI主题配置，将css vars添加至html &nbsp;-&nbsp; by **Soybean** [<samp>(2c196)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2c196841)
  - 初始化加载效果：应用主题颜色 &nbsp;-&nbsp; by **Soybean** [<samp>(035fa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/035fa114)
  - 登录页面开始迁移 &nbsp;-&nbsp; by **Soybean** [<samp>(f5a36)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f5a36a05)
  - 迁移登录完成 &nbsp;-&nbsp; by **Soybean** [<samp>(b93b8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b93b80cb)
  - 添加NaiveProvider组件 &nbsp;-&nbsp; by **Soybean** [<samp>(c804b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c804b21c)
  - 多级路由的所有子路由转换成二级路由 &nbsp;-&nbsp; by **Soybean** [<samp>(85b55)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/85b55bb3)
  - 新增BasicLayout布局 &nbsp;-&nbsp; by **Soybean** [<samp>(00646)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/006467a0)
  - 创建自定义布局组件SoybeanLayout &nbsp;-&nbsp; by **Soybean** [<samp>(0653f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0653fb14)
  - 添加抽屉 &nbsp;-&nbsp; by **Soybean** [<samp>(10e4d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/10e4d81b)
  - theme store完成 &nbsp;-&nbsp; by **Soybean** [<samp>(bf020)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bf020a82)
  - 主题配置抽屉：迁移暗黑模式、布局模式、添加颜色选择面板 &nbsp;-&nbsp; by **Soybean** [<samp>(912bf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/912bfdf4)
  - 主题配置抽屉: 迁移其他功能 &nbsp;-&nbsp; by **Soybean** [<samp>(6d132)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6d132c59)
  - 添加头部折叠按钮 &nbsp;-&nbsp; by **Soybean** [<samp>(a090d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a090d398)
  - 添加侧边菜单 &nbsp;-&nbsp; by **Soybean** [<samp>(e25af)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e25afe2f)
  - 面包屑 &nbsp;-&nbsp; by **Soybean** [<samp>(09c76)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/09c7658c)
  - 请求拦截器添加刷新token &nbsp;-&nbsp; by **Soybean** [<samp>(839b8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/839b82ba)
  - 细节完善 &nbsp;-&nbsp; by **Soybean** [<samp>(cc290)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cc290acc)
  - 迁移多页签 &nbsp;-&nbsp; by **Soybean** [<samp>(28efb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/28efbdbc)
  - 细节完善、迁移页面 &nbsp;-&nbsp; by **Soybean** [<samp>(ce531)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ce531ce5)
  - 添加页面缓存、记录在tab中的缓存页面的滚动条位置 &nbsp;-&nbsp; by **Soybean** [<samp>(1d63a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1d63a838)
  - 添加缓存主题色 &nbsp;-&nbsp; by **Soybean** [<samp>(37092)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/37092974)
  - 新版重构完成 &nbsp;-&nbsp; by **Soybean** [<samp>(68b42)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/68b42304)
  - 迁移全局搜索菜单功能 &nbsp;-&nbsp; by **yanbowen** [<samp>(554d7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/554d7fd6)
  - 添加naiveUI按需引入 &nbsp;-&nbsp; by **Soybean** [<samp>(a810e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a810ef85)
  - 添加SvgIcon,配置vite plugin &nbsp;-&nbsp; by **Liushengqun** [<samp>(378d5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/378d55ac)
  - 引入soybean-admin-tab、去除vite-plugin-svg-icons，用unplugin-icons实现自定义svg的iconify写法、代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(a1a57)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a1a57a18)
  - 新增子菜单图标和多页签图标 &nbsp;-&nbsp; by **Soybean** [<samp>(f5c56)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f5c56c35)
  - 重构项目的TS类型架构，去除interface文件夹 &nbsp;-&nbsp; by **Soybean** [<samp>(81914)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8191490f)
  - 添加网络代理 &nbsp;-&nbsp; by **Soybean** [<samp>(094dc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/094dca96)
  - 添加全局组件自动引入注册 &nbsp;-&nbsp; by **Soybean** [<samp>(f5a04)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f5a043b1)
  - 新增自定义svg图标动态渲染 &nbsp;-&nbsp; by **Soybean** [<samp>(f83c7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f83c7b59)
  - 新增静态路由 &nbsp;-&nbsp; by **Soybean** [<samp>(ca2df)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ca2dfa61)
  - 插件方式按需引入naiveUI &nbsp;-&nbsp; by **Soybean** [<samp>(6bed9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6bed9ead)
  - 添加请求适配器的请求示例 &nbsp;-&nbsp; by **Soybean** [<samp>(bed42)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bed4292e)
  - 登录页面适配移动端 &nbsp;-&nbsp; by **Soybean** [<samp>(ec077)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ec0776e2)
  - 登录页背景图片位置适配移动端 &nbsp;-&nbsp; by **Soybean** [<samp>(24010)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/24010d05)
  - 引入unocss替换windicss &nbsp;-&nbsp; by **Soybean** [<samp>(c9d3e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c9d3e5a3)
  - HTML lang 修改为 zh-cmn-Hans &nbsp;-&nbsp; by **相思** [<samp>(dbeb5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/dbeb595c)
  - HTML lang 修改为 zh-cmn-Hans &nbsp;-&nbsp; by **相思** [<samp>(b9c5c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b9c5c349)
  - 权限完善及权限示例页面 &nbsp;-&nbsp; by **Soybean** [<samp>(80744)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/807448ae)
  - mock添加权限过滤 &nbsp;-&nbsp; by **Soybean** [<samp>(7f435)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7f4350ae)
  - 添加自动跟随系统主题设置 &nbsp;-&nbsp; by **相思** [<samp>(ba07b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ba07b695)
  - 引入echarts替换antvG2plot &nbsp;-&nbsp; by **Soybean** [<samp>(e7ad0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e7ad0868)
  - 添加百度地图、升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(39854)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/39854a49)
  - 添加插件页面：图表 &nbsp;-&nbsp; by **Soybean** [<samp>(0a46e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0a46ea08)
  - 添加antv g2图表示例 &nbsp;-&nbsp; by **Soybean** [<samp>(44b02)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/44b022ae)
  - 补充更多的ECharts示例 &nbsp;-&nbsp; by **Soybean** [<samp>(c7762)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c7762490)
  - 动态路由根路由重定向只需取决于后端返回的路由首页 &nbsp;-&nbsp; by **Soybean** [<samp>(434ab)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/434ab1c5)
  - 支持同一路由根据不同query和hash同时显示不同Tab &nbsp;-&nbsp; by **Soybean** [<samp>(41226)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/41226858)
  - 新增Antv G2图表示例 &nbsp;-&nbsp; by **Soybean** [<samp>(2d64a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2d64a2e5)
  - 上下结构，菜单支持横向滚动 &nbsp;-&nbsp; by **tanminglin** [<samp>(80805)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/808051b2)
  - 增加设置当前Tab页签名称功能 &nbsp;-&nbsp; by **燕博文** [<samp>(48721)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/487213b6)
  - 本地svg动态渲染图标 &nbsp;-&nbsp; by **Soybean** [<samp>(c3c97)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c3c975ee)
  - 增加系统消息组件 &nbsp;-&nbsp; by **燕博文** [<samp>(afa01)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/afa0134f)
  - 系统消息组件代码优化 &nbsp;-&nbsp; by **燕博文** [<samp>(95183)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9518372f)
  - 增加返回顶部功能 &nbsp;-&nbsp; by **燕博文** [<samp>(894b0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/894b0f1c)
  - 添加生产的主题配置缓存 &nbsp;-&nbsp; by **Soybean** [<samp>(718c3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/718c3626)
  - 添加provide、inject上下文示例 &nbsp;-&nbsp; by **Soybean** [<samp>(a4447)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a444731e)
  - 添加组件名称，调整vue文件里面的类型声明位置 &nbsp;-&nbsp; by **Soybean** [<samp>(f64bc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f64bc91c)
  - 适配移动端，修复Tab关闭图标的bug &nbsp;-&nbsp; by **Soybean** [<samp>(296b1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/296b154b)
  - 添加系统管理的页面 &nbsp;-&nbsp; by **Soybean** [<samp>(c33b5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c33b5ebf)
  - useNaiveTable函数：类型部分 &nbsp;-&nbsp; by **Soybean** [<samp>(02992)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/02992dc0)
  - 添加请求适配adapter层应用的示例页面 &nbsp;-&nbsp; by **Soybean** [<samp>(8d11a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8d11a6af)
  - 实现用户管理页面 &nbsp;-&nbsp; by **Soybean** [<samp>(472f9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/472f93bf)
  - 全局搜索菜单及消息通知适配移动端 &nbsp;-&nbsp; by **燕博文** [<samp>(97e2f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/97e2ffdd)
  - support constant route without login status[支持未登录状态下访问自定义的固定路由] &nbsp;-&nbsp; by **Soybean** [<samp>(a5391)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a539112a)
  - add pinia setup syntax example: setup-store[添加setup syntax的pinia示例setup-store] &nbsp;-&nbsp; by **Soybean** [<samp>(82c4b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/82c4b09b)
  - add constant route page without login status[添加未登录可访问的固定路由示例页面] &nbsp;-&nbsp; by **Soybean** [<samp>(78efd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/78efd779)
  - refactor icon system, unify icon usage [重构图标系统，统一图标用法] &nbsp;-&nbsp; by **Soybean** [<samp>(811f8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/811f8206)
  - import i18n [引入i18n] &nbsp;-&nbsp; by **Soybean** [<samp>(b632b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b632b7ff)
  - new router system [新的路由系统] &nbsp;-&nbsp; by **Soybean** [<samp>(c7b6a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c7b6a3fb)
  - add compress script [添加压缩命令] &nbsp;-&nbsp; by **Soybean** [<samp>(be6d4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/be6d4314)
  - add script about generating png logo from [添加根据svg生成png图标的命令] &nbsp;-&nbsp; by **Soybean** [<samp>(70aee)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/70aeefea)
  - add generate logo script &nbsp;-&nbsp; by **Soybean** [<samp>(25daa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/25daa236)
  - add new route plugin @soybeanjs/vite-plugin-vue-page-route [集成新的路由插件] &nbsp;-&nbsp; by **Soybean** [<samp>(3131e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3131e00f)
  - custom unocss colors support opacity &nbsp;-&nbsp; by **Soybean** [<samp>(488e6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/488e6e32)
  - new layout,tab and add update theme settings &nbsp;-&nbsp; by **Soybean** [<samp>(912c3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/912c3531)
  - 返回顶部功能适配新布局 &nbsp;-&nbsp; by **燕博文** [<samp>(54e2c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/54e2cb51)
  - 增加i18n支持翻译菜单,tab,title &nbsp;-&nbsp; by **cc** [<samp>(3d48a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3d48aa8b)
  - add menu translate [翻译菜单] &nbsp;-&nbsp; by **Soybean** [<samp>(f6828)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f68285fb)
  - 增加主题切换过渡效果 &nbsp;-&nbsp; by **cc** [<samp>(8da88)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8da8843f)
  - support mobile layout [支持移动端布局] &nbsp;-&nbsp; by **Soybean** [<samp>(f2b51)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f2b518ed)
  - add websocket demo &nbsp;-&nbsp; by **Soybean** [<samp>(af53e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/af53ec76)
  - add switch for customize darkmode transition &nbsp;-&nbsp; by **Soybean** [<samp>(6e0cc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6e0cce4d)
  - new i18n function $t & login page and setting drawer config i18n &nbsp;-&nbsp; by @soybeanjs [<samp>(854d0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/854d0bcf)
  - add plugin-web-update-notification &nbsp;-&nbsp; by @soybeanjs [<samp>(c9164)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c91644b8)
  - 1.0 beta &nbsp;-&nbsp; by @soybeanjs [<samp>(e918a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e918a2c0)
  - support Vite5 &nbsp;-&nbsp; by @soybeanjs [<samp>(96e4a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/96e4aff5)
  - @sa/axios: createRequest, createFlatRequest, createHookRequest &nbsp;-&nbsp; by @soybeanjs [<samp>(bac16)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bac16324)
  - add app loading &nbsp;-&nbsp; by @soybeanjs [<samp>(c6545)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c65451b3)
  - add copyright, unocss shortcut: card-wrapper, update package.json &nbsp;-&nbsp; by @soybeanjs [<samp>(affcc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/affcc26b)
  - add page: about &nbsp;-&nbsp; by @soybeanjs [<samp>(4955f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4955f1af)
  - add custom route exception &nbsp;-&nbsp; by @soybeanjs [<samp>(b43c9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b43c9256)
  - filter tabs which are not in routes &nbsp;-&nbsp; by @soybeanjs [<samp>(f59f3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f59f3488)
  - packages/scripts: add command changelog,release &nbsp;-&nbsp; by @soybeanjs [<samp>(dafb6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/dafb6fa0)
  - add script: gen-route &nbsp;-&nbsp; by @soybeanjs [<samp>(697c1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/697c1b61)
  - @sa/axios: add qs stringify for params &nbsp;-&nbsp; by @soybeanjs [<samp>(2400c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2400c026)
  - page home & perf useEcharts &nbsp;-&nbsp; by @soybeanjs [<samp>(62e4d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/62e4da05)
  - finish page home &nbsp;-&nbsp; by @soybeanjs [<samp>(7bd1e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7bd1e47a)
  - add page function_tab &nbsp;-&nbsp; by @soybeanjs [<samp>(6ff86)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6ff86e77)
  - page manage_role &nbsp;-&nbsp; by @soybeanjs [<samp>(237c6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/237c6d22)
  - page manage_user &nbsp;-&nbsp; by @soybeanjs [<samp>(8a170)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8a170eee)
  - page manage_menu &nbsp;-&nbsp; by @soybeanjs [<samp>(87d65)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/87d65d3b)
  - page manage_menu operateDrawer &nbsp;-&nbsp; by @soybeanjs [<samp>(db17c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/db17c916)
  - Add type to TabRoute: matched &nbsp;-&nbsp; by @Azir-11 [<samp>(2d102)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2d102a05)
  - support directory menu hide all child menus. fixed #325 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/325 [<samp>(7256a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7256ad4e)
  - mock manage list data with pagination &nbsp;-&nbsp; by @soybeanjs [<samp>(1a6be)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1a6be003)
  - globalSearch add i18n &nbsp;-&nbsp; by **燕博文** [<samp>(0126d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0126da47)
  - Add route meta parameter:fixedQuery &nbsp;-&nbsp; by **Azir-11** [<samp>(874aa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/874aaca5)
  - update &nbsp;-&nbsp; by @soybeanjs [<samp>(4158a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4158a72b)
  - change borderRadius to 6px of naiveUI &nbsp;-&nbsp; by @soybeanjs [<samp>(49558)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/49558ca0)
  - pef manage role &nbsp;-&nbsp; by @soybeanjs [<samp>(18709)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/18709813)
  - login page: code-login &nbsp;-&nbsp; by @soybeanjs [<samp>(c91dd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c91dd282)
  - login page: register &nbsp;-&nbsp; by @soybeanjs [<samp>(1ed33)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1ed33dc4)
  - add request refresh token & logout &nbsp;-&nbsp; by @soybeanjs [<samp>(11a6a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/11a6a3bd)
  - add request exception example page &nbsp;-&nbsp; by @soybeanjs [<samp>(41e8b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/41e8bc44)
  - add auth example &nbsp;-&nbsp; by @soybeanjs [<samp>(c11d5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c11d56da)
  - support grayscale. fixed #385 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/385 [<samp>(d335d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d335df6f)
  - Add prefix to local storage &nbsp;-&nbsp; by **Azir** [<samp>(1fc34)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1fc34cc5)
  - add table showTotal options &nbsp;-&nbsp; by @paynezhuang [<samp>(3e61e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3e61eab4)
  - support iframe page with diffrent url of custom route &nbsp;-&nbsp; by @soybeanjs [<samp>(da12d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/da12d4a5)
  - add recommend color switch. closed #388 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/388 [<samp>(a1920)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a1920fca)
  - add menu route field &nbsp;-&nbsp; by @paynezhuang [<samp>(dbe31)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/dbe31eb1)
  - support repeated request errors occur once in a short time. close #368, close #369 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/368 and https://github.com/faiz-Liu/soybean-admin/issues/369 [<samp>(e3bd3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e3bd3972)
  - close tab by mouse wheel button click &nbsp;-&nbsp; by **JianJroh** [<samp>(d3849)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d3849baa)
  - page: support manage_menu more options. close #366 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/366 [<samp>(c4b5c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c4b5c656)
  - useTable adds expand to display &nbsp;-&nbsp; by @paynezhuang [<samp>(0a90d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0a90dd37)
  - support system new version update notification. close #420 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/420 [<samp>(584cd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/584cd54d)
  - get user info in router guard and remove in localStorage. close #459 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/459 [<samp>(5531a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5531a686)
  - reset scroll position when tab change &nbsp;-&nbsp; by @soybeanjs [<samp>(9094b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9094b21c)
  - make branch `main` tiny & modify request retry times to 0 &nbsp;-&nbsp; by @Azir-11 [<samp>(793b1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/793b16e9)
  - add color fading mode.close #567 &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/569 and https://github.com/faiz-Liu/soybean-admin/issues/567 [<samp>(4dde4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4dde4c22)
  - add full screen watermark. close#571 &nbsp;-&nbsp; by @paynezhuang in https://github.com/faiz-Liu/soybean-admin/issues/573 and https://github.com/faiz-Liu/soybean-admin/issues/571 [<samp>(ea8aa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ea8aa6c4)
  - README.zh_CN.md 添加合作推广 &nbsp;-&nbsp; by @PZ-18664918826 in https://github.com/faiz-Liu/soybean-admin/issues/601 [<samp>(2fa40)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2fa400b1)
  - Add more commit types according to Apache specifications &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/610 [<samp>(878d9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/878d9c39)
  - does the configuration support automatic updates. close#612 &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/617 and https://github.com/faiz-Liu/soybean-admin/issues/612 [<samp>(4c9f4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4c9f4e09)
  - add app error handler. close #587 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/587 [<samp>(be855)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/be8556cd)
  - login supports accessible operation. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/637 [<samp>(cfaab)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cfaab852)
  - support scheduled detection and update system. close #657 &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/669 and https://github.com/faiz-Liu/soybean-admin/issues/657 [<samp>(d088f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d088f813)
  - app version notification plugin support sub deploy path. close #668 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/668 [<samp>(a53eb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a53eb10c)
  - support show tab when not loggedIn &nbsp;-&nbsp; by @soybeanjs [<samp>(ba381)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ba38119e)
  - multi language buttons support hiding. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/683 [<samp>(d7aeb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d7aebb7d)
  - support loading page dark mode adaptation. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/702 [<samp>(9b945)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9b9455d9)
  - tab support touch event &nbsp;-&nbsp; by @soybeanjs [<samp>(a03be)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a03becda)
  - support proxy log in terminal &nbsp;-&nbsp; by @soybeanjs [<samp>(4cc14)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4cc1487f)
  - support vite devtools specify the editor by launchEditor option. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/730 [<samp>(29698)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/29698bef)
  - clear tabs cache when switching users. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/744 [<samp>(1ff4d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1ff4d82d)
  - add configurable user name watermark option &nbsp;-&nbsp; by @wenyuanw [<samp>(7c3da)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7c3dac42)
- **projects): feat(projects**:
  - TableColumnCheck title support VNode &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/716 [<samp>(a1a5c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a1a5c74c)
- **route**:
  - 增加功能示例模块 &nbsp;-&nbsp; by **Yanbowen** [<samp>(efd29)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/efd29bc3)
  - 路由meta新增activeMenu属性 &nbsp;-&nbsp; by **燕博文** [<samp>(ebd16)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ebd16a4d)
- **router**:
  - add sortRoutesByOrder function &nbsp;-&nbsp; by **Azir-11** [<samp>(0cf09)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0cf09bae)
- **storage**:
  - local存储增加有效期 &nbsp;-&nbsp; by **Yanbowen** [<samp>(e6c9b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e6c9b35a)
- **tabs**:
  - 多页签增加关闭所有 &nbsp;-&nbsp; by **燕博文** [<samp>(8237a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8237adb9)
- **theme**:
  - global search button toggle &nbsp;-&nbsp; by **t8y2** [<samp>(75455)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/75455b00)
- **types**:
  - enhance Option type to support customizable label types &nbsp;-&nbsp; by @WgoW and @testbrate in https://github.com/faiz-Liu/soybean-admin/issues/735 [<samp>(123d2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/123d2c90)
- **utils**:
  - support replaceTab. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/713 [<samp>(be608)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/be6080ba)
  - support quick generation of code templates. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/733 [<samp>(8527a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8527aa80)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- remove height limit h-360px &nbsp;-&nbsp; by **Wang Zheng** [<samp>(b5c57)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b5c570ad)
- set password attributes &nbsp;-&nbsp; by **Wang Zheng** [<samp>(a9a37)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a9a37036)
- **app**:
  - replace console.error with window.console.error for consistency &nbsp;-&nbsp; by @soybeanjs [<samp>(7d840)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7d84062e)
- **auth**:
  - remove redundant authStore declaration in resetStore function &nbsp;-&nbsp; by @soybeanjs [<samp>(c57f8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c57f88aa)
- **components**:
  - tab组件在黑暗模式下泛白的颜色问题以及chromeTab的重叠问题 &nbsp;-&nbsp; by **lingdu** [<samp>(6797d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6797dbf1)
  - 修复tab组件适应暗黑主题模式 &nbsp;-&nbsp; by **Soybean** [<samp>(2fe3d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2fe3d27a)
  - 修复按钮Tab自适应主题颜色 &nbsp;-&nbsp; by **Soybean** [<samp>(3d1f4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3d1f4192)
  - 修复BaseLayout的HorizontalLayout &nbsp;-&nbsp; by **Soybean** [<samp>(0344f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0344f46c)
  - 修复多页签Tab自动滚动问题 &nbsp;-&nbsp; by **Soybean** [<samp>(20aa3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/20aa39f1)
  - 修复多页签按钮风格的tab滚动问题 &nbsp;-&nbsp; by **Soybean** [<samp>(c429c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c429cd02)
  - 修复HorizontalLayout布局 &nbsp;-&nbsp; by **Soybean** [<samp>(9fb64)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9fb641f7)
  - 修复Tab在移动端设备无法点击的问题 &nbsp;-&nbsp; by **Soybean** [<samp>(2c966)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2c9660fd)
  - 修复组件LoadingEmptyWrapper适应暗黑模式 &nbsp;-&nbsp; by **Soybean** [<samp>(811b1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/811b15e6)
  - 组件LoadingEmptyWrapper添加背景颜色动画过渡 &nbsp;-&nbsp; by **Soybean** [<samp>(7add5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7add5c2e)
  - 修复路由在path中包含重复路单词径菜单时，被激活会错误展开 &nbsp;-&nbsp; by **shabby2333** [<samp>(264da)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/264da00e)
  - 页面跳转被拦截, 则会出现 tab 页签与页面不一致的问题 &nbsp;-&nbsp; by **刘璐** [<samp>(bd5dd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bd5dd2cf)
  - 修复iconSelect选择器点击事件失效 &nbsp;-&nbsp; by **燕博文** [<samp>(7e505)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7e505f9b)
  - refresh cached routes &nbsp;-&nbsp; by **alue_mobile** [<samp>(b0f98)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b0f98e4b)
  - fix mix-menu layout when the locale is English (fixed 241) &nbsp;-&nbsp; by **Soybean** [<samp>(5c085)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5c085a19)
  - 修复动态路由主页404 &nbsp;-&nbsp; by **lapislazulisch** [<samp>(3ae19)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3ae19526)
  - 修复动态路由home页404 &nbsp;-&nbsp; by **lapislazulisch** [<samp>(ad6ac)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ad6ac722)
  - fix tooltip zIndex of ButtonIcon &nbsp;-&nbsp; by @soybeanjs [<samp>(99097)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/99097b46)
  - supplement the `NaiveUI` type &nbsp;-&nbsp; by **tnt group** [<samp>(ccc2b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ccc2b674)
  - fix homeTab closeRight and disable colseLeft &nbsp;-&nbsp; by **~li** [<samp>(d28bf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d28bf526)
  - fix PinToggler label. fixed #407 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/407 [<samp>(c0ed1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c0ed1f26)
  - Fix the issue of search box popping up repeatedly due to carriage return &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/468 [<samp>(5bd96)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5bd96b8d)
  - fix VerticalMixMenu name &nbsp;-&nbsp; by @soybeanjs [<samp>(20f8e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/20f8ed31)
- **deps**:
  - 去除图片验证码依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(76a1a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/76a1afae)
  - 降低vite版本，新版本有些许问题 &nbsp;-&nbsp; by **Soybean** [<samp>(b429c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b429c8b8)
  - vite依赖放入devDependencies &nbsp;-&nbsp; by **Soybean** [<samp>(7527b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7527b1f0)
  - 降低vite版本 &nbsp;-&nbsp; by **Soybean** [<samp>(c9c5c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c9c5ca99)
  - decrease @types/node version to fix TS type error [降低@types/node版本修复TS的类型错误] &nbsp;-&nbsp; by **Soybean** [<samp>(149d2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/149d22a4)
  - move json5 from devDependencies to dependencies to support production usage &nbsp;-&nbsp; by **Ohh** in https://github.com/faiz-Liu/soybean-admin/issues/618 [<samp>(7cb43)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7cb43fc3)
  - reduced eslint version to 9.14.0 &nbsp;-&nbsp; by @soybeanjs [<samp>(af417)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/af4177e7)
- **hooks**:
  - 修复toLogin函数导致登录重定向地址过多 &nbsp;-&nbsp; by **Soybean** [<samp>(b4adf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b4adf678)
  - 修复登录页切换登录页参数丢失问题 &nbsp;-&nbsp; by **Soybean** [<samp>(78985)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/789855a3)
  - Fix Naive Pagination's outdated API &nbsp;-&nbsp; by **tnt group** [<samp>(37436)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3743612d)
  - prevent program freezing when pagesize returns 0 &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/545 [<samp>(f4eeb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f4eeb2ed)
  - The total number before assigning a value to the table is incorrect. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/687 [<samp>(56760)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/56760245)
  - fixed the issue where loading was not properly closed in some cases. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/737 [<samp>(85e40)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/85e40b19)
  - refactor useCountDown hook for improved countdown logic and clarity. &nbsp;-&nbsp; by **Azir** [<samp>(dfb64)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/dfb647a8)
- **packages**:
  - @sa/hooks: fix searchParams of useHookTable. fixed #552 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/552 [<samp>(96c10)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/96c1044f)
  - axios: fix json response. fixed #815 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/815 [<samp>(fd087)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fd087f59)
- **projects**:
  - 修复顶部加载条主题 &nbsp;-&nbsp; by **Soybean** [<samp>(ea591)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ea5917d2)
  - 修复主题配置 &nbsp;-&nbsp; by **Soybean** [<samp>(ff24f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ff24fda5)
  - 修复页面滚动行为 &nbsp;-&nbsp; by **Soybean** [<samp>(57e00)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/57e00e64)
  - 头部logo链接更正 &nbsp;-&nbsp; by **Soybean** [<samp>(5d8c3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5d8c3f54)
  - 修复登录的重定向地址 &nbsp;-&nbsp; by **Soybean** [<samp>(f97f2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f97f2266)
  - 修复页面缓存，添加多页签删除 &nbsp;-&nbsp; by **Soybean** [<samp>(24893)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/24893747)
  - 修复多页签删除功能 &nbsp;-&nbsp; by **Soybean** [<samp>(99adb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/99adbc5a)
  - 修复页面缓存 &nbsp;-&nbsp; by **Soybean** [<samp>(fa0a9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fa0a9079)
  - 修复页面滚动和页面100%视高占比 &nbsp;-&nbsp; by **Soybean** [<samp>(fa2cc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fa2cc789)
  - 修复同时显示两种multiTab &nbsp;-&nbsp; by **Soybean** [<samp>(5be2e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5be2e2a2)
  - 修复vertical-mix导航模式的二级菜单显示问题 &nbsp;-&nbsp; by **Soybean** [<samp>(6f286)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6f286e67)
  - 修复多级菜单页面multitab显示问题 &nbsp;-&nbsp; by **Soybean** [<samp>(f0474)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f0474bd9)
  - 完善侧边菜单展开逻辑 &nbsp;-&nbsp; by **Soybean** [<samp>(b5f05)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b5f05128)
  - 修复vertical sider自适应主题 &nbsp;-&nbsp; by **Soybean** [<samp>(9097f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9097fa38)
  - 修复登录页刷新跳404 &nbsp;-&nbsp; by **Soybean** [<samp>(358d4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/358d4e8a)
  - 修复没有子页面的路由写法问题 &nbsp;-&nbsp; by **Soybean** [<samp>(b80c2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b80c2246)
  - 修复globalFooter适应暗黑模式 &nbsp;-&nbsp; by **Soybean** [<samp>(93f08)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/93f08d90)
  - 修复主题相关，自适应操作系统暗黑模式 &nbsp;-&nbsp; by **Soybean** [<samp>(bfa42)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bfa42d76)
  - 修复tab过多时样式坍塌，添加tab横向滚动 &nbsp;-&nbsp; by **Soybean** [<samp>(0ec4d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0ec4d218)
  - 关于页面：开发环境依赖更正 &nbsp;-&nbsp; by **Soybean** [<samp>(3b3ba)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3b3baf93)
  - 修复分析页折线图表布局问题 &nbsp;-&nbsp; by **Soybean** [<samp>(43b83)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/43b832be)
  - 修复multiTab关闭逻辑，添加关闭左边和右边的标签右键操作 &nbsp;-&nbsp; by **Soybean** [<samp>(ed90c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ed90cb8f)
  - wangEditor在暗黑模式下的背景色问题 &nbsp;-&nbsp; by **Yanbowen** [<samp>(a7de3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a7de3140)
  - 修复百度地图sdk地址 &nbsp;-&nbsp; by **Soybean** [<samp>(9a97d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9a97d23c)
  - 腾讯地图容器高自适应 &nbsp;-&nbsp; by **Soybean** [<samp>(d7054)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d7054c59)
  - 修复在暗黑模式下第一次进入网页不会触发暗黑模式监听 &nbsp;-&nbsp; by **Yanbowen** [<samp>(c4a65)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c4a652e2)
  - 修复富文本编辑器在亮色主题下全屏后背景色丢失 &nbsp;-&nbsp; by **14534** [<samp>(4ab77)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4ab77021)
  - 修复tab在移动端无法点击 &nbsp;-&nbsp; by **Soybean** [<samp>(1a76d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1a76de04)
  - 页面各部分背景颜色添加自然过渡 &nbsp;-&nbsp; by **Soybean** [<samp>(1c5fd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1c5fdca5)
  - 更正dashboard的布局文件 &nbsp;-&nbsp; by **Soybean** [<samp>(31fda)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/31fda0ce)
  - 布局修复：从填充屏幕高的页面切换至滚动页面导致布局坍塌 &nbsp;-&nbsp; by **Soybean** [<samp>(2fdb5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2fdb5f56)
  - 修复打包构建时图标错误 &nbsp;-&nbsp; by **Soybean** [<samp>(93f9a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/93f9aa95)
  - 添加西瓜视频实例在onUnMounted的销毁，多页签居中距离精确 &nbsp;-&nbsp; by **Soybean** [<samp>(73896)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/738964a7)
  - 修复网络请求错误空信息的提示 &nbsp;-&nbsp; by **Soybean** [<samp>(ff921)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ff9216b6)
  - 请求相关细节修复 &nbsp;-&nbsp; by **Soybean** [<samp>(2ad1a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2ad1ad32)
  - 修复redirect-not-found子路由 &nbsp;-&nbsp; by **Soybean** [<samp>(5bfb8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5bfb8199)
  - 去除Layout组件冗余代码 &nbsp;-&nbsp; by **Soybean** [<samp>(0e783)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0e783bcf)
  - 修复面包屑数据 &nbsp;-&nbsp; by **Soybean** [<samp>(28b5d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/28b5d224)
  - 修复vertical-mix布局、重构初始化的loading &nbsp;-&nbsp; by **Soybean** [<samp>(579e0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/579e0740)
  - 修复未登录时会调用获取用户路由的接口 &nbsp;-&nbsp; by **Soybean** [<samp>(21bab)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/21bab1f7)
  - 修复路由守卫的动态路由逻辑 &nbsp;-&nbsp; by **Soybean** [<samp>(b61b0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b61b0ce2)
  - vite配置修复 &nbsp;-&nbsp; by **Soybean** [<samp>(facc0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/facc00e8)
  - 修复分析页和工作台的布局问题 &nbsp;-&nbsp; by **Soybean** [<samp>(e93b9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e93b94cb)
  - 修复项目配置拷贝功能 &nbsp;-&nbsp; by **Soybean** [<samp>(a7a26)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a7a269d6)
  - 修复页面切换动画无变化 &nbsp;-&nbsp; by **Soybean** [<samp>(c4546)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c4546bdf)
  - 修复页面切换动画开关不生效 &nbsp;-&nbsp; by **bundle** [<samp>(9d4ed)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9d4ed617)
  - 修复 BASE_URL 没有生效的问题 &nbsp;-&nbsp; by **pany** [<samp>(72d7d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/72d7dcfa)
  - 修复vite alias &nbsp;-&nbsp; by **Soybean** [<samp>(cd7ca)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cd7ca8f4)
  - 修复路由守卫的动态路由逻辑 &nbsp;-&nbsp; by **Soybean** [<samp>(e6c26)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e6c26fcb)
  - 全局搜索弹窗弹出时动画闪屏问题 &nbsp;-&nbsp; by @yanbowe [<samp>(bb1bb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bb1bbf27)
  - 去除从环境文件引入端口号导致的错误 &nbsp;-&nbsp; by **Soybean** [<samp>(2d6d1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2d6d179d)
  - 修复在新版vite下环境变量获取不到的问题 &nbsp;-&nbsp; by **Soybean** [<samp>(3fb13)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3fb13ca9)
  - 修复获取vite环境变量的方式 &nbsp;-&nbsp; by **Soybean** [<samp>(46e1a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/46e1ae78)
  - 添加获取路由组件文件未找到时的错误提示 &nbsp;-&nbsp; by **Soybean** [<samp>(219f8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/219f87f4)
  - 添加.npmrc修复无法获取自动引入的全局组件声明类型 &nbsp;-&nbsp; by **Soybean** [<samp>(e8488)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e8488e4d)
  - 修复样式 &nbsp;-&nbsp; by **Soybean** [<samp>(e8999)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e8999144)
  - 修复插件不存在的错误提示 &nbsp;-&nbsp; by **Grazing Wind** [<samp>(71652)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/71652820)
  - 修复权限切换路由数据未更新的问题 &nbsp;-&nbsp; by **Soybean** [<samp>(60f91)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/60f91250)
  - 修复页面切换时导致的溢出滚动条 &nbsp;-&nbsp; by **Soybean** [<samp>(e0233)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e0233061)
  - 修复@antv/g2生产环境报错 &nbsp;-&nbsp; by **Soybean** [<samp>(4558c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4558c24d)
  - 修复顶部菜单的位置失效问题 &nbsp;-&nbsp; by **Soybean** [<samp>(4ee0d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4ee0d94f)
  - 设置tab标题导致meta属性丢失 &nbsp;-&nbsp; by **燕博文** [<samp>(efcfa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/efcfa576)
  - 修复tab不显示路由首页的问题 &nbsp;-&nbsp; by **Soybean** [<samp>(a792b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a792bb5c)
  - 修复多个后端服务时的本地代理 &nbsp;-&nbsp; by **Soybean** [<samp>(2aba5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2aba58c9)
  - 修复图标的TS类型 &nbsp;-&nbsp; by **Soybean** [<samp>(dbd67)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/dbd67609)
  - 修复import.meta.env的TS类型 &nbsp;-&nbsp; by **Soybean** [<samp>(19942)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/19942625)
  - 修复构建后mockjs对xhr的影响问题 &nbsp;-&nbsp; by **Soybean** [<samp>(77572)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/77572855)
  - 修复TS类型问题 &nbsp;-&nbsp; by **Soybean** [<samp>(16dce)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/16dce9a4)
  - 修复eslint规则 &nbsp;-&nbsp; by **Soybean** [<samp>(d7f5b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d7f5bf33)
  - add iconify json &nbsp;-&nbsp; by **Soybean** [<samp>(8a1ec)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8a1ec938)
  - fix vite-pwa plugin config &nbsp;-&nbsp; by **Soybean** [<samp>(94098)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/94098d02)
  - add router-page.d.ts to git [将router-page.d.ts添加git提交] &nbsp;-&nbsp; by **Soybean** [<samp>(7a580)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7a580355)
  - fix router when the dynamic routes api was failed [修复当动态路由接口失败后路由异常问题] &nbsp;-&nbsp; by **Soybean** [<samp>(f2b58)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f2b580fc)
  - fix login success message [修复登录成功的消息提示] &nbsp;-&nbsp; by **Soybean** [<samp>(81039)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/810398ab)
  - 修复tabs在static路由模式下可以关闭首页 &nbsp;-&nbsp; by **燕博文** [<samp>(7211a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7211a17a)
  - 修复动态路由模式下路由不排序的问题 &nbsp;-&nbsp; by **“青菜白玉汤”** [<samp>(58b27)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/58b27c96)
  - fix eslint svg cause incorrect icon render &nbsp;-&nbsp; by **Soybean** [<samp>(0b5af)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0b5afda2)
  - sortRoutes recursively &nbsp;-&nbsp; by **sunhao1256** [<samp>(91889)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/91889414)
  - not only `/login` claim dynamic path scenario , but also others , eg:/user/1 &nbsp;-&nbsp; by **sunhao1256** [<samp>(60598)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/60598915)
  - the length of routes children list should greater than 0 &nbsp;-&nbsp; by **HuangZheng** [<samp>(e1afc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e1afc10b)
  - fix pwa logo &nbsp;-&nbsp; by **Soybean** [<samp>(bf2f6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bf2f6172)
  - fix github bug-report &nbsp;-&nbsp; by **Soybean** [<samp>(f73e3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f73e3f64)
  - fix router guide [修复路由跳转异常] fixed #216 &nbsp;-&nbsp; by **Soybean** in https://github.com/faiz-Liu/soybean-admin/issues/216 [<samp>(59578)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5957833a)
  - fix better-mock usage [修复better-mock用法] &nbsp;-&nbsp; by **Soybean** [<samp>(c5764)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c57640ac)
  - tsconfig missing isolatedModules &nbsp;-&nbsp; by **Kirk Lin** [<samp>(ab49a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ab49afd3)
  - fix mockjs [修复mockjs] &nbsp;-&nbsp; by **Soybean** [<samp>(9b19f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9b19f96f)
  - add prod mockjs switch [添加生产模式的mockjs的开关] &nbsp;-&nbsp; by **Soybean** [<samp>(9f563)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9f5638f1)
  - 修复面包屑导航下拉菜单语言显示问题 &nbsp;-&nbsp; by **cc** [<samp>(ee8fa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ee8fa048)
  - hide the drawer when it is initial mobile mode [初始化时为移动端布局则隐藏侧边栏] fixed #238 &nbsp;-&nbsp; by **Soybean** in https://github.com/faiz-Liu/soybean-admin/issues/238 [<samp>(0abde)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0abde46e)
  - fix userRoleOptions &nbsp;-&nbsp; by **Soybean** [<samp>(2ca2b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2ca2b766)
  - fix set tab title (fixed #256) &nbsp;-&nbsp; by **Soybean** in https://github.com/faiz-Liu/soybean-admin/issues/256 [<samp>(13f6c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/13f6cd8e)
  - correct the lang file name & add recommend vscode plugin i18n-ally &nbsp;-&nbsp; by @soybeanjs [<samp>(864ec)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/864ec473)
  - fix reload button animate &nbsp;-&nbsp; by @soybeanjs [<samp>(41f23)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/41f23386)
  - 修复路由命名为包含关系时导致导航数据出错的问题 &nbsp;-&nbsp; by **pantao** [<samp>(76636)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/766369f9)
  - rename zh-ch &nbsp;-&nbsp; by @soybeanjs [<samp>(a8a77)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a8a77ea5)
  - Fix welcome notification not closing &nbsp;-&nbsp; by @Azir-11 [<samp>(748cf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/748cfa2c)
  - fix i18n vscode settings &nbsp;-&nbsp; by @soybeanjs [<samp>(fbf4c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fbf4cc43)
  - add duration of login success notification &nbsp;-&nbsp; by @soybeanjs [<samp>(1335d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1335d47a)
  - fix menu indent &nbsp;-&nbsp; by @soybeanjs [<samp>(87143)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/87143172)
  - fix theme mode segment &nbsp;-&nbsp; by @soybeanjs [<samp>(2372d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2372dc9b)
  - fix app loading theme color &nbsp;-&nbsp; by @soybeanjs [<samp>(0ba19)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0ba19d54)
  - fix page about style in mobile &nbsp;-&nbsp; by @soybeanjs [<samp>(8b6de)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8b6de484)
  - fix themeDrawer darkMode segement &nbsp;-&nbsp; by @soybeanjs [<samp>(1b5ca)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1b5caa08)
  - fix themeDrawer copy &nbsp;-&nbsp; by @soybeanjs [<samp>(b3779)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b3779a63)
  - remove space in tab content &nbsp;-&nbsp; by @soybeanjs [<samp>(4aae6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4aae6a52)
  - fix horizontal menu &nbsp;-&nbsp; by @soybeanjs [<samp>(d886e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d886e50f)
  - perf card style &nbsp;-&nbsp; by @soybeanjs [<samp>(c1afb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c1afb9dc)
  - fix manage_user title &nbsp;-&nbsp; by @soybeanjs [<samp>(7770b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7770b378)
  - default proxy prefix &nbsp;-&nbsp; by **smileluck** [<samp>(da246)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/da246427)
  - fix request msg &nbsp;-&nbsp; by @soybeanjs [<samp>(ae6b6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ae6b6134)
  - Fix the issue of tab error displaying parent localIcon &nbsp;-&nbsp; by @Azir-11 [<samp>(a9c98)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a9c98d96)
  - The matched value of TabRoute should be optional &nbsp;-&nbsp; by @Azir-11 [<samp>(e6fed)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e6fed1fd)
  - fix build [unocss]: build failed to load icon "close", fixed #319 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/319 [<samp>(c18d8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c18d82f9)
  - fix resolve alias &nbsp;-&nbsp; by @soybeanjs [<samp>(3bdcb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3bdcbc71)
  - Missing default value for tab icon &nbsp;-&nbsp; by @Azir-11 [<samp>(72a46)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/72a4679c)
  - add route icon: fucntion_hide-child &nbsp;-&nbsp; by @soybeanjs [<samp>(0a3ef)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0a3efe34)
  - fix table x-scroll. fixed #324 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/324 [<samp>(c7e2c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c7e2c559)
  - Fix the logic of root route redirection to home &nbsp;-&nbsp; by **恕瑞玛的皇帝** [<samp>(0123c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0123c37d)
  - Fix homepage mount error under dynamic routing &nbsp;-&nbsp; by **恕瑞玛的皇帝** [<samp>(9cf2a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9cf2a513)
  - fix repeat home tab &nbsp;-&nbsp; by @soybeanjs [<samp>(bccd6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bccd6cb3)
  - fix proxy config &nbsp;-&nbsp; by @soybeanjs [<samp>(c8019)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c8019c4f)
  - fix proxy config &nbsp;-&nbsp; by @soybeanjs [<samp>(ffc95)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ffc95d2b)
  - fix table row-key ts type &nbsp;-&nbsp; by @soybeanjs [<samp>(0cc8f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0cc8f05a)
  - fix class name conflict with unocss icon &nbsp;-&nbsp; by @soybeanjs [<samp>(455e4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/455e48f7)
  - fix repeat routes &nbsp;-&nbsp; by @soybeanjs [<samp>(2c543)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2c543f19)
  - fix route init &nbsp;-&nbsp; by @soybeanjs [<samp>(23a40)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/23a4098b)
  - fix pin-toggler toolTip zIndex &nbsp;-&nbsp; by @soybeanjs [<samp>(f89e6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f89e6c03)
  - fix flatRequest error type. fixed #376 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/376 [<samp>(1ec5e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1ec5ea0f)
  - add maxWidth for GlobalTab to fix bg with gap. fixed #350 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/350 [<samp>(cc539)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cc539974)
  - unify border-radius of Tag. fixed #378 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/378 [<samp>(2f15a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2f15a2ac)
  - fix menu edit rules &nbsp;-&nbsp; by @paynezhuang [<samp>(00105)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/001059cc)
  - fix SvgIcon inheritAttrs warning &nbsp;-&nbsp; by @soybeanjs [<samp>(efc0e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/efc0e25c)
  - fix axios createRequest: add default state &nbsp;-&nbsp; by @soybeanjs [<samp>(d6eda)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d6eda8f9)
  - update union-key.d.ts &nbsp;-&nbsp; by @soybeanjs [<samp>(60bef)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/60beff7e)
  - fix update theme color &nbsp;-&nbsp; by @soybeanjs [<samp>(27c53)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/27c53cd6)
  - fix CHANGELOG versions &nbsp;-&nbsp; by @soybeanjs [<samp>(d9af5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d9af5aa2)
  - fix disabled page animate &nbsp;-&nbsp; by @soybeanjs [<samp>(23f28)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/23f283aa)
  - fix routes data when role is change. fixed #391 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/391 [<samp>(cb83d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cb83d6d9)
  - fix tabs data when role is change. fixed #392 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/392 [<samp>(04aa0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/04aa0972)
  - recovery pnpm-lock.yaml &nbsp;-&nbsp; by @soybeanjs [<samp>(c6952)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c695208f)
  - added responseType judgment. #396 &nbsp;-&nbsp; by **alleycharming** in https://github.com/faiz-Liu/soybean-admin/issues/396 [<samp>(82eab)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/82eabab7)
  - supply $t import statement &nbsp;-&nbsp; by @soybeanjs [<samp>(b2660)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b2660358)
  - fix mix-menu blank. fixed #389 & cache mixMenuFixed &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/389 [<samp>(93c7f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/93c7ff71)
  - text level low. #409 &nbsp;-&nbsp; by **alleycharming** in https://github.com/faiz-Liu/soybean-admin/issues/409 [<samp>(3ddb1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3ddb17a0)
  - menu fixedIndexInTab default null &nbsp;-&nbsp; by @paynezhuang [<samp>(3d10e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3d10ef1a)
  - fix tab fixedIndex as null case &nbsp;-&nbsp; by @paynezhuang [<samp>(4708e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4708eded)
  - recovery the layout config before is mobile. fixed #408, fixed #361 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/408 and https://github.com/faiz-Liu/soybean-admin/issues/361 [<samp>(dae2a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/dae2aa55)
  - fix manage page drawer operate about data reset. fixed #415, fixed #417 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/415 and https://github.com/faiz-Liu/soybean-admin/issues/417 [<samp>(f4513)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f4513e1e)
  - fix menu-toggler zIndex &nbsp;-&nbsp; by @soybeanjs [<samp>(7bd43)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7bd43df5)
  - fix manage_menu modal style &nbsp;-&nbsp; by @soybeanjs [<samp>(60f3b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/60f3b140)
  - fix menu data when role is changed. fixed #391 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/391 [<samp>(3b47b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3b47b5a5)
  - fix useRouter. fixed #436 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/436 [<samp>(0774a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0774a515)
  - add error handle when get routes in dynamic route mode. fixed 440 &nbsp;-&nbsp; by @soybeanjs [<samp>(57b4a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/57b4a9d5)
  - fix header style & fix button highlight when click global-tab. fixed #446 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/446 [<samp>(64fc0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/64fc0996)
  - fix multi tab page only render once. fixed #441 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/441 [<samp>(e379d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e379d6ce)
  - fix click menu search. fixed #466, close #467 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/466 and https://github.com/faiz-Liu/soybean-admin/issues/467 [<samp>(8efdb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8efdb10d)
  - fix reCacheRoute. fixed #464 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/464 [<samp>(59faf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/59faf152)
  - fix register name, CodeLogin => Register &nbsp;-&nbsp; by @m-xlsea in https://github.com/faiz-Liu/soybean-admin/issues/478 [<samp>(ddf38)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ddf3823a)
  - fix get user info when page reload &nbsp;-&nbsp; by @soybeanjs [<samp>(ff51b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ff51b72d)
  - fix setupAppVersionNotification render &nbsp;-&nbsp; by @soybeanjs [<samp>(6a6eb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6a6eb9af)
  - hide AppVersionNotification in DEV mode &nbsp;-&nbsp; by @sigma-plus in https://github.com/faiz-Liu/soybean-admin/issues/482 [<samp>(62592)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/62592872)
  - fix menu-toggler hidden in mobile layout. fixed #483 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/483 [<samp>(4470c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4470cb4e)
  - fix mobile browser theme issue by adding color-scheme meta tag to index.html &nbsp;-&nbsp; by @KickCashew in https://github.com/faiz-Liu/soybean-admin/issues/488 [<samp>(c2125)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c2125652)
  - Fix secondary directory components is empty &nbsp;-&nbsp; by @paynezhuang in https://github.com/faiz-Liu/soybean-admin/issues/491 [<samp>(aabb2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/aabb2a49)
  - Fix the issue of abnormal tab caching after logout. fixed #495 &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/495 [<samp>(3eeac)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3eeace94)
  - request modal title use i18n. fixed #507 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/507 [<samp>(f7de3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f7de3fd0)
  - add `getDataByPage` for `useTable`. fixed #499 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/499 [<samp>(425c6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/425c69ac)
  - fix login redirect to routeHome when routeHome of dynamic route is not same as static route. fixed #511 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/511 [<samp>(49f60)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/49f60b2d)
  - fix the issue of abnormal width of the sidebar in the top menu mix and reverse mode &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/562 [<samp>(c4695)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c469512b)
  - fix HorizontalMixMenu inverted. fixed #563 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/563 [<samp>(4e55b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4e55b0e9)
  - fix vertical-menu will not render when the layout is from mobile &nbsp;-&nbsp; by @soybeanjs [<samp>(84027)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/84027347)
  - fix vertical-mix menu selected &nbsp;-&nbsp; by @soybeanjs [<samp>(59f07)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/59f07d8a)
  - fix watermark settings &nbsp;-&nbsp; by @soybeanjs [<samp>(5646a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5646a50d)
  - avoid retrieving cached HTML &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/605 [<samp>(ef6cf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ef6cf93d)
  - fix login redirect &nbsp;-&nbsp; by @soybeanjs [<samp>(3830e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3830ec7a)
  - fix vertical-mix-menu when sider collapse. fixed #608 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/608 [<samp>(c3f1f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c3f1f698)
  - fix breadcrumb when activeMenu is parent menu. fixed #589 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/589 [<samp>(79b2a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/79b2a28b)
  - fix refresh token when meet multi requests. fixed #581 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/581 [<samp>(27b52)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/27b5222c)
  - fix click global-tab in iPad. fixed #624 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/624 [<samp>(04d05)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/04d05647)
  - when the roles filter submenu is empty, the parent menu is not excluded. fixed #621. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/626 and https://github.com/faiz-Liu/soybean-admin/issues/621 [<samp>(0ac95)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0ac95bdc)
  - fix global-tab click conflict with contextmenu &nbsp;-&nbsp; by @soybeanjs [<samp>(3e72c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3e72c3b4)
  - fix route guard hook `onRouteSwitchWhenLoggedIn`. fixed #680 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/680 [<samp>(ab985)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ab9858c7)
  - check if init userInfo when initAuthRoute. fixed #680 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/680 [<samp>(9f4fb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9f4fb8c3)
  - fix login success notification. fixed #688 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/688 [<samp>(60dd2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/60dd2262)
  - fix update notifications. fixed #691, fixed #692 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/691 and https://github.com/faiz-Liu/soybean-admin/issues/692 [<samp>(ac862)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ac862478)
  - hidden multi-language button in login page. fix #694 &nbsp;-&nbsp; by **Azir** in https://github.com/faiz-Liu/soybean-admin/issues/694 [<samp>(54e7d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/54e7d6d0)
  - fix multiple calls to the login API when clicking quickly. fixed #697 &nbsp;-&nbsp; by @zsdycs in https://github.com/faiz-Liu/soybean-admin/issues/698 and https://github.com/faiz-Liu/soybean-admin/issues/697 [<samp>(86da7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/86da767e)
  - fix multiple calls to the login API when clicking quickly. fixed #697 " &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/698 and https://github.com/faiz-Liu/soybean-admin/issues/697 [<samp>(15163)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/15163d70)
  - fix active tab switch issue after removal &nbsp;-&nbsp; by @me-o in https://github.com/faiz-Liu/soybean-admin/issues/723 [<samp>(a7c59)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a7c59ada)
  - tab closure did not remove cache correctly. &nbsp;-&nbsp; by **Azir** [<samp>(7fb5c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7fb5c72f)
  - ensure proper text color when themes are inverted &nbsp;-&nbsp; by @wenyuanw [<samp>(afd60)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/afd60421)
  - Fix i18n-ally not working when setting moduleResolution to bundler. fixed #780 &nbsp;-&nbsp; by @xiaobao0505 in https://github.com/faiz-Liu/soybean-admin/issues/780 [<samp>(41191)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/41191d54)
- **readme**:
  - update GitHub stars and forks links for gitee &nbsp;-&nbsp; by @soybeanjs [<samp>(923eb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/923eb98a)
- **route**:
  - 当为左侧混合菜单时activeMenu无效情况 &nbsp;-&nbsp; by **燕博文** [<samp>(3e4f9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3e4f9e28)
- **styles**:
  - fix toggle-lang bg &nbsp;-&nbsp; by **Soybean** [<samp>(47309)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/473095b0)
  - 用户管理页面布局自适应屏幕高度 (fixed #253) &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/253 [<samp>(0f7b9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0f7b9d5e)
  - fix css var is inserted repeatedly &nbsp;-&nbsp; by **燕博文** [<samp>(769d8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/769d84a7)
  - fix useTable type &nbsp;-&nbsp; by @soybeanjs [<samp>(07124)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/071241f8)
  - fix FirstLevelMenu style. fixed #450 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/450 [<samp>(db64b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/db64b0e2)
  - fix PinToggler style. fixed #451 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/451 [<samp>(42b12)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/42b121a1)
- **svg-icon**:
  - 自定义图标在Dropdown组件下hover状态无法显示图标 &nbsp;-&nbsp; by **燕博文** [<samp>(0523f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0523f083)
- **types**:
  - 修复naive组件回调函数参数类型错误 &nbsp;-&nbsp; by **Soybean** [<samp>(66728)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/667282f8)
  - 数据类型 EnumDataType.boolean 为 [object Boolean] &nbsp;-&nbsp; by **liujunzheng** [<samp>(e9b55)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e9b55608)
  - 修复TS类型错误 &nbsp;-&nbsp; by **Soybean** [<samp>(45d31)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/45d31a0f)
  - 添加dotEnv类型的非空判断 &nbsp;-&nbsp; by **Soybean** [<samp>(cff11)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cff11d91)
  - Fixed the reference type error &nbsp;-&nbsp; by **dodu2014** in https://github.com/faiz-Liu/soybean-admin/issues/551 [<samp>(3e2a9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3e2a993d)
  - fix data type of useHookTable &nbsp;-&nbsp; by @soybeanjs [<samp>(276ea)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/276ea7fa)
  - fix the type of TableApiFn &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/599 [<samp>(26c93)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/26c93dff)
  - The environment variable VITE_ICON_LOCAL_PREFIX has the wrong type. &nbsp;-&nbsp; by **chenziwen** [<samp>(da149)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/da149e5b)
  - fix proxy types &nbsp;-&nbsp; by @soybeanjs [<samp>(12b25)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/12b25e0d)
- **utils**:
  - utils函数名称更正 &nbsp;-&nbsp; by **Soybean** [<samp>(68f4d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/68f4d012)
  - 修复iconifyRender &nbsp;-&nbsp; by **Soybean** [<samp>(c37d0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c37d0ac7)
  - make AxiosRequestConfig optional for request.handleDelete() &nbsp;-&nbsp; by **guuuuo** [<samp>(4a6fe)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4a6fec8a)
  - modalLogout bug when esc is pressed &nbsp;-&nbsp; by @sigma-plus in https://github.com/faiz-Liu/soybean-admin/issues/470 [<samp>(bd69c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bd69c00e)
  - fix `isPC`. fixed #644 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/644 [<samp>(47264)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4726498f)
- **多页签**:
  - 在pc模式下右键某个多页签会切换路由 &nbsp;-&nbsp; by **Yanbowen** [<samp>(a4394)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a4394dc3)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- refresh-koken命名 &nbsp;-&nbsp; by **“Southliu”** [<samp>(17155)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/17155047)
- **components**:
  - 添加更多主题颜色设置模态窗的层级 &nbsp;-&nbsp; by **xiaotao2018** [<samp>(ee7eb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ee7eb3ac)
  - 添加更多主题颜色设置模态窗的层级，z-index为int &nbsp;-&nbsp; by **xiaotao2018** [<samp>(e2d65)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e2d65543)
  - Optimize internationalized menu search code &nbsp;-&nbsp; by **燕博文** [<samp>(8c1ef)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8c1ef4b0)
  - Optimize menu search code &nbsp;-&nbsp; by **燕博文** [<samp>(296a2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/296a2d2f)
  - perf count-to &nbsp;-&nbsp; by @soybeanjs [<samp>(b2c61)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b2c61f03)
  - components  name is converted to uppercase &nbsp;-&nbsp; by **燕博文** [<samp>(04aa1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/04aa10b4)
  - perf global-search &nbsp;-&nbsp; by @soybeanjs [<samp>(72745)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/72745229)
- **hooks**:
  - perf use-table &nbsp;-&nbsp; by **Soybean** [<samp>(33180)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3318041b)
  - perf useHookTable &nbsp;-&nbsp; by @soybeanjs [<samp>(809fa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/809fa857)
  - perf useSignal &nbsp;-&nbsp; by @soybeanjs [<samp>(5d45c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5d45cef1)
- **project**:
  - Initializing the static routing function does not require asynchronization &nbsp;-&nbsp; by **CHENZL** in https://github.com/faiz-Liu/soybean-admin/issues/493 [<samp>(2198b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2198b982)
- **projects**:
  - 添加windicss指定的扫描目录，提升构建性能 &nbsp;-&nbsp; by **Soybean** [<samp>(8e6b0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8e6b0b29)
  - complete dynamic route translate [补充动态路由的翻译] &nbsp;-&nbsp; by **Soybean** [<samp>(7b746)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7b746fa0)
  - move changing document title by locale to global event of composables & add appLoading unmount &nbsp;-&nbsp; by **Soybean** [<samp>(08e19)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/08e194ef)
  - remove useless code &nbsp;-&nbsp; by **Soybean** [<samp>(eb8e4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/eb8e49e2)
  - use transformObjectToOption to generate option of object labels &nbsp;-&nbsp; by **Soybean** [<samp>(da611)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/da611fb1)
  - add type declaration for document startViewTransition &nbsp;-&nbsp; by **Soybean** [<samp>(d3ebe)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d3ebe950)
  - perf code &nbsp;-&nbsp; by @soybeanjs [<samp>(8081e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8081e19e)
  - env config &nbsp;-&nbsp; by @soybeanjs [<samp>(1bac3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1bac3b78)
  - add detailed annotations for route role &nbsp;-&nbsp; by @soybeanjs [<samp>(f6bab)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f6bab0cc)
  - perf code &nbsp;-&nbsp; by @soybeanjs [<samp>(5c49d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5c49d245)
  - remove useless file &nbsp;-&nbsp; by @soybeanjs [<samp>(c624f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c624f325)
  - remove @soybeanjs/cli &nbsp;-&nbsp; by @soybeanjs [<samp>(41349)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/41349555)
  - echarts loading style &nbsp;-&nbsp; by @soybeanjs [<samp>(456c3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/456c318a)
  - perf page manage_role, useTable &nbsp;-&nbsp; by @soybeanjs [<samp>(39aa7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/39aa7aa2)
  - perf table columns style &nbsp;-&nbsp; by @soybeanjs [<samp>(babdb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/babdb5d5)
  - perf page manage_menu style &nbsp;-&nbsp; by @soybeanjs [<samp>(0aa75)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0aa75c04)
  - perf code &nbsp;-&nbsp; by @soybeanjs [<samp>(7fa87)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7fa87f53)
  - perf code &nbsp;-&nbsp; by @soybeanjs [<samp>(05db8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/05db8c08)
  - perf code &nbsp;-&nbsp; by @soybeanjs [<samp>(dc24a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/dc24a367)
  - perf manage page style &nbsp;-&nbsp; by @soybeanjs [<samp>(779ba)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/779ba4e4)
  - perf manage menu &nbsp;-&nbsp; by @soybeanjs [<samp>(71f2c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/71f2c553)
  - manage menu: add transform to component &nbsp;-&nbsp; by @soybeanjs [<samp>(0abbf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0abbfa5d)
  - perf code &nbsp;-&nbsp; by @soybeanjs [<samp>(a0bad)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a0bad57a)
  - perf code &nbsp;-&nbsp; by @soybeanjs [<samp>(b7f07)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b7f07491)
  - remove useless prop `title` of `NDrawer` &nbsp;-&nbsp; by @soybeanjs [<samp>(fdde6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fdde679c)
  - add tsconfig.json for @sa/color-palette &nbsp;-&nbsp; by @soybeanjs [<samp>(d460e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d460e5cc)
  - perf judgement the fixed tab &nbsp;-&nbsp; by @soybeanjs [<samp>(b3e9b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b3e9bbae)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **components**:
  - accuracy draggable area for TableColumnSetting with animation &nbsp;-&nbsp; by @orangelckc in https://github.com/faiz-Liu/soybean-admin/issues/465 [<samp>(2aa85)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2aa85c6f)
  - optimize spacing for lang-switch dropdown options &nbsp;-&nbsp; by @wenyuanw [<samp>(fcb89)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fcb89883)
- **hooks**:
  - remove obsolete disabling cache. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/729 [<samp>(4e1b6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4e1b65b6)
  - update detection function to cover the exceptions that occur when the request fails. &nbsp;-&nbsp; by **恕瑞玛的皇帝** [<samp>(22218)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/222187d3)
- **projects**:
  - remove deprecated code &nbsp;-&nbsp; by @soybeanjs [<samp>(72ccb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/72ccb6bf)
  - optimize code &nbsp;-&nbsp; by @soybeanjs [<samp>(bc8dc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bc8dc47d)
  - unocss border shortcut &nbsp;-&nbsp; by @soybeanjs [<samp>(40d0f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/40d0f8ac)
  - optimize RouteMeta remarks &nbsp;-&nbsp; by @soybeanjs [<samp>(ffb48)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ffb48b15)
  - optimize `setupAppVersionNotification` &nbsp;-&nbsp; by @soybeanjs [<samp>(b5a72)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b5a723cb)
  - get buildTime with timezone 'Asia/Shanghai' &nbsp;-&nbsp; by @soybeanjs [<samp>(069fa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/069fa8a8)
  - optimize code &nbsp;-&nbsp; by @soybeanjs [<samp>(b94ba)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b94baa18)
  - optimize `getRouteQueryOfLoginRoute` &nbsp;-&nbsp; by @soybeanjs [<samp>(693f7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/693f7046)
  - supports custom menu icon sizes &nbsp;-&nbsp; by @wynn-w in https://github.com/faiz-Liu/soybean-admin/issues/534 [<samp>(e035e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e035eab2)
  - add type WatermarkProps &nbsp;-&nbsp; by @soybeanjs [<samp>(f26d0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f26d0a61)
  - remove home NAlert closable &nbsp;-&nbsp; by @soybeanjs [<samp>(98b75)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/98b75c22)
  - optimize response code comparison &nbsp;-&nbsp; by @soybeanjs [<samp>(cf67d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cf67d55c)
  - optimize code &nbsp;-&nbsp; by @soybeanjs [<samp>(cb1d4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cb1d4452)
  - optimize menu selectedKey &nbsp;-&nbsp; by @soybeanjs [<samp>(531bf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/531bfaf1)
  - optimize code &nbsp;-&nbsp; by @soybeanjs [<samp>(6561f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6561f0b5)
  - optimize code &nbsp;-&nbsp; by @soybeanjs [<samp>(38eeb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/38eeb678)
  - remove defineModel setting，enabled by default &nbsp;-&nbsp; by @yanbowe in https://github.com/faiz-Liu/soybean-admin/issues/620 [<samp>(60bbd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/60bbd2d1)
  - optimize code &nbsp;-&nbsp; by @soybeanjs [<samp>(9ad5d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9ad5d717)
  - optimize router guard &nbsp;-&nbsp; by @soybeanjs [<samp>(0dfcf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0dfcf18b)
  - use `defu` to fill added theme config &nbsp;-&nbsp; by @soybeanjs [<samp>(101b6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/101b6f90)
  - optimize code &nbsp;-&nbsp; by @soybeanjs [<samp>(6489e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6489ec46)
  - optimize tab deletion logic. closed #755 &nbsp;-&nbsp; by @wenyuanw in https://github.com/faiz-Liu/soybean-admin/issues/755 [<samp>(e6044)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e6044d0f)
- **types**:
  - Enhance compatibility of global types &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/494 [<samp>(cd9d5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cd9d58d4)
  - remove useless types. &nbsp;-&nbsp; by **Azir** [<samp>(eed61)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/eed617f9)
- **utils**:
  - Reduce code indentation and improve readability &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/496 [<samp>(ad2f2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ad2f2470)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **auth**:
  - 页面跳转逻辑优化 &nbsp;-&nbsp; by **Soybean** [<samp>(c84c3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c84c37d1)
- **components**:
  - 用NCard组件替换ShadowCard &nbsp;-&nbsp; by **Soybean** [<samp>(048ea)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/048eae67)
  - hoverContainer组件属性调整 &nbsp;-&nbsp; by **Soybean** [<samp>(4642e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4642ee62)
  - 重构AppProvider &nbsp;-&nbsp; by **Soybean** [<samp>(e70a3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e70a3282)
  - basicLayout布局组件重构完成：根据NavMode拆分为多个布局组件 &nbsp;-&nbsp; by **Soybean** [<samp>(ffe98)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ffe98783)
  - blankLayout引入GlobalContent &nbsp;-&nbsp; by **Soybean** [<samp>(1ffb7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1ffb75af)
  - 去除packages的soybean-layout，通过npm的方式引入 &nbsp;-&nbsp; by **Soybean** [<samp>(c1182)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c1182fef)
- **czg**:
  - update cz-git,czg breaking changes &nbsp;-&nbsp; by **燕博文** [<samp>(fcb7a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fcb7ad96)
- **hooks**:
  - 状态管理模块拆分 &nbsp;-&nbsp; by **Soybean** [<samp>(1128a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1128ae18)
  - 重构hook函数取消监听方式 &nbsp;-&nbsp; by **燕博文** [<samp>(fd948)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fd948867)
  - refactor @sa/color-palette &nbsp;-&nbsp; by @soybeanjs [<samp>(93191)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/93191737)
  - refactor useSignal, useComputed &nbsp;-&nbsp; by @soybeanjs [<samp>(3b5e4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3b5e4b34)
- **iframe-page**:
  - remove unused lifecycle hooks and clean up script setup &nbsp;-&nbsp; by @soybeanjs [<samp>(276d8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/276d836c)
- **layouts**:
  - layout/header 反转色样式补充 &nbsp;-&nbsp; by **元家怿** [<samp>(01d0b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/01d0bcbf)
- **packages**:
  - @sa/materials: remove tab close shortcut by mouse &nbsp;-&nbsp; by @soybeanjs [<samp>(4da58)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4da588c6)
- **projects**:
  - element-plus国际化 &nbsp;-&nbsp; by **Soybean** [<samp>(88320)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/88320a8e)
  - 名称变更 &nbsp;-&nbsp; by **Soybean** [<samp>(93bba)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/93bbaca8)
  - 完善路由配置 &nbsp;-&nbsp; by **Soybean** [<samp>(ab77d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ab77d58e)
  - 顶部header和多页签的高度调整 &nbsp;-&nbsp; by **Soybean** [<samp>(e1dc0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e1dc0f29)
  - 环境文件重命名 &nbsp;-&nbsp; by **Soybean** [<samp>(e9db6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e9db67ee)
  - 重构browser tab初步 &nbsp;-&nbsp; by **Soybean** [<samp>(51b86)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/51b86035)
  - chrome Tab重构完成 &nbsp;-&nbsp; by **Soybean** [<samp>(d4884)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d488451f)
  - 路由文件夹拆分模块，代码重构 &nbsp;-&nbsp; by **Soybean** [<samp>(73505)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/73505d91)
  - 登录重定向地址相关重构 &nbsp;-&nbsp; by **Soybean** [<samp>(04008)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/04008b63)
  - 路由组件导入拆分 &nbsp;-&nbsp; by **Soybean** [<samp>(3edf4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3edf46eb)
  - 路由文件夹重构 &nbsp;-&nbsp; by **Soybean** [<samp>(b2854)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b2854d57)
  - 精简代码 &nbsp;-&nbsp; by **Soybean** [<samp>(5dc86)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5dc8626c)
  - 注入全局常量：PROJECT_BUILD_TIME - 构建时间 &nbsp;-&nbsp; by **Soybean** [<samp>(ec907)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ec907f06)
  - 项目依赖信息直接从package.json获取 &nbsp;-&nbsp; by **Soybean** [<samp>(4487f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4487f9fb)
  - 添加exportDefaults替换defineProps &nbsp;-&nbsp; by **Soybean** [<samp>(e61ee)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e61ee32a)
  - 去除vicons，统一使用iconify图标 &nbsp;-&nbsp; by **Soybean** [<samp>(cd6db)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cd6db3d4)
  - 地图插件页面布局重构 &nbsp;-&nbsp; by **Soybean** [<samp>(36e0e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/36e0e669)
  - 嵌入naive-ui的css vars，替换windicss的extend color &nbsp;-&nbsp; by **Soybean** [<samp>(2869b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2869b4cd)
  - basicLayout重构初步 &nbsp;-&nbsp; by **Soybean** [<samp>(33770)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/33770d23)
  - 路由声明重构，添加composables，BaseLayout进行中，文件夹规范 &nbsp;-&nbsp; by **Soybean** [<samp>(1e84d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1e84d13d)
  - 系统暗黑主题模式抽离成composables &nbsp;-&nbsp; by **Soybean** [<samp>(195e5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/195e5b9e)
  - 优化路由声明，添加路由模块导入，规范路相关文件夹 &nbsp;-&nbsp; by **Soybean** [<samp>(f1997)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f199794d)
  - 请求函数重构初步 &nbsp;-&nbsp; by **Soybean** [<samp>(9f643)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9f64321d)
  - axios封装：文件夹规范，错误处理完善 &nbsp;-&nbsp; by **Soybean** [<samp>(451c7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/451c7547)
  - axios封装完成 &nbsp;-&nbsp; by **Soybean** [<samp>(03b39)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/03b398af)
  - axios处理的请求结果去除网路状态 &nbsp;-&nbsp; by **Soybean** [<samp>(05696)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0569666a)
  - 文件夹位置规范 &nbsp;-&nbsp; by **Soybean** [<samp>(f5a5f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f5a5f44a)
  - 细节完善 &nbsp;-&nbsp; by **Soybean** [<samp>(62611)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6261156c)
  - 重构路由类型和路由元数据类型，重构多级菜单路由写法 &nbsp;-&nbsp; by **Soybean** [<samp>(d6838)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d683894b)
  - 优化路由导入页面写法，页面路由调整 &nbsp;-&nbsp; by **Soybean** [<samp>(0b10b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0b10b505)
  - 登录模块由query变更为动态路由params &nbsp;-&nbsp; by **Soybean** [<samp>(225c4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/225c4fe0)
  - 精简版+动态路由权限初步 &nbsp;-&nbsp; by **Soybean** [<samp>(de205)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/de2057f1)
  - 单独一级路由相关逻辑重构 &nbsp;-&nbsp; by **Soybean** [<samp>(ab9a6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ab9a6a2f)
  - 单独路由逻辑重构、路由转换函数优化 &nbsp;-&nbsp; by **Soybean** [<samp>(b36a6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b36a62b1)
  - 恢复pinia默认写法 &nbsp;-&nbsp; by **Soybean** [<samp>(b2a4d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b2a4ddf5)
  - 请求构造函数适配不同后端接口的数据结构 &nbsp;-&nbsp; by **Soybean** [<samp>(4f9d5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4f9d544d)
  - 细节完善 &nbsp;-&nbsp; by **Soybean** [<samp>(651e5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/651e58dc)
  - 重构路由页面组件的导入 &nbsp;-&nbsp; by **Soybean** [<samp>(e6503)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e65034d9)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(4e31a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4e31abd4)
  - lint命令修改 &nbsp;-&nbsp; by **Soybean** [<samp>(20911)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/20911dd8)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(e8b53)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e8b534b8)
  - 去除在pinia的getters的函数调用副作用，用watch代替 &nbsp;-&nbsp; by **Soybean** [<samp>(b35ed)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b35ed896)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(5e276)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5e276421)
  - mock权限相关数据优化 &nbsp;-&nbsp; by **Soybean** [<samp>(41e46)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/41e46a5d)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(251b5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/251b5b96)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(a7824)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a7824614)
  - 细节优化 &nbsp;-&nbsp; by **Soybean** [<samp>(c275f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c275f263)
  - layout和tab组件依赖名称变更、样式修复 &nbsp;-&nbsp; by **Soybean** [<samp>(de5fb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/de5fb842)
  - merge branch unocss to main &nbsp;-&nbsp; by **Soybean** [<samp>(69d51)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/69d51318)
  - 动态路由权限完善 &nbsp;-&nbsp; by **Soybean** [<samp>(55ddc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/55ddc9ca)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(14c14)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/14c145ee)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(3590b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3590b65e)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(a1c7e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a1c7e105)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(44ab5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/44ab55d5)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(095c4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/095c4323)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(d28b9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d28b9039)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(4c2f5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4c2f535a)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(d9ac7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d9ac7e4d)
  - 优化菜单支持横向滚动 &nbsp;-&nbsp; by **Soybean** [<samp>(8f3e8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8f3e855f)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(5fa82)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5fa822f4)
  - 代码优化 &nbsp;-&nbsp; by **燕博文** [<samp>(41147)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/41147b34)
  - 添加subscribeAppStore &nbsp;-&nbsp; by **Soybean** [<samp>(aa2f7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/aa2f78a8)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(b60db)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b60db898)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(61436)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/61436052)
  - 请求适配器函数范型重构、优化请求相关的命名 &nbsp;-&nbsp; by **Soybean** [<samp>(7f9c9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7f9c98ab)
  - 更新搜索弹窗的图标 &nbsp;-&nbsp; by **Soybean** [<samp>(ed9cd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ed9cd6ce)
  - 抽离格式化相关依赖配置 &nbsp;-&nbsp; by **Soybean** [<samp>(f4d37)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f4d37cf7)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(49f95)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/49f95c4e)
  - cancel autoinstall @iconify-json [取消@iconify-json自动安装] &nbsp;-&nbsp; by **Soybean** [<samp>(c29b8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c29b887e)
  - refactor page: user-management [重构用户管理页面] &nbsp;-&nbsp; by **Soybean** [<samp>(468b4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/468b4bb0)
  - format code style [调整代码格式] &nbsp;-&nbsp; by **Soybean** [<samp>(a9d58)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a9d58f88)
  - import cz-git, czg replace @soybeanjs/cli [引入cz-git、czg替换@soybeanjs/cli] &nbsp;-&nbsp; by **Soybean** [<samp>(1bdd8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1bdd81a1)
  - perfect scrollbar style [完善滚动条] &nbsp;-&nbsp; by **Soybean** [<samp>(1a02c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1a02cab9)
  - refactor app init loading [重构系统初始化的加载] &nbsp;-&nbsp; by **Soybean** [<samp>(57bfe)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/57bfe278)
  - new storage system [新的本地数据存储系统] &nbsp;-&nbsp; by **Soybean** [<samp>(97191)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/97191594)
  - add simple-git-hooks replace husky &nbsp;-&nbsp; by **Soybean** [<samp>(9110d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9110d875)
  - all file and folder use kebab-case &nbsp;-&nbsp; by **Soybean** [<samp>(cea60)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cea600f1)
  - update service and proxy config &nbsp;-&nbsp; by **Soybean** [<samp>(8debf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8debfe7e)
  - remove enum &nbsp;-&nbsp; by **Soybean** [<samp>(21d52)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/21d52142)
  - rename union key &nbsp;-&nbsp; by **Soybean** [<samp>(e2b32)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e2b320ad)
  - update useTable &nbsp;-&nbsp; by **Soybean** [<samp>(211ae)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/211ae1f9)
  - remove page examples: tree [去除tree相关示例页面] &nbsp;-&nbsp; by **Soybean** [<samp>(f3090)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f309003e)
  - use better-mock replace mockjs [用better-mock替换mockjs] &nbsp;-&nbsp; by **Soybean** [<samp>(9d3c7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9d3c7329)
  - upgrade vue3.3, official support defineOptions &nbsp;-&nbsp; by **Kirk Lin** [<samp>(86a37)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/86a370fd)
  - 生产环境缓存主题变更为sessionStorage &nbsp;-&nbsp; by @soybeanjs [<samp>(c46a5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c46a5920)
  - add reCacheRoute method &nbsp;-&nbsp; by @soybeanjs [<samp>(f92ee)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f92ee770)
  - update soybean domain &nbsp;-&nbsp; by @soybeanjs [<samp>(073fd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/073fd16b)
  - remove plugin-web-update-notification &nbsp;-&nbsp; by @soybeanjs [<samp>(f6c6d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f6c6dbd3)
  - fix conflict with locale file &nbsp;-&nbsp; by @soybeanjs [<samp>(3346b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3346bcdf)
  - refactor app-loading &nbsp;-&nbsp; by @soybeanjs [<samp>(b4f3d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b4f3dd2f)
  - use naive-ui color-picker &nbsp;-&nbsp; by @soybeanjs [<samp>(b5551)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b5551d67)
  - perf page home &nbsp;-&nbsp; by @soybeanjs [<samp>(4c61c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4c61c6ff)
  - login components => modules &nbsp;-&nbsp; by @soybeanjs [<samp>(59bec)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/59bec2d9)
  - perf page function_tab &nbsp;-&nbsp; by @soybeanjs [<samp>(b5477)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b5477e89)
  - update mock api &nbsp;-&nbsp; by @soybeanjs [<samp>(27241)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2724169e)
  - page manage_role: extract module &nbsp;-&nbsp; by @soybeanjs [<samp>(0e9e2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0e9e2e1d)
  - perf page manage_role &nbsp;-&nbsp; by @soybeanjs [<samp>(a19f8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a19f895c)
  - manage_route => manage_menu &nbsp;-&nbsp; by @soybeanjs [<samp>(f8467)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f8467ceb)
  - refactor service env config &nbsp;-&nbsp; by @soybeanjs [<samp>(43193)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/43193e28)
  - refactor unocss shortcuts: wh-full => size-full &nbsp;-&nbsp; by @soybeanjs [<samp>(b4c00)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b4c00ce1)
  - use enquirer replace prompts &nbsp;-&nbsp; by @soybeanjs [<samp>(b546f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b546ff86)
  - refactor useTable &nbsp;-&nbsp; by @soybeanjs [<samp>(c3efa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c3efa1b6)
  - finish refactor useTable &nbsp;-&nbsp; by @soybeanjs [<samp>(86301)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8630175a)
  - finish refactor useTable and apply &nbsp;-&nbsp; by @soybeanjs [<samp>(3fd15)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3fd15e56)
  - perf code &nbsp;-&nbsp; by @soybeanjs [<samp>(f91ef)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f91ef30b)
  - new route guard &nbsp;-&nbsp; by @soybeanjs [<samp>(37d20)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/37d20b8e)
  - refactor addThemeVarsToHtml &nbsp;-&nbsp; by @soybeanjs [<samp>(41e47)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/41e470ed)
  - update naive-ui.d.ts &nbsp;-&nbsp; by @soybeanjs [<samp>(bb74d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bb74d994)
  - useMixMenuContext replace useMixMenu &nbsp;-&nbsp; by @soybeanjs [<samp>(1e142)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1e14293d)
  - refactor @sa/color-palette => @sa/color & perf @sa/utils &nbsp;-&nbsp; by @soybeanjs [<samp>(34999)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/34999971)
  - `Soybean Admin` to `SoybeanAdmin` &nbsp;-&nbsp; by @soybeanjs [<samp>(a8dbc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a8dbc03e)
  - menu-operate-drawer => menu-operate-modal &nbsp;-&nbsp; by @soybeanjs [<samp>(003e1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/003e145e)
  - replace `cloneDeep` of `lodash-es` with `klona` &nbsp;-&nbsp; by @soybeanjs [<samp>(a9133)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a91335d7)
  - combine `theme tokens` and `theme settings`. close #379 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/379 [<samp>(1d1b1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1d1b148c)
  - change css vars mount to root &nbsp;-&nbsp; by @soybeanjs [<samp>(00f41)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/00f41dd2)
  - refactor router guard. fix #655 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/667 and https://github.com/faiz-Liu/soybean-admin/issues/655 [<samp>(09144)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/09144dfe)
- **styles**:
  - 样式调整 &nbsp;-&nbsp; by **Soybean** [<samp>(f2910)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f29106e4)
  - 代码格式 &nbsp;-&nbsp; by **Soybean** [<samp>(8f6d6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8f6d6ce3)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **README**:
  - Add supporting ecosystem tools to the open-source repository &nbsp;-&nbsp; by @WgoW and @testbrate in https://github.com/faiz-Liu/soybean-admin/issues/740 [<samp>(a013e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a013ea2c)
- **deps**:
  - update the Vite version of the project description. &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/732 [<samp>(80486)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/80486099)
- **other**:
  - 注释文案修改 &nbsp;-&nbsp; by **毛博文** [<samp>(d0064)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d00643c9)
  - update docs with video tutorial link. &nbsp;-&nbsp; by **Azir** [<samp>(7b2e5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7b2e510a)
- **projects**:
  - 更新README.md &nbsp;-&nbsp; by **Soybean** [<samp>(963ae)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/963aebee)
  - 更新README.md &nbsp;-&nbsp; by **Soybean** [<samp>(848fa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/848fa0c0)
  - 更新README.md &nbsp;-&nbsp; by **Soybean** [<samp>(39a74)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/39a7411d)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(22f8f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/22f8f3f0)
  - 添加书写规范文档 &nbsp;-&nbsp; by **Soybean** [<samp>(d9fd9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d9fd91d1)
  - 文档更新 &nbsp;-&nbsp; by **Soybean** [<samp>(8d2ba)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8d2ba3e5)
  - 文档格式规范 &nbsp;-&nbsp; by **Soybean** [<samp>(560b8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/560b8a15)
  - 文档更新 &nbsp;-&nbsp; by **Soybean** [<samp>(448d2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/448d28db)
  - 更新README &nbsp;-&nbsp; by **Soybean** [<samp>(c950a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c950ae9c)
  - vscode配置更新 &nbsp;-&nbsp; by **Soybean** [<samp>(7c5ed)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7c5ed9d3)
  - 更新README.md &nbsp;-&nbsp; by **Soybean** [<samp>(5790a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5790a4f5)
  - 更新README.md &nbsp;-&nbsp; by **Soybean** [<samp>(1d64e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1d64ebea)
  - 更新README.md &nbsp;-&nbsp; by **Soybean** [<samp>(6940f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6940f376)
  - 更新README.md &nbsp;-&nbsp; by **Soybean** [<samp>(4ef2e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4ef2ea58)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(54577)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/54577f10)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(1b346)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1b3463d2)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(98a7d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/98a7d25c)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(659e4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/659e4606)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(90ddf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/90ddf983)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(5eddb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5eddb491)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(02c51)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/02c51e6f)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(47f28)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/47f2871c)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(7ed5d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7ed5d0de)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(3befb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3befb229)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(e856c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e856cdb7)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(3aded)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3aded404)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(225e7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/225e7128)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(5b401)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5b401a79)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(8cdad)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8cdad542)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(a0dfa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a0dfa3d3)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(b8db2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b8db2116)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(21645)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/21645537)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(9a90f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9a90f18e)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(60a55)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/60a55a77)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(d5c75)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d5c75115)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(3d8be)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3d8befa3)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(21e63)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/21e63998)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(0811f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0811ffa5)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(84cb0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/84cb07ba)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(4b80a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4b80a661)
  - update docs &nbsp;-&nbsp; by **Soybean** [<samp>(e9656)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e9656c6e)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(ae99e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ae99e57c)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(0c70a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0c70a9e0)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(e2727)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e2727e6f)
  - revert docs &nbsp;-&nbsp; by **Soybean** [<samp>(2c562)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2c562331)
  - update README &nbsp;-&nbsp; by **Soybean** [<samp>(828a2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/828a2f5b)
  - update README &nbsp;-&nbsp; by **Soybean** [<samp>(a3562)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a3562d92)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(cf8c7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cf8c7cb2)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(1ef1b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1ef1b6bd)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(aaef0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/aaef0bec)
  - add qq to README.md [文档添加QQ群] &nbsp;-&nbsp; by **Soybean** [<samp>(f74a6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f74a6424)
  - update README.md [更新README.md] &nbsp;-&nbsp; by **Soybean** [<samp>(39709)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/397092c2)
  - update README.md [更新README.md] &nbsp;-&nbsp; by **Soybean** [<samp>(5a4f8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5a4f8427)
  - update README.md [更新README.md] &nbsp;-&nbsp; by **Soybean** [<samp>(a765d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a765da6e)
  - update README.md [更新README.md] &nbsp;-&nbsp; by **Soybean** [<samp>(a989b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a989b44a)
  - 优化README.md &nbsp;-&nbsp; by **xiaojunnuo** [<samp>(6ea75)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6ea755f2)
  - readme.md 二次开发的项目内容换行 &nbsp;-&nbsp; by **xiaojunnuo** [<samp>(f3a17)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f3a1707b)
  - update CHANGELOG.md &nbsp;-&nbsp; by **Soybean** [<samp>(5f6ca)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5f6caab3)
  - CHANGELOG.md &nbsp;-&nbsp; by **Soybean** [<samp>(a2521)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a2521385)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(b5839)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b5839eab)
  - CHANGELOG.md &nbsp;-&nbsp; by **Soybean** [<samp>(bb2ea)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bb2eab60)
  - update README.md: update example image url [更新示例图片的链接] &nbsp;-&nbsp; by **Soybean** [<samp>(4f512)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4f512635)
  - fix README.md: example image link &nbsp;-&nbsp; by **Soybean** [<samp>(56ea8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/56ea8937)
  - CHANGELOG.md &nbsp;-&nbsp; by **Soybean** [<samp>(ff5bf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ff5bf629)
  - generate full CHANGELOG.md &nbsp;-&nbsp; by **Soybean** [<samp>(055d4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/055d4cce)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(3c7e1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3c7e1cf4)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(1681c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1681c34a)
  - update README.md picture url &nbsp;-&nbsp; by **Soybean** [<samp>(4eefc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4eefc95b)
  - update README.md &nbsp;-&nbsp; by **Soybean** [<samp>(8f24a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8f24a94e)
  - update CHANGELOG.md by regenerate changelog &nbsp;-&nbsp; by **Soybean** [<samp>(2a9b7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2a9b725c)
  - update README.md logo &nbsp;-&nbsp; by @soybeanjs [<samp>(19141)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/19141a73)
  - update Docker deployment method &nbsp;-&nbsp; by **muzzyh** [<samp>(00da0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/00da0009)
  - update git hooks init command &nbsp;-&nbsp; by **muzzyh** [<samp>(7f35e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7f35e87e)
  - update README.md &nbsp;-&nbsp; by **Ikko Eltociear Ashimine** [<samp>(93ed5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/93ed5ad0)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(78364)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/783648f5)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(1ea48)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1ea4817f)
  - add README &nbsp;-&nbsp; by @soybeanjs [<samp>(2371b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2371ba84)
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(d16a9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d16a9d58)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(6a771)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6a771eae)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(57b6d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/57b6d8a0)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(b30c0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b30c0359)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(c260f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c260fe26)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(03c42)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/03c42aa8)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(0fae9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0fae9932)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(4e4d2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4e4d2de5)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(86b44)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/86b445c2)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(e2085)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e2085e05)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(6ea9b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6ea9b85f)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(ef4af)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ef4af79a)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(41830)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/418302a3)
  - add CHANGELOG.md &nbsp;-&nbsp; by @soybeanjs [<samp>(46b61)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/46b61566)
  - add communication &nbsp;-&nbsp; by @soybeanjs [<samp>(8c7ea)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8c7ea235)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(07d8d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/07d8d25d)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(1a707)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1a7070f0)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(f69e1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f69e1523)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(76011)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/76011af8)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(f4a9c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f4a9cf83)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(5a523)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5a5232bd)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(79d9c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/79d9c514)
  - update CHANGELOG.md &nbsp;-&nbsp; by @soybeanjs [<samp>(cf5bc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cf5bc88a)
  - add ecosystem to README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(d0f17)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d0f17a44)
  - add PanisAdmin to README &nbsp;-&nbsp; by @paynezhuang [<samp>(ce2a7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ce2a75b5)
  - add CHANGELOG.zh_CN.md &nbsp;-&nbsp; by @soybeanjs [<samp>(18b3f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/18b3f053)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(4d17c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4d17cfdc)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(19783)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1978397c)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(fa56e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fa56e9c9)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(419ea)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/419ea423)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(87b18)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/87b18386)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(756f8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/756f84ab)
  - update Node&pnpm version &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/472 [<samp>(9b05d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9b05d73e)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(2bec8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2bec8990)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(fe06b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fe06b8c4)
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(8f9a7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8f9a7050)
  - Fixed the hyperlink pointing error &nbsp;-&nbsp; by **Azir** [<samp>(20a81)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/20a81274)
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(70261)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7026126a)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(b3368)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b3368415)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(5c67d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5c67d065)
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(1e67a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1e67ae8c)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(58fc0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/58fc0962)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(a0b76)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a0b76dae)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(613c8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/613c836e)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(d3759)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d37591dd)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(ebc83)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ebc838c3)
  - update README &nbsp;-&nbsp; by **Ohh** in https://github.com/faiz-Liu/soybean-admin/issues/594 [<samp>(a8f92)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a8f923eb)
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(e9a2e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e9a2ee4a)
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(73e91)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/73e917ad)
  - update the location of important information in the document &nbsp;-&nbsp; by **Azir** [<samp>(9c012)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9c012c7d)
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(5baf1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5baf19d2)
  - set the Chinese version of README as default &nbsp;-&nbsp; by @soybeanjs [<samp>(9d28b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9d28b31c)
  - ✏️  add element-plus version link &nbsp;-&nbsp; by **一寸灰** in https://github.com/faiz-Liu/soybean-admin/issues/679 [<samp>(5c6ab)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5c6ab0b5)
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(21434)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/214341ee)
  - update README &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/718 [<samp>(3febb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3febb65d)
  - update README &nbsp;-&nbsp; by @xiatianYa in https://github.com/faiz-Liu/soybean-admin/issues/726 [<samp>(3cbaf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3cbaf4f4)
  - add gitcode link &nbsp;-&nbsp; by @soybeanjs [<samp>(f35c2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f35c250a)
- **projects): docs(projects**:
  - 更新README &nbsp;-&nbsp; by **Soybean** [<samp>(fb0dd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fb0dd3f2)
- **projects): docs(projects): docs(projects**:
  - 更新README &nbsp;-&nbsp; by **Soybean** [<samp>(1b440)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1b440403)
- **readme**:
  - add warning about upcoming `V2` version and link to plan list &nbsp;-&nbsp; by @soybeanjs [<samp>(4d42d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4d42dcbe)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**:
  - 添加多种插件：element-plus、iconify、windicss &nbsp;-&nbsp; by **Soybean** [<samp>(afd4d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/afd4d041)
  - 添加smooth-scroll插件、axios封装 &nbsp;-&nbsp; by **Soybean** [<samp>(82411)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/82411cc5)
  - 添加打包时跳过对依赖的类型校验 &nbsp;-&nbsp; by **Soybean** [<samp>(f5220)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f5220e5a)
  - 依赖升级 &nbsp;-&nbsp; by **Soybean** [<samp>(4382b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4382bfa9)
  - 修复element-plus国际化引入问题 &nbsp;-&nbsp; by **Soybean** [<samp>(aa16d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/aa16dc65)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(1e393)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1e393eb9)
  - 依赖升级 &nbsp;-&nbsp; by **Soybean** [<samp>(97820)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/97820a4e)
  - 依赖升级 &nbsp;-&nbsp; by **Soybean** [<samp>(78a28)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/78a28a45)
  - 依赖升级 &nbsp;-&nbsp; by **Soybean** [<samp>(6b7f4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6b7f4cfc)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(50c1d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/50c1d51e)
  - 更新依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(ffe50)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ffe50143)
  - 更新依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(d2464)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d246450d)
  - 更新依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(0fb01)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0fb011f6)
  - 更新依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(e59b8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e59b85a8)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(9c7bd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9c7bdb67)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(4e1a0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4e1a09c7)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(6de48)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6de48ad9)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(4e04a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4e04a8f8)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(c8122)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c81221ef)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(a6bdc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a6bdc380)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(ae7ec)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ae7ec99a)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(e755c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e755caab)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(f3c86)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f3c86efb)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(e776d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e776df49)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(777cf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/777cf8e0)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(284af)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/284af63c)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(57c69)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/57c692be)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(7ba33)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7ba332cd)
  - upgrade deps &nbsp;-&nbsp; by **Soybean** [<samp>(50c8b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/50c8b9da)
  - upgrade deps &nbsp;-&nbsp; by **Soybean** [<samp>(8d00b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8d00b238)
  - upgrade deps &nbsp;-&nbsp; by **Soybean** [<samp>(b298a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b298af1d)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(cecce)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cecce83b)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(5c75e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5c75e9d9)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(518f7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/518f7eed)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(92b84)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/92b84064)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(50d7c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/50d7ccd8)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(3f822)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3f822a7d)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(02809)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/028096e5)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(be45d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/be45d837)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(6a5a3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6a5a357f)
  - 依赖升级 &nbsp;-&nbsp; by **Soybean** [<samp>(e3c4a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e3c4a6ec)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(906ae)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/906aed5e)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(9917b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9917b5e5)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(83301)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/833018a8)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(69e39)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/69e39c14)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(ea1a3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ea1a3365)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(73fa3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/73fa3d14)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(973ab)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/973ab144)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(75000)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/750000ec)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(8dcfb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8dcfbb29)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(1523c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1523c7b0)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(da407)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/da407b66)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(cec0f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cec0f25c)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(d9cfe)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d9cfeabb)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(dd113)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/dd113248)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(d0823)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d0823b03)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(94ff7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/94ff7870)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(b32bc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b32bca49)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(f6b61)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f6b61418)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(0f0cd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0f0cd0b7)
  - 更新@soybeanjs/eslint-config &nbsp;-&nbsp; by **Soybean** [<samp>(36f06)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/36f06bc8)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(d9324)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d9324f07)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(1ad92)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1ad92a2d)
  - 升级依赖 &nbsp;-&nbsp; by **Soybean** [<samp>(7240b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7240be84)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(c5ba6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c5ba6318)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(3e0cc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3e0cc8c2)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(21b6f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/21b6fb69)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(d823e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d823ee56)
  - unplugin-vue-define-options替换为unplugin-vue-macros &nbsp;-&nbsp; by **Soybean** [<samp>(22c90)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/22c90257)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(7dd7c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7dd7c71d)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(fe8ca)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fe8cab3d)
  - unplugin-icon autoinstall @iconify-json [unplugin-icon自动安装@iconify-json] &nbsp;-&nbsp; by **Soybean** [<samp>(c045e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c045e3fe)
  - update deps [升级依赖] &nbsp;-&nbsp; by **Soybean** [<samp>(331b1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/331b14e7)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(88e53)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/88e535f6)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(89985)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8998581b)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(65ac6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/65ac69ef)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(abd02)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/abd02d19)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(d6b15)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d6b15307)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(8e801)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8e801dd7)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(41b3b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/41b3bcb4)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(1f3e6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1f3e6e4f)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(74772)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/74772a1f)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(84567)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/84567509)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(fcc65)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fcc65c37)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(c097b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c097b568)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(61998)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/61998886)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(db629)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/db629593)
  - update deps [升级依赖] &nbsp;-&nbsp; by **Soybean** [<samp>(f2e82)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f2e82da7)
  - update deps and remove vite-plugin-html [升级依赖，去除vite-plugin-html] &nbsp;-&nbsp; by **Soybean** [<samp>(eaf36)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/eaf36787)
  - update deps [升级依赖] &nbsp;-&nbsp; by **Soybean** [<samp>(bae17)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bae17671)
  - update deps [升级依赖] &nbsp;-&nbsp; by **Soybean** [<samp>(c2642)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c2642160)
  - update deps [升级依赖] &nbsp;-&nbsp; by **Soybean** [<samp>(40f85)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/40f8587f)
  - Restrict the minimum Node.js version. &nbsp;-&nbsp; by **一寸灰** in https://github.com/faiz-Liu/soybean-admin/issues/720 [<samp>(a6ecd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a6ecd3e0)
- **other**:
  - update cz config &nbsp;-&nbsp; by **Soybean** [<samp>(07baa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/07baac7c)
- **projects**:
  - 依赖升级，规范目录 &nbsp;-&nbsp; by **Soybean** [<samp>(a0ec8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a0ec8458)
  - 依赖升级 &nbsp;-&nbsp; by **Soybean** [<samp>(025a9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/025a9bea)
  - 依赖升级 &nbsp;-&nbsp; by **Soybean** [<samp>(09a28)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/09a28d8e)
  - pnpm替换yarn &nbsp;-&nbsp; by **Soybean** [<samp>(36491)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/36491310)
  - 依赖升级 &nbsp;-&nbsp; by **Soybean** [<samp>(f1649)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f1649de6)
  - 依赖升级 &nbsp;-&nbsp; by **Soybean** [<samp>(d00bb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d00bb228)
  - 主题配置完善 &nbsp;-&nbsp; by **Soybean** [<samp>(20503)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/20503739)
  - 添加构建打包的不同环境配置 &nbsp;-&nbsp; by **Soybean** [<samp>(ef57d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ef57d9e6)
  - 更新README.md &nbsp;-&nbsp; by **Soybean** [<samp>(f2ad7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f2ad76df)
  - 项目名称变更，添加README内容：项目基本介绍 &nbsp;-&nbsp; by **Soybean** [<samp>(638a8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/638a8e98)
  - 添加vscode插件推荐配置和设置配置 &nbsp;-&nbsp; by **Soybean** [<samp>(b9395)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b9395221)
  - 取消打包显示brotliSize &nbsp;-&nbsp; by **Soybean** [<samp>(9af89)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9af89885)
  - 添加构建大小可视化分析的插件 &nbsp;-&nbsp; by **Soybean** [<samp>(8ba8a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8ba8a4fe)
  - vite配置更新 &nbsp;-&nbsp; by **Soybean** [<samp>(e5d99)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e5d9962a)
  - 环境变量获取方式变更 &nbsp;-&nbsp; by **Soybean** [<samp>(21c2f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/21c2f5a8)
  - 修改vscode配置 &nbsp;-&nbsp; by **Soybean** [<samp>(0c577)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0c5770df)
  - 添加vercel打包的环境 &nbsp;-&nbsp; by **Soybean** [<samp>(371fa)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/371fad4f)
  - add license &nbsp;-&nbsp; by **Soybean** [<samp>(b1672)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b16721b2)
  - 更新tsconfig.json &nbsp;-&nbsp; by **Soybean** [<samp>(f42ee)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f42ee9db)
  - update tsconfig、eslintrc &nbsp;-&nbsp; by **Soybean** [<samp>(75de2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/75de2b06)
  - vite.config代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(ca707)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ca707a45)
  - 细节调整 &nbsp;-&nbsp; by **Soybean** [<samp>(401f0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/401f0c74)
  - update config &nbsp;-&nbsp; by **Soybean** [<samp>(a0c40)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a0c405da)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(de09f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/de09f825)
  - 配置优化 &nbsp;-&nbsp; by **Soybean** [<samp>(fd787)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fd787912)
  - 配置更改 &nbsp;-&nbsp; by **Soybean** [<samp>(c8717)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c8717c25)
  - update deps, update config &nbsp;-&nbsp; by **Soybean** [<samp>(8e6e7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8e6e7875)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(5c1b0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5c1b086c)
  - update tsconfig &nbsp;-&nbsp; by **Soybean** [<samp>(9ce58)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9ce58073)
  - update vscode settings &nbsp;-&nbsp; by **Soybean** [<samp>(3fe4e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3fe4e92f)
  - 添加.gitattributes &nbsp;-&nbsp; by **Soybean** [<samp>(896e6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/896e6f2e)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(6a9a3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6a9a362c)
  - 升级依赖，添加对json的eslint检测及格式化 &nbsp;-&nbsp; by **Soybean** [<samp>(711a4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/711a4ae3)
  - update deps and README.md &nbsp;-&nbsp; by **Soybean** [<samp>(35aee)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/35aeedf3)
  - 升级依赖、vite配置optimizeDeps &nbsp;-&nbsp; by **Soybean** [<samp>(ee434)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ee434b46)
  - 去除prettier，已集成进@soybeanjs/eslint-config &nbsp;-&nbsp; by **Soybean** [<samp>(182da)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/182dac0d)
  - update eslint &nbsp;-&nbsp; by **Soybean** [<samp>(907cf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/907cf44c)
  - 引入pwa插件，更新配置 &nbsp;-&nbsp; by **Soybean** [<samp>(695ec)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/695ec7e5)
  - 更新依赖、调整页面 &nbsp;-&nbsp; by **Soybean** [<samp>(40ecc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/40ecc320)
  - 引入vite-plugin-progress &nbsp;-&nbsp; by **Soybean** [<samp>(44ab0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/44ab0777)
  - 升级依赖、修复T标签右键菜单连续显示问题 &nbsp;-&nbsp; by **Soybean** [<samp>(639c4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/639c4458)
  - 引入TS高级类型库 &nbsp;-&nbsp; by **Soybean** [<samp>(71a75)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/71a753f3)
  - 更换eslint依赖为eslint-config-soybeanjs-vue &nbsp;-&nbsp; by **Soybean** [<samp>(07325)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/07325a42)
  - 升级依赖，降低naive-ui版本修复打包问题 &nbsp;-&nbsp; by **Soybean** [<samp>(f408e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f408ea01)
  - 升级依赖，修复TS类型 &nbsp;-&nbsp; by **Soybean** [<samp>(73ce5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/73ce53a3)
  - 引入@unocss/vite替换unocss，精简体积 &nbsp;-&nbsp; by **Soybean** [<samp>(3540b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3540b755)
  - update deps, update logos &nbsp;-&nbsp; by **Soybean** [<samp>(22c05)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/22c05674)
  - add constant page content &nbsp;-&nbsp; by **Soybean** [<samp>(13d0c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/13d0c415)
  - add tauri scripts, change tauri icon, fix mockjs [添加tauri相关的命令，变更tauri图标，修复mockjs] &nbsp;-&nbsp; by **Soybean** [<samp>(1b45b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1b45b71f)
  - use @soybeanjs/cli replace commitizen &nbsp;-&nbsp; by **Soybean** [<samp>(428d4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/428d41b4)
  - use pnpm patch replace @milahu/patch-package &nbsp;-&nbsp; by **Soybean** [<samp>(9455a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9455ad9a)
  - remove useless file: commitlint.config.js &nbsp;-&nbsp; by **Soybean** [<samp>(67736)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6773659e)
  - move tauri to branch tauri &nbsp;-&nbsp; by **Soybean** [<samp>(6c14b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6c14bfe6)
  - update deps and update config &nbsp;-&nbsp; by **Soybean** [<samp>(7d699)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7d699926)
  - new router branch &nbsp;-&nbsp; by **Soybean** [<samp>(288d5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/288d586d)
  - add vite plugin @soybeanjs/router-page &nbsp;-&nbsp; by **Soybean** [<samp>(40c1e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/40c1e13b)
  - update plugin config &nbsp;-&nbsp; by **Soybean** [<samp>(6a344)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6a344ff2)
  - update deps and perfect the details [升级依赖，完善细节] &nbsp;-&nbsp; by **Soybean** [<samp>(61a43)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/61a43b8e)
  - update deps and update config &nbsp;-&nbsp; by **Soybean** [<samp>(b08c3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b08c389e)
  - update lint-staged config &nbsp;-&nbsp; by **Soybean** [<samp>(0882c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0882c250)
  - add VSCode debug config file &nbsp;-&nbsp; by **Soybean** [<samp>(0c126)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0c12665f)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(f7181)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f71812d6)
  - update deps and fix project config &nbsp;-&nbsp; by **Soybean** [<samp>(da521)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/da521b35)
  - perf logo &nbsp;-&nbsp; by **Soybean** [<samp>(a8a6e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a8a6ed97)
  - update vscode config &nbsp;-&nbsp; by **Soybean** [<samp>(608d7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/608d7fb3)
  - update unocss config &nbsp;-&nbsp; by **Soybean** [<samp>(3503d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3503dff6)
  - update deps, add prettier format command &nbsp;-&nbsp; by **Soybean** [<samp>(36e5f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/36e5feac)
  - remove old layout,tab package [去除旧的布局和页签依赖] &nbsp;-&nbsp; by **Soybean** [<samp>(42e6d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/42e6de39)
  - update deps and fix type error [升级依赖并修复类型问题] &nbsp;-&nbsp; by **Soybean** [<samp>(34f02)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/34f023c4)
  - update deps and fix style [升级依赖&修复代码格式] &nbsp;-&nbsp; by **Soybean** [<samp>(c1c43)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c1c4335c)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- rename env.d.ts to vite-env.d.ts &nbsp;-&nbsp; by @wzc520pyfm in https://github.com/faiz-Liu/soybean-admin/issues/675 [<samp>(b93c2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b93c2036)
- **deps**:
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(4eb46)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4eb46ea3)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(a70e4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a70e4161)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(7487a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7487ab79)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(cebbe)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cebbef68)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(f9d47)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f9d47c08)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(47ab0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/47ab0184)
  - decrease vite-plugin-page-route &nbsp;-&nbsp; by **Soybean** [<samp>(882f2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/882f2814)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(e6abf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e6abf934)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(bba68)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bba68bff)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(0e6d2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0e6d2891)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(135ce)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/135ce772)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(44ba3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/44ba3273)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(9296e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9296e698)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(751de)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/751ded44)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(305d9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/305d9567)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(3eaf0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3eaf05bd)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(36fe1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/36fe1dad)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(55342)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/55342941)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(f1b86)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f1b86ccb)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(840e7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/840e7f99)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(6114b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6114b9f9)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(9cc7e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9cc7ee5c)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(9c4ba)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9c4ba665)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(fb3b9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fb3b94b1)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(14aa8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/14aa856a)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(02d4b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/02d4b0a5)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(b2ee9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b2ee9eef)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(0fee1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0fee104b)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(c0a65)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c0a65a16)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(6b513)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6b5132c1)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(82b53)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/82b53d7e)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(a1b48)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a1b484a8)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(ac928)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ac928173)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(3ceeb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3ceeb6f9)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(9a669)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9a66979f)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(e57bf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e57bf0b0)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(fbd80)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fbd80c28)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(1cb38)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1cb3816e)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(413a8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/413a8b29)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(734ef)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/734ef985)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(599b4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/599b4e19)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(d0380)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d0380ce5)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(1f464)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1f4647b9)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(060c0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/060c0a91)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(08827)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/08827a42)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(813d8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/813d8ce4)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(bf718)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/bf718374)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(b094d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b094d688)
  - update deps. close #510 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/510 [<samp>(53143)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/531432d5)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(c7f6f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c7f6f2a5)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(72ede)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/72ede8bf)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(be13c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/be13ca27)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(752ec)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/752ec1e9)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(cf019)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cf0192ad)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(f6bd6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f6bd6b86)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(993e9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/993e9caf)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(a1c14)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a1c14a15)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(7fa55)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7fa55905)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(a44ea)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a44ea624)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(207d6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/207d6eb6)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(f3562)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f35627e1)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(baefd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/baefdfd8)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(8dcda)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8dcda385)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(91de4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/91de4a8e)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(0c809)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0c809de6)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(c9433)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c9433e17)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(132e1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/132e1012)
  - update deps &nbsp;-&nbsp; by **Azir** [<samp>(52c33)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/52c336d7)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(b8112)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b8112613)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(5d8b7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5d8b782d)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(2e8cb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2e8cb35c)
  - add vscode recommend plugin  close #738 &nbsp;-&nbsp; by @tu6ge in https://github.com/faiz-Liu/soybean-admin/issues/739 and https://github.com/faiz-Liu/soybean-admin/issues/738 [<samp>(61244)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/61244f0f)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(41b5f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/41b5f493)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(3e4e1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3e4e17ab)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(dc674)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/dc674ce8)
  - update NodeJS and pnpm version requirements in package.json and documentation &nbsp;-&nbsp; by **Junior25306** [<samp>(a5c4b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a5c4b4e3)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(5cb1c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5cb1cebd)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(aeb63)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/aeb63690)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(e89b8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e89b86ce)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(e33f9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e33f944a)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(9fa95)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9fa951aa)
- **other**:
  - correct spell mistake &nbsp;-&nbsp; by @orangelckc in https://github.com/faiz-Liu/soybean-admin/issues/460 [<samp>(086ba)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/086bad47)
  - correct spell mistake &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/462 [<samp>(f1850)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f1850416)
  - update the ESLint validation configuration to support more file types. &nbsp;-&nbsp; by **Azir-11** [<samp>(8d7f9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8d7f91dc)
- **packages**:
  - update Vite version to 7 in package.json and documentation. &nbsp;-&nbsp; by **Azir** [<samp>(03dd6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/03dd64c5)
- **project**:
  - delete src/locales/lang/zh-CN.ts &nbsp;-&nbsp; by @soybeanjs [<samp>(377db)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/377db829)
- **projects**:
  - 更新.cz-config &nbsp;-&nbsp; by **Soybean** [<samp>(b18c4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b18c49e9)
  - 更新eslint配置 &nbsp;-&nbsp; by **Soybean** [<samp>(872bb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/872bb845)
  - add github action &nbsp;-&nbsp; by **lixin** [<samp>(f355a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/f355a698)
  - 修复issue模板格式问题 &nbsp;-&nbsp; by **lixin59** [<samp>(d8bab)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d8baba58)
  - remove useless packages, update lint-staged config, add githublogen &nbsp;-&nbsp; by **Soybean** [<samp>(5aaa3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5aaa3181)
  - add switch for pageRoute plugin [添加自动生成路由的插件的开关] &nbsp;-&nbsp; by **Soybean** [<samp>(780ac)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/780ac75b)
  - update deps and use soy lint-staged replace lint-staged &nbsp;-&nbsp; by **Soybean** [<samp>(9a238)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9a238174)
  - remove bumpp & add release script &nbsp;-&nbsp; by **Soybean** [<samp>(a3dfe)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a3dfe61a)
  - update @soybeanjs/cli and generate total changelog &nbsp;-&nbsp; by **Soybean** [<samp>(58591)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/58591f66)
  - update deps & update unocss deprecated api exclude &nbsp;-&nbsp; by **Soybean** [<samp>(0907d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0907d38c)
  - update deps & update package.json &nbsp;-&nbsp; by **Soybean** [<samp>(0b2f6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0b2f68ac)
  - add vite-plugin-vue-devtools &nbsp;-&nbsp; by **Soybean** [<samp>(c1bee)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c1bee404)
  - update deps and fix swiper &nbsp;-&nbsp; by @soybeanjs [<samp>(9d105)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9d1051b0)
  - update package.json &nbsp;-&nbsp; by @soybeanjs [<samp>(d7aea)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d7aea9d1)
  - update deps & fix eslint code &nbsp;-&nbsp; by @soybeanjs [<samp>(08e0c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/08e0cf5a)
  - update pnpm-lock.yaml &nbsp;-&nbsp; by @soybeanjs [<samp>(94644)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/94644739)
  - update VSCode setting &nbsp;-&nbsp; by @soybeanjs [<samp>(56c77)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/56c770c4)
  - correct the word spell &nbsp;-&nbsp; by @soybeanjs [<samp>(458e3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/458e387b)
  - correct word spell & eslint fix code &nbsp;-&nbsp; by @soybeanjs [<samp>(cffc3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cffc30af)
  - When tab is switched, keep the page without refreshing &nbsp;-&nbsp; by **linjiangl** [<samp>(83f25)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/83f25144)
  - use eslint flat config & update config &nbsp;-&nbsp; by @soybeanjs [<samp>(a176d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a176dc44)
  - update @sa/scripts &nbsp;-&nbsp; by @soybeanjs [<samp>(d7785)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d778560d)
  - update pnpm version &nbsp;-&nbsp; by @soybeanjs [<samp>(55f76)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/55f76385)
  - update eslint config &nbsp;-&nbsp; by @soybeanjs [<samp>(5023f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5023f371)
  - lock deps versions &nbsp;-&nbsp; by @soybeanjs [<samp>(a24f9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a24f9631)
  - update pnpm version &nbsp;-&nbsp; by @soybeanjs [<samp>(ea02b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ea02b237)
  - remove @simonwep/pickr &nbsp;-&nbsp; by @soybeanjs [<samp>(502a4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/502a4d2b)
  - remove soybean.svg &nbsp;-&nbsp; by @soybeanjs [<samp>(4031f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4031fafc)
  - update pnpm version &nbsp;-&nbsp; by @soybeanjs [<samp>(adec0)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/adec0d75)
  - update deps & fix keep-alive &nbsp;-&nbsp; by @soybeanjs [<samp>(13001)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/13001bc8)
  - update @elegant-router/vue, fix inject name in windows &nbsp;-&nbsp; by @soybeanjs [<samp>(0b56e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0b56e44c)
  - add dev and build command with service env &nbsp;-&nbsp; by @soybeanjs [<samp>(ebb15)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ebb15484)
  - update deps & remove packages docs &nbsp;-&nbsp; by @soybeanjs [<samp>(57963)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/579636b0)
  - update pnpm-lock.yaml &nbsp;-&nbsp; by @soybeanjs [<samp>(147f6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/147f60d1)
  - update repository url &nbsp;-&nbsp; by @soybeanjs [<samp>(806a1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/806a1cba)
  - update deps & update pnpm version &nbsp;-&nbsp; by @soybeanjs [<samp>(9772a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9772aec2)
  - add unocss eslint config &nbsp;-&nbsp; by @soybeanjs [<samp>(40635)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4063529a)
  - update launch.json &nbsp;-&nbsp; by @soybeanjs [<samp>(3db82)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3db82acb)
  - update vscode extensions.json &nbsp;-&nbsp; by @soybeanjs [<samp>(4e29a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4e29acaa)
  - update pnpm version &nbsp;-&nbsp; by @soybeanjs [<samp>(7065f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7065f6f0)
  - update deps & fix eslint vue rule &nbsp;-&nbsp; by @soybeanjs [<samp>(8143b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8143b006)
  - update pnpm version &nbsp;-&nbsp; by @soybeanjs [<samp>(6ad51)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6ad51e94)
  - add .gitattributes &nbsp;-&nbsp; by @soybeanjs [<samp>(c0009)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c0009203)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(4babb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4babbe19)
  - update pnpm version &nbsp;-&nbsp; by @soybeanjs [<samp>(9125c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/9125cc9b)
  - disabled unocss eslint rule: order-attributify &nbsp;-&nbsp; by @soybeanjs [<samp>(1c72d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1c72dc76)
  - update pnpm version &nbsp;-&nbsp; by @soybeanjs [<samp>(42e16)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/42e16a01)
  - update deps & update pnpm version & update eslint config &nbsp;-&nbsp; by @soybeanjs [<samp>(7392b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7392bebf)
  - lower vue version to 3.4.23 &nbsp;-&nbsp; by @soybeanjs [<samp>(b5243)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b52432a7)
  - update pnpm-lock.yaml &nbsp;-&nbsp; by @soybeanjs [<samp>(516f4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/516f46a4)
  - use `engines` replace `packageManager` &nbsp;-&nbsp; by @soybeanjs [<samp>(dcd51)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/dcd51f4c)
  - update pnpm version requirement &nbsp;-&nbsp; by @soybeanjs [<samp>(19e65)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/19e65c1a)
  - update .npmrc &nbsp;-&nbsp; by @soybeanjs [<samp>(52188)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/52188d88)
  - update vscode settings &nbsp;-&nbsp; by @soybeanjs [<samp>(c137b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c137b970)
  - merge main to v1.1.0 &nbsp;-&nbsp; by @soybeanjs [<samp>(ebe55)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ebe55af7)
  - update deps & fix TS error &nbsp;-&nbsp; by @soybeanjs [<samp>(4ea9c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4ea9c857)
  - update eslint-config & fix code &nbsp;-&nbsp; by @soybeanjs [<samp>(68ea9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/68ea9746)
  - update @elegant-router/vue & add error handle for resolve route. fixed #442 &nbsp;-&nbsp; by @soybeanjs in https://github.com/faiz-Liu/soybean-admin/issues/442 [<samp>(24ff8)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/24ff8521)
  - update vscode launch.json &nbsp;-&nbsp; by @soybeanjs [<samp>(4c1c7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4c1c7e65)
  - close http proxy &nbsp;-&nbsp; by @soybeanjs [<samp>(d08a3)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d08a3817)
  - update mock url &nbsp;-&nbsp; by @soybeanjs [<samp>(e6086)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e6086f0f)
  - update vscode settings &nbsp;-&nbsp; by @soybeanjs [<samp>(910df)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/910dfca8)
  - update vscode settings: vue official &nbsp;-&nbsp; by @soybeanjs [<samp>(76649)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/76649e2a)
  - Fix deprecated configuration config &nbsp;-&nbsp; by @paynezhuang in https://github.com/faiz-Liu/soybean-admin/issues/524 [<samp>(0d20e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0d20e4c9)
  - add script `czh` &nbsp;-&nbsp; by @soybeanjs [<samp>(02069)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0206969e)
  - update deps & fix vue-router type &nbsp;-&nbsp; by @soybeanjs [<samp>(96837)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/968370b1)
  - use json5 resolve env `VITE_OTHER_SERVICE_BASE_URL` & fix proxy enable &nbsp;-&nbsp; by @soybeanjs [<samp>(b16a9)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b16a9632)
  - update vscode extensions &nbsp;-&nbsp; by @soybeanjs [<samp>(24bb6)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/24bb6d95)
  - update deps & fix sass usage &nbsp;-&nbsp; by @soybeanjs [<samp>(71e63)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/71e6307d)
  - add desc for base url of app &nbsp;-&nbsp; by @soybeanjs [<samp>(17d7e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/17d7e522)
  - update deps & fix vite config &nbsp;-&nbsp; by @soybeanjs [<samp>(3e0eb)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3e0eb720)
  - update unocss preset &nbsp;-&nbsp; by @Wangijun in https://github.com/faiz-Liu/soybean-admin/issues/712 [<samp>(3e007)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/3e0076d4)
  - update vscode settings and launch &nbsp;-&nbsp; by @soybeanjs [<samp>(8b12e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8b12ef9f)
  - update deps & fix `moduleResolution` &nbsp;-&nbsp; by @soybeanjs [<samp>(dbd99)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/dbd995c1)
- **readme**:
  - remove DartNode sponsorship badge from README files &nbsp;-&nbsp; by @soybeanjs [<samp>(33ade)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/33ade539)
- **release**:
  - 0.0.2 &nbsp;-&nbsp; by **Soybean** [<samp>(e44f5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e44f5d72)
  - 0.0.3 &nbsp;-&nbsp; by **Soybean** [<samp>(e1dac)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e1dacdbc)
  - 0.0.4 &nbsp;-&nbsp; by **Soybean** [<samp>(8b27f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/8b27fc8b)
  - 0.0.5 &nbsp;-&nbsp; by **Soybean** [<samp>(e53e7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e53e7936)
  - 0.1.1 精简版发布 &nbsp;-&nbsp; by **Soybean** [<samp>(db3c2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/db3c25ea)
  - 0.1.2 &nbsp;-&nbsp; by **Soybean** [<samp>(db75c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/db75c914)
  - 0.1.3 &nbsp;-&nbsp; by **Soybean** [<samp>(32a7c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/32a7cc40)
  - 0.9.1 &nbsp;-&nbsp; by **Soybean** [<samp>(be374)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/be374089)
  - 0.9.2 &nbsp;-&nbsp; by **Soybean** [<samp>(11407)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/11407227)
  - 0.9.3 &nbsp;-&nbsp; by **Soybean** [<samp>(d0522)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d0522ce5)
  - 0.9.4 &nbsp;-&nbsp; by **Soybean** [<samp>(97c92)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/97c92626)
  - 0.9.5 &nbsp;-&nbsp; by **Soybean** [<samp>(08d83)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/08d83ecb)
  - 0.9.6 &nbsp;-&nbsp; by **Soybean** [<samp>(65c21)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/65c21812)
  - 0.9.8 &nbsp;-&nbsp; by **Soybean** [<samp>(34ffd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/34ffd9c1)
  - 0.9.9 &nbsp;-&nbsp; by **Soybean** [<samp>(c0066)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c0066b22)
- **types**:
  - remove type declaration for document.startViewTransition (TypeScript 5.6 includes it) &nbsp;-&nbsp; by @NHZEX in https://github.com/faiz-Liu/soybean-admin/issues/633 [<samp>(83ba7)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/83ba7987)
- **vscode**:
  - remove unused vue.server.hybridMode setting from .vscode/settings.json &nbsp;-&nbsp; by @soybeanjs [<samp>(13319)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/133196f3)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **GlobalBreadcrumb**:
  - 代码格式fix &nbsp;-&nbsp; by **Eric_Yuan** [<samp>(0243b)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/0243b275)
- **components**:
  - 格式规范 &nbsp;-&nbsp; by **Soybean** [<samp>(d8d3c)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d8d3cc23)
  - 代码优化 &nbsp;-&nbsp; by **Soybean** [<samp>(1e2fd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/1e2fdda0)
  - Uniform icon size for header &nbsp;-&nbsp; by @Azir-11 [<samp>(b37c1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b37c1e94)
- **other**:
  - modify the Chinese name of the grayscale mode &nbsp;-&nbsp; by **Azir** [<samp>(53770)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/53770029)
- **projects**:
  - 格式化代码 &nbsp;-&nbsp; by **Soybean** [<samp>(d680e)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/d680e7d9)
  - 代码格式化 &nbsp;-&nbsp; by **Soybean** [<samp>(2bc50)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/2bc50009)
  - 路由相关文件夹简化 &nbsp;-&nbsp; by **Soybean** [<samp>(e5793)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/e5793e1c)
  - update prettier config &nbsp;-&nbsp; by **Soybean** [<samp>(df56a)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/df56abe1)
  - format yaml &nbsp;-&nbsp; by **Soybean** [<samp>(fb46d)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/fb46d7ec)
  - per style [完善样式] &nbsp;-&nbsp; by **Soybean** [<samp>(209ef)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/209ef3d8)
  - unify card border radius, 16px to 8px &nbsp;-&nbsp; by **Soybean** [<samp>(cbda4)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/cbda4a38)
  - update default theme color &nbsp;-&nbsp; by @soybeanjs [<samp>(43ac2)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/43ac23f1)
  - prettier format code &nbsp;-&nbsp; by @soybeanjs [<samp>(24cf1)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/24cf1d92)
  - format code &nbsp;-&nbsp; by @soybeanjs [<samp>(a7481)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/a7481663)
  - update theme mode segment height &nbsp;-&nbsp; by @soybeanjs [<samp>(4d846)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4d8469e2)
  - fix tooltip zIndex of ButtonIcon &nbsp;-&nbsp; by @soybeanjs [<samp>(db747)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/db747c4a)
  - sort defineProps, defineEmits with TS type &nbsp;-&nbsp; by @soybeanjs [<samp>(123fd)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/123fd4f9)
  - rename script czh to commit:zh &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/597 [<samp>(5094f)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/5094f0ee)
  - reduce ambiguity in theme configuration instructions. &nbsp;-&nbsp; by @Azir-11 [<samp>(75cbf)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/75cbfbbf)

### &nbsp;&nbsp;&nbsp;🤖 CI

- add docker build &nbsp;-&nbsp; by **徐志强** [<samp>(af740)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/af740461)
- change docker image name &nbsp;-&nbsp; by **徐志强** [<samp>(6fbde)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/6fbde1eb)
- **hooks**:
  - remove lint-staged in git hook.  close #724 &nbsp;-&nbsp; by @Azir-11 in https://github.com/faiz-Liu/soybean-admin/issues/743 and https://github.com/faiz-Liu/soybean-admin/issues/724 [<samp>(c3abc)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/c3abc3df)
- **projects**:
  - add github actions config &nbsp;-&nbsp; by @soybeanjs [<samp>(4cb17)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/4cb17c74)
  - update release.yml &nbsp;-&nbsp; by @soybeanjs [<samp>(7b298)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/7b298c67)
  - add issue template &nbsp;-&nbsp; by @soybeanjs [<samp>(06e20)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/06e204a7)
  - add github issues template &nbsp;-&nbsp; by @soybeanjs [<samp>(b5027)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/b5027c8f)
  - update github issues template &nbsp;-&nbsp; by @soybeanjs [<samp>(ff1d5)</samp>](https://github.com/faiz-Liu/soybean-admin/commit/ff1d5046)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![xiaobao0505](https://github.com/xiaobao0505.png?size=48)](https://github.com/xiaobao0505)&nbsp;&nbsp;[![wenyuanw](https://github.com/wenyuanw.png?size=48)](https://github.com/wenyuanw)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;[![WgoW](https://github.com/WgoW.png?size=48)](https://github.com/WgoW)&nbsp;&nbsp;[![testbrate](https://github.com/testbrate.png?size=48)](https://github.com/testbrate)&nbsp;&nbsp;[![tu6ge](https://github.com/tu6ge.png?size=48)](https://github.com/tu6ge)&nbsp;&nbsp;[![xiatianYa](https://github.com/xiatianYa.png?size=48)](https://github.com/xiatianYa)&nbsp;&nbsp;[![me-o](https://github.com/me-o.png?size=48)](https://github.com/me-o)&nbsp;&nbsp;[![Wangijun](https://github.com/Wangijun.png?size=48)](https://github.com/Wangijun)&nbsp;&nbsp;[![zsdycs](https://github.com/zsdycs.png?size=48)](https://github.com/zsdycs)&nbsp;&nbsp;[![wzc520pyfm](https://github.com/wzc520pyfm.png?size=48)](https://github.com/wzc520pyfm)&nbsp;&nbsp;[![JOU-amjs](https://github.com/JOU-amjs.png?size=48)](https://github.com/JOU-amjs)&nbsp;&nbsp;[![NHZEX](https://github.com/NHZEX.png?size=48)](https://github.com/NHZEX)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;[![PZ-18664918826](https://github.com/PZ-18664918826.png?size=48)](https://github.com/PZ-18664918826)&nbsp;&nbsp;[![paynezhuang](https://github.com/paynezhuang.png?size=48)](https://github.com/paynezhuang)&nbsp;&nbsp;[![mmdapl](https://github.com/mmdapl.png?size=48)](https://github.com/mmdapl)&nbsp;&nbsp;[![wynn-w](https://github.com/wynn-w.png?size=48)](https://github.com/wynn-w)&nbsp;&nbsp;[![KickCashew](https://github.com/KickCashew.png?size=48)](https://github.com/KickCashew)&nbsp;&nbsp;[![sigma-plus](https://github.com/sigma-plus.png?size=48)](https://github.com/sigma-plus)&nbsp;&nbsp;[![m-xlsea](https://github.com/m-xlsea.png?size=48)](https://github.com/m-xlsea)&nbsp;&nbsp;[![orangelckc](https://github.com/orangelckc.png?size=48)](https://github.com/orangelckc)&nbsp;&nbsp;
[Azir-11](mailto:2075125282@qq.com),&nbsp;[Junior25306](mailto:dayu429@qq.com),&nbsp;[chenziwen](mailto:chenziwen@qesong.com),&nbsp;[t8y2](mailto:1156263951@qq.com),&nbsp;[一寸灰](mailto:webzhangfei@163.com),&nbsp;[Ohh](mailto:155351881+mufeng889@users.noreply.github.com),&nbsp;[dodu2014](mailto:dodu@live.cn),&nbsp;[CHENZL](mailto:zlong5568863@qq.com),&nbsp;[JianJroh](mailto:rhjian@foxmail.com),&nbsp;[alleycharming](mailto:alleycharming@gmail.com),&nbsp;[燕博文](mailto:349952469@qq.com),&nbsp;[~li](mailto:miciili-02@outlook.com),&nbsp;[smileluck](mailto:12386904+smileluck@users.noreply.github.com),&nbsp;[Kori](mailto:kexin@korix.top),&nbsp;[pantao](mailto:980141374@qq.com),&nbsp;[Ikko Eltociear Ashimine](mailto:eltociear@gmail.com),&nbsp;[linjiangl](mailto:8257796@qq.com),&nbsp;[lapislazulisch](mailto:108389666+lapislazulisch@users.noreply.github.com),&nbsp;[muzzyh](mailto:1430750200@qq.com),&nbsp;[liwei](mailto:liwei@e-agency-china.com),&nbsp;[Soybean](mailto:honghuangdc@gmail.com),&nbsp;[cc](mailto:cc@qq.com),&nbsp;[xiaojunnuo](mailto:xiaojunnuo@qq.com),&nbsp;[Kirk Lin](mailto:linkirk@163.com),&nbsp;[small_happy](mailto:5304122+small_happy@user.noreply.gitee.com),&nbsp;[guuuuo](mailto:1460412+guuuuo@users.noreply.github.com),&nbsp;[lixin59](mailto:1453287107@qq.com),&nbsp;[alue_mobile](mailto:hi.alue@qq.com),&nbsp;[HuangZheng](mailto:huangzheng@shu.edu.cn),&nbsp;[sunhao1256](mailto:lssh731105702@qq.com),&nbsp;[shabby2333](mailto:1308933842@qq.com),&nbsp;[zuihou](mailto:244387066@qq.com),&nbsp;[Wang Zheng](mailto:wz@sdu.edu.cn),&nbsp;[RockerHX](mailto:rockerhx@gmail.com),&nbsp;[Henry.Huang](mailto:hhglory@outlook.com),&nbsp;[徐志强](mailto:zhiqiang.xu@dolphindb.com),&nbsp;[xiaotao2018](mailto:37537969+xiaotao2018@users.noreply.github.com),&nbsp;[Soybean](mailto:2570172956@qq.com),&nbsp;[tanminglin](mailto:846518677@qq.com),&nbsp;[Grazing Wind](mailto:dxxzst@gmail.com),&nbsp;[Eric_Yuan](mailto:330365043@qq.com),&nbsp;[元家怿](mailto:jiayi.yuan@lkcoffee.com),&nbsp;[相思](mailto:admin@toolv.cn),&nbsp;[元家怿](mailto:jiayi.yuan@luckincoffee.com),&nbsp;[“Southliu”](mailto:1275093225@qq.com),&nbsp;[Soybean](mailto:49704545+honghuangdc@users.noreply.github.com),&nbsp;[毛博文](mailto:maobowen@bonc.com.cn),&nbsp;[pany](mailto:939630029@qq.com),&nbsp;[bundle](mailto:bundle.js@gmail.com),&nbsp;[Lsq128](mailto:924500075@qq.com),&nbsp;[Liushengqun](mailto:18232366809@163.com),&nbsp;[liujunzheng](mailto:liujunzheng@weihaizixun.com),&nbsp;[lingdu](mailto:waong2005@126.com)

## [v1.3.15](https://github.com/soybeanjs/soybean-admin/compare/v1.3.14...v1.3.15) (2025-06-24)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**: add configurable user name watermark option &nbsp;-&nbsp; by @wenyuanw [<samp>(7c3da)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7c3dac42)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **app**: replace console.error with window.console.error for consistency &nbsp;-&nbsp; by @soybeanjs [<samp>(7d840)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7d84062e)
- **projects**: ensure proper text color when themes are inverted &nbsp;-&nbsp; by @wenyuanw [<samp>(afd60)</samp>](https://github.com/soybeanjs/soybean-admin/commit/afd60421)
- **types**: The environment variable VITE_ICON_LOCAL_PREFIX has the wrong type. &nbsp;-&nbsp; by **chenziwen** [<samp>(da149)</samp>](https://github.com/soybeanjs/soybean-admin/commit/da149e5b)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **components**: optimize spacing for lang-switch dropdown options &nbsp;-&nbsp; by @wenyuanw [<samp>(fcb89)</samp>](https://github.com/soybeanjs/soybean-admin/commit/fcb89883)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **iframe-page**: remove unused lifecycle hooks and clean up script setup &nbsp;-&nbsp; by @soybeanjs [<samp>(276d8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/276d836c)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **other**: update docs with video tutorial link. &nbsp;-&nbsp; by **Azir** [<samp>(7b2e5)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7b2e510a)
- **readme**: add warning about upcoming `V2` version and link to plan list &nbsp;-&nbsp; by @soybeanjs [<samp>(4d42d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4d42dcbe)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(dc674)</samp>](https://github.com/soybeanjs/soybean-admin/commit/dc674ce8)
- **projects**: update deps & fix `moduleResolution` &nbsp;-&nbsp; by @soybeanjs [<samp>(dbd99)</samp>](https://github.com/soybeanjs/soybean-admin/commit/dbd995c1)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![wenyuanw](https://github.com/wenyuanw.png?size=48)](https://github.com/wenyuanw)&nbsp;&nbsp;
[Azir](mailto:2075125282@qq.com),&nbsp;[chenziwen](mailto:chenziwen@qesong.com)

## [v1.3.14](https://github.com/soybeanjs/soybean-admin/compare/v1.3.13...v1.3.14) (2025-06-09)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **docs**:
  - add GitCode star badge to README files &nbsp;-&nbsp; by @soybeanjs [<samp>(05dc1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/05dc11e2)
  - add DartNode sponsorship badge to README files &nbsp;-&nbsp; by @soybeanjs [<samp>(2ed0b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2ed0b648)
- **projects**:
  - support vite devtools specify the editor by launchEditor option. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/730 [<samp>(29698)</samp>](https://github.com/soybeanjs/soybean-admin/commit/29698bef)
  - clear tabs cache when switching users. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/744 [<samp>(1ff4d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1ff4d82d)
- **theme**:
  - global search button toggle &nbsp;-&nbsp; by **t8y2** [<samp>(75455)</samp>](https://github.com/soybeanjs/soybean-admin/commit/75455b00)
- **types**:
  - enhance Option type to support customizable label types &nbsp;-&nbsp; by @WgoW and @testbrate in https://github.com/soybeanjs/soybean-admin/issues/735 [<samp>(123d2)</samp>](https://github.com/soybeanjs/soybean-admin/commit/123d2c90)
- **utils**:
  - support quick generation of code templates. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/733 [<samp>(8527a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8527aa80)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **auth**:
  - remove redundant authStore declaration in resetStore function &nbsp;-&nbsp; by @soybeanjs [<samp>(c57f8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c57f88aa)
- **hooks**:
  - fixed the issue where loading was not properly closed in some cases. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/737 [<samp>(85e40)</samp>](https://github.com/soybeanjs/soybean-admin/commit/85e40b19)
  - refactor useCountDown hook for improved countdown logic and clarity. &nbsp;-&nbsp; by **Azir** [<samp>(dfb64)</samp>](https://github.com/soybeanjs/soybean-admin/commit/dfb647a8)
- **projects**:
  - tab closure did not remove cache correctly. &nbsp;-&nbsp; by **Azir** [<samp>(7fb5c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7fb5c72f)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **hooks**:
  - remove obsolete disabling cache. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/729 [<samp>(4e1b6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4e1b65b6)
  - update detection function to cover the exceptions that occur when the request fails. &nbsp;-&nbsp; by **恕瑞玛的皇帝** [<samp>(22218)</samp>](https://github.com/soybeanjs/soybean-admin/commit/222187d3)
- **projects**:
  - optimize tab deletion logic. closed #755 &nbsp;-&nbsp; by @wenyuanw in https://github.com/soybeanjs/soybean-admin/issues/755 [<samp>(e6044)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e6044d0f)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **README**:
  - Add supporting ecosystem tools to the open-source repository &nbsp;-&nbsp; by @WgoW and @testbrate in https://github.com/soybeanjs/soybean-admin/issues/740 [<samp>(a013e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a013ea2c)
- **deps**:
  - update the Vite version of the project description. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/732 [<samp>(80486)</samp>](https://github.com/soybeanjs/soybean-admin/commit/80486099)
- **projects**:
  - update README &nbsp;-&nbsp; by @xiatianYa in https://github.com/soybeanjs/soybean-admin/issues/726 [<samp>(3cbaf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3cbaf4f4)
  - add gitcode link &nbsp;-&nbsp; by @soybeanjs [<samp>(f35c2)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f35c250a)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - add vscode recommend plugin  close #738 &nbsp;-&nbsp; by @tu6ge in https://github.com/soybeanjs/soybean-admin/issues/739 and https://github.com/soybeanjs/soybean-admin/issues/738 [<samp>(61244)</samp>](https://github.com/soybeanjs/soybean-admin/commit/61244f0f)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(41b5f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/41b5f493)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(3e4e1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3e4e17ab)

### &nbsp;&nbsp;&nbsp;🤖 CI

- **hooks**: remove lint-staged in git hook.  close #724 &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/743 and https://github.com/soybeanjs/soybean-admin/issues/724 [<samp>(c3abc)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c3abc3df)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![wenyuanw](https://github.com/wenyuanw.png?size=48)](https://github.com/wenyuanw)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;[![WgoW](https://github.com/WgoW.png?size=48)](https://github.com/WgoW)&nbsp;&nbsp;[![testbrate](https://github.com/testbrate.png?size=48)](https://github.com/testbrate)&nbsp;&nbsp;[![tu6ge](https://github.com/tu6ge.png?size=48)](https://github.com/tu6ge)&nbsp;&nbsp;[![xiatianYa](https://github.com/xiatianYa.png?size=48)](https://github.com/xiatianYa)&nbsp;&nbsp;
[恕瑞玛的皇帝](mailto:2075125282@qq.com),&nbsp;[t8y2](mailto:1156263951@qq.com),&nbsp;

## [v1.3.13](https://github.com/soybeanjs/soybean-admin/compare/v1.3.12...v1.3.13) (2025-03-19)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**: fix active tab switch issue after removal &nbsp;-&nbsp; by @me-o in https://github.com/soybeanjs/soybean-admin/issues/723 [<samp>(a7c59)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a7c59ada)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update README &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/718 [<samp>(3febb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3febb65d)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**: Restrict the minimum Node.js version. &nbsp;-&nbsp; by **一寸灰** in https://github.com/soybeanjs/soybean-admin/issues/720 [<samp>(a6ecd)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a6ecd3e0)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(5d8b7)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5d8b782d)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(2e8cb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2e8cb35c)
- **projects**:
  - update vscode settings and launch &nbsp;-&nbsp; by @soybeanjs [<samp>(8b12e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8b12ef9f)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![me-o](https://github.com/me-o.png?size=48)](https://github.com/me-o)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;
[一寸灰](mailto:webzhangfei@163.com),&nbsp;

## [v1.3.12](https://github.com/soybeanjs/soybean-admin/compare/v1.3.11...v1.3.12) (2025-03-12)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - support loading page dark mode adaptation. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/702 [<samp>(9b945)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9b9455d9)
  - tab support touch event &nbsp;-&nbsp; by @soybeanjs [<samp>(a03be)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a03becda)
  - support proxy log in terminal &nbsp;-&nbsp; by @soybeanjs [<samp>(4cc14)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4cc1487f)
- **projects): feat(projects**:
  - TableColumnCheck title support VNode &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/716 [<samp>(a1a5c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a1a5c74c)
- **utils**:
  - support replaceTab. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/713 [<samp>(be608)</samp>](https://github.com/soybeanjs/soybean-admin/commit/be6080ba)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - hidden multi-language button in login page. fix #694 &nbsp;-&nbsp; by **Azir** in https://github.com/soybeanjs/soybean-admin/issues/694 [<samp>(54e7d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/54e7d6d0)
  - fix multiple calls to the login API when clicking quickly. fixed #697 &nbsp;-&nbsp; by @zsdycs in https://github.com/soybeanjs/soybean-admin/issues/698 and https://github.com/soybeanjs/soybean-admin/issues/697 [<samp>(86da7)</samp>](https://github.com/soybeanjs/soybean-admin/commit/86da767e)
  - fix multiple calls to the login API when clicking quickly. fixed #697 " &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/698 and https://github.com/soybeanjs/soybean-admin/issues/697 [<samp>(15163)</samp>](https://github.com/soybeanjs/soybean-admin/commit/15163d70)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(132e1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/132e1012)
  - update deps &nbsp;-&nbsp; by **Azir** [<samp>(52c33)</samp>](https://github.com/soybeanjs/soybean-admin/commit/52c336d7)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(b8112)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b8112613)
- **projects**:
  - update unocss preset &nbsp;-&nbsp; by @Wangijun in https://github.com/soybeanjs/soybean-admin/issues/712 [<samp>(3e007)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3e0076d4)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;[![Wangijun](https://github.com/Wangijun.png?size=48)](https://github.com/Wangijun)&nbsp;&nbsp;[![zsdycs](https://github.com/zsdycs.png?size=48)](https://github.com/zsdycs)&nbsp;&nbsp;
[Azir](mailto:2075125282@qq.com),&nbsp;

## [v1.3.11](https://github.com/soybeanjs/soybean-admin/compare/v1.3.10...v1.3.11) (2025-01-19)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**: multi language buttons support hiding. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/683 [<samp>(d7aeb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d7aebb7)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **hooks**:
  - The total number before assigning a value to the table is incorrect. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/687 [<samp>(56760)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5676024)
- **projects**:
  - fix login success notification. fixed #688 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/688 [<samp>(60dd2)</samp>](https://github.com/soybeanjs/soybean-admin/commit/60dd226)
  - fix update notifications. fixed #691, fixed #692 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/691 and https://github.com/soybeanjs/soybean-admin/issues/692 [<samp>(ac862)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ac86247)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**: optimize code &nbsp;-&nbsp; by @soybeanjs [<samp>(6489e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6489ec4)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update README &nbsp;-&nbsp; by @soybeanjs [<samp>(21434)</samp>](https://github.com/soybeanjs/soybean-admin/commit/214341e)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(c9433)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c9433e1)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;

## [v1.3.10](https://github.com/honghuangdc/soybean-admin/compare/v1.3.9...v1.3.10) (2024-12-16)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**: support show tab when not loggedIn &nbsp;-&nbsp; by @soybeanjs [<samp>(ba381)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ba38119)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **deps**:
  - reduced eslint version to 9.14.0 &nbsp;-&nbsp; by @soybeanjs [<samp>(af417)</samp>](https://github.com/honghuangdc/soybean-admin/commit/af4177e)
- **projects**:
  - fix route guard hook `onRouteSwitchWhenLoggedIn`. fixed #680 &nbsp;-&nbsp; by @soybeanjs in https://github.com/honghuangdc/soybean-admin/issues/680 [<samp>(ab985)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ab9858c)
  - check if init userInfo when initAuthRoute. fixed #680 &nbsp;-&nbsp; by @soybeanjs in https://github.com/honghuangdc/soybean-admin/issues/680 [<samp>(9f4fb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9f4fb8c)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**:
  - optimize router guard &nbsp;-&nbsp; by @soybeanjs [<samp>(0dfcf)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0dfcf18)
  - use `defu` to fill added theme config &nbsp;-&nbsp; by @soybeanjs [<samp>(101b6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/101b6f9)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: ✏️  add element-plus version link &nbsp;-&nbsp; by **一寸灰** in https://github.com/honghuangdc/soybean-admin/issues/679 [<samp>(5c6ab)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5c6ab0b)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- rename env.d.ts to vite-env.d.ts &nbsp;-&nbsp; by @wzc520pyfm in https://github.com/honghuangdc/soybean-admin/issues/675 [<samp>(b93c2)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b93c203)
- **projects**: update deps & fix vite config &nbsp;-&nbsp; by @soybeanjs [<samp>(3e0eb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3e0eb72)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![wzc520pyfm](https://github.com/wzc520pyfm.png?size=48)](https://github.com/wzc520pyfm)&nbsp;&nbsp;
[一寸灰](mailto:webzhangfei@163.com),&nbsp;

## [v1.3.9](https://github.com/soybeanjs/soybean-admin/compare/v1.3.8...v1.3.9) (2024-11-17)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - support scheduled detection and update system. close #657 &nbsp;-&nbsp; by **青菜白玉汤** in https://github.com/soybeanjs/soybean-admin/issues/669 and https://github.com/soybeanjs/soybean-admin/issues/657 [<samp>(d088f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d088f81)
  - app version notification plugin support sub deploy path. close #668 &nbsp;-&nbsp; by **Soybean** in https://github.com/soybeanjs/soybean-admin/issues/668 [<samp>(a53eb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a53eb10)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**: optimize code &nbsp;-&nbsp; by **Soybean** [<samp>(9ad5d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9ad5d71)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**: refactor router guard. fix #655 &nbsp;-&nbsp; by **Soybean** in https://github.com/soybeanjs/soybean-admin/issues/667 and https://github.com/soybeanjs/soybean-admin/issues/655 [<samp>(09144)</samp>](https://github.com/soybeanjs/soybean-admin/commit/09144df)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: set the Chinese version of README as default &nbsp;-&nbsp; by **Soybean** [<samp>(9d28b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9d28b31)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(91de4)</samp>](https://github.com/soybeanjs/soybean-admin/commit/91de4a8)
  - update deps &nbsp;-&nbsp; by **Soybean** [<samp>(0c809)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0c809de)
- **projects**:
  - add desc for base url of app &nbsp;-&nbsp; by **Soybean** [<samp>(17d7e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/17d7e52)

### &nbsp;&nbsp;&nbsp;❤️ Contributors


[Soybean](mailto:soybeanjs@outlook.com),&nbsp;[青菜白玉汤](mailto:79054161+Azir-11@users.noreply.github.com)

## [v1.3.8](https://github.com/soybeanjs/soybean-admin/compare/v1.3.7...v1.3.8) (2024-10-25)

### &nbsp;&nbsp;&nbsp;🚨 Breaking Changes

- **projects**: refactor route cache & support reset route cache strategy &nbsp;-&nbsp; by @soybeanjs [<samp>(b667e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b667eab)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **packages**:
  - add subpackage `@sa/alova` &nbsp;-&nbsp; by @JOU-amjs in https://github.com/soybeanjs/soybean-admin/issues/640 [<samp>(2072f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2072f58)
  - optimistic subpackage `@sa/alova` &nbsp;-&nbsp; by @JOU-amjs in https://github.com/soybeanjs/soybean-admin/issues/646 [<samp>(4b3ac)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4b3ac11)
- **projects**:
  - login supports accessible operation. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/637 [<samp>(cfaab)</samp>](https://github.com/soybeanjs/soybean-admin/commit/cfaab85)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **utils**: fix `isPC`. fixed #644 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/644 [<samp>(47264)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4726498)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(8dcda)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8dcda38)
- **projects**:
  - update vscode extensions &nbsp;-&nbsp; by @soybeanjs [<samp>(24bb6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/24bb6d9)
  - update deps & fix sass usage &nbsp;-&nbsp; by @soybeanjs [<samp>(71e63)</samp>](https://github.com/soybeanjs/soybean-admin/commit/71e6307)
- **types**:
  - remove type declaration for document.startViewTransition (TypeScript 5.6 includes it) &nbsp;-&nbsp; by @NHZEX in https://github.com/soybeanjs/soybean-admin/issues/633 [<samp>(83ba7)</samp>](https://github.com/soybeanjs/soybean-admin/commit/83ba798)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **projects**: reduce ambiguity in theme configuration instructions. &nbsp;-&nbsp; by @Azir-11 [<samp>(75cbf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/75cbfbb)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![JOU-amjs](https://github.com/JOU-amjs.png?size=48)](https://github.com/JOU-amjs)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;[![NHZEX](https://github.com/NHZEX.png?size=48)](https://github.com/NHZEX)&nbsp;&nbsp;

## [v1.3.7](https://github.com/soybeanjs/soybean-admin/compare/v1.3.6...v1.3.7) (2024-09-21)

### &nbsp;&nbsp;&nbsp;🚨 Breaking Changes

- **projects**: update scss config &nbsp;-&nbsp; by @soybeanjs [<samp>(24e9e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/24e9e57)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**: fix global-tab click conflict with contextmenu &nbsp;-&nbsp; by @soybeanjs [<samp>(3e72c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3e72c3b)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **packages**: @sa/materials: remove tab close shortcut by mouse &nbsp;-&nbsp; by @soybeanjs [<samp>(4da58)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4da588c)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(baefd)</samp>](https://github.com/soybeanjs/soybean-admin/commit/baefdfd)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;

## [v1.3.6](https://github.com/soybeanjs/soybean-admin/compare/v1.3.5...v1.3.6) (2024-09-20)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**:
  - fix VerticalMixMenu name &nbsp;-&nbsp; by @soybeanjs [<samp>(20f8e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/20f8ed3)
- **projects**:
  - fix click global-tab in iPad. fixed #624 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/624 [<samp>(04d05)</samp>](https://github.com/soybeanjs/soybean-admin/commit/04d0564)
  - when the roles filter submenu is empty, the parent menu is not excluded. fixed #621. &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/626 and https://github.com/soybeanjs/soybean-admin/issues/621 [<samp>(0ac95)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0ac95bd)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**:
  - optimize code &nbsp;-&nbsp; by @soybeanjs [<samp>(6561f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6561f0b)
  - optimize code &nbsp;-&nbsp; by @soybeanjs [<samp>(38eeb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/38eeb67)
  - remove defineModel setting，enabled by default &nbsp;-&nbsp; by @yanbowe in https://github.com/soybeanjs/soybean-admin/issues/620 [<samp>(60bbd)</samp>](https://github.com/soybeanjs/soybean-admin/commit/60bbd2d)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(5baf1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5baf19d)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(207d6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/207d6eb)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(f3562)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f35627e)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;

## [v1.3.5](https://github.com/soybeanjs/soybean-admin/compare/v1.3.4...v1.3.5) (2024-09-07)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **packages**:
  - @sa/axios: add response to flatRequest when success &nbsp;-&nbsp; by @soybeanjs [<samp>(c4e16)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c4e1610)
- **projects**:
  - README.zh_CN.md 添加合作推广 &nbsp;-&nbsp; by @PZ-18664918826 in https://github.com/soybeanjs/soybean-admin/issues/601 [<samp>(2fa40)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2fa400b)
  - Add more commit types according to Apache specifications &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/610 [<samp>(878d9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/878d9c3)
  - does the configuration support automatic updates. close#612 &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/617 and https://github.com/soybeanjs/soybean-admin/issues/612 [<samp>(4c9f4)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4c9f4e0)
  - add app error handler. close #587 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/587 [<samp>(be855)</samp>](https://github.com/soybeanjs/soybean-admin/commit/be8556c)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **deps**:
  - move json5 from devDependencies to dependencies to support production usage &nbsp;-&nbsp; by @mufeng889 in https://github.com/soybeanjs/soybean-admin/issues/618 [<samp>(7cb43)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7cb43fc)
- **projects**:
  - avoid retrieving cached HTML &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/605 [<samp>(ef6cf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ef6cf93)
  - fix login redirect &nbsp;-&nbsp; by @soybeanjs [<samp>(3830e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3830ec7)
  - fix vertical-mix-menu when sider collapse. fixed #608 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/608 [<samp>(c3f1f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c3f1f69)
  - fix breadcrumb when activeMenu is parent menu. fixed #589 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/589 [<samp>(79b2a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/79b2a28)
  - fix refresh token when meet multi requests. fixed #581 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/581 [<samp>(27b52)</samp>](https://github.com/soybeanjs/soybean-admin/commit/27b5222)
- **types**:
  - fix the type of TableApiFn &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/599 [<samp>(26c93)</samp>](https://github.com/soybeanjs/soybean-admin/commit/26c93df)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**: optimize menu selectedKey &nbsp;-&nbsp; by @soybeanjs [<samp>(531bf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/531bfaf)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README &nbsp;-&nbsp; by @mufeng889 in https://github.com/soybeanjs/soybean-admin/issues/594 [<samp>(a8f92)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a8f923e)
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(e9a2e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e9a2ee4)
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(73e91)</samp>](https://github.com/soybeanjs/soybean-admin/commit/73e917a)
  - update the location of important information in the document &nbsp;-&nbsp; by **Azir** [<samp>(9c012)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9c012c7)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(a1c14)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a1c14a1)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(7fa55)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7fa5590)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(a44ea)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a44ea62)
- **projects**:
  - use json5 resolve env `VITE_OTHER_SERVICE_BASE_URL` & fix proxy enable &nbsp;-&nbsp; by @soybeanjs [<samp>(b16a9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b16a963)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **projects**: rename script czh to commit:zh &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/597 [<samp>(5094f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5094f0e)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![mufeng889](https://github.com/mufeng889.png?size=48)](https://github.com/mufeng889)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;[![PZ-18664918826](https://github.com/PZ-18664918826.png?size=48)](https://github.com/PZ-18664918826)&nbsp;&nbsp;
[Azir](mailto:2075125282@qq.com),&nbsp;

## [v1.3.4](https://github.com/honghuangdc/soybean-admin/compare/v1.3.3...v1.3.4) (2024-08-01)

### &nbsp;&nbsp;&nbsp;🚨 Breaking Changes

- **projects**: don't reset active menu of vertical-mix layout when it is mixSiderFixed &nbsp;-&nbsp; by @honghuangdc [<samp>(939c5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/939c512)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**: optimize code &nbsp;-&nbsp; by @honghuangdc [<samp>(cb1d4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cb1d445)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **projects**: update deps & fix vue-router type &nbsp;-&nbsp; by @honghuangdc [<samp>(96837)</samp>](https://github.com/honghuangdc/soybean-admin/commit/968370b)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v1.3.3](https://github.com/honghuangdc/soybean-admin/compare/v1.3.2...v1.3.3) (2024-07-30)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**: fix watermark settings &nbsp;-&nbsp; by @honghuangdc [<samp>(5646a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5646a50)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update CHANGELOG &nbsp;-&nbsp; by @honghuangdc [<samp>(ebc83)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ebc838c)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v1.3.2](https://github.com/honghuangdc/soybean-admin/compare/v1.3.1...v1.3.2) (2024-07-30)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - add color fading mode.close #567 &nbsp;-&nbsp; by @Azir-11 in https://github.com/honghuangdc/soybean-admin/issues/569 and https://github.com/honghuangdc/soybean-admin/issues/567 [<samp>(4dde4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4dde4c2)
  - add full screen watermark. close#571 &nbsp;-&nbsp; by @paynezhuang in https://github.com/honghuangdc/soybean-admin/issues/573 and https://github.com/honghuangdc/soybean-admin/issues/571 [<samp>(ea8aa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ea8aa6c)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**: fix vertical-mix menu selected &nbsp;-&nbsp; by @honghuangdc [<samp>(59f07)</samp>](https://github.com/honghuangdc/soybean-admin/commit/59f07d8)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**:
  - add type WatermarkProps &nbsp;-&nbsp; by @honghuangdc [<samp>(f26d0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f26d0a6)
  - remove home NAlert closable &nbsp;-&nbsp; by @honghuangdc [<samp>(98b75)</samp>](https://github.com/honghuangdc/soybean-admin/commit/98b75c2)
  - optimize response code comparison &nbsp;-&nbsp; by @honghuangdc [<samp>(cf67d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cf67d55)
- **types**:
  - remove useless types. &nbsp;-&nbsp; by **Azir** [<samp>(eed61)</samp>](https://github.com/honghuangdc/soybean-admin/commit/eed617f)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update CHANGELOG &nbsp;-&nbsp; by @honghuangdc [<samp>(d3759)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d37591d)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(993e9)</samp>](https://github.com/honghuangdc/soybean-admin/commit/993e9ca)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![paynezhuang](https://github.com/paynezhuang.png?size=48)](https://github.com/paynezhuang)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;
[Azir](mailto:2075125282@qq.com),&nbsp;

## [v1.3.1](https://github.com/honghuangdc/soybean-admin/compare/v1.3.0...v1.3.1) (2024-07-22)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - fix the issue of abnormal width of the sidebar in the top menu mix and reverse mode &nbsp;-&nbsp; by @Azir-11 in https://github.com/honghuangdc/soybean-admin/issues/562 [<samp>(c4695)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c469512)
  - fix HorizontalMixMenu inverted. fixed #563 &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/563 [<samp>(4e55b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4e55b0e)
  - fix vertical-menu will not render when the layout is from mobile &nbsp;-&nbsp; by @honghuangdc [<samp>(84027)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8402734)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update CHANGELOG &nbsp;-&nbsp; by @honghuangdc [<samp>(613c8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/613c836)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **other**: modify the Chinese name of the grayscale mode &nbsp;-&nbsp; by **Azir** [<samp>(53770)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5377002)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;
[Azir](mailto:2075125282@qq.com),&nbsp;

## [v1.3.0](https://github.com/soybeanjs/soybean-admin/compare/v1.2.8...v1.3.0) (2024-07-22)

### &nbsp;&nbsp;&nbsp;🚨 Breaking Changes

- **projects**: refactor global menu & support `reversed-horizontal-mix-menu`. close #365 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/365 [<samp>(087e5)</samp>](https://github.com/soybeanjs/soybean-admin/commit/087e532)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **packages**:
  - `@sa/scripts`: command `gitCommit` support chinese &nbsp;-&nbsp; by @mmdapl in https://github.com/soybeanjs/soybean-admin/issues/548 [<samp>(06971)</samp>](https://github.com/soybeanjs/soybean-admin/commit/06971f3)
  - @sa/axios: replace CancelTokenSource by AbortController. close #530, close #532 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/530 and https://github.com/soybeanjs/soybean-admin/issues/532 [<samp>(527fd)</samp>](https://github.com/soybeanjs/soybean-admin/commit/527fd79)
  - @sa/scripts: add ignore pattern list for command `gitCommitVerify`. close #504 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/504 [<samp>(958d0)</samp>](https://github.com/soybeanjs/soybean-admin/commit/958d0ba)
- **projects**:
  - make branch `main` tiny & modify request retry times to 0 &nbsp;-&nbsp; by @Azir-11 [<samp>(793b1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/793b16e)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **hooks**: prevent program freezing when pagesize returns 0 &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/545 [<samp>(f4eeb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f4eeb2e)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - combine `theme tokens` and `theme settings`. close #379 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/379 [<samp>(1d1b1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1d1b148)
  - change css vars mount to root &nbsp;-&nbsp; by @honghuangdc [<samp>(00f41)</samp>](https://github.com/soybeanjs/soybean-admin/commit/00f41dd)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update CHANGELOG &nbsp;-&nbsp; by @honghuangdc [<samp>(a0b76)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a0b76da)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(f6bd6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f6bd6b8)
- **projects**: add script `czh` &nbsp;-&nbsp; by @honghuangdc [<samp>(02069)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0206969)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![mmdapl](https://github.com/mmdapl.png?size=48)](https://github.com/mmdapl)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;

## [v1.2.8](https://github.com/soybeanjs/soybean-admin/compare/v1.2.7...v1.2.8) (2024-07-20)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **packages**:
  - @sa/hooks: fix searchParams of useHookTable. fixed #552 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/552 [<samp>(96c10)</samp>](https://github.com/soybeanjs/soybean-admin/commit/96c1044)
- **types**:
  - Fixed the reference type error &nbsp;-&nbsp; by **dodu2014** in https://github.com/soybeanjs/soybean-admin/issues/551 [<samp>(3e2a9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3e2a993)
  - fix data type of useHookTable &nbsp;-&nbsp; by @honghuangdc [<samp>(276ea)</samp>](https://github.com/soybeanjs/soybean-admin/commit/276ea7f)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**: replace `cloneDeep` of `lodash-es` with `klona` &nbsp;-&nbsp; by @honghuangdc [<samp>(a9133)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a91335d)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update CHANGELOG &nbsp;-&nbsp; by @honghuangdc [<samp>(58fc0)</samp>](https://github.com/soybeanjs/soybean-admin/commit/58fc096)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(cf019)</samp>](https://github.com/soybeanjs/soybean-admin/commit/cf0192a)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;
[dodu2014](mailto:dodu@live.cn)

## [v1.2.7](https://github.com/honghuangdc/soybean-admin/compare/v1.2.6...v1.2.7) (2024-07-12)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**: supports custom menu icon sizes &nbsp;-&nbsp; by @wynn-w in https://github.com/honghuangdc/soybean-admin/issues/534 [<samp>(e035e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e035eab)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(72ede)</samp>](https://github.com/honghuangdc/soybean-admin/commit/72ede8b)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(be13c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/be13ca2)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(752ec)</samp>](https://github.com/honghuangdc/soybean-admin/commit/752ec1e)
- **projects**:
  - Fix deprecated configuration config &nbsp;-&nbsp; by @paynezhuang in https://github.com/honghuangdc/soybean-admin/issues/524 [<samp>(0d20e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0d20e4c)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![wynn-w](https://github.com/wynn-w.png?size=48)](https://github.com/wynn-w)&nbsp;&nbsp;[![paynezhuang](https://github.com/paynezhuang.png?size=48)](https://github.com/paynezhuang)&nbsp;&nbsp;

## [v1.2.6](https://github.com/honghuangdc/soybean-admin/compare/v1.2.5...v1.2.6) (2024-06-21)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - request modal title use i18n. fixed #507 &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/507 [<samp>(f7de3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f7de3fd)
  - add `getDataByPage` for `useTable`. fixed #499 &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/499 [<samp>(425c6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/425c69a)
  - fix login redirect to routeHome when routeHome of dynamic route is not same as static route. fixed #511 &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/511 [<samp>(49f60)</samp>](https://github.com/honghuangdc/soybean-admin/commit/49f60b2)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**: optimize `getRouteQueryOfLoginRoute` &nbsp;-&nbsp; by @honghuangdc [<samp>(693f7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/693f704)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update CHANGELOG &nbsp;-&nbsp; by @honghuangdc [<samp>(5c67d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5c67d06)
  - update README &nbsp;-&nbsp; by @honghuangdc [<samp>(1e67a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1e67ae8)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps. close #510 &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/510 [<samp>(53143)</samp>](https://github.com/honghuangdc/soybean-admin/commit/531432d)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(c7f6f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c7f6f2a)

### &nbsp;&nbsp;&nbsp;🤖 CI

- **projects**:
  - add github issues template &nbsp;-&nbsp; by @honghuangdc [<samp>(b5027)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b5027c8)
  - update github issues template &nbsp;-&nbsp; by @honghuangdc [<samp>(ff1d5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ff1d504)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v1.2.5](https://github.com/soybeanjs/soybean-admin/compare/v1.2.4...v1.2.5) (2024-06-15)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**: Fix the issue of abnormal tab caching after logout. fixed #495 &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/495 [<samp>(3eeac)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3eeace9)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- **project**: Initializing the static routing function does not require asynchronization &nbsp;-&nbsp; by **CHENZL** in https://github.com/soybeanjs/soybean-admin/issues/493 [<samp>(2198b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2198b98)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**: optimize code &nbsp;-&nbsp; by @soybeanjs [<samp>(b94ba)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b94baa1)
- **types**: Enhance compatibility of global types &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/494 [<samp>(cd9d5)</samp>](https://github.com/soybeanjs/soybean-admin/commit/cd9d58d)
- **utils**: Reduce code indentation and improve readability &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/496 [<samp>(ad2f2)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ad2f247)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(b3368)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b336841)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(b094d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b094d68)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;
[CHENZL](mailto:zlong5568863@qq.com)

## [v1.2.4](https://github.com/soybeanjs/soybean-admin/compare/v1.2.3...v1.2.4) (2024-06-14)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**:
  - optimize `setupAppVersionNotification` &nbsp;-&nbsp; by @soybeanjs [<samp>(b5a72)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b5a723c)
  - get buildTime with timezone 'Asia/Shanghai' &nbsp;-&nbsp; by @soybeanjs [<samp>(069fa)</samp>](https://github.com/soybeanjs/soybean-admin/commit/069fa8a)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;

## [v1.2.3](https://github.com/soybeanjs/soybean-admin/compare/v1.2.2...v1.2.3) (2024-06-13)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - fix mobile browser theme issue by adding color-scheme meta tag to index.html &nbsp;-&nbsp; by @KickCashew in https://github.com/soybeanjs/soybean-admin/issues/488 [<samp>(c2125)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c212565)
  - Fix secondary directory components is empty &nbsp;-&nbsp; by @paynezhuang in https://github.com/soybeanjs/soybean-admin/issues/491 [<samp>(aabb2)</samp>](https://github.com/soybeanjs/soybean-admin/commit/aabb2a4)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - Fixed the hyperlink pointing error &nbsp;-&nbsp; by **Azir** [<samp>(20a81)</samp>](https://github.com/soybeanjs/soybean-admin/commit/20a8127)
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(70261)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7026126)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(813d8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/813d8ce)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(bf718)</samp>](https://github.com/soybeanjs/soybean-admin/commit/bf71837)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![paynezhuang](https://github.com/paynezhuang.png?size=48)](https://github.com/paynezhuang)&nbsp;&nbsp;[![KickCashew](https://github.com/KickCashew.png?size=48)](https://github.com/KickCashew)&nbsp;&nbsp;
[Azir](mailto:2075125282@qq.com)

## [v1.2.2](https://github.com/honghuangdc/soybean-admin/compare/v1.2.1...v1.2.2) (2024-06-12)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**: reset scroll position when tab change &nbsp;-&nbsp; by @soybeanjs [<samp>(9094b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9094b21)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - hide AppVersionNotification in DEV mode &nbsp;-&nbsp; by @sigma-plus in https://github.com/honghuangdc/soybean-admin/issues/482 [<samp>(62592)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6259287)
  - fix menu-toggler hidden in mobile layout. fixed #483 &nbsp;-&nbsp; by @soybeanjs in https://github.com/honghuangdc/soybean-admin/issues/483 [<samp>(4470c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4470cb4)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update README &nbsp;-&nbsp; by @soybeanjs [<samp>(8f9a7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8f9a705)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![sigma-plus](https://github.com/sigma-plus.png?size=48)](https://github.com/sigma-plus)&nbsp;&nbsp;

## [v1.2.1](https://github.com/honghuangdc/soybean-admin/compare/v1.2.0...v1.2.1) (2024-06-07)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - fix get user info when page reload &nbsp;-&nbsp; by @soybeanjs [<samp>(ff51b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ff51b72)
  - fix setupAppVersionNotification render &nbsp;-&nbsp; by @soybeanjs [<samp>(6a6eb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6a6eb9a)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(fe06b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/fe06b8c)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(08827)</samp>](https://github.com/honghuangdc/soybean-admin/commit/08827a4)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;

## [v1.2.0](https://github.com/soybeanjs/soybean-admin/compare/v1.1.5...v1.2.0) (2024-06-06)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - support system new version update notification. close #420 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/420 [<samp>(584cd)</samp>](https://github.com/soybeanjs/soybean-admin/commit/584cd54)
  - get user info in router guard and remove in localStorage. close #459 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/459 [<samp>(5531a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5531a68)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(2bec8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2bec899)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;

## [v1.1.5](https://github.com/soybeanjs/soybean-admin/compare/v1.1.4...v1.1.5) (2024-06-06)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**: fix register name, CodeLogin => Register &nbsp;-&nbsp; by @m-xlsea in https://github.com/soybeanjs/soybean-admin/issues/478 [<samp>(ddf38)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ddf3823)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(060c0)</samp>](https://github.com/soybeanjs/soybean-admin/commit/060c0a9)
- **projects**: update vscode settings: vue official &nbsp;-&nbsp; by @soybeanjs [<samp>(76649)</samp>](https://github.com/soybeanjs/soybean-admin/commit/76649e2)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![m-xlsea](https://github.com/m-xlsea.png?size=48)](https://github.com/m-xlsea)&nbsp;&nbsp;

## [v1.1.4](https://github.com/honghuangdc/soybean-admin/compare/v1.1.3...v1.1.4) (2024-06-06)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **utils**: modalLogout bug when esc is pressed &nbsp;-&nbsp; by @sigma-plus in https://github.com/honghuangdc/soybean-admin/issues/470 [<samp>(bd69c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bd69c00)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**: optimize RouteMeta remarks &nbsp;-&nbsp; by @soybeanjs [<samp>(ffb48)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ffb48b1)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(756f8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/756f84a)
  - update Node&pnpm version &nbsp;-&nbsp; by @Azir-11 in https://github.com/honghuangdc/soybean-admin/issues/472 [<samp>(9b05d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9b05d73)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(d0380)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d0380ce)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(1f464)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1f4647b)
- **projects**:
  - close http proxy &nbsp;-&nbsp; by @soybeanjs [<samp>(d08a3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d08a381)
  - update mock url &nbsp;-&nbsp; by @soybeanjs [<samp>(e6086)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e6086f0)
  - update vscode settings &nbsp;-&nbsp; by @soybeanjs [<samp>(910df)</samp>](https://github.com/honghuangdc/soybean-admin/commit/910dfca)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;[![sigma-plus](https://github.com/sigma-plus.png?size=48)](https://github.com/sigma-plus)&nbsp;&nbsp;

## [v1.1.3](https://github.com/soybeanjs/soybean-admin/compare/v1.1.2...v1.1.3) (2024-06-02)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**:
  - Fix the issue of search box popping up repeatedly due to carriage return &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/468 [<samp>(5bd96)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5bd96b8)
- **projects**:
  - fix click menu search. fixed #466, close #467 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/466 and https://github.com/soybeanjs/soybean-admin/issues/467 [<samp>(8efdb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8efdb10)
  - fix reCacheRoute. fixed #464 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/464 [<samp>(59faf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/59faf15)
- **styles**:
  - fix FirstLevelMenu style. fixed #450 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/450 [<samp>(db64b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/db64b0e)
  - fix PinToggler style. fixed #451 &nbsp;-&nbsp; by @soybeanjs in https://github.com/soybeanjs/soybean-admin/issues/451 [<samp>(42b12)</samp>](https://github.com/soybeanjs/soybean-admin/commit/42b121a)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **components**: accuracy draggable area for TableColumnSetting with animation &nbsp;-&nbsp; by @orangelckc in https://github.com/soybeanjs/soybean-admin/issues/465 [<samp>(2aa85)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2aa85c6)
- **projects**: unocss border shortcut &nbsp;-&nbsp; by @soybeanjs [<samp>(40d0f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/40d0f8a)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update CHANGELOG &nbsp;-&nbsp; by @soybeanjs [<samp>(87b18)</samp>](https://github.com/soybeanjs/soybean-admin/commit/87b1838)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **other**:
  - correct spell mistake &nbsp;-&nbsp; by @orangelckc in https://github.com/soybeanjs/soybean-admin/issues/460 [<samp>(086ba)</samp>](https://github.com/soybeanjs/soybean-admin/commit/086bad4)
  - correct spell mistake &nbsp;-&nbsp; by @Azir-11 in https://github.com/soybeanjs/soybean-admin/issues/462 [<samp>(f1850)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f185041)
- **projects**:
  - update vscode launch.json &nbsp;-&nbsp; by @soybeanjs [<samp>(4c1c7)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4c1c7e6)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;[![orangelckc](https://github.com/orangelckc.png?size=48)](https://github.com/orangelckc)&nbsp;&nbsp;

## [v1.1.2](https://github.com/soybeanjs/soybean-admin/compare/v1.1.1...v1.1.2) (2024-05-24)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - fix header style & fix button highlight when click global-tab. fixed #446 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/446 [<samp>(64fc0)</samp>](https://github.com/soybeanjs/soybean-admin/commit/64fc099)
  - fix multi tab page only render once. fixed #441 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/441 [<samp>(e379d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e379d6c)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**: optimize code &nbsp;-&nbsp; by @honghuangdc [<samp>(bc8dc)</samp>](https://github.com/soybeanjs/soybean-admin/commit/bc8dc47)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v1.1.1](https://github.com/soybeanjs/soybean-admin/compare/v1.1.0...v1.1.1) (2024-05-20)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **hooks**: add setOptions for useEcharts &nbsp;-&nbsp; by @honghuangdc [<samp>(e4d53)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e4d53aa)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - fix useRouter. fixed #436 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/436 [<samp>(0774a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0774a51)
  - add error handle when get routes in dynamic route mode. fixed 440 &nbsp;-&nbsp; by @honghuangdc [<samp>(57b4a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/57b4a9d)
- **styles**:
  - fix useTable type &nbsp;-&nbsp; by @honghuangdc [<samp>(07124)</samp>](https://github.com/soybeanjs/soybean-admin/commit/071241f)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update CHANGELOG &nbsp;-&nbsp; by @honghuangdc [<samp>(19783)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1978397)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(fa56e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/fa56e9c)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(419ea)</samp>](https://github.com/soybeanjs/soybean-admin/commit/419ea42)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **projects**:
  - update deps & fix TS error &nbsp;-&nbsp; by @honghuangdc [<samp>(4ea9c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4ea9c85)
  - update eslint-config & fix code &nbsp;-&nbsp; by @honghuangdc [<samp>(68ea9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/68ea974)
  - update @elegant-router/vue & add error handle for resolve route. fixed #442 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/442 [<samp>(24ff8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/24ff852)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v1.1.0](https://github.com/honghuangdc/soybean-admin/compare/v1.0.9...v1.1.0) (2024-05-07)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - support grayscale. fixed #385 &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/385 [<samp>(d335d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d335df6)
  - Add prefix to local storage &nbsp;-&nbsp; by **Azir** [<samp>(1fc34)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1fc34cc)
  - add table showTotal options &nbsp;-&nbsp; by **paynezhuang** [<samp>(3e61e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3e61eab)
  - add recommend color switch. closed #388 &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/388 [<samp>(a1920)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a1920fc)
  - add menu route field &nbsp;-&nbsp; by **paynezhuang** [<samp>(dbe31)</samp>](https://github.com/honghuangdc/soybean-admin/commit/dbe31eb)
  - support repeated request errors occur once in a short time. close #368, close #369 &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/368 and https://github.com/honghuangdc/soybean-admin/issues/369 [<samp>(e3bd3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e3bd397)
  - close tab by mouse wheel button click &nbsp;-&nbsp; by **JianJroh** [<samp>(d3849)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d3849ba)
  - page: support manage_menu more options. close #366 &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/366 [<samp>(c4b5c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c4b5c65)
  - useTable adds expand to display &nbsp;-&nbsp; by **paynezhuang** [<samp>(0a90d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0a90dd3)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - menu fixedIndexInTab default null &nbsp;-&nbsp; by **paynezhuang** [<samp>(3d10e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3d10ef1)
  - fix menu-toggler zIndex &nbsp;-&nbsp; by @honghuangdc [<samp>(7bd43)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7bd43df)
  - fix manage_menu modal style &nbsp;-&nbsp; by @honghuangdc [<samp>(60f3b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/60f3b14)
  - fix menu data when role is changed. fixed #391 &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/391 [<samp>(3b47b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3b47b5a)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**: remove deprecated code &nbsp;-&nbsp; by @honghuangdc [<samp>(72ccb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/72ccb6b)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - refactor @sa/color-palette => @sa/color & perf @sa/utils &nbsp;-&nbsp; by @honghuangdc [<samp>(34999)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3499997)
  - menu-operate-drawer => menu-operate-modal &nbsp;-&nbsp; by @honghuangdc [<samp>(003e1)</samp>](https://github.com/honghuangdc/soybean-admin/commit/003e145)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - add CHANGELOG.zh_CN.md &nbsp;-&nbsp; by @honghuangdc [<samp>(18b3f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/18b3f05)
  - update CHANGELOG &nbsp;-&nbsp; by @honghuangdc [<samp>(4d17c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4d17cfd)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(1cb38)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1cb3816)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(599b4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/599b4e1)
- **projects**:
  - merge main to v1.1.0 &nbsp;-&nbsp; by @honghuangdc [<samp>(ebe55)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ebe55af)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;
[paynezhuang](mailto:paynezhuang@gmail.com),&nbsp;[JianJroh](mailto:rhjian@foxmail.com),&nbsp;[Azir](mailto:2075125282@qq.com)

## [v1.1.0-beta.2](https://github.com/honghuangdc/soybean-admin/compare/v1.1.0-beta.1...v1.1.0-beta.2) (2024-05-07)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**: useTable adds expand to display &nbsp;-&nbsp; by **paynezhuang** [<samp>(0a90d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0a90dd3)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - fix manage_menu modal style &nbsp;-&nbsp; by @honghuangdc [<samp>(60f3b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/60f3b14)
  - fix menu data when role is changed. fixed #391 &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/391 [<samp>(3b47b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3b47b5a)

### &nbsp;&nbsp;&nbsp;🛠 Optimizations

- **projects**: remove deprecated code &nbsp;-&nbsp; by @honghuangdc [<samp>(72ccb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/72ccb6b)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: add CHANGELOG.zh_CN.md &nbsp;-&nbsp; by @honghuangdc [<samp>(18b3f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/18b3f05)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;
[paynezhuang](mailto:paynezhuang@gmail.com)

## [v1.1.0-beta.1](https://github.com/soybeanjs/soybean-admin/compare/v1.0.9...v1.1.0-beta.1) (2024-05-07)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - support grayscale. fixed #385 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/385 [<samp>(d335d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d335df6)
  - Add prefix to local storage &nbsp;-&nbsp; by **Azir** [<samp>(1fc34)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1fc34cc)
  - add table showTotal options &nbsp;-&nbsp; by **paynezhuang** [<samp>(3e61e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3e61eab)
  - add recommend color switch. closed #388 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/388 [<samp>(a1920)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a1920fc)
  - add menu route field &nbsp;-&nbsp; by **paynezhuang** [<samp>(dbe31)</samp>](https://github.com/soybeanjs/soybean-admin/commit/dbe31eb)
  - support repeated request errors occur once in a short time. close #368, close #369 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/368 and https://github.com/soybeanjs/soybean-admin/issues/369 [<samp>(e3bd3)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e3bd397)
  - close tab by mouse wheel button click &nbsp;-&nbsp; by **JianJroh** [<samp>(d3849)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d3849ba)
  - page: support manage_menu more options. close #366 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/366 [<samp>(c4b5c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c4b5c65)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - menu fixedIndexInTab default null &nbsp;-&nbsp; by **paynezhuang** [<samp>(3d10e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3d10ef1)
  - fix menu-toggler zIndex &nbsp;-&nbsp; by @honghuangdc [<samp>(7bd43)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7bd43df)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - refactor @sa/color-palette => @sa/color & perf @sa/utils &nbsp;-&nbsp; by @honghuangdc [<samp>(34999)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3499997)
  - menu-operate-drawer => menu-operate-modal &nbsp;-&nbsp; by @honghuangdc [<samp>(003e1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/003e145)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(1cb38)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1cb3816)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(599b4)</samp>](https://github.com/soybeanjs/soybean-admin/commit/599b4e1)
- **projects**:
  - merge main to v1.1.0 &nbsp;-&nbsp; by @honghuangdc [<samp>(ebe55)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ebe55af)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;
[JianJroh](mailto:rhjian@foxmail.com),&nbsp;[paynezhuang](mailto:paynezhuang@gmail.com),&nbsp;[Azir](mailto:2075125282@qq.com)

## [v1.0.9](https://github.com/soybeanjs/soybean-admin/compare/v1.0.8...v1.0.9) (2024-05-05)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **packages**: @sa/scripts: add new commit type `optimize` and commit scope `packages` &nbsp;-&nbsp; by @honghuangdc [<samp>(fbc2e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/fbc2e61)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**: fix manage page drawer operate about data reset. fixed #415, fixed #417 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/415 and https://github.com/soybeanjs/soybean-admin/issues/417 [<samp>(f4513)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f4513e1)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - add ecosystem to README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(d0f17)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d0f17a4)
  - add PanisAdmin to README &nbsp;-&nbsp; by **paynezhuang** [<samp>(ce2a7)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ce2a75b)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(413a8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/413a8b2)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(734ef)</samp>](https://github.com/soybeanjs/soybean-admin/commit/734ef98)
- **projects**:
  - update .npmrc &nbsp;-&nbsp; by @honghuangdc [<samp>(52188)</samp>](https://github.com/soybeanjs/soybean-admin/commit/52188d8)
  - update vscode settings &nbsp;-&nbsp; by @honghuangdc [<samp>(c137b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c137b97)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;
[paynezhuang](mailto:paynezhuang@gmail.com)

## [v1.0.8](https://github.com/soybeanjs/soybean-admin/compare/v1.0.7...v1.0.8) (2024-04-27)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**:
  - fix PinToggler label. fixed #407 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/407 [<samp>(c0ed1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c0ed1f2)
- **projects**:
  - text level low. #409 &nbsp;-&nbsp; by **alleycharming** in https://github.com/soybeanjs/soybean-admin/issues/409 [<samp>(3ddb1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3ddb17a)
  - fix tab fixedIndex as null case &nbsp;-&nbsp; by **paynezhuang** [<samp>(4708e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4708ede)
  - recovery the layout config before is mobile. fixed #408, fixed #361 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/408 and https://github.com/soybeanjs/soybean-admin/issues/361 [<samp>(dae2a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/dae2aa5)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- **projects**: perf judgement the fixed tab &nbsp;-&nbsp; by @honghuangdc [<samp>(b3e9b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b3e9bba)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**: `Soybean Admin` to `SoybeanAdmin` &nbsp;-&nbsp; by @honghuangdc [<samp>(a8dbc)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a8dbc03)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;
[paynezhuang](mailto:paynezhuang@gmail.com),&nbsp;[alleycharming](mailto:alleycharming@gmail.com)

## [v1.0.7](https://github.com/soybeanjs/soybean-admin/compare/v1.0.6...v1.0.7) (2024-04-25)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**: support iframe page with diffrent url of custom route &nbsp;-&nbsp; by @honghuangdc [<samp>(da12d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/da12d4a)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(fbd80)</samp>](https://github.com/soybeanjs/soybean-admin/commit/fbd80c2)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v1.0.6](https://github.com/soybeanjs/soybean-admin/compare/v1.0.5...v1.0.6) (2024-04-25)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **hooks**: add state hooks: useRef, useState, useSignal &nbsp;-&nbsp; by @honghuangdc [<samp>(09f64)</samp>](https://github.com/soybeanjs/soybean-admin/commit/09f6464)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - added responseType judgment. #396 &nbsp;-&nbsp; by **alleycharming** in https://github.com/soybeanjs/soybean-admin/issues/396 [<samp>(82eab)</samp>](https://github.com/soybeanjs/soybean-admin/commit/82eabab)
  - supply $t import statement &nbsp;-&nbsp; by @honghuangdc [<samp>(b2660)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b266035)
  - fix mix-menu blank. fixed #389 & cache mixMenuFixed &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/389 [<samp>(93c7f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/93c7ff7)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- **hooks**:
  - perf useSignal &nbsp;-&nbsp; by @honghuangdc [<samp>(5d45c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5d45cef)
- **projects**:
  - remove useless prop `title` of `NDrawer` &nbsp;-&nbsp; by @honghuangdc [<samp>(fdde6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/fdde679)
  - add tsconfig.json for @sa/color-palette &nbsp;-&nbsp; by @honghuangdc [<samp>(d460e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d460e5c)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **hooks**: refactor useSignal, useComputed &nbsp;-&nbsp; by @honghuangdc [<samp>(3b5e4)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3b5e4b3)
- **projects**: useMixMenuContext replace useMixMenu &nbsp;-&nbsp; by @honghuangdc [<samp>(1e142)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1e14293)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(e57bf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e57bf0b)
- **projects**:
  - use `engines` replace `packageManager` &nbsp;-&nbsp; by @honghuangdc [<samp>(dcd51)</samp>](https://github.com/soybeanjs/soybean-admin/commit/dcd51f4)
  - update pnpm version requirement &nbsp;-&nbsp; by @honghuangdc [<samp>(19e65)</samp>](https://github.com/soybeanjs/soybean-admin/commit/19e65c1)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;
[alleycharming](mailto:alleycharming@gmail.com)

## [v1.0.5](https://github.com/honghuangdc/soybean-admin/compare/v1.0.4...v1.0.5) (2024-04-24)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update CHANGELOG.md &nbsp;-&nbsp; by @honghuangdc [<samp>(cf5bc)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cf5bc88)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **projects**:
  - lower vue version to 3.4.23 &nbsp;-&nbsp; by @honghuangdc [<samp>(b5243)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b52432a)
  - update pnpm-lock.yaml &nbsp;-&nbsp; by @honghuangdc [<samp>(516f4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/516f46a)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v1.0.4](https://github.com/soybeanjs/soybean-admin/compare/v1.0.3...v1.0.4) (2024-04-24)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - fix CHANGELOG versions &nbsp;-&nbsp; by @honghuangdc [<samp>(d9af5)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d9af5aa)
  - fix disabled page animate &nbsp;-&nbsp; by @honghuangdc [<samp>(23f28)</samp>](https://github.com/soybeanjs/soybean-admin/commit/23f283a)
  - fix routes data when role is change. fixed #391 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/391 [<samp>(cb83d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/cb83d6d)
  - fix tabs data when role is change. fixed #392 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/392 [<samp>(04aa0)</samp>](https://github.com/soybeanjs/soybean-admin/commit/04aa097)
  - recovery pnpm-lock.yaml &nbsp;-&nbsp; by @honghuangdc [<samp>(c6952)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c695208)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **hooks**: refactor @sa/color &nbsp;-&nbsp; by @honghuangdc [<samp>(93191)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9319173)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(5a523)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5a5232b)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(79d9c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/79d9c51)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(ac928)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ac92817)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(3ceeb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3ceeb6f)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(9a669)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9a66979)
- **projects**:
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(42e16)</samp>](https://github.com/soybeanjs/soybean-admin/commit/42e16a0)
  - update deps & update pnpm version & update eslint config &nbsp;-&nbsp; by @honghuangdc [<samp>(7392b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7392beb)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v1.0.3](https://github.com/soybeanjs/soybean-admin/compare/v1.0.2...v1.0.3) (2024-04-16)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **hooks**: deleting the route export of useRoutePush, use vue-router &nbsp;-&nbsp; by **paynezhuang** [<samp>(c6648)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c6648b6)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - fix menu edit rules &nbsp;-&nbsp; by **paynezhuang** [<samp>(00105)</samp>](https://github.com/soybeanjs/soybean-admin/commit/001059c)
  - fix SvgIcon inheritAttrs warning &nbsp;-&nbsp; by @honghuangdc [<samp>(efc0e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/efc0e25)
  - fix axios createRequest: add default state &nbsp;-&nbsp; by @honghuangdc [<samp>(d6eda)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d6eda8f)
  - update union-key.d.ts &nbsp;-&nbsp; by @honghuangdc [<samp>(60bef)</samp>](https://github.com/soybeanjs/soybean-admin/commit/60beff7)
  - fix update theme color &nbsp;-&nbsp; by @honghuangdc [<samp>(27c53)</samp>](https://github.com/soybeanjs/soybean-admin/commit/27c53cd)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- **projects**: perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(b7f07)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b7f0749)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**: update naive-ui.d.ts &nbsp;-&nbsp; by @honghuangdc [<samp>(bb74d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/bb74d99)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(f4a9c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f4a9cf8)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;
[paynezhuang](mailto:paynezhuang@gmail.com)

## [v1.0.2](https://github.com/soybeanjs/soybean-admin/compare/v1.0.1...v1.0.2) (2024-04-08)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**: unify border-radius of Tag. fixed #378 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/378 [<samp>(2f15a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2f15a2a)
- **styles**: fix css var is inserted repeatedly &nbsp;-&nbsp; by **燕博文** [<samp>(769d8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/769d84a)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**: refactor addThemeVarsToHtml &nbsp;-&nbsp; by @honghuangdc [<samp>(41e47)</samp>](https://github.com/soybeanjs/soybean-admin/commit/41e470e)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(a1b48)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a1b484a)
- **projects**: disabled unocss eslint rule: order-attributify &nbsp;-&nbsp; by @honghuangdc [<samp>(1c72d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1c72dc7)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;
[燕博文](mailto:349952469@qq.com)

## [v1.0.1](https://github.com/soybeanjs/soybean-admin/compare/v1.0.0...v1.0.1) (2024-04-03)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - fix flatRequest error type. fixed #376 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/376 [<samp>(1ec5e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1ec5ea0)
  - add maxWidth for GlobalTab to fix bg with gap. fixed #350 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/350 [<samp>(cc539)</samp>](https://github.com/soybeanjs/soybean-admin/commit/cc53997)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(76011)</samp>](https://github.com/soybeanjs/soybean-admin/commit/76011af)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **projects**:
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(4babb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4babbe1)
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(9125c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9125cc9)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v1.0.0](https://github.com/soybeanjs/soybean-admin/compare/v0.10.4...v1.0.0) (2024-03-31)

### &nbsp;&nbsp;&nbsp;🚀 Features

- internationalized menu search &nbsp;-&nbsp; by **Kori** [<samp>(9e115)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9e115da)
- **components**:
  - enhance the custom strength of the 'TableHeaderOperation' component &nbsp;-&nbsp; by **tnt group** [<samp>(fdf64)</samp>](https://github.com/soybeanjs/soybean-admin/commit/fdf64f7)
  - add GlobalSearch components &nbsp;-&nbsp; by **燕博文** [<samp>(9ea87)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9ea8789)
- **hooks**:
  - add use-echarts &nbsp;-&nbsp; by @honghuangdc [<samp>(726ab)</samp>](https://github.com/soybeanjs/soybean-admin/commit/726abe4)
- **projects**:
  - 1.0 beta &nbsp;-&nbsp; by @honghuangdc [<samp>(e918a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e918a2c)
  - support Vite5 &nbsp;-&nbsp; by @honghuangdc [<samp>(96e4a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/96e4aff)
  - @sa/axios: createRequest, createFlatRequest, createHookRequest &nbsp;-&nbsp; by @honghuangdc [<samp>(bac16)</samp>](https://github.com/soybeanjs/soybean-admin/commit/bac1632)
  - add app loading &nbsp;-&nbsp; by @honghuangdc [<samp>(c6545)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c65451b)
  - add copyright, unocss shortcut: card-wrapper, update package.json &nbsp;-&nbsp; by @honghuangdc [<samp>(affcc)</samp>](https://github.com/soybeanjs/soybean-admin/commit/affcc26)
  - add page: about &nbsp;-&nbsp; by @honghuangdc [<samp>(4955f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4955f1a)
  - add custom route exception &nbsp;-&nbsp; by @honghuangdc [<samp>(b43c9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b43c925)
  - filter tabs which are not in routes &nbsp;-&nbsp; by @honghuangdc [<samp>(f59f3)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f59f348)
  - packages/scripts: add command changelog,release &nbsp;-&nbsp; by @honghuangdc [<samp>(dafb6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/dafb6fa)
  - add script: gen-route &nbsp;-&nbsp; by @honghuangdc [<samp>(697c1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/697c1b6)
  - @sa/axios: add qs stringify for params &nbsp;-&nbsp; by @honghuangdc [<samp>(2400c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2400c02)
  - page home & perf useEcharts &nbsp;-&nbsp; by @honghuangdc [<samp>(62e4d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/62e4da0)
  - finish page home &nbsp;-&nbsp; by @honghuangdc [<samp>(7bd1e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7bd1e47)
  - add page function_tab &nbsp;-&nbsp; by @honghuangdc [<samp>(6ff86)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6ff86e7)
  - page manage_role &nbsp;-&nbsp; by @honghuangdc [<samp>(237c6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/237c6d2)
  - page manage_user &nbsp;-&nbsp; by @honghuangdc [<samp>(8a170)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8a170ee)
  - page manage_menu &nbsp;-&nbsp; by @honghuangdc [<samp>(87d65)</samp>](https://github.com/soybeanjs/soybean-admin/commit/87d65d3)
  - page manage_menu operateDrawer &nbsp;-&nbsp; by @honghuangdc [<samp>(db17c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/db17c91)
  - Add type to TabRoute: matched &nbsp;-&nbsp; by @Azir-11 [<samp>(2d102)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2d102a0)
  - support directory menu hide all child menus. fixed #325 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/325 [<samp>(7256a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7256ad4)
  - mock manage list data with pagination &nbsp;-&nbsp; by @honghuangdc [<samp>(1a6be)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1a6be00)
  - globalSearch add i18n &nbsp;-&nbsp; by **燕博文** [<samp>(0126d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0126da4)
  - Add route meta parameter:fixedQuery &nbsp;-&nbsp; by @Azir-11 [<samp>(874aa)</samp>](https://github.com/soybeanjs/soybean-admin/commit/874aaca)
  - update &nbsp;-&nbsp; by @honghuangdc [<samp>(4158a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4158a72)
  - change borderRadius to 6px of naiveUI &nbsp;-&nbsp; by @honghuangdc [<samp>(49558)</samp>](https://github.com/soybeanjs/soybean-admin/commit/49558ca)
  - pef manage role &nbsp;-&nbsp; by @honghuangdc [<samp>(18709)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1870981)
  - login page: code-login &nbsp;-&nbsp; by @honghuangdc [<samp>(c91dd)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c91dd28)
  - login page: register &nbsp;-&nbsp; by @honghuangdc [<samp>(1ed33)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1ed33dc)
  - add request refresh token & logout &nbsp;-&nbsp; by @honghuangdc [<samp>(11a6a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/11a6a3b)
  - add request exception example page &nbsp;-&nbsp; by @honghuangdc [<samp>(41e8b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/41e8bc4)
  - add auth example &nbsp;-&nbsp; by @honghuangdc [<samp>(c11d5)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c11d56d)
- **router**:
  - add sortRoutesByOrder function &nbsp;-&nbsp; by @Azir-11 [<samp>(0cf09)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0cf09ba)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**:
  - fix tooltip zIndex of ButtonIcon &nbsp;-&nbsp; by @honghuangdc [<samp>(99097)</samp>](https://github.com/soybeanjs/soybean-admin/commit/99097b4)
  - supplement the `NaiveUI` type &nbsp;-&nbsp; by **tnt group** [<samp>(ccc2b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ccc2b67)
  - fix homeTab closeRight and disable colseLeft &nbsp;-&nbsp; by **~li** [<samp>(d28bf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d28bf52)
- **hooks**:
  - Fix Naive Pagination's outdated API &nbsp;-&nbsp; by **tnt group** [<samp>(37436)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3743612)
- **projects**:
  - 修复路由命名为包含关系时导致导航数据出错的问题 &nbsp;-&nbsp; by @Particaly [<samp>(76636)</samp>](https://github.com/soybeanjs/soybean-admin/commit/766369f)
  - rename zh-ch &nbsp;-&nbsp; by @honghuangdc [<samp>(a8a77)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a8a77ea)
  - Fix welcome notification not closing &nbsp;-&nbsp; by @Azir-11 [<samp>(748cf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/748cfa2)
  - fix i18n vscode settings &nbsp;-&nbsp; by @honghuangdc [<samp>(fbf4c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/fbf4cc4)
  - add duration of login success notification &nbsp;-&nbsp; by @honghuangdc [<samp>(1335d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1335d47)
  - fix menu indent &nbsp;-&nbsp; by @honghuangdc [<samp>(87143)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8714317)
  - fix theme mode segment &nbsp;-&nbsp; by @honghuangdc [<samp>(2372d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2372dc9)
  - fix app loading theme color &nbsp;-&nbsp; by @honghuangdc [<samp>(0ba19)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0ba19d5)
  - fix page about style in mobile &nbsp;-&nbsp; by @honghuangdc [<samp>(8b6de)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8b6de48)
  - fix themeDrawer darkMode segement &nbsp;-&nbsp; by @honghuangdc [<samp>(1b5ca)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1b5caa0)
  - fix themeDrawer copy &nbsp;-&nbsp; by @honghuangdc [<samp>(b3779)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b3779a6)
  - remove space in tab content &nbsp;-&nbsp; by @honghuangdc [<samp>(4aae6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4aae6a5)
  - fix horizontal menu &nbsp;-&nbsp; by @honghuangdc [<samp>(d886e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d886e50)
  - perf card style &nbsp;-&nbsp; by @honghuangdc [<samp>(c1afb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c1afb9d)
  - fix manage_user title &nbsp;-&nbsp; by @honghuangdc [<samp>(7770b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7770b37)
  - default proxy prefix &nbsp;-&nbsp; by @smileluck [<samp>(da246)</samp>](https://github.com/soybeanjs/soybean-admin/commit/da24642)
  - fix request msg &nbsp;-&nbsp; by @honghuangdc [<samp>(ae6b6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ae6b613)
  - Fix the issue of tab error displaying parent localIcon &nbsp;-&nbsp; by @Azir-11 [<samp>(a9c98)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a9c98d9)
  - The matched value of TabRoute should be optional &nbsp;-&nbsp; by @Azir-11 [<samp>(e6fed)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e6fed1f)
  - fix build [unocss]: build failed to load icon "close", fixed #319 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/319 [<samp>(c18d8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c18d82f)
  - fix resolve alias &nbsp;-&nbsp; by @honghuangdc [<samp>(3bdcb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3bdcbc7)
  - Missing default value for tab icon &nbsp;-&nbsp; by @Azir-11 [<samp>(72a46)</samp>](https://github.com/soybeanjs/soybean-admin/commit/72a4679)
  - add route icon: fucntion_hide-child &nbsp;-&nbsp; by @honghuangdc [<samp>(0a3ef)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0a3efe3)
  - fix table x-scroll. fixed #324 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/324 [<samp>(c7e2c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c7e2c55)
  - Fix the logic of root route redirection to home &nbsp;-&nbsp; by **恕瑞玛的皇帝** [<samp>(0123c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0123c37)
  - Fix homepage mount error under dynamic routing &nbsp;-&nbsp; by **恕瑞玛的皇帝** [<samp>(9cf2a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9cf2a51)
  - fix repeat home tab &nbsp;-&nbsp; by @honghuangdc [<samp>(bccd6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/bccd6cb)
  - fix proxy config &nbsp;-&nbsp; by @honghuangdc [<samp>(c8019)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c8019c4)
  - fix proxy config &nbsp;-&nbsp; by @honghuangdc [<samp>(ffc95)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ffc95d2)
  - fix table row-key ts type &nbsp;-&nbsp; by @honghuangdc [<samp>(0cc8f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0cc8f05)
  - fix class name conflict with unocss icon &nbsp;-&nbsp; by @honghuangdc [<samp>(455e4)</samp>](https://github.com/soybeanjs/soybean-admin/commit/455e48f)
  - fix repeat routes &nbsp;-&nbsp; by @honghuangdc [<samp>(2c543)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2c543f1)
  - fix route init &nbsp;-&nbsp; by @honghuangdc [<samp>(23a40)</samp>](https://github.com/soybeanjs/soybean-admin/commit/23a4098)
  - fix pin-toggler toolTip zIndex &nbsp;-&nbsp; by @honghuangdc [<samp>(f89e6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f89e6c0)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- **components**:
  - Optimize internationalized menu search code &nbsp;-&nbsp; by **燕博文** [<samp>(8c1ef)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8c1ef4b)
  - Optimize menu search code &nbsp;-&nbsp; by **燕博文** [<samp>(296a2)</samp>](https://github.com/soybeanjs/soybean-admin/commit/296a2d2)
  - perf count-to &nbsp;-&nbsp; by @honghuangdc [<samp>(b2c61)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b2c61f0)
  - components  name is converted to uppercase &nbsp;-&nbsp; by **燕博文** [<samp>(04aa1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/04aa10b)
  - perf global-search &nbsp;-&nbsp; by @honghuangdc [<samp>(72745)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7274522)
- **projects**:
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(8081e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8081e19)
  - env config &nbsp;-&nbsp; by @honghuangdc [<samp>(1bac3)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1bac3b7)
  - add detailed annotations for route role &nbsp;-&nbsp; by @honghuangdc [<samp>(f6bab)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f6bab0c)
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(5c49d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5c49d24)
  - remove useless file &nbsp;-&nbsp; by @honghuangdc [<samp>(c624f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c624f32)
  - remove @soybeanjs/cli &nbsp;-&nbsp; by @honghuangdc [<samp>(41349)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4134955)
  - echarts loading style &nbsp;-&nbsp; by @honghuangdc [<samp>(456c3)</samp>](https://github.com/soybeanjs/soybean-admin/commit/456c318)
  - perf page manage_role, useTable &nbsp;-&nbsp; by @honghuangdc [<samp>(39aa7)</samp>](https://github.com/soybeanjs/soybean-admin/commit/39aa7aa)
  - perf table columns style &nbsp;-&nbsp; by @honghuangdc [<samp>(babdb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/babdb5d)
  - perf page manage_menu style &nbsp;-&nbsp; by @honghuangdc [<samp>(0aa75)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0aa75c0)
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(7fa87)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7fa87f5)
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(05db8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/05db8c0)
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(dc24a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/dc24a36)
  - perf manage page style &nbsp;-&nbsp; by @honghuangdc [<samp>(779ba)</samp>](https://github.com/soybeanjs/soybean-admin/commit/779ba4e)
  - perf manage menu &nbsp;-&nbsp; by @honghuangdc [<samp>(71f2c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/71f2c55)
  - manage menu: add transform to component &nbsp;-&nbsp; by @honghuangdc [<samp>(0abbf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0abbfa5)
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(a0bad)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a0bad57)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - remove plugin-web-update-notification &nbsp;-&nbsp; by @honghuangdc [<samp>(f6c6d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f6c6dbd)
  - fix conflict with locale file &nbsp;-&nbsp; by @honghuangdc [<samp>(3346b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3346bcd)
  - refactor app-loading &nbsp;-&nbsp; by @honghuangdc [<samp>(b4f3d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b4f3dd2)
  - use naive-ui color-picker &nbsp;-&nbsp; by @honghuangdc [<samp>(b5551)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b5551d6)
  - perf page home &nbsp;-&nbsp; by @honghuangdc [<samp>(4c61c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4c61c6f)
  - login components => modules &nbsp;-&nbsp; by @honghuangdc [<samp>(59bec)</samp>](https://github.com/soybeanjs/soybean-admin/commit/59bec2d)
  - perf page function_tab &nbsp;-&nbsp; by @honghuangdc [<samp>(b5477)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b5477e8)
  - update mock api &nbsp;-&nbsp; by @honghuangdc [<samp>(27241)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2724169)
  - page manage_role: extract module &nbsp;-&nbsp; by @honghuangdc [<samp>(0e9e2)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0e9e2e1)
  - perf page manage_role &nbsp;-&nbsp; by @honghuangdc [<samp>(a19f8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a19f895)
  - manage_route => manage_menu &nbsp;-&nbsp; by @honghuangdc [<samp>(f8467)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f8467ce)
  - refactor service env config &nbsp;-&nbsp; by @honghuangdc [<samp>(43193)</samp>](https://github.com/soybeanjs/soybean-admin/commit/43193e2)
  - refactor unocss shortcuts: wh-full => size-full &nbsp;-&nbsp; by @honghuangdc [<samp>(b4c00)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b4c00ce)
  - use enquirer replace prompts &nbsp;-&nbsp; by @honghuangdc [<samp>(b546f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b546ff8)
  - refactor useTable &nbsp;-&nbsp; by @honghuangdc [<samp>(c3efa)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c3efa1b)
  - finish refactor useTable &nbsp;-&nbsp; by @honghuangdc [<samp>(86301)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8630175)
  - finish refactor useTable and apply &nbsp;-&nbsp; by @honghuangdc [<samp>(3fd15)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3fd15e5)
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(f91ef)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f91ef30)
  - new route guard &nbsp;-&nbsp; by @honghuangdc [<samp>(37d20)</samp>](https://github.com/soybeanjs/soybean-admin/commit/37d20b8)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(78364)</samp>](https://github.com/soybeanjs/soybean-admin/commit/783648f)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(1ea48)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1ea4817)
  - add README &nbsp;-&nbsp; by @honghuangdc [<samp>(2371b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2371ba8)
  - update README &nbsp;-&nbsp; by @honghuangdc [<samp>(d16a9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d16a9d5)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(6a771)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6a771ea)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(57b6d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/57b6d8a)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(b30c0)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b30c035)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(c260f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c260fe2)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(03c42)</samp>](https://github.com/soybeanjs/soybean-admin/commit/03c42aa)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(0fae9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0fae993)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(4e4d2)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4e4d2de)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(86b44)</samp>](https://github.com/soybeanjs/soybean-admin/commit/86b445c)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(e2085)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e2085e0)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(6ea9b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6ea9b85)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(ef4af)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ef4af79)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(41830)</samp>](https://github.com/soybeanjs/soybean-admin/commit/418302a)
  - add CHANGELOG.md &nbsp;-&nbsp; by @honghuangdc [<samp>(46b61)</samp>](https://github.com/soybeanjs/soybean-admin/commit/46b6156)
  - add communication &nbsp;-&nbsp; by @honghuangdc [<samp>(8c7ea)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8c7ea23)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(07d8d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/07d8d25)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(1a707)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1a7070f)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(f69e1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f69e152)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(3eaf0)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3eaf05b)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(36fe1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/36fe1da)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(55342)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5534294)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(f1b86)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f1b86cc)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(840e7)</samp>](https://github.com/soybeanjs/soybean-admin/commit/840e7f9)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(6114b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6114b9f)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(9cc7e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9cc7ee5)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(9c4ba)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9c4ba66)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(fb3b9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/fb3b94b)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(14aa8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/14aa856)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(02d4b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/02d4b0a)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(b2ee9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b2ee9ee)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(0fee1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0fee104)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(c0a65)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c0a65a1)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(6b513)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6b5132c)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(82b53)</samp>](https://github.com/soybeanjs/soybean-admin/commit/82b53d7)
- **project**:
  - delete src/locales/lang/zh-CN.ts &nbsp;-&nbsp; by @honghuangdc [<samp>(377db)</samp>](https://github.com/soybeanjs/soybean-admin/commit/377db82)
- **projects**:
  - use eslint flat config & update config &nbsp;-&nbsp; by @honghuangdc [<samp>(a176d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a176dc4)
  - update @sa/scripts &nbsp;-&nbsp; by @honghuangdc [<samp>(d7785)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d778560)
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(55f76)</samp>](https://github.com/soybeanjs/soybean-admin/commit/55f7638)
  - update eslint config &nbsp;-&nbsp; by @honghuangdc [<samp>(5023f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5023f37)
  - lock deps versions &nbsp;-&nbsp; by @honghuangdc [<samp>(a24f9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a24f963)
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(ea02b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ea02b23)
  - remove @simonwep/pickr &nbsp;-&nbsp; by @honghuangdc [<samp>(502a4)</samp>](https://github.com/soybeanjs/soybean-admin/commit/502a4d2)
  - remove soybean.svg &nbsp;-&nbsp; by @honghuangdc [<samp>(4031f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4031faf)
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(adec0)</samp>](https://github.com/soybeanjs/soybean-admin/commit/adec0d7)
  - update deps & fix keep-alive &nbsp;-&nbsp; by @honghuangdc [<samp>(13001)</samp>](https://github.com/soybeanjs/soybean-admin/commit/13001bc)
  - update @elegant-router/vue, fix inject name in windows &nbsp;-&nbsp; by @honghuangdc [<samp>(0b56e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0b56e44)
  - add dev and build command with service env &nbsp;-&nbsp; by @honghuangdc [<samp>(ebb15)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ebb1548)
  - update deps & remove packages docs &nbsp;-&nbsp; by @honghuangdc [<samp>(57963)</samp>](https://github.com/soybeanjs/soybean-admin/commit/579636b)
  - update pnpm-lock.yaml &nbsp;-&nbsp; by @honghuangdc [<samp>(147f6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/147f60d)
  - update repository url &nbsp;-&nbsp; by @honghuangdc [<samp>(806a1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/806a1cb)
  - update deps & update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(9772a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9772aec)
  - add unocss eslint config &nbsp;-&nbsp; by @honghuangdc [<samp>(40635)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4063529)
  - update launch.json &nbsp;-&nbsp; by @honghuangdc [<samp>(3db82)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3db82ac)
  - update vscode extensions.json &nbsp;-&nbsp; by @honghuangdc [<samp>(4e29a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4e29aca)
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(7065f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7065f6f)
  - update deps & fix eslint vue rule &nbsp;-&nbsp; by @honghuangdc [<samp>(8143b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8143b00)
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(6ad51)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6ad51e9)
  - add .gitattributes &nbsp;-&nbsp; by @honghuangdc [<samp>(c0009)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c000920)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **components**:
  - Uniform icon size for header &nbsp;-&nbsp; by @Azir-11 [<samp>(b37c1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b37c1e9)
- **projects**:
  - format code &nbsp;-&nbsp; by @honghuangdc [<samp>(a7481)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a748166)
  - update theme mode segment height &nbsp;-&nbsp; by @honghuangdc [<samp>(4d846)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4d8469e)
  - fix tooltip zIndex of ButtonIcon &nbsp;-&nbsp; by @honghuangdc [<samp>(db747)</samp>](https://github.com/soybeanjs/soybean-admin/commit/db747c4)
  - sort defineProps, defineEmits with TS type &nbsp;-&nbsp; by @honghuangdc [<samp>(123fd)</samp>](https://github.com/soybeanjs/soybean-admin/commit/123fd4f)

### &nbsp;&nbsp;&nbsp;🤖 CI

- **projects**:
  - add github actions config &nbsp;-&nbsp; by @honghuangdc [<samp>(4cb17)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4cb17c7)
  - update release.yml &nbsp;-&nbsp; by @honghuangdc [<samp>(7b298)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7b298c6)
  - add issue template &nbsp;-&nbsp; by @honghuangdc [<samp>(06e20)</samp>](https://github.com/soybeanjs/soybean-admin/commit/06e204a)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;[![smileluck](https://github.com/smileluck.png?size=48)](https://github.com/smileluck)&nbsp;&nbsp;[![Particaly](https://github.com/Particaly.png?size=48)](https://github.com/Particaly)&nbsp;&nbsp;
[~li](mailto:miciili-02@outlook.com),&nbsp;[Azir-11](mailto:2075125282@qq.com),&nbsp;[燕博文](mailto:349952469@qq.com),&nbsp;[tnt group](mailto:dodu@live.cn),&nbsp;[Kori](mailto:kexin@korix.top),&nbsp;

## [v1.0.0-beta.3](https://github.com/soybeanjs/soybean-admin/compare/v1.0.0-beta.2...v1.0.0-beta.3) (2024-03-31)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(f69e1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f69e152)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(82b53)</samp>](https://github.com/soybeanjs/soybean-admin/commit/82b53d7)
- **projects**: add .gitattributes &nbsp;-&nbsp; by @honghuangdc [<samp>(c0009)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c000920)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v1.0.0-beta.2](https://github.com/soybeanjs/soybean-admin/compare/v1.0.0-beta.1...v1.0.0-beta.2) (2024-03-27)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**: fix pin-toggler toolTip zIndex &nbsp;-&nbsp; by @honghuangdc [<samp>(f89e6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f89e6c0)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- **projects**: perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(a0bad)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a0bad57)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - add communication &nbsp;-&nbsp; by @honghuangdc [<samp>(8c7ea)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8c7ea23)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(07d8d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/07d8d25)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(1a707)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1a7070f)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(6b513)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6b5132c)

### &nbsp;&nbsp;&nbsp;🤖 CI

- **projects**:
  - update release.yml &nbsp;-&nbsp; by @honghuangdc [<samp>(7b298)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7b298c6)
  - add issue template &nbsp;-&nbsp; by @honghuangdc [<samp>(06e20)</samp>](https://github.com/soybeanjs/soybean-admin/commit/06e204a)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v1.0.0-beta.1](https://github.com/soybeanjs/soybean-admin/compare/v0.10.4...v1.0.0-beta.1) (2024-03-25)

### &nbsp;&nbsp;&nbsp;🚀 Features

- internationalized menu search &nbsp;-&nbsp; by **Kori** [<samp>(9e115)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9e115da)
- **components**:
  - enhance the custom strength of the 'TableHeaderOperation' component &nbsp;-&nbsp; by **tnt group** [<samp>(fdf64)</samp>](https://github.com/soybeanjs/soybean-admin/commit/fdf64f7)
  - add GlobalSearch components &nbsp;-&nbsp; by **燕博文** [<samp>(9ea87)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9ea8789)
- **hooks**:
  - add use-echarts &nbsp;-&nbsp; by @honghuangdc [<samp>(726ab)</samp>](https://github.com/soybeanjs/soybean-admin/commit/726abe4)
- **projects**:
  - 1.0 beta &nbsp;-&nbsp; by @honghuangdc [<samp>(e918a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e918a2c)
  - support Vite5 &nbsp;-&nbsp; by @honghuangdc [<samp>(96e4a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/96e4aff)
  - @sa/axios: createRequest, createFlatRequest, createHookRequest &nbsp;-&nbsp; by @honghuangdc [<samp>(bac16)</samp>](https://github.com/soybeanjs/soybean-admin/commit/bac1632)
  - add app loading &nbsp;-&nbsp; by @honghuangdc [<samp>(c6545)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c65451b)
  - add copyright, unocss shortcut: card-wrapper, update package.json &nbsp;-&nbsp; by @honghuangdc [<samp>(affcc)</samp>](https://github.com/soybeanjs/soybean-admin/commit/affcc26)
  - add page: about &nbsp;-&nbsp; by @honghuangdc [<samp>(4955f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4955f1a)
  - add custom route exception &nbsp;-&nbsp; by @honghuangdc [<samp>(b43c9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b43c925)
  - filter tabs which are not in routes &nbsp;-&nbsp; by @honghuangdc [<samp>(f59f3)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f59f348)
  - packages/scripts: add command changelog,release &nbsp;-&nbsp; by @honghuangdc [<samp>(dafb6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/dafb6fa)
  - add script: gen-route &nbsp;-&nbsp; by @honghuangdc [<samp>(697c1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/697c1b6)
  - @sa/axios: add qs stringify for params &nbsp;-&nbsp; by @honghuangdc [<samp>(2400c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2400c02)
  - page home & perf useEcharts &nbsp;-&nbsp; by @honghuangdc [<samp>(62e4d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/62e4da0)
  - finish page home &nbsp;-&nbsp; by @honghuangdc [<samp>(7bd1e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7bd1e47)
  - add page function_tab &nbsp;-&nbsp; by @honghuangdc [<samp>(6ff86)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6ff86e7)
  - page manage_role &nbsp;-&nbsp; by @honghuangdc [<samp>(237c6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/237c6d2)
  - page manage_user &nbsp;-&nbsp; by @honghuangdc [<samp>(8a170)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8a170ee)
  - page manage_menu &nbsp;-&nbsp; by @honghuangdc [<samp>(87d65)</samp>](https://github.com/soybeanjs/soybean-admin/commit/87d65d3)
  - page manage_menu operateDrawer &nbsp;-&nbsp; by @honghuangdc [<samp>(db17c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/db17c91)
  - Add type to TabRoute: matched &nbsp;-&nbsp; by @Azir-11 [<samp>(2d102)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2d102a0)
  - support directory menu hide all child menus. fixed #325 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/325 [<samp>(7256a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7256ad4)
  - mock manage list data with pagination &nbsp;-&nbsp; by @honghuangdc [<samp>(1a6be)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1a6be00)
  - globalSearch add i18n &nbsp;-&nbsp; by **燕博文** [<samp>(0126d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0126da4)
  - Add route meta parameter:fixedQuery &nbsp;-&nbsp; by @Azir-11 [<samp>(874aa)</samp>](https://github.com/soybeanjs/soybean-admin/commit/874aaca)
  - update &nbsp;-&nbsp; by @honghuangdc [<samp>(4158a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4158a72)
  - change borderRadius to 6px of naiveUI &nbsp;-&nbsp; by @honghuangdc [<samp>(49558)</samp>](https://github.com/soybeanjs/soybean-admin/commit/49558ca)
  - pef manage role &nbsp;-&nbsp; by @honghuangdc [<samp>(18709)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1870981)
  - login page: code-login &nbsp;-&nbsp; by @honghuangdc [<samp>(c91dd)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c91dd28)
  - login page: register &nbsp;-&nbsp; by @honghuangdc [<samp>(1ed33)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1ed33dc)
  - add request refresh token & logout &nbsp;-&nbsp; by @honghuangdc [<samp>(11a6a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/11a6a3b)
  - add request exception example page &nbsp;-&nbsp; by @honghuangdc [<samp>(41e8b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/41e8bc4)
  - add auth example &nbsp;-&nbsp; by @honghuangdc [<samp>(c11d5)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c11d56d)
- **router**:
  - add sortRoutesByOrder function &nbsp;-&nbsp; by @Azir-11 [<samp>(0cf09)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0cf09ba)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**:
  - fix tooltip zIndex of ButtonIcon &nbsp;-&nbsp; by @honghuangdc [<samp>(99097)</samp>](https://github.com/soybeanjs/soybean-admin/commit/99097b4)
  - supplement the `NaiveUI` type &nbsp;-&nbsp; by **tnt group** [<samp>(ccc2b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ccc2b67)
  - fix homeTab closeRight and disable colseLeft &nbsp;-&nbsp; by **~li** [<samp>(d28bf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d28bf52)
- **hooks**:
  - Fix Naive Pagination's outdated API &nbsp;-&nbsp; by **tnt group** [<samp>(37436)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3743612)
- **projects**:
  - 修复路由命名为包含关系时导致导航数据出错的问题 &nbsp;-&nbsp; by **pantao** [<samp>(76636)</samp>](https://github.com/soybeanjs/soybean-admin/commit/766369f)
  - rename zh-ch &nbsp;-&nbsp; by @honghuangdc [<samp>(a8a77)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a8a77ea)
  - Fix welcome notification not closing &nbsp;-&nbsp; by @Azir-11 [<samp>(748cf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/748cfa2)
  - fix i18n vscode settings &nbsp;-&nbsp; by @honghuangdc [<samp>(fbf4c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/fbf4cc4)
  - add duration of login success notification &nbsp;-&nbsp; by @honghuangdc [<samp>(1335d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1335d47)
  - fix menu indent &nbsp;-&nbsp; by @honghuangdc [<samp>(87143)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8714317)
  - fix theme mode segment &nbsp;-&nbsp; by @honghuangdc [<samp>(2372d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2372dc9)
  - fix app loading theme color &nbsp;-&nbsp; by @honghuangdc [<samp>(0ba19)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0ba19d5)
  - fix page about style in mobile &nbsp;-&nbsp; by @honghuangdc [<samp>(8b6de)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8b6de48)
  - fix themeDrawer darkMode segement &nbsp;-&nbsp; by @honghuangdc [<samp>(1b5ca)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1b5caa0)
  - fix themeDrawer copy &nbsp;-&nbsp; by @honghuangdc [<samp>(b3779)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b3779a6)
  - remove space in tab content &nbsp;-&nbsp; by @honghuangdc [<samp>(4aae6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4aae6a5)
  - fix horizontal menu &nbsp;-&nbsp; by @honghuangdc [<samp>(d886e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d886e50)
  - perf card style &nbsp;-&nbsp; by @honghuangdc [<samp>(c1afb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c1afb9d)
  - fix manage_user title &nbsp;-&nbsp; by @honghuangdc [<samp>(7770b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7770b37)
  - default proxy prefix &nbsp;-&nbsp; by @smileluck [<samp>(da246)</samp>](https://github.com/soybeanjs/soybean-admin/commit/da24642)
  - fix request msg &nbsp;-&nbsp; by @honghuangdc [<samp>(ae6b6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ae6b613)
  - Fix the issue of tab error displaying parent localIcon &nbsp;-&nbsp; by @Azir-11 [<samp>(a9c98)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a9c98d9)
  - The matched value of TabRoute should be optional &nbsp;-&nbsp; by @Azir-11 [<samp>(e6fed)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e6fed1f)
  - fix build [unocss]: build failed to load icon "close", fixed #319 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/319 [<samp>(c18d8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c18d82f)
  - fix resolve alias &nbsp;-&nbsp; by @honghuangdc [<samp>(3bdcb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3bdcbc7)
  - Missing default value for tab icon &nbsp;-&nbsp; by @Azir-11 [<samp>(72a46)</samp>](https://github.com/soybeanjs/soybean-admin/commit/72a4679)
  - add route icon: fucntion_hide-child &nbsp;-&nbsp; by @honghuangdc [<samp>(0a3ef)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0a3efe3)
  - fix table x-scroll. fixed #324 &nbsp;-&nbsp; by @honghuangdc in https://github.com/soybeanjs/soybean-admin/issues/324 [<samp>(c7e2c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c7e2c55)
  - Fix the logic of root route redirection to home &nbsp;-&nbsp; by **恕瑞玛的皇帝** [<samp>(0123c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0123c37)
  - Fix homepage mount error under dynamic routing &nbsp;-&nbsp; by **恕瑞玛的皇帝** [<samp>(9cf2a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9cf2a51)
  - fix repeat home tab &nbsp;-&nbsp; by @honghuangdc [<samp>(bccd6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/bccd6cb)
  - fix proxy config &nbsp;-&nbsp; by @honghuangdc [<samp>(c8019)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c8019c4)
  - fix proxy config &nbsp;-&nbsp; by @honghuangdc [<samp>(ffc95)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ffc95d2)
  - fix table row-key ts type &nbsp;-&nbsp; by @honghuangdc [<samp>(0cc8f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0cc8f05)
  - fix class name conflict with unocss icon &nbsp;-&nbsp; by @honghuangdc [<samp>(455e4)</samp>](https://github.com/soybeanjs/soybean-admin/commit/455e48f)
  - fix repeat routes &nbsp;-&nbsp; by @honghuangdc [<samp>(2c543)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2c543f1)
  - fix route init &nbsp;-&nbsp; by @honghuangdc [<samp>(23a40)</samp>](https://github.com/soybeanjs/soybean-admin/commit/23a4098)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- **components**:
  - Optimize internationalized menu search code &nbsp;-&nbsp; by **燕博文** [<samp>(8c1ef)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8c1ef4b)
  - Optimize menu search code &nbsp;-&nbsp; by **燕博文** [<samp>(296a2)</samp>](https://github.com/soybeanjs/soybean-admin/commit/296a2d2)
  - perf count-to &nbsp;-&nbsp; by @honghuangdc [<samp>(b2c61)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b2c61f0)
  - components  name is converted to uppercase &nbsp;-&nbsp; by **燕博文** [<samp>(04aa1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/04aa10b)
  - perf global-search &nbsp;-&nbsp; by @honghuangdc [<samp>(72745)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7274522)
- **projects**:
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(8081e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8081e19)
  - env config &nbsp;-&nbsp; by @honghuangdc [<samp>(1bac3)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1bac3b7)
  - add detailed annotations for route role &nbsp;-&nbsp; by @honghuangdc [<samp>(f6bab)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f6bab0c)
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(5c49d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5c49d24)
  - remove useless file &nbsp;-&nbsp; by @honghuangdc [<samp>(c624f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c624f32)
  - remove @soybeanjs/cli &nbsp;-&nbsp; by @honghuangdc [<samp>(41349)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4134955)
  - echarts loading style &nbsp;-&nbsp; by @honghuangdc [<samp>(456c3)</samp>](https://github.com/soybeanjs/soybean-admin/commit/456c318)
  - perf page manage_role, useTable &nbsp;-&nbsp; by @honghuangdc [<samp>(39aa7)</samp>](https://github.com/soybeanjs/soybean-admin/commit/39aa7aa)
  - perf table columns style &nbsp;-&nbsp; by @honghuangdc [<samp>(babdb)</samp>](https://github.com/soybeanjs/soybean-admin/commit/babdb5d)
  - perf page manage_menu style &nbsp;-&nbsp; by @honghuangdc [<samp>(0aa75)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0aa75c0)
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(7fa87)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7fa87f5)
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(05db8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/05db8c0)
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(dc24a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/dc24a36)
  - perf manage page style &nbsp;-&nbsp; by @honghuangdc [<samp>(779ba)</samp>](https://github.com/soybeanjs/soybean-admin/commit/779ba4e)
  - perf manage menu &nbsp;-&nbsp; by @honghuangdc [<samp>(71f2c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/71f2c55)
  - manage menu: add transform to component &nbsp;-&nbsp; by @honghuangdc [<samp>(0abbf)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0abbfa5)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - remove plugin-web-update-notification &nbsp;-&nbsp; by @honghuangdc [<samp>(f6c6d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f6c6dbd)
  - fix conflict with locale file &nbsp;-&nbsp; by @honghuangdc [<samp>(3346b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3346bcd)
  - refactor app-loading &nbsp;-&nbsp; by @honghuangdc [<samp>(b4f3d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b4f3dd2)
  - use naive-ui color-picker &nbsp;-&nbsp; by @honghuangdc [<samp>(b5551)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b5551d6)
  - perf page home &nbsp;-&nbsp; by @honghuangdc [<samp>(4c61c)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4c61c6f)
  - login components => modules &nbsp;-&nbsp; by @honghuangdc [<samp>(59bec)</samp>](https://github.com/soybeanjs/soybean-admin/commit/59bec2d)
  - perf page function_tab &nbsp;-&nbsp; by @honghuangdc [<samp>(b5477)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b5477e8)
  - update mock api &nbsp;-&nbsp; by @honghuangdc [<samp>(27241)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2724169)
  - page manage_role: extract module &nbsp;-&nbsp; by @honghuangdc [<samp>(0e9e2)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0e9e2e1)
  - perf page manage_role &nbsp;-&nbsp; by @honghuangdc [<samp>(a19f8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a19f895)
  - manage_route => manage_menu &nbsp;-&nbsp; by @honghuangdc [<samp>(f8467)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f8467ce)
  - refactor service env config &nbsp;-&nbsp; by @honghuangdc [<samp>(43193)</samp>](https://github.com/soybeanjs/soybean-admin/commit/43193e2)
  - refactor unocss shortcuts: wh-full => size-full &nbsp;-&nbsp; by @honghuangdc [<samp>(b4c00)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b4c00ce)
  - use enquirer replace prompts &nbsp;-&nbsp; by @honghuangdc [<samp>(b546f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b546ff8)
  - refactor useTable &nbsp;-&nbsp; by @honghuangdc [<samp>(c3efa)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c3efa1b)
  - finish refactor useTable &nbsp;-&nbsp; by @honghuangdc [<samp>(86301)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8630175)
  - finish refactor useTable and apply &nbsp;-&nbsp; by @honghuangdc [<samp>(3fd15)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3fd15e5)
  - perf code &nbsp;-&nbsp; by @honghuangdc [<samp>(f91ef)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f91ef30)
  - new route guard &nbsp;-&nbsp; by @honghuangdc [<samp>(37d20)</samp>](https://github.com/soybeanjs/soybean-admin/commit/37d20b8)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(78364)</samp>](https://github.com/soybeanjs/soybean-admin/commit/783648f)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(1ea48)</samp>](https://github.com/soybeanjs/soybean-admin/commit/1ea4817)
  - add README &nbsp;-&nbsp; by @honghuangdc [<samp>(2371b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/2371ba8)
  - update README &nbsp;-&nbsp; by @honghuangdc [<samp>(d16a9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d16a9d5)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(6a771)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6a771ea)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(57b6d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/57b6d8a)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(b30c0)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b30c035)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(c260f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c260fe2)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(03c42)</samp>](https://github.com/soybeanjs/soybean-admin/commit/03c42aa)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(0fae9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0fae993)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(4e4d2)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4e4d2de)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(86b44)</samp>](https://github.com/soybeanjs/soybean-admin/commit/86b445c)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(e2085)</samp>](https://github.com/soybeanjs/soybean-admin/commit/e2085e0)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(6ea9b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6ea9b85)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(ef4af)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ef4af79)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(41830)</samp>](https://github.com/soybeanjs/soybean-admin/commit/418302a)
  - add CHANGELOG.md &nbsp;-&nbsp; by @honghuangdc [<samp>(46b61)</samp>](https://github.com/soybeanjs/soybean-admin/commit/46b6156)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(3eaf0)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3eaf05b)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(36fe1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/36fe1da)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(55342)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5534294)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(f1b86)</samp>](https://github.com/soybeanjs/soybean-admin/commit/f1b86cc)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(840e7)</samp>](https://github.com/soybeanjs/soybean-admin/commit/840e7f9)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(6114b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6114b9f)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(9cc7e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9cc7ee5)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(9c4ba)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9c4ba66)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(fb3b9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/fb3b94b)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(14aa8)</samp>](https://github.com/soybeanjs/soybean-admin/commit/14aa856)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(02d4b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/02d4b0a)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(b2ee9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b2ee9ee)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(0fee1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0fee104)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(c0a65)</samp>](https://github.com/soybeanjs/soybean-admin/commit/c0a65a1)
- **project**:
  - delete src/locales/lang/zh-CN.ts &nbsp;-&nbsp; by @honghuangdc [<samp>(377db)</samp>](https://github.com/soybeanjs/soybean-admin/commit/377db82)
- **projects**:
  - use eslint flat config & update config &nbsp;-&nbsp; by @honghuangdc [<samp>(a176d)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a176dc4)
  - update @sa/scripts &nbsp;-&nbsp; by @honghuangdc [<samp>(d7785)</samp>](https://github.com/soybeanjs/soybean-admin/commit/d778560)
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(55f76)</samp>](https://github.com/soybeanjs/soybean-admin/commit/55f7638)
  - update eslint config &nbsp;-&nbsp; by @honghuangdc [<samp>(5023f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/5023f37)
  - lock deps versions &nbsp;-&nbsp; by @honghuangdc [<samp>(a24f9)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a24f963)
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(ea02b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ea02b23)
  - remove @simonwep/pickr &nbsp;-&nbsp; by @honghuangdc [<samp>(502a4)</samp>](https://github.com/soybeanjs/soybean-admin/commit/502a4d2)
  - remove soybean.svg &nbsp;-&nbsp; by @honghuangdc [<samp>(4031f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4031faf)
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(adec0)</samp>](https://github.com/soybeanjs/soybean-admin/commit/adec0d7)
  - update deps & fix keep-alive &nbsp;-&nbsp; by @honghuangdc [<samp>(13001)</samp>](https://github.com/soybeanjs/soybean-admin/commit/13001bc)
  - update @elegant-router/vue, fix inject name in windows &nbsp;-&nbsp; by @honghuangdc [<samp>(0b56e)</samp>](https://github.com/soybeanjs/soybean-admin/commit/0b56e44)
  - add dev and build command with service env &nbsp;-&nbsp; by @honghuangdc [<samp>(ebb15)</samp>](https://github.com/soybeanjs/soybean-admin/commit/ebb1548)
  - update deps & remove packages docs &nbsp;-&nbsp; by @honghuangdc [<samp>(57963)</samp>](https://github.com/soybeanjs/soybean-admin/commit/579636b)
  - update pnpm-lock.yaml &nbsp;-&nbsp; by @honghuangdc [<samp>(147f6)</samp>](https://github.com/soybeanjs/soybean-admin/commit/147f60d)
  - update repository url &nbsp;-&nbsp; by @honghuangdc [<samp>(806a1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/806a1cb)
  - update deps & update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(9772a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/9772aec)
  - add unocss eslint config &nbsp;-&nbsp; by @honghuangdc [<samp>(40635)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4063529)
  - update launch.json &nbsp;-&nbsp; by @honghuangdc [<samp>(3db82)</samp>](https://github.com/soybeanjs/soybean-admin/commit/3db82ac)
  - update vscode extensions.json &nbsp;-&nbsp; by @honghuangdc [<samp>(4e29a)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4e29aca)
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(7065f)</samp>](https://github.com/soybeanjs/soybean-admin/commit/7065f6f)
  - update deps & fix eslint vue rule &nbsp;-&nbsp; by @honghuangdc [<samp>(8143b)</samp>](https://github.com/soybeanjs/soybean-admin/commit/8143b00)
  - update pnpm version &nbsp;-&nbsp; by @honghuangdc [<samp>(6ad51)</samp>](https://github.com/soybeanjs/soybean-admin/commit/6ad51e9)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **components**:
  - Uniform icon size for header &nbsp;-&nbsp; by @Azir-11 [<samp>(b37c1)</samp>](https://github.com/soybeanjs/soybean-admin/commit/b37c1e9)
- **projects**:
  - format code &nbsp;-&nbsp; by @honghuangdc [<samp>(a7481)</samp>](https://github.com/soybeanjs/soybean-admin/commit/a748166)
  - update theme mode segment height &nbsp;-&nbsp; by @honghuangdc [<samp>(4d846)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4d8469e)
  - fix tooltip zIndex of ButtonIcon &nbsp;-&nbsp; by @honghuangdc [<samp>(db747)</samp>](https://github.com/soybeanjs/soybean-admin/commit/db747c4)
  - sort defineProps, defineEmits with TS type &nbsp;-&nbsp; by @honghuangdc [<samp>(123fd)</samp>](https://github.com/soybeanjs/soybean-admin/commit/123fd4f)

### &nbsp;&nbsp;&nbsp;🤖 CI

- **projects**: add github actions config &nbsp;-&nbsp; by @honghuangdc [<samp>(4cb17)</samp>](https://github.com/soybeanjs/soybean-admin/commit/4cb17c7)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![Azir-11](https://github.com/Azir-11.png?size=48)](https://github.com/Azir-11)&nbsp;&nbsp;[![smileluck](https://github.com/smileluck.png?size=48)](https://github.com/smileluck)&nbsp;&nbsp;[![Particaly](https://github.com/Particaly.png?size=48)](https://github.com/Particaly)&nbsp;&nbsp;
[~li](mailto:miciili-02@outlook.com),&nbsp;[Azir-11](mailto:2075125282@qq.com),&nbsp;[燕博文](mailto:349952469@qq.com),&nbsp;[tnt group](mailto:dodu@live.cn),&nbsp;[Kori](mailto:kexin@korix.top),&nbsp;

## [v0.10.4](https://github.com/honghuangdc/soybean-admin/compare/v0.10.3...v0.10.4) (23-09-20)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **auth**:
  - 防止多次刷新token &nbsp;-&nbsp; by @eAliwei [<samp>(0eaa3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0eaa327)
- **hooks**:
  - add useHookTable &nbsp;-&nbsp; by @honghuangdc [<samp>(b3ae7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b3ae760)
- **projects**:
  - add websocket demo &nbsp;-&nbsp; by @honghuangdc [<samp>(af53e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/af53ec7)
  - add switch for customize darkmode transition &nbsp;-&nbsp; by @honghuangdc [<samp>(6e0cc)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6e0cce4)
  - new i18n function $t & login page and setting drawer config i18n &nbsp;-&nbsp; by @honghuangdc [<samp>(854d0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/854d0bc)
  - add plugin-web-update-notification &nbsp;-&nbsp; by @honghuangdc [<samp>(c9164)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c91644b)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**:
  - 修复动态路由主页404 &nbsp;-&nbsp; by @lapislazulisch [<samp>(3ae19)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3ae1952)
  - 修复动态路由home页404 &nbsp;-&nbsp; by @lapislazulisch [<samp>(ad6ac)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ad6ac72)
- **projects**:
  - fix set tab title (fixed #256) &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/256 [<samp>(13f6c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/13f6cd8)
  - correct the lang file name & add recommend vscode plugin i18n-ally &nbsp;-&nbsp; by @honghuangdc [<samp>(864ec)</samp>](https://github.com/honghuangdc/soybean-admin/commit/864ec47)
  - fix reload button animate &nbsp;-&nbsp; by @honghuangdc [<samp>(41f23)</samp>](https://github.com/honghuangdc/soybean-admin/commit/41f2338)
- **styles**:
  - 用户管理页面布局自适应屏幕高度 (fixed #253) &nbsp;-&nbsp; by @honghuangdc in https://github.com/honghuangdc/soybean-admin/issues/253 [<samp>(0f7b9)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0f7b9d5)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- **hooks**:
  - perf use-table &nbsp;-&nbsp; by @honghuangdc [<samp>(33180)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3318041)
  - perf useHookTable &nbsp;-&nbsp; by @honghuangdc [<samp>(809fa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/809fa85)
- **projects**:
  - add type declaration for document startViewTransition &nbsp;-&nbsp; by @honghuangdc [<samp>(d3ebe)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d3ebe95)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - 生产环境缓存主题变更为sessionStorage &nbsp;-&nbsp; by @honghuangdc [<samp>(c46a5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c46a592)
  - add reCacheRoute method &nbsp;-&nbsp; by @honghuangdc [<samp>(f92ee)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f92ee77)
  - update soybean domain &nbsp;-&nbsp; by @honghuangdc [<samp>(073fd)</samp>](https://github.com/honghuangdc/soybean-admin/commit/073fd16)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md logo &nbsp;-&nbsp; by @honghuangdc [<samp>(19141)</samp>](https://github.com/honghuangdc/soybean-admin/commit/19141a7)
  - update Docker deployment method &nbsp;-&nbsp; by @snowords [<samp>(00da0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/00da000)
  - update git hooks init command &nbsp;-&nbsp; by @snowords [<samp>(7f35e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7f35e87)
  - update README.md &nbsp;-&nbsp; by @eltociear [<samp>(93ed5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/93ed5ad)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(bba68)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bba68bf)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(0e6d2)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0e6d289)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(135ce)</samp>](https://github.com/honghuangdc/soybean-admin/commit/135ce77)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(44ba3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/44ba327)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(9296e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9296e69)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(751de)</samp>](https://github.com/honghuangdc/soybean-admin/commit/751ded4)
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(305d9)</samp>](https://github.com/honghuangdc/soybean-admin/commit/305d956)
- **projects**:
  - update deps and fix swiper &nbsp;-&nbsp; by @honghuangdc [<samp>(9d105)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9d1051b)
  - update package.json &nbsp;-&nbsp; by @honghuangdc [<samp>(d7aea)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d7aea9d)
  - update deps & fix eslint code &nbsp;-&nbsp; by @honghuangdc [<samp>(08e0c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/08e0cf5)
  - update pnpm-lock.yaml &nbsp;-&nbsp; by @honghuangdc [<samp>(94644)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9464473)
  - update VSCode setting &nbsp;-&nbsp; by @honghuangdc [<samp>(56c77)</samp>](https://github.com/honghuangdc/soybean-admin/commit/56c770c)
  - correct the word spell &nbsp;-&nbsp; by @honghuangdc [<samp>(458e3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/458e387)
  - correct word spell & eslint fix code &nbsp;-&nbsp; by @honghuangdc [<samp>(cffc3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cffc30a)
  - When tab is switched, keep the page without refreshing &nbsp;-&nbsp; by @linjiangl [<samp>(83f25)</samp>](https://github.com/honghuangdc/soybean-admin/commit/83f2514)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **projects**:
  - unify card border radius, 16px to 8px &nbsp;-&nbsp; by @honghuangdc [<samp>(cbda4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cbda4a3)
  - update default theme color &nbsp;-&nbsp; by @honghuangdc [<samp>(43ac2)</samp>](https://github.com/honghuangdc/soybean-admin/commit/43ac23f)
  - prettier format code &nbsp;-&nbsp; by @honghuangdc [<samp>(24cf1)</samp>](https://github.com/honghuangdc/soybean-admin/commit/24cf1d9)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![eltociear](https://github.com/eltociear.png?size=48)](https://github.com/eltociear)&nbsp;&nbsp;[![linjiangl](https://github.com/linjiangl.png?size=48)](https://github.com/linjiangl)&nbsp;&nbsp;[![lapislazulisch](https://github.com/lapislazulisch.png?size=48)](https://github.com/lapislazulisch)&nbsp;&nbsp;[![snowords](https://github.com/snowords.png?size=48)](https://github.com/snowords)&nbsp;&nbsp;[![eAliwei](https://github.com/eAliwei.png?size=48)](https://github.com/eAliwei)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v0.10.3](https://github.com/honghuangdc/soybean-admin/compare/v0.10.2...v0.10.3) (23-06-15)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**: fix userRoleOptions &nbsp;-&nbsp; by @soybeanjs [<samp>(2ca2b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2ca2b76)
- **styles**: fix toggle-lang bg &nbsp;-&nbsp; by @soybeanjs [<samp>(47309)</samp>](https://github.com/honghuangdc/soybean-admin/commit/473095b)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- **projects**:
  - remove useless code &nbsp;-&nbsp; by @soybeanjs [<samp>(eb8e4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/eb8e49e)
  - use transformObjectToOption to generate option of object labels &nbsp;-&nbsp; by @soybeanjs [<samp>(da611)</samp>](https://github.com/honghuangdc/soybean-admin/commit/da611fb)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - CHANGELOG.md &nbsp;-&nbsp; by @soybeanjs [<samp>(ff5bf)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ff5bf62)
  - generate full CHANGELOG.md &nbsp;-&nbsp; by @soybeanjs [<samp>(055d4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/055d4cc)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(3c7e1)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3c7e1cf)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(1681c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1681c34)
  - update README.md picture url &nbsp;-&nbsp; by @soybeanjs [<samp>(4eefc)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4eefc95)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(8f24a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8f24a94)
  - update CHANGELOG.md by regenerate changelog &nbsp;-&nbsp; by @soybeanjs [<samp>(2a9b7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2a9b725)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(f9d47)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f9d47c0)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(47ab0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/47ab018)
  - decrease vite-plugin-page-route &nbsp;-&nbsp; by @soybeanjs [<samp>(882f2)</samp>](https://github.com/honghuangdc/soybean-admin/commit/882f281)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(e6abf)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e6abf93)
- **projects**:
  - remove bumpp & add release script &nbsp;-&nbsp; by @soybeanjs [<samp>(a3dfe)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a3dfe61)
  - update @soybeanjs/cli and generate total changelog &nbsp;-&nbsp; by @soybeanjs [<samp>(58591)</samp>](https://github.com/honghuangdc/soybean-admin/commit/58591f6)
  - update deps & update unocss deprecated api exclude &nbsp;-&nbsp; by @soybeanjs [<samp>(0907d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0907d38)
  - update deps & update package.json &nbsp;-&nbsp; by @soybeanjs [<samp>(0b2f6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0b2f68a)
  - add vite-plugin-vue-devtools &nbsp;-&nbsp; by @soybeanjs [<samp>(c1bee)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c1bee40)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;

## [v0.10.2](https://github.com/honghuangdc/soybean-admin/compare/v0.10.1...v0.10.2) (2023-06-01)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**: fix mix-menu layout when the locale is English (fixed 241) &nbsp;-&nbsp; by @soybeanjs [<samp>(5c085)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5c085a1)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - CHANGELOG.md &nbsp;-&nbsp; by @soybeanjs [<samp>(bb2ea)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bb2eab6)
  - update README.md: update example image url [更新示例图片的链接] &nbsp;-&nbsp; by @soybeanjs [<samp>(4f512)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4f51263)
  - fix README.md: example image link &nbsp;-&nbsp; by @soybeanjs [<samp>(56ea8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/56ea893)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- release v0.10.2 &nbsp;-&nbsp; by @soybeanjs [<samp>(1f6d0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1f6d079)
- **projects**: update deps and use soy lint-staged replace lint-staged &nbsp;-&nbsp; by @soybeanjs [<samp>(9a238)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9a23817)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;

## [v0.10.1](https://github.com/honghuangdc/soybean-admin/compare/v0.10.0...v0.10.1) (2023-05-31)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - CHANGELOG.md &nbsp;-&nbsp; by @soybeanjs [<samp>(a2521)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a252138)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(b5839)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b5839ea)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- release v0.10.1 &nbsp;-&nbsp; by @soybeanjs [<samp>(44e4c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/44e4c04)
- **projects**: add switch for pageRoute plugin [添加自动生成路由的插件的开关] &nbsp;-&nbsp; by @soybeanjs [<samp>(780ac)</samp>](https://github.com/honghuangdc/soybean-admin/commit/780ac75)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;

## [v0.10.0](https://github.com/honghuangdc/soybean-admin/compare/v0.9.9...v0.10.0) (2023-05-31)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **components**:
  - Add tree related component instances &nbsp;-&nbsp; by **small_happy** [<samp>(d203a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d203a35)
  - Add routing data related to tree components and page display optimization &nbsp;-&nbsp; by **small_happy** [<samp>(a0f55)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a0f55ac)
- **projects**:
  - 返回顶部功能适配新布局 &nbsp;-&nbsp; by @yanbowe [<samp>(54e2c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/54e2cb5)
  - 增加i18n支持翻译菜单,tab,title &nbsp;-&nbsp; by **cc** [<samp>(3d48a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3d48aa8)
  - add menu translate [翻译菜单] &nbsp;-&nbsp; by @soybeanjs [<samp>(f6828)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f68285f)
  - 增加主题切换过渡效果 &nbsp;-&nbsp; by **cc** [<samp>(8da88)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8da8843)
  - support mobile layout [支持移动端布局] &nbsp;-&nbsp; by @soybeanjs [<samp>(f2b51)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f2b518e)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - fix router guide [修复路由跳转异常] fixed #216 &nbsp;-&nbsp; by @soybeanjs in https://github.com/honghuangdc/soybean-admin/issues/216 [<samp>(59578)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5957833)
  - fix better-mock usage [修复better-mock用法] &nbsp;-&nbsp; by @soybeanjs [<samp>(c5764)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c57640a)
  - tsconfig missing isolatedModules &nbsp;-&nbsp; by @kirklin [<samp>(ab49a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ab49afd)
  - fix mockjs [修复mockjs] &nbsp;-&nbsp; by @soybeanjs [<samp>(9b19f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9b19f96)
  - add prod mockjs switch [添加生产模式的mockjs的开关] &nbsp;-&nbsp; by @soybeanjs [<samp>(9f563)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9f5638f)
  - 修复面包屑导航下拉菜单语言显示问题 &nbsp;-&nbsp; by **cc** [<samp>(ee8fa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ee8fa04)
  - hide the drawer when it is initial mobile mode [初始化时为移动端布局则隐藏侧边栏] fixed #238 &nbsp;-&nbsp; by @soybeanjs in https://github.com/honghuangdc/soybean-admin/issues/238 [<samp>(0abde)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0abde46)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- **projects**:
  - complete dynamic route translate [补充动态路由的翻译] &nbsp;-&nbsp; by @soybeanjs [<samp>(7b746)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7b746fa)
  - move changing document title by locale to global event of composables & add appLoading unmount &nbsp;-&nbsp; by @soybeanjs [<samp>(08e19)</samp>](https://github.com/honghuangdc/soybean-admin/commit/08e194e)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - update useTable &nbsp;-&nbsp; by @soybeanjs [<samp>(211ae)</samp>](https://github.com/honghuangdc/soybean-admin/commit/211ae1f)
  - remove page examples: tree [去除tree相关示例页面] &nbsp;-&nbsp; by @soybeanjs [<samp>(f3090)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f309003)
  - use better-mock replace mockjs [用better-mock替换mockjs] &nbsp;-&nbsp; by @soybeanjs [<samp>(9d3c7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9d3c732)
  - upgrade vue3.3, official support defineOptions &nbsp;-&nbsp; by @kirklin [<samp>(86a37)</samp>](https://github.com/honghuangdc/soybean-admin/commit/86a370f)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - add qq to README.md [文档添加QQ群] &nbsp;-&nbsp; by @soybeanjs [<samp>(f74a6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f74a642)
  - update README.md [更新README.md] &nbsp;-&nbsp; by @soybeanjs [<samp>(39709)</samp>](https://github.com/honghuangdc/soybean-admin/commit/397092c)
  - update README.md [更新README.md] &nbsp;-&nbsp; by @soybeanjs [<samp>(5a4f8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5a4f842)
  - update README.md [更新README.md] &nbsp;-&nbsp; by @soybeanjs [<samp>(a765d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a765da6)
  - update README.md [更新README.md] &nbsp;-&nbsp; by @soybeanjs [<samp>(a989b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a989b44)
  - 优化README.md &nbsp;-&nbsp; by @greper [<samp>(6ea75)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6ea755f)
  - readme.md 二次开发的项目内容换行 &nbsp;-&nbsp; by @greper [<samp>(f3a17)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f3a1707)
  - update CHANGELOG.md &nbsp;-&nbsp; by @soybeanjs [<samp>(5f6ca)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5f6caab)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(db629)</samp>](https://github.com/honghuangdc/soybean-admin/commit/db62959)
  - update deps [升级依赖] &nbsp;-&nbsp; by @soybeanjs [<samp>(f2e82)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f2e82da)
  - update deps and remove vite-plugin-html [升级依赖，去除vite-plugin-html] &nbsp;-&nbsp; by @soybeanjs [<samp>(eaf36)</samp>](https://github.com/honghuangdc/soybean-admin/commit/eaf3678)
  - update deps [升级依赖] &nbsp;-&nbsp; by @soybeanjs [<samp>(bae17)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bae1767)
  - update deps [升级依赖] &nbsp;-&nbsp; by @soybeanjs [<samp>(c2642)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c264216)
  - update deps [升级依赖] &nbsp;-&nbsp; by @soybeanjs [<samp>(40f85)</samp>](https://github.com/honghuangdc/soybean-admin/commit/40f8587)
- **projects**:
  - remove old layout,tab package [去除旧的布局和页签依赖] &nbsp;-&nbsp; by @soybeanjs [<samp>(42e6d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/42e6de3)
  - update deps and fix type error [升级依赖并修复类型问题] &nbsp;-&nbsp; by @soybeanjs [<samp>(34f02)</samp>](https://github.com/honghuangdc/soybean-admin/commit/34f023c)
  - update deps and fix style [升级依赖&修复代码格式] &nbsp;-&nbsp; by @soybeanjs [<samp>(c1c43)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c1c4335)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- release v0.10.0 &nbsp;-&nbsp; by @soybeanjs [<samp>(270a0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/270a055)
- **deps**: update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(cebbe)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cebbef6)
- **projects**: remove useless packages, update lint-staged config, add githublogen &nbsp;-&nbsp; by @soybeanjs [<samp>(5aaa3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5aaa318)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **projects**: per style [完善样式] &nbsp;-&nbsp; by @soybeanjs [<samp>(209ef)</samp>](https://github.com/honghuangdc/soybean-admin/commit/209ef3d)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![greper](https://github.com/greper.png?size=48)](https://github.com/greper)&nbsp;&nbsp;[![kirklin](https://github.com/kirklin.png?size=48)](https://github.com/kirklin)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;
[cc](mailto:cc@qq.com),&nbsp;[small_happy](mailto:5304122+small_happy@user.noreply.gitee.com),&nbsp;

## [v0.9.9](https://github.com/honghuangdc/soybean-admin/compare/v0.9.8...v0.9.9) (2023-03-13)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **hooks**:
  - add useNaiveTable &nbsp;-&nbsp; by @soybeanjs [<samp>(cc13f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cc13fcc)
- **projects**:
  - custom unocss colors support opacity &nbsp;-&nbsp; by @soybeanjs [<samp>(488e6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/488e6e3)
  - new layout,tab and add update theme settings &nbsp;-&nbsp; by @soybeanjs [<samp>(912c3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/912c353)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**:
  - 页面跳转被拦截, 则会出现 tab 页签与页面不一致的问题 &nbsp;-&nbsp; by @taisha [<samp>(bd5dd)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bd5dd2c)
  - 修复iconSelect选择器点击事件失效 &nbsp;-&nbsp; by @yanbowe [<samp>(7e505)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7e505f9)
  - refresh cached routes &nbsp;-&nbsp; by @taisha [<samp>(b0f98)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b0f98e4)
- **projects**:
  - fix eslint svg cause incorrect icon render &nbsp;-&nbsp; by @soybeanjs [<samp>(0b5af)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0b5afda)
  - sortRoutes recursively &nbsp;-&nbsp; by @sunhao1256 [<samp>(91889)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9188941)
  - not only `/login` claim dynamic path scenario , but also others , eg:/user/1 &nbsp;-&nbsp; by @sunhao1256 [<samp>(60598)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6059891)
  - the length of routes children list should greater than 0 &nbsp;-&nbsp; by @Shadowsight9 [<samp>(e1afc)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e1afc10)
  - fix pwa logo &nbsp;-&nbsp; by @soybeanjs [<samp>(bf2f6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bf2f617)
  - fix github bug-report &nbsp;-&nbsp; by @soybeanjs [<samp>(f73e3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f73e3f6)
- **utils**:
  - make AxiosRequestConfig optional for request.handleDelete() &nbsp;-&nbsp; by @guuuuo [<samp>(4a6fe)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4a6fec8)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - all file and folder use kebab-case &nbsp;-&nbsp; by @soybeanjs [<samp>(cea60)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cea600f)
  - update service and proxy config &nbsp;-&nbsp; by @soybeanjs [<samp>(8debf)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8debfe7)
  - remove enum &nbsp;-&nbsp; by @soybeanjs [<samp>(21d52)</samp>](https://github.com/honghuangdc/soybean-admin/commit/21d5214)
  - rename union key &nbsp;-&nbsp; by @soybeanjs [<samp>(e2b32)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e2b320a)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(cf8c7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cf8c7cb)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(1ef1b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1ef1b6b)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(aaef0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/aaef0be)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(61998)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6199888)
- **projects**:
  - update deps and fix project config &nbsp;-&nbsp; by @soybeanjs [<samp>(da521)</samp>](https://github.com/honghuangdc/soybean-admin/commit/da521b3)
  - perf logo &nbsp;-&nbsp; by @soybeanjs [<samp>(a8a6e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a8a6ed9)
  - update vscode config &nbsp;-&nbsp; by @soybeanjs [<samp>(608d7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/608d7fb)
  - update unocss config &nbsp;-&nbsp; by @soybeanjs [<samp>(3503d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3503dff)
  - update deps, add prettier format command &nbsp;-&nbsp; by @soybeanjs [<samp>(36e5f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/36e5fea)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **projects**:
  - add github action &nbsp;-&nbsp; by @lixin59 [<samp>(f355a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f355a69)
  - 修复issue模板格式问题 &nbsp;-&nbsp; by @lixin59 [<samp>(d8bab)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d8baba5)
- **release**:
  - 0.9.9 &nbsp;-&nbsp; by @soybeanjs [<samp>(c0066)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c0066b2)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **projects**: format yaml &nbsp;-&nbsp; by @soybeanjs [<samp>(fb46d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/fb46d7e)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![guuuuo](https://github.com/guuuuo.png?size=48)](https://github.com/guuuuo)&nbsp;&nbsp;[![lixin59](https://github.com/lixin59.png?size=48)](https://github.com/lixin59)&nbsp;&nbsp;[![taisha](https://github.com/taisha.png?size=48)](https://github.com/taisha)&nbsp;&nbsp;[![Shadowsight9](https://github.com/Shadowsight9.png?size=48)](https://github.com/Shadowsight9)&nbsp;&nbsp;[![sunhao1256](https://github.com/sunhao1256.png?size=48)](https://github.com/sunhao1256)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;

## [v0.9.8](https://github.com/honghuangdc/soybean-admin/compare/v0.9.7...v0.9.8) (2023-01-15)

### &nbsp;&nbsp;&nbsp;🚀 Features

- setting 页面新增 是否显示footer的开关 &nbsp;-&nbsp; by @zuihou [<samp>(d064f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d064f62)
- 新增 affix 属性，用于将其固定在tab卡 &nbsp;-&nbsp; by @zuihou [<samp>(e772f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e772ff0)
- **projects**:
  - add compress script [添加压缩命令] &nbsp;-&nbsp; by @soybeanjs [<samp>(be6d4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/be6d431)
  - add script about generating png logo from [添加根据svg生成png图标的命令] &nbsp;-&nbsp; by @soybeanjs [<samp>(70aee)</samp>](https://github.com/honghuangdc/soybean-admin/commit/70aeefe)
  - add generate logo script &nbsp;-&nbsp; by @soybeanjs [<samp>(25daa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/25daa23)
  - add new route plugin @soybeanjs/vite-plugin-vue-page-route [集成新的路由插件] &nbsp;-&nbsp; by @soybeanjs [<samp>(3131e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3131e00)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- remove height limit h-360px &nbsp;-&nbsp; by @codearhat [<samp>(b5c57)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b5c570a)
- set password attributes &nbsp;-&nbsp; by @codearhat [<samp>(a9a37)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a9a3703)
- **components**:
  - 修复路由在path中包含重复路单词径菜单时，被激活会错误展开 &nbsp;-&nbsp; by @shabby2333 [<samp>(264da)</samp>](https://github.com/honghuangdc/soybean-admin/commit/264da00)
- **projects**:
  - fix vite-pwa plugin config &nbsp;-&nbsp; by @soybeanjs [<samp>(94098)</samp>](https://github.com/honghuangdc/soybean-admin/commit/94098d0)
  - add router-page.d.ts to git [将router-page.d.ts添加git提交] &nbsp;-&nbsp; by @soybeanjs [<samp>(7a580)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7a58035)
  - fix router when the dynamic routes api was failed [修复当动态路由接口失败后路由异常问题] &nbsp;-&nbsp; by @soybeanjs [<samp>(f2b58)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f2b580f)
  - fix login success message [修复登录成功的消息提示] &nbsp;-&nbsp; by @soybeanjs [<samp>(81039)</samp>](https://github.com/honghuangdc/soybean-admin/commit/810398a)
  - 修复tabs在static路由模式下可以关闭首页 &nbsp;-&nbsp; by @yanbowe [<samp>(7211a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7211a17)
  - 修复动态路由模式下路由不排序的问题 &nbsp;-&nbsp; by @HnyLi [<samp>(58b27)</samp>](https://github.com/honghuangdc/soybean-admin/commit/58b27c9)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **czg**:
  - update cz-git,czg breaking changes &nbsp;-&nbsp; by @yanbowe [<samp>(fcb7a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/fcb7ad9)
- **hooks**:
  - 重构hook函数取消监听方式 &nbsp;-&nbsp; by @yanbowe [<samp>(fd948)</samp>](https://github.com/honghuangdc/soybean-admin/commit/fd94886)
- **projects**:
  - format code style [调整代码格式] &nbsp;-&nbsp; by @soybeanjs [<samp>(a9d58)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a9d58f8)
  - import cz-git, czg replace @soybeanjs/cli [引入cz-git、czg替换@soybeanjs/cli] &nbsp;-&nbsp; by @soybeanjs [<samp>(1bdd8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1bdd81a)
  - perfect scrollbar style [完善滚动条] &nbsp;-&nbsp; by @soybeanjs [<samp>(1a02c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1a02cab)
  - refactor app init loading [重构系统初始化的加载] &nbsp;-&nbsp; by @soybeanjs [<samp>(57bfe)</samp>](https://github.com/honghuangdc/soybean-admin/commit/57bfe27)
  - new storage system [新的本地数据存储系统] &nbsp;-&nbsp; by @soybeanjs [<samp>(97191)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9719159)
  - add simple-git-hooks replace husky &nbsp;-&nbsp; by @soybeanjs [<samp>(9110d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9110d87)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(828a2)</samp>](https://github.com/honghuangdc/soybean-admin/commit/828a2f5)
  - update README &nbsp;-&nbsp; by @soybeanjs [<samp>(a3562)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a3562d9)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(84567)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8456750)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(fcc65)</samp>](https://github.com/honghuangdc/soybean-admin/commit/fcc65c3)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(c097b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c097b56)
- **projects**:
  - update plugin config &nbsp;-&nbsp; by @soybeanjs [<samp>(6a344)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6a344ff)
  - update deps and perfect the details [升级依赖，完善细节] &nbsp;-&nbsp; by @soybeanjs [<samp>(61a43)</samp>](https://github.com/honghuangdc/soybean-admin/commit/61a43b8)
  - update deps and update config &nbsp;-&nbsp; by @soybeanjs [<samp>(b08c3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b08c389)
  - update lint-staged config &nbsp;-&nbsp; by @soybeanjs [<samp>(0882c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0882c25)
  - add VSCode debug config file &nbsp;-&nbsp; by @soybeanjs [<samp>(0c126)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0c12665)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(f7181)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f71812d)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**: 0.9.8 &nbsp;-&nbsp; by @soybeanjs [<samp>(34ffd)</samp>](https://github.com/honghuangdc/soybean-admin/commit/34ffd9c)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![shabby2333](https://github.com/shabby2333.png?size=48)](https://github.com/shabby2333)&nbsp;&nbsp;[![HnyLi](https://github.com/HnyLi.png?size=48)](https://github.com/HnyLi)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;[![zuihou](https://github.com/zuihou.png?size=48)](https://github.com/zuihou)&nbsp;&nbsp;[![codearhat](https://github.com/codearhat.png?size=48)](https://github.com/codearhat)&nbsp;&nbsp;[![RockerHX](https://github.com/RockerHX.png?size=48)](https://github.com/RockerHX)&nbsp;&nbsp;

## [v0.9.7](https://github.com/honghuangdc/soybean-admin/compare/v0.9.6...v0.9.7) (2022-11-08)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - 增加系统消息组件 &nbsp;-&nbsp; by @yanbowe [<samp>(afa01)</samp>](https://github.com/honghuangdc/soybean-admin/commit/afa0134)
  - 系统消息组件代码优化 &nbsp;-&nbsp; by @yanbowe [<samp>(95183)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9518372)
  - 增加返回顶部功能 &nbsp;-&nbsp; by @yanbowe [<samp>(894b0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/894b0f1)
  - 添加生产的主题配置缓存 &nbsp;-&nbsp; by @soybeanjs [<samp>(718c3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/718c362)
  - 添加provide、inject上下文示例 &nbsp;-&nbsp; by @soybeanjs [<samp>(a4447)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a444731)
  - 添加组件名称，调整vue文件里面的类型声明位置 &nbsp;-&nbsp; by @soybeanjs [<samp>(f64bc)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f64bc91)
  - 适配移动端，修复Tab关闭图标的bug &nbsp;-&nbsp; by @soybeanjs [<samp>(296b1)</samp>](https://github.com/honghuangdc/soybean-admin/commit/296b154)
  - 添加系统管理的页面 &nbsp;-&nbsp; by @soybeanjs [<samp>(c33b5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c33b5eb)
  - useNaiveTable函数：类型部分 &nbsp;-&nbsp; by @soybeanjs [<samp>(02992)</samp>](https://github.com/honghuangdc/soybean-admin/commit/02992dc)
  - 添加请求适配adapter层应用的示例页面 &nbsp;-&nbsp; by @soybeanjs [<samp>(8d11a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8d11a6a)
  - 实现用户管理页面 &nbsp;-&nbsp; by @soybeanjs [<samp>(472f9)</samp>](https://github.com/honghuangdc/soybean-admin/commit/472f93b)
  - 全局搜索菜单及消息通知适配移动端 &nbsp;-&nbsp; by @yanbowe [<samp>(97e2f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/97e2ffd)
  - support constant route without login status[支持未登录状态下访问自定义的固定路由] &nbsp;-&nbsp; by @soybeanjs [<samp>(a5391)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a539112)
  - add pinia setup syntax example: setup-store[添加setup syntax的pinia示例setup-store] &nbsp;-&nbsp; by @soybeanjs [<samp>(82c4b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/82c4b09)
  - add constant route page without login status[添加未登录可访问的固定路由示例页面] &nbsp;-&nbsp; by @soybeanjs [<samp>(78efd)</samp>](https://github.com/honghuangdc/soybean-admin/commit/78efd77)
  - refactor icon system, unify icon usage [重构图标系统，统一图标用法] &nbsp;-&nbsp; by @soybeanjs [<samp>(811f8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/811f820)
  - import i18n [引入i18n] &nbsp;-&nbsp; by @soybeanjs [<samp>(b632b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b632b7f)
  - new router system [新的路由系统] &nbsp;-&nbsp; by @soybeanjs [<samp>(c7b6a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c7b6a3f)
- **tabs**:
  - 多页签增加关闭所有 &nbsp;-&nbsp; by @yanbowe [<samp>(8237a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8237adb)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **deps**:
  - decrease @types/node version to fix TS type error [降低@types/node版本修复TS的类型错误] &nbsp;-&nbsp; by @soybeanjs [<samp>(149d2)</samp>](https://github.com/honghuangdc/soybean-admin/commit/149d22a)
- **projects**:
  - 修复tab不显示路由首页的问题 &nbsp;-&nbsp; by @soybeanjs [<samp>(a792b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a792bb5)
  - 修复多个后端服务时的本地代理 &nbsp;-&nbsp; by @soybeanjs [<samp>(2aba5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2aba58c)
  - 修复图标的TS类型 &nbsp;-&nbsp; by @soybeanjs [<samp>(dbd67)</samp>](https://github.com/honghuangdc/soybean-admin/commit/dbd6760)
  - 修复import.meta.env的TS类型 &nbsp;-&nbsp; by @soybeanjs [<samp>(19942)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1994262)
  - 修复构建后mockjs对xhr的影响问题 &nbsp;-&nbsp; by @soybeanjs [<samp>(77572)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7757285)
  - 修复TS类型问题 &nbsp;-&nbsp; by @soybeanjs [<samp>(16dce)</samp>](https://github.com/honghuangdc/soybean-admin/commit/16dce9a)
  - 修复eslint规则 &nbsp;-&nbsp; by @soybeanjs [<samp>(d7f5b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d7f5bf3)
  - add iconify json &nbsp;-&nbsp; by @soybeanjs [<samp>(8a1ec)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8a1ec93)
- **svg-icon**:
  - 自定义图标在Dropdown组件下hover状态无法显示图标 &nbsp;-&nbsp; by @yanbowe [<samp>(0523f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0523f08)
- **utils**:
  - 修复iconifyRender &nbsp;-&nbsp; by @soybeanjs [<samp>(c37d0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c37d0ac)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- **components**:
  - 添加更多主题颜色设置模态窗的层级 &nbsp;-&nbsp; by @xiaotao2018 [<samp>(ee7eb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ee7eb3a)
  - 添加更多主题颜色设置模态窗的层级，z-index为int &nbsp;-&nbsp; by @xiaotao2018 [<samp>(e2d65)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e2d6554)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - 代码优化 &nbsp;-&nbsp; by @yanbowe [<samp>(41147)</samp>](https://github.com/honghuangdc/soybean-admin/commit/41147b3)
  - 添加subscribeAppStore &nbsp;-&nbsp; by @soybeanjs [<samp>(aa2f7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/aa2f78a)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(b60db)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b60db89)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(61436)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6143605)
  - 请求适配器函数范型重构、优化请求相关的命名 &nbsp;-&nbsp; by @soybeanjs [<samp>(7f9c9)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7f9c98a)
  - 更新搜索弹窗的图标 &nbsp;-&nbsp; by @soybeanjs [<samp>(ed9cd)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ed9cd6c)
  - 抽离格式化相关依赖配置 &nbsp;-&nbsp; by @soybeanjs [<samp>(f4d37)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f4d37cf)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(49f95)</samp>](https://github.com/honghuangdc/soybean-admin/commit/49f95c4)
  - cancel autoinstall @iconify-json [取消@iconify-json自动安装] &nbsp;-&nbsp; by @soybeanjs [<samp>(c29b8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c29b887)
  - refactor page: user-management [重构用户管理页面] &nbsp;-&nbsp; by @soybeanjs [<samp>(468b4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/468b4bb)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(e2727)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e2727e6)
  - revert docs &nbsp;-&nbsp; by @soybeanjs [<samp>(2c562)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2c56233)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(69e39)</samp>](https://github.com/honghuangdc/soybean-admin/commit/69e39c1)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(ea1a3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ea1a336)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(73fa3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/73fa3d1)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(973ab)</samp>](https://github.com/honghuangdc/soybean-admin/commit/973ab14)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(75000)</samp>](https://github.com/honghuangdc/soybean-admin/commit/750000e)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(8dcfb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8dcfbb2)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(1523c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1523c7b)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(da407)</samp>](https://github.com/honghuangdc/soybean-admin/commit/da407b6)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(cec0f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cec0f25)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(d9cfe)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d9cfeab)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(dd113)</samp>](https://github.com/honghuangdc/soybean-admin/commit/dd11324)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(d0823)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d0823b0)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(94ff7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/94ff787)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(b32bc)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b32bca4)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(f6b61)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f6b6141)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(0f0cd)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0f0cd0b)
  - 更新@soybeanjs/eslint-config &nbsp;-&nbsp; by @soybeanjs [<samp>(36f06)</samp>](https://github.com/honghuangdc/soybean-admin/commit/36f06bc)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(d9324)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d9324f0)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(1ad92)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1ad92a2)
  - 升级依赖 &nbsp;-&nbsp; by @soybeanjs [<samp>(7240b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7240be8)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(c5ba6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c5ba631)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(3e0cc)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3e0cc8c)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(21b6f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/21b6fb6)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(d823e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d823ee5)
  - unplugin-vue-define-options替换为unplugin-vue-macros &nbsp;-&nbsp; by @soybeanjs [<samp>(22c90)</samp>](https://github.com/honghuangdc/soybean-admin/commit/22c9025)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(7dd7c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7dd7c71)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(fe8ca)</samp>](https://github.com/honghuangdc/soybean-admin/commit/fe8cab3)
  - unplugin-icon autoinstall @iconify-json [unplugin-icon自动安装@iconify-json] &nbsp;-&nbsp; by @soybeanjs [<samp>(c045e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c045e3f)
  - update deps [升级依赖] &nbsp;-&nbsp; by @soybeanjs [<samp>(331b1)</samp>](https://github.com/honghuangdc/soybean-admin/commit/331b14e)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(88e53)</samp>](https://github.com/honghuangdc/soybean-admin/commit/88e535f)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(89985)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8998581)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(65ac6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/65ac69e)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(abd02)</samp>](https://github.com/honghuangdc/soybean-admin/commit/abd02d1)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(d6b15)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d6b1530)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(8e801)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8e801dd)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(41b3b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/41b3bcb)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(1f3e6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1f3e6e4)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(74772)</samp>](https://github.com/honghuangdc/soybean-admin/commit/74772a1)
- **projects**:
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(5c1b0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5c1b086)
  - update tsconfig &nbsp;-&nbsp; by @soybeanjs [<samp>(9ce58)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9ce5807)
  - update vscode settings &nbsp;-&nbsp; by @soybeanjs [<samp>(3fe4e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3fe4e92)
  - 添加.gitattributes &nbsp;-&nbsp; by @soybeanjs [<samp>(896e6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/896e6f2)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(6a9a3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6a9a362)
  - 升级依赖，添加对json的eslint检测及格式化 &nbsp;-&nbsp; by @soybeanjs [<samp>(711a4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/711a4ae)
  - update deps and README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(35aee)</samp>](https://github.com/honghuangdc/soybean-admin/commit/35aeedf)
  - 升级依赖、vite配置optimizeDeps &nbsp;-&nbsp; by @soybeanjs [<samp>(ee434)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ee434b4)
  - 去除prettier，已集成进@soybeanjs/eslint-config &nbsp;-&nbsp; by @soybeanjs [<samp>(182da)</samp>](https://github.com/honghuangdc/soybean-admin/commit/182dac0)
  - update eslint &nbsp;-&nbsp; by @soybeanjs [<samp>(907cf)</samp>](https://github.com/honghuangdc/soybean-admin/commit/907cf44)
  - 引入pwa插件，更新配置 &nbsp;-&nbsp; by @soybeanjs [<samp>(695ec)</samp>](https://github.com/honghuangdc/soybean-admin/commit/695ec7e)
  - 更新依赖、调整页面 &nbsp;-&nbsp; by @soybeanjs [<samp>(40ecc)</samp>](https://github.com/honghuangdc/soybean-admin/commit/40ecc32)
  - 引入vite-plugin-progress &nbsp;-&nbsp; by @soybeanjs [<samp>(44ab0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/44ab077)
  - 升级依赖、修复T标签右键菜单连续显示问题 &nbsp;-&nbsp; by @soybeanjs [<samp>(639c4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/639c445)
  - 引入TS高级类型库 &nbsp;-&nbsp; by @soybeanjs [<samp>(71a75)</samp>](https://github.com/honghuangdc/soybean-admin/commit/71a753f)
  - 更换eslint依赖为eslint-config-soybeanjs-vue &nbsp;-&nbsp; by @soybeanjs [<samp>(07325)</samp>](https://github.com/honghuangdc/soybean-admin/commit/07325a4)
  - 升级依赖，降低naive-ui版本修复打包问题 &nbsp;-&nbsp; by @soybeanjs [<samp>(f408e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f408ea0)
  - 升级依赖，修复TS类型 &nbsp;-&nbsp; by @soybeanjs [<samp>(73ce5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/73ce53a)
  - 引入@unocss/vite替换unocss，精简体积 &nbsp;-&nbsp; by @soybeanjs [<samp>(3540b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3540b75)
  - update deps, update logos &nbsp;-&nbsp; by @soybeanjs [<samp>(22c05)</samp>](https://github.com/honghuangdc/soybean-admin/commit/22c0567)
  - add constant page content &nbsp;-&nbsp; by @soybeanjs [<samp>(13d0c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/13d0c41)
  - add tauri scripts, change tauri icon, fix mockjs [添加tauri相关的命令，变更tauri图标，修复mockjs] &nbsp;-&nbsp; by @soybeanjs [<samp>(1b45b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1b45b71)
  - use @soybeanjs/cli replace commitizen &nbsp;-&nbsp; by @soybeanjs [<samp>(428d4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/428d41b)
  - use pnpm patch replace @milahu/patch-package &nbsp;-&nbsp; by @soybeanjs [<samp>(9455a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9455ad9)
  - remove useless file: commitlint.config.js &nbsp;-&nbsp; by @soybeanjs [<samp>(67736)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6773659)
  - move tauri to branch tauri &nbsp;-&nbsp; by @soybeanjs [<samp>(6c14b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6c14bfe)
  - update deps and update config &nbsp;-&nbsp; by @soybeanjs [<samp>(7d699)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7d69992)
  - new router branch &nbsp;-&nbsp; by @soybeanjs [<samp>(288d5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/288d586)
  - add vite plugin @soybeanjs/router-page &nbsp;-&nbsp; by @soybeanjs [<samp>(40c1e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/40c1e13)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **other**:
  - release v0.9.7 &nbsp;-&nbsp; by @soybeanjs [<samp>(cc00c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cc00c8f)
- **projects**:
  - 更新.cz-config &nbsp;-&nbsp; by @soybeanjs [<samp>(b18c4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b18c49e)
  - 更新eslint配置 &nbsp;-&nbsp; by @soybeanjs [<samp>(872bb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/872bb84)

### &nbsp;&nbsp;&nbsp;🤖 CI

- add docker build &nbsp;-&nbsp; by @zq-xu [<samp>(af740)</samp>](https://github.com/honghuangdc/soybean-admin/commit/af74046)
- change docker image name &nbsp;-&nbsp; by @zq-xu [<samp>(6fbde)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6fbde1e)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![hhstore](https://github.com/hhstore.png?size=48)](https://github.com/hhstore)&nbsp;&nbsp;[![zq-xu](https://github.com/zq-xu.png?size=48)](https://github.com/zq-xu)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;[![xiaotao2018](https://github.com/xiaotao2018.png?size=48)](https://github.com/xiaotao2018)&nbsp;&nbsp;

## [v0.9.6](https://github.com/honghuangdc/soybean-admin/compare/v0.9.5...v0.9.6) (2022-06-16)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - 新增Antv G2图表示例 &nbsp;-&nbsp; by @soybeanjs [<samp>(2d64a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2d64a2e)
  - 上下结构，菜单支持横向滚动 &nbsp;-&nbsp; by @suiyingsky [<samp>(80805)</samp>](https://github.com/honghuangdc/soybean-admin/commit/808051b)
  - 增加设置当前Tab页签名称功能 &nbsp;-&nbsp; by @yanbowe [<samp>(48721)</samp>](https://github.com/honghuangdc/soybean-admin/commit/487213b)
  - 本地svg动态渲染图标 &nbsp;-&nbsp; by @soybeanjs [<samp>(c3c97)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c3c975e)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - 修复顶部菜单的位置失效问题 &nbsp;-&nbsp; by @honghuangdc [<samp>(4ee0d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4ee0d94)
  - 设置tab标题导致meta属性丢失 &nbsp;-&nbsp; by @yanbowe [<samp>(efcfa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/efcfa57)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - 优化菜单支持横向滚动 &nbsp;-&nbsp; by @soybeanjs [<samp>(8f3e8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8f3e855)
  - 代码优化 &nbsp;-&nbsp; by @honghuangdc [<samp>(5fa82)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5fa822f)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(0c70a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0c70a9e)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(906ae)</samp>](https://github.com/honghuangdc/soybean-admin/commit/906aed5)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(9917b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9917b5e)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(83301)</samp>](https://github.com/honghuangdc/soybean-admin/commit/833018a)
- **projects**:
  - update deps, update config &nbsp;-&nbsp; by @honghuangdc [<samp>(8e6e7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8e6e787)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**: 0.9.6 &nbsp;-&nbsp; by @soybeanjs [<samp>(65c21)</samp>](https://github.com/honghuangdc/soybean-admin/commit/65c2181)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![suiyingsky](https://github.com/suiyingsky.png?size=48)](https://github.com/suiyingsky)&nbsp;&nbsp;

## [v0.9.5](https://github.com/honghuangdc/soybean-admin/compare/v0.9.4...v0.9.5) (2022-06-07)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - 添加自动跟随系统主题设置 &nbsp;-&nbsp; by @toolvcn [<samp>(ba07b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ba07b69)
  - 引入echarts替换antvG2plot &nbsp;-&nbsp; by @soybeanjs [<samp>(e7ad0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e7ad086)
  - 添加百度地图、升级依赖 &nbsp;-&nbsp; by @soybeanjs [<samp>(39854)</samp>](https://github.com/honghuangdc/soybean-admin/commit/39854a4)
  - 添加插件页面：图表 &nbsp;-&nbsp; by @soybeanjs [<samp>(0a46e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0a46ea0)
  - 添加antv g2图表示例 &nbsp;-&nbsp; by @soybeanjs [<samp>(44b02)</samp>](https://github.com/honghuangdc/soybean-admin/commit/44b022a)
  - 补充更多的ECharts示例 &nbsp;-&nbsp; by @soybeanjs [<samp>(c7762)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c776249)
  - 动态路由根路由重定向只需取决于后端返回的路由首页 &nbsp;-&nbsp; by @soybeanjs [<samp>(434ab)</samp>](https://github.com/honghuangdc/soybean-admin/commit/434ab1c)
  - 支持同一路由根据不同query和hash同时显示不同Tab &nbsp;-&nbsp; by @soybeanjs [<samp>(41226)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4122685)
- **route**:
  - 路由meta新增activeMenu属性 &nbsp;-&nbsp; by @yanbowe [<samp>(ebd16)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ebd16a4)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - 修复插件不存在的错误提示 &nbsp;-&nbsp; by @ThinkDevelop [<samp>(71652)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7165282)
  - 修复权限切换路由数据未更新的问题 &nbsp;-&nbsp; by @soybeanjs [<samp>(60f91)</samp>](https://github.com/honghuangdc/soybean-admin/commit/60f9125)
  - 修复页面切换时导致的溢出滚动条 &nbsp;-&nbsp; by @soybeanjs [<samp>(e0233)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e023306)
  - 修复@antv/g2生产环境报错 &nbsp;-&nbsp; by @soybeanjs [<samp>(4558c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4558c24)
- **route**:
  - 当为左侧混合菜单时activeMenu无效情况 &nbsp;-&nbsp; by @yanbowe [<samp>(3e4f9)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3e4f9e2)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **layouts**:
  - layout/header 反转色样式补充 &nbsp;-&nbsp; by **元家怿** [<samp>(01d0b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/01d0bcb)
- **projects**:
  - 代码优化 &nbsp;-&nbsp; by @honghuangdc [<samp>(14c14)</samp>](https://github.com/honghuangdc/soybean-admin/commit/14c145e)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(3590b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3590b65)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(a1c7e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a1c7e10)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(44ab5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/44ab55d)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(095c4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/095c432)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(d28b9)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d28b903)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(4c2f5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4c2f535)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(d9ac7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d9ac7e4)
- **styles**:
  - 代码格式 &nbsp;-&nbsp; by @soybeanjs [<samp>(8f6d6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8f6d6ce)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(3d8be)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3d8befa)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(21e63)</samp>](https://github.com/honghuangdc/soybean-admin/commit/21e6399)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(0811f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0811ffa)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(84cb0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/84cb07b)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(4b80a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4b80a66)
  - update docs &nbsp;-&nbsp; by @honghuangdc [<samp>(e9656)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e9656c6)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(ae99e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ae99e57)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**:
  - update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(518f7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/518f7ee)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(92b84)</samp>](https://github.com/honghuangdc/soybean-admin/commit/92b8406)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(50d7c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/50d7ccd)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(3f822)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3f822a7)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(02809)</samp>](https://github.com/honghuangdc/soybean-admin/commit/028096e)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(be45d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/be45d83)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(6a5a3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6a5a357)
  - 依赖升级 &nbsp;-&nbsp; by @honghuangdc [<samp>(e3c4a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e3c4a6e)
- **other**:
  - update cz config &nbsp;-&nbsp; by @honghuangdc [<samp>(07baa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/07baac7)
- **projects**:
  - update config &nbsp;-&nbsp; by @soybeanjs [<samp>(a0c40)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a0c405d)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(de09f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/de09f82)
  - 配置优化 &nbsp;-&nbsp; by @honghuangdc [<samp>(fd787)</samp>](https://github.com/honghuangdc/soybean-admin/commit/fd78791)
  - 配置更改 &nbsp;-&nbsp; by @honghuangdc [<samp>(c8717)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c8717c2)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**:
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(a70e4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a70e416)
  - update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(7487a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7487ab7)
- **release**:
  - 0.9.5 &nbsp;-&nbsp; by @soybeanjs [<samp>(08d83)</samp>](https://github.com/honghuangdc/soybean-admin/commit/08d83ec)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **GlobalBreadcrumb**: 代码格式fix &nbsp;-&nbsp; by @tclyjy [<samp>(0243b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0243b27)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;[![ThinkDevelop](https://github.com/ThinkDevelop.png?size=48)](https://github.com/ThinkDevelop)&nbsp;&nbsp;[![tclyjy](https://github.com/tclyjy.png?size=48)](https://github.com/tclyjy)&nbsp;&nbsp;[![toolvcn](https://github.com/toolvcn.png?size=48)](https://github.com/toolvcn)&nbsp;&nbsp;
[元家怿](mailto:jiayi.yuan@lkcoffee.com),&nbsp;

## [v0.9.4](https://github.com/honghuangdc/soybean-admin/compare/main-0428...v0.9.4) (2022-04-29)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **layouts**:
  - 添加侧边栏/头部的反转模式来增加对比度 &nbsp;-&nbsp; by **元家怿** [<samp>(861c8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/861c8b9)
- **projects**:
  - 引入unocss替换windicss &nbsp;-&nbsp; by @honghuangdc [<samp>(c9d3e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c9d3e5a)
  - HTML lang 修改为 zh-cmn-Hans &nbsp;-&nbsp; by @toolvcn [<samp>(b9c5c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b9c5c34)
  - 权限完善及权限示例页面 &nbsp;-&nbsp; by @soybeanjs [<samp>(80744)</samp>](https://github.com/honghuangdc/soybean-admin/commit/807448a)
  - mock添加权限过滤 &nbsp;-&nbsp; by @soybeanjs [<samp>(7f435)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7f4350a)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - 添加.npmrc修复无法获取自动引入的全局组件声明类型 &nbsp;-&nbsp; by @honghuangdc [<samp>(e8488)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e8488e4)
  - 修复样式 &nbsp;-&nbsp; by @honghuangdc [<samp>(e8999)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e899914)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - mock权限相关数据优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(41e46)</samp>](https://github.com/honghuangdc/soybean-admin/commit/41e46a5)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(251b5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/251b5b9)
  - 代码优化 &nbsp;-&nbsp; by @honghuangdc [<samp>(a7824)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a782461)
  - 细节优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(c275f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c275f26)
  - layout和tab组件依赖名称变更、样式修复 &nbsp;-&nbsp; by @soybeanjs [<samp>(de5fb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/de5fb84)
  - merge branch unocss to main &nbsp;-&nbsp; by @soybeanjs [<samp>(69d51)</samp>](https://github.com/honghuangdc/soybean-admin/commit/69d5131)
  - 动态路由权限完善 &nbsp;-&nbsp; by @soybeanjs [<samp>(55ddc)</samp>](https://github.com/honghuangdc/soybean-admin/commit/55ddc9c)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**: update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(d5c75)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d5c7511)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**: update deps &nbsp;-&nbsp; by @honghuangdc [<samp>(5c75e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5c75e9d)
- **projects**: 细节调整 &nbsp;-&nbsp; by @soybeanjs [<samp>(401f0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/401f0c7)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**: 0.9.4 &nbsp;-&nbsp; by @soybeanjs [<samp>(97c92)</samp>](https://github.com/honghuangdc/soybean-admin/commit/97c9262)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![toolvcn](https://github.com/toolvcn.png?size=48)](https://github.com/toolvcn)&nbsp;&nbsp;
[元家怿](mailto:jiayi.yuan@luckincoffee.com),&nbsp;

## [v0.10.2](https://github.com/honghuangdc/soybean-admin/compare/v0.9.3...main-0428) (23-06-07)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **layouts**:
  - 添加侧边栏/头部的反转模式来增加对比度 &nbsp;-&nbsp; by **元家怿** [<samp>(3c8dd)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3c8dd77)
- **projects**:
  - 新增静态路由 &nbsp;-&nbsp; by @soybeanjs [<samp>(ca2df)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ca2dfa6)
  - 插件方式按需引入naiveUI &nbsp;-&nbsp; by @soybeanjs [<samp>(6bed9)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6bed9ea)
  - 添加请求适配器的请求示例 &nbsp;-&nbsp; by @soybeanjs [<samp>(bed42)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bed4292)
  - 登录页面适配移动端 &nbsp;-&nbsp; by @soybeanjs [<samp>(ec077)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ec0776e)
  - 登录页背景图片位置适配移动端 &nbsp;-&nbsp; by @soybeanjs [<samp>(24010)</samp>](https://github.com/honghuangdc/soybean-admin/commit/24010d0)
  - HTML lang 修改为 zh-cmn-Hans &nbsp;-&nbsp; by @toolvcn [<samp>(dbeb5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/dbeb595)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - 修复vite alias &nbsp;-&nbsp; by @soybeanjs [<samp>(cd7ca)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cd7ca8f)
  - 修复路由守卫的动态路由逻辑 &nbsp;-&nbsp; by @soybeanjs [<samp>(e6c26)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e6c26fc)
  - 全局搜索弹窗弹出时动画闪屏问题 &nbsp;-&nbsp; by @yanbowe [<samp>(bb1bb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bb1bbf2)
  - 去除从环境文件引入端口号导致的错误 &nbsp;-&nbsp; by @soybeanjs [<samp>(2d6d1)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2d6d179)
  - 修复在新版vite下环境变量获取不到的问题 &nbsp;-&nbsp; by @soybeanjs [<samp>(3fb13)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3fb13ca)
  - 修复获取vite环境变量的方式 &nbsp;-&nbsp; by @soybeanjs [<samp>(46e1a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/46e1ae7)
  - 添加获取路由组件文件未找到时的错误提示 &nbsp;-&nbsp; by @honghuangdc [<samp>(219f8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/219f87f)

### &nbsp;&nbsp;&nbsp;🔥 Performance

- refresh-koken命名 &nbsp;-&nbsp; by @southliu [<samp>(17155)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1715504)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - lint命令修改 &nbsp;-&nbsp; by @soybeanjs [<samp>(20911)</samp>](https://github.com/honghuangdc/soybean-admin/commit/20911dd)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(e8b53)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e8b534b)
  - 去除在pinia的getters的函数调用副作用，用watch代替 &nbsp;-&nbsp; by @soybeanjs [<samp>(b35ed)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b35ed89)
  - 代码优化 &nbsp;-&nbsp; by @honghuangdc [<samp>(5e276)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5e27642)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(21645)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2164553)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(9a90f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9a90f18)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(60a55)</samp>](https://github.com/honghuangdc/soybean-admin/commit/60a55a7)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**: update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(cecce)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cecce83)
- **projects**: vite.config代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(ca707)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ca707a4)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **deps**: update deps &nbsp;-&nbsp; by @soybeanjs [<samp>(4eb46)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4eb46ea)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **projects**: update prettier config &nbsp;-&nbsp; by @honghuangdc [<samp>(df56a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/df56abe)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![toolvcn](https://github.com/toolvcn.png?size=48)](https://github.com/toolvcn)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;[![southliu](https://github.com/southliu.png?size=48)](https://github.com/southliu)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;
[元家怿](mailto:jiayi.yuan@luckincoffee.com),&nbsp;

## [v0.9.3](https://github.com/honghuangdc/soybean-admin/compare/old-version...v0.9.3) (2022-03-12)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **components**:
  - svgIcon,添加type,调整size方案 &nbsp;-&nbsp; by @Lsq128 [<samp>(ce4e0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ce4e039)
- **projects**:
  - 路由页面跳转权限完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(0d2a5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0d2a562)
  - 集成naiveUI主题配置，将css vars添加至html &nbsp;-&nbsp; by @soybeanjs [<samp>(2c196)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2c19684)
  - 初始化加载效果：应用主题颜色 &nbsp;-&nbsp; by @honghuangdc [<samp>(035fa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/035fa11)
  - 登录页面开始迁移 &nbsp;-&nbsp; by @honghuangdc [<samp>(f5a36)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f5a36a0)
  - 迁移登录完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(b93b8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b93b80c)
  - 添加NaiveProvider组件 &nbsp;-&nbsp; by @honghuangdc [<samp>(c804b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c804b21)
  - 多级路由的所有子路由转换成二级路由 &nbsp;-&nbsp; by @honghuangdc [<samp>(85b55)</samp>](https://github.com/honghuangdc/soybean-admin/commit/85b55bb)
  - 新增BasicLayout布局 &nbsp;-&nbsp; by @soybeanjs [<samp>(00646)</samp>](https://github.com/honghuangdc/soybean-admin/commit/006467a)
  - 创建自定义布局组件SoybeanLayout &nbsp;-&nbsp; by @honghuangdc [<samp>(0653f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0653fb1)
  - 添加抽屉 &nbsp;-&nbsp; by @honghuangdc [<samp>(10e4d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/10e4d81)
  - theme store完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(bf020)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bf020a8)
  - 主题配置抽屉：迁移暗黑模式、布局模式、添加颜色选择面板 &nbsp;-&nbsp; by @soybeanjs [<samp>(912bf)</samp>](https://github.com/honghuangdc/soybean-admin/commit/912bfdf)
  - 主题配置抽屉: 迁移其他功能 &nbsp;-&nbsp; by @soybeanjs [<samp>(6d132)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6d132c5)
  - 添加头部折叠按钮 &nbsp;-&nbsp; by @honghuangdc [<samp>(a090d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a090d39)
  - 添加侧边菜单 &nbsp;-&nbsp; by @soybeanjs [<samp>(e25af)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e25afe2)
  - 面包屑 &nbsp;-&nbsp; by @honghuangdc [<samp>(09c76)</samp>](https://github.com/honghuangdc/soybean-admin/commit/09c7658)
  - 请求拦截器添加刷新token &nbsp;-&nbsp; by @honghuangdc [<samp>(839b8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/839b82b)
  - 细节完善 &nbsp;-&nbsp; by @soybeanjs [<samp>(cc290)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cc290ac)
  - 迁移多页签 &nbsp;-&nbsp; by @soybeanjs [<samp>(28efb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/28efbdb)
  - 细节完善、迁移页面 &nbsp;-&nbsp; by @soybeanjs [<samp>(ce531)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ce531ce)
  - 添加页面缓存、记录在tab中的缓存页面的滚动条位置 &nbsp;-&nbsp; by @soybeanjs [<samp>(1d63a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1d63a83)
  - 添加缓存主题色 &nbsp;-&nbsp; by @soybeanjs [<samp>(37092)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3709297)
  - 新版重构完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(68b42)</samp>](https://github.com/honghuangdc/soybean-admin/commit/68b4230)
  - 迁移全局搜索菜单功能 &nbsp;-&nbsp; by @yanbowe [<samp>(554d7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/554d7fd)
  - 添加naiveUI按需引入 &nbsp;-&nbsp; by @soybeanjs [<samp>(a810e)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a810ef8)
  - 添加SvgIcon,配置vite plugin &nbsp;-&nbsp; by **Liushengqun** [<samp>(378d5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/378d55a)
  - 引入soybean-admin-tab、去除vite-plugin-svg-icons，用unplugin-icons实现自定义svg的iconify写法、代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(a1a57)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a1a57a1)
  - 新增子菜单图标和多页签图标 &nbsp;-&nbsp; by @soybeanjs [<samp>(f5c56)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f5c56c3)
  - 重构项目的TS类型架构，去除interface文件夹 &nbsp;-&nbsp; by @soybeanjs [<samp>(81914)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8191490)
  - 添加网络代理 &nbsp;-&nbsp; by @soybeanjs [<samp>(094dc)</samp>](https://github.com/honghuangdc/soybean-admin/commit/094dca9)
  - 添加全局组件自动引入注册 &nbsp;-&nbsp; by @soybeanjs [<samp>(f5a04)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f5a043b)
  - 新增自定义svg图标动态渲染 &nbsp;-&nbsp; by @soybeanjs [<samp>(f83c7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f83c7b5)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**:
  - 修复Tab在移动端设备无法点击的问题 &nbsp;-&nbsp; by @honghuangdc [<samp>(2c966)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2c9660f)
  - 修复组件LoadingEmptyWrapper适应暗黑模式 &nbsp;-&nbsp; by @soybeanjs [<samp>(811b1)</samp>](https://github.com/honghuangdc/soybean-admin/commit/811b15e)
  - 组件LoadingEmptyWrapper添加背景颜色动画过渡 &nbsp;-&nbsp; by @soybeanjs [<samp>(7add5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7add5c2)
- **projects**:
  - 修复redirect-not-found子路由 &nbsp;-&nbsp; by @honghuangdc [<samp>(5bfb8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5bfb819)
  - 去除Layout组件冗余代码 &nbsp;-&nbsp; by @honghuangdc [<samp>(0e783)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0e783bc)
  - 修复面包屑数据 &nbsp;-&nbsp; by @honghuangdc [<samp>(28b5d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/28b5d22)
  - 修复vertical-mix布局、重构初始化的loading &nbsp;-&nbsp; by @soybeanjs [<samp>(579e0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/579e074)
  - 修复未登录时会调用获取用户路由的接口 &nbsp;-&nbsp; by @soybeanjs [<samp>(21bab)</samp>](https://github.com/honghuangdc/soybean-admin/commit/21bab1f)
  - 修复路由守卫的动态路由逻辑 &nbsp;-&nbsp; by @soybeanjs [<samp>(b61b0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b61b0ce)
  - vite配置修复 &nbsp;-&nbsp; by @soybeanjs [<samp>(facc0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/facc00e)
  - 修复分析页和工作台的布局问题 &nbsp;-&nbsp; by @honghuangdc [<samp>(e93b9)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e93b94c)
  - 修复项目配置拷贝功能 &nbsp;-&nbsp; by @soybeanjs [<samp>(a7a26)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a7a269d)
  - 修复页面切换动画无变化 &nbsp;-&nbsp; by @soybeanjs [<samp>(c4546)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c4546bd)
  - 修复页面切换动画开关不生效 &nbsp;-&nbsp; by @bundlejs [<samp>(9d4ed)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9d4ed61)
  - 修复 BASE_URL 没有生效的问题 &nbsp;-&nbsp; by @pany-ang [<samp>(72d7d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/72d7dcf)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **components**:
  - 去除packages的soybean-layout，通过npm的方式引入 &nbsp;-&nbsp; by @soybeanjs [<samp>(c1182)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c1182fe)
- **projects**:
  - 精简版+动态路由权限初步 &nbsp;-&nbsp; by @soybeanjs [<samp>(de205)</samp>](https://github.com/honghuangdc/soybean-admin/commit/de2057f)
  - 单独一级路由相关逻辑重构 &nbsp;-&nbsp; by @honghuangdc [<samp>(ab9a6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ab9a6a2)
  - 单独路由逻辑重构、路由转换函数优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(b36a6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b36a62b)
  - 恢复pinia默认写法 &nbsp;-&nbsp; by @soybeanjs [<samp>(b2a4d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b2a4ddf)
  - 请求构造函数适配不同后端接口的数据结构 &nbsp;-&nbsp; by @soybeanjs [<samp>(4f9d5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4f9d544)
  - 细节完善 &nbsp;-&nbsp; by @soybeanjs [<samp>(651e5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/651e58d)
  - 重构路由页面组件的导入 &nbsp;-&nbsp; by @honghuangdc [<samp>(e6503)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e65034d)
  - 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(4e31a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4e31abd)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **other**:
  - 注释文案修改 &nbsp;-&nbsp; by **毛博文** [<samp>(d0064)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d00643c)
- **projects**:
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(5eddb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5eddb49)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(02c51)</samp>](https://github.com/honghuangdc/soybean-admin/commit/02c51e6)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(47f28)</samp>](https://github.com/honghuangdc/soybean-admin/commit/47f2871)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(7ed5d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7ed5d0d)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(3befb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3befb22)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(e856c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e856cdb)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(3aded)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3aded40)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(225e7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/225e712)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(5b401)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5b401a7)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(8cdad)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8cdad54)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(a0dfa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a0dfa3d)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(b8db2)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b8db211)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**:
  - 升级依赖 &nbsp;-&nbsp; by @soybeanjs [<samp>(284af)</samp>](https://github.com/honghuangdc/soybean-admin/commit/284af63)
  - 升级依赖 &nbsp;-&nbsp; by @soybeanjs [<samp>(57c69)</samp>](https://github.com/honghuangdc/soybean-admin/commit/57c692b)
  - 升级依赖 &nbsp;-&nbsp; by @soybeanjs [<samp>(7ba33)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7ba332c)
  - upgrade deps &nbsp;-&nbsp; by @soybeanjs [<samp>(50c8b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/50c8b9d)
  - upgrade deps &nbsp;-&nbsp; by @soybeanjs [<samp>(8d00b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8d00b23)
  - upgrade deps &nbsp;-&nbsp; by @soybeanjs [<samp>(b298a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b298af1)
- **projects**:
  - 修改vscode配置 &nbsp;-&nbsp; by @honghuangdc [<samp>(0c577)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0c5770d)
  - 添加vercel打包的环境 &nbsp;-&nbsp; by @honghuangdc [<samp>(371fa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/371fad4)
  - add license &nbsp;-&nbsp; by @soybeanjs [<samp>(b1672)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b16721b)
  - 更新tsconfig.json &nbsp;-&nbsp; by @soybeanjs [<samp>(f42ee)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f42ee9d)
  - update tsconfig、eslintrc &nbsp;-&nbsp; by @soybeanjs [<samp>(75de2)</samp>](https://github.com/honghuangdc/soybean-admin/commit/75de2b0)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**:
  - 0.1.1 精简版发布 &nbsp;-&nbsp; by @soybeanjs [<samp>(db3c2)</samp>](https://github.com/honghuangdc/soybean-admin/commit/db3c25e)
  - 0.1.2 &nbsp;-&nbsp; by @soybeanjs [<samp>(db75c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/db75c91)
  - 0.1.3 &nbsp;-&nbsp; by @soybeanjs [<samp>(32a7c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/32a7cc4)
  - 0.9.1 &nbsp;-&nbsp; by @soybeanjs [<samp>(be374)</samp>](https://github.com/honghuangdc/soybean-admin/commit/be37408)
  - 0.9.2 &nbsp;-&nbsp; by @honghuangdc [<samp>(11407)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1140722)
  - 0.9.3 &nbsp;-&nbsp; by @soybeanjs [<samp>(d0522)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d0522ce)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **components**: 代码优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(1e2fd)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1e2fdda)
- **projects**: 路由相关文件夹简化 &nbsp;-&nbsp; by @honghuangdc [<samp>(e5793)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e5793e1)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![pany-ang](https://github.com/pany-ang.png?size=48)](https://github.com/pany-ang)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![bundlejs](https://github.com/bundlejs.png?size=48)](https://github.com/bundlejs)&nbsp;&nbsp;[![Lsq128](https://github.com/Lsq128.png?size=48)](https://github.com/Lsq128)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;
[毛博文](mailto:maobowen@bonc.com.cn),&nbsp;[Liushengqun](mailto:18232366809@163.com),&nbsp;

## [v0.10.2](https://github.com/honghuangdc/soybean-admin/compare/v0.9.2...old-version) (23-06-07)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - 路由页面跳转权限完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(0d2a5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0d2a562)
  - 集成naiveUI主题配置，将css vars添加至html &nbsp;-&nbsp; by @soybeanjs [<samp>(2c196)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2c19684)
  - 初始化加载效果：应用主题颜色 &nbsp;-&nbsp; by @honghuangdc [<samp>(035fa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/035fa11)
  - 登录页面开始迁移 &nbsp;-&nbsp; by @honghuangdc [<samp>(f5a36)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f5a36a0)
  - 迁移登录完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(b93b8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b93b80c)
  - 添加NaiveProvider组件 &nbsp;-&nbsp; by @honghuangdc [<samp>(c804b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c804b21)
  - 多级路由的所有子路由转换成二级路由 &nbsp;-&nbsp; by @honghuangdc [<samp>(85b55)</samp>](https://github.com/honghuangdc/soybean-admin/commit/85b55bb)
  - 新增BasicLayout布局 &nbsp;-&nbsp; by @soybeanjs [<samp>(00646)</samp>](https://github.com/honghuangdc/soybean-admin/commit/006467a)
  - 创建自定义布局组件SoybeanLayout &nbsp;-&nbsp; by @honghuangdc [<samp>(0653f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0653fb1)
  - 添加抽屉 &nbsp;-&nbsp; by @honghuangdc [<samp>(10e4d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/10e4d81)
  - theme store完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(bf020)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bf020a8)
  - 主题配置抽屉：迁移暗黑模式、布局模式、添加颜色选择面板 &nbsp;-&nbsp; by @soybeanjs [<samp>(912bf)</samp>](https://github.com/honghuangdc/soybean-admin/commit/912bfdf)
  - 主题配置抽屉: 迁移其他功能 &nbsp;-&nbsp; by @soybeanjs [<samp>(6d132)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6d132c5)
  - 添加头部折叠按钮 &nbsp;-&nbsp; by @honghuangdc [<samp>(a090d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a090d39)
  - 添加侧边菜单 &nbsp;-&nbsp; by @soybeanjs [<samp>(e25af)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e25afe2)
  - 面包屑 &nbsp;-&nbsp; by @honghuangdc [<samp>(09c76)</samp>](https://github.com/honghuangdc/soybean-admin/commit/09c7658)
  - 请求拦截器添加刷新token &nbsp;-&nbsp; by @honghuangdc [<samp>(839b8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/839b82b)
  - 细节完善 &nbsp;-&nbsp; by @soybeanjs [<samp>(cc290)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cc290ac)
  - 迁移多页签 &nbsp;-&nbsp; by @soybeanjs [<samp>(28efb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/28efbdb)
  - 细节完善、迁移页面 &nbsp;-&nbsp; by @soybeanjs [<samp>(ce531)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ce531ce)
  - 添加页面缓存、记录在tab中的缓存页面的滚动条位置 &nbsp;-&nbsp; by @soybeanjs [<samp>(1d63a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1d63a83)
  - 添加缓存主题色 &nbsp;-&nbsp; by @soybeanjs [<samp>(37092)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3709297)
  - 新版重构完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(68b42)</samp>](https://github.com/honghuangdc/soybean-admin/commit/68b4230)
  - 迁移全局搜索菜单功能 &nbsp;-&nbsp; by @yanbowe [<samp>(554d7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/554d7fd)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**:
  - 修复Tab在移动端设备无法点击的问题 &nbsp;-&nbsp; by @honghuangdc [<samp>(2c966)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2c9660f)
- **projects**:
  - 修复redirect-not-found子路由 &nbsp;-&nbsp; by @honghuangdc [<samp>(5bfb8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5bfb819)
  - 去除Layout组件冗余代码 &nbsp;-&nbsp; by @honghuangdc [<samp>(0e783)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0e783bc)
  - 修复面包屑数据 &nbsp;-&nbsp; by @honghuangdc [<samp>(28b5d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/28b5d22)
  - 修复vertical-mix布局、重构初始化的loading &nbsp;-&nbsp; by @soybeanjs [<samp>(579e0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/579e074)
  - 修复未登录时会调用获取用户路由的接口 &nbsp;-&nbsp; by @soybeanjs [<samp>(21bab)</samp>](https://github.com/honghuangdc/soybean-admin/commit/21bab1f)
  - 修复路由守卫的动态路由逻辑 &nbsp;-&nbsp; by @soybeanjs [<samp>(b61b0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b61b0ce)
  - vite配置修复 &nbsp;-&nbsp; by @soybeanjs [<samp>(facc0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/facc00e)
  - 修复分析页和工作台的布局问题 &nbsp;-&nbsp; by @honghuangdc [<samp>(e93b9)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e93b94c)
  - 修复项目配置拷贝功能 &nbsp;-&nbsp; by @soybeanjs [<samp>(a7a26)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a7a269d)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - 精简版+动态路由权限初步 &nbsp;-&nbsp; by @soybeanjs [<samp>(de205)</samp>](https://github.com/honghuangdc/soybean-admin/commit/de2057f)
  - 单独一级路由相关逻辑重构 &nbsp;-&nbsp; by @honghuangdc [<samp>(ab9a6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ab9a6a2)
  - 单独路由逻辑重构、路由转换函数优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(b36a6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b36a62b)
  - 恢复pinia默认写法 &nbsp;-&nbsp; by @soybeanjs [<samp>(b2a4d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b2a4ddf)
  - 请求构造函数适配不同后端接口的数据结构 &nbsp;-&nbsp; by @soybeanjs [<samp>(4f9d5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4f9d544)
  - 细节完善 &nbsp;-&nbsp; by @soybeanjs [<samp>(651e5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/651e58d)
  - 重构路由页面组件的导入 &nbsp;-&nbsp; by @honghuangdc [<samp>(e6503)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e65034d)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(5eddb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5eddb49)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(02c51)</samp>](https://github.com/honghuangdc/soybean-admin/commit/02c51e6)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(47f28)</samp>](https://github.com/honghuangdc/soybean-admin/commit/47f2871)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(7ed5d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7ed5d0d)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(3befb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3befb22)

### &nbsp;&nbsp;&nbsp;📦 Build

- **projects**:
  - 修改vscode配置 &nbsp;-&nbsp; by @honghuangdc [<samp>(0c577)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0c5770d)
  - 添加vercel打包的环境 &nbsp;-&nbsp; by @honghuangdc [<samp>(371fa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/371fad4)
  - add license &nbsp;-&nbsp; by @soybeanjs [<samp>(b1672)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b16721b)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**:
  - 0.1.1 精简版发布 &nbsp;-&nbsp; by @soybeanjs [<samp>(db3c2)</samp>](https://github.com/honghuangdc/soybean-admin/commit/db3c25e)
  - 0.1.2 &nbsp;-&nbsp; by @soybeanjs [<samp>(db75c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/db75c91)
  - 0.1.3 &nbsp;-&nbsp; by @soybeanjs [<samp>(32a7c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/32a7cc4)
  - 0.9.1 &nbsp;-&nbsp; by @soybeanjs [<samp>(be374)</samp>](https://github.com/honghuangdc/soybean-admin/commit/be37408)
  - 0.9.2 &nbsp;-&nbsp; by @honghuangdc [<samp>(11407)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1140722)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **projects**: 路由相关文件夹简化 &nbsp;-&nbsp; by @honghuangdc [<samp>(e5793)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e5793e1)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;

## [v0.9.2](https://github.com/honghuangdc/soybean-admin/compare/v0.9.1...v0.9.2) (2022-02-11)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**: 迁移全局搜索菜单功能 &nbsp;-&nbsp; by @yanbowe [<samp>(554d7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/554d7fd)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**:
  - 修复Tab在移动端设备无法点击的问题 &nbsp;-&nbsp; by @honghuangdc [<samp>(2c966)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2c9660f)
- **projects**:
  - vite配置修复 &nbsp;-&nbsp; by @soybeanjs [<samp>(facc0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/facc00e)
  - 修复分析页和工作台的布局问题 &nbsp;-&nbsp; by @honghuangdc [<samp>(e93b9)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e93b94c)
  - 修复项目配置拷贝功能 &nbsp;-&nbsp; by @soybeanjs [<samp>(a7a26)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a7a269d)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**: 重构路由页面组件的导入 &nbsp;-&nbsp; by @honghuangdc [<samp>(e6503)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e65034d)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(02c51)</samp>](https://github.com/honghuangdc/soybean-admin/commit/02c51e6)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(47f28)</samp>](https://github.com/honghuangdc/soybean-admin/commit/47f2871)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(7ed5d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7ed5d0d)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(3befb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3befb22)

### &nbsp;&nbsp;&nbsp;📦 Build

- **projects**: add license &nbsp;-&nbsp; by @soybeanjs [<samp>(b1672)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b16721b)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**: 0.9.2 &nbsp;-&nbsp; by @honghuangdc [<samp>(11407)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1140722)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;

## [v0.9.1](https://github.com/honghuangdc/soybean-admin/compare/v0.1.3...v0.9.1) (2022-01-24)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**: 新版重构完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(68b42)</samp>](https://github.com/honghuangdc/soybean-admin/commit/68b4230)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**: 0.9.1 &nbsp;-&nbsp; by @soybeanjs [<samp>(be374)</samp>](https://github.com/honghuangdc/soybean-admin/commit/be37408)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;

## [v0.1.3](https://github.com/honghuangdc/soybean-admin/compare/v0.1.2...v0.1.3) (2022-01-24)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **projects**:
  - 修复未登录时会调用获取用户路由的接口 &nbsp;-&nbsp; by @soybeanjs [<samp>(21bab)</samp>](https://github.com/honghuangdc/soybean-admin/commit/21bab1f)
  - 修复路由守卫的动态路由逻辑 &nbsp;-&nbsp; by @soybeanjs [<samp>(b61b0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b61b0ce)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - 请求构造函数适配不同后端接口的数据结构 &nbsp;-&nbsp; by @soybeanjs [<samp>(4f9d5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4f9d544)
  - 细节完善 &nbsp;-&nbsp; by @soybeanjs [<samp>(651e5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/651e58d)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**: 0.1.3 &nbsp;-&nbsp; by @soybeanjs [<samp>(32a7c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/32a7cc4)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;

## [v0.1.2](https://github.com/honghuangdc/soybean-admin/compare/v0.1.1...v0.1.2) (2022-01-22)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - 添加页面缓存、记录在tab中的缓存页面的滚动条位置 &nbsp;-&nbsp; by @soybeanjs [<samp>(1d63a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1d63a83)
  - 添加缓存主题色 &nbsp;-&nbsp; by @soybeanjs [<samp>(37092)</samp>](https://github.com/honghuangdc/soybean-admin/commit/3709297)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**: 0.1.2 &nbsp;-&nbsp; by @soybeanjs [<samp>(db75c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/db75c91)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;

## [v0.1.1](https://github.com/honghuangdc/soybean-admin/compare/v0.0.5...v0.1.1) (2022-01-20)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**:
  - 添加路由跳转浏览器新标签 &nbsp;-&nbsp; by @honghuangdc [<samp>(987ce)</samp>](https://github.com/honghuangdc/soybean-admin/commit/987cef3)
  - 添加常用组件、composables函数 &nbsp;-&nbsp; by @soybeanjs [<samp>(230a5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/230a50a)
  - 添加表格页面示例 &nbsp;-&nbsp; by @soybeanjs [<samp>(51c74)</samp>](https://github.com/honghuangdc/soybean-admin/commit/51c744c)
  - 增加Icon选择器组件 &nbsp;-&nbsp; by @yanbowe [<samp>(9472b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9472b51)
  - 图标选择器增加扩展树形 &nbsp;-&nbsp; by @yanbowe [<samp>(04101)</samp>](https://github.com/honghuangdc/soybean-admin/commit/041012b)
  - 增加项目文档外链 &nbsp;-&nbsp; by @yanbowe [<samp>(1901a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1901a0b)
  - 引入mockjs &nbsp;-&nbsp; by @soybeanjs [<samp>(9bc68)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9bc682d)
  - 增加全局搜索菜单功能 &nbsp;-&nbsp; by @yanbowe [<samp>(b9ce6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b9ce691)
  - 菜单搜索增加大小写转换 &nbsp;-&nbsp; by @yanbowe [<samp>(29078)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2907868)
  - 添加cryptojs，对本地缓存数据进行加密 &nbsp;-&nbsp; by @soybeanjs [<samp>(7a064)</samp>](https://github.com/honghuangdc/soybean-admin/commit/7a0648d)
  - 路由页面跳转权限完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(0d2a5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0d2a562)
  - 集成naiveUI主题配置，将css vars添加至html &nbsp;-&nbsp; by @soybeanjs [<samp>(2c196)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2c19684)
  - 初始化加载效果：应用主题颜色 &nbsp;-&nbsp; by @honghuangdc [<samp>(035fa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/035fa11)
  - 登录页面开始迁移 &nbsp;-&nbsp; by @honghuangdc [<samp>(f5a36)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f5a36a0)
  - 迁移登录完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(b93b8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b93b80c)
  - 添加NaiveProvider组件 &nbsp;-&nbsp; by @honghuangdc [<samp>(c804b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c804b21)
  - 多级路由的所有子路由转换成二级路由 &nbsp;-&nbsp; by @honghuangdc [<samp>(85b55)</samp>](https://github.com/honghuangdc/soybean-admin/commit/85b55bb)
  - 新增BasicLayout布局 &nbsp;-&nbsp; by @soybeanjs [<samp>(00646)</samp>](https://github.com/honghuangdc/soybean-admin/commit/006467a)
  - 创建自定义布局组件SoybeanLayout &nbsp;-&nbsp; by @honghuangdc [<samp>(0653f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0653fb1)
  - 添加抽屉 &nbsp;-&nbsp; by @honghuangdc [<samp>(10e4d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/10e4d81)
  - theme store完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(bf020)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bf020a8)
  - 主题配置抽屉：迁移暗黑模式、布局模式、添加颜色选择面板 &nbsp;-&nbsp; by @soybeanjs [<samp>(912bf)</samp>](https://github.com/honghuangdc/soybean-admin/commit/912bfdf)
  - 主题配置抽屉: 迁移其他功能 &nbsp;-&nbsp; by @soybeanjs [<samp>(6d132)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6d132c5)
  - 添加头部折叠按钮 &nbsp;-&nbsp; by @honghuangdc [<samp>(a090d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a090d39)
  - 添加侧边菜单 &nbsp;-&nbsp; by @soybeanjs [<samp>(e25af)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e25afe2)
  - 面包屑 &nbsp;-&nbsp; by @honghuangdc [<samp>(09c76)</samp>](https://github.com/honghuangdc/soybean-admin/commit/09c7658)
  - 请求拦截器添加刷新token &nbsp;-&nbsp; by @honghuangdc [<samp>(839b8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/839b82b)
  - 细节完善 &nbsp;-&nbsp; by @soybeanjs [<samp>(cc290)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cc290ac)
  - 迁移多页签 &nbsp;-&nbsp; by @soybeanjs [<samp>(28efb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/28efbdb)
  - 细节完善、迁移页面 &nbsp;-&nbsp; by @soybeanjs [<samp>(ce531)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ce531ce)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **deps**:
  - 降低vite版本 &nbsp;-&nbsp; by @honghuangdc [<samp>(c9c5c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c9c5ca9)
- **projects**:
  - 修复网络请求错误空信息的提示 &nbsp;-&nbsp; by @honghuangdc [<samp>(ff921)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ff9216b)
  - 请求相关细节修复 &nbsp;-&nbsp; by @honghuangdc [<samp>(2ad1a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/2ad1ad3)
  - 修复redirect-not-found子路由 &nbsp;-&nbsp; by @honghuangdc [<samp>(5bfb8)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5bfb819)
  - 去除Layout组件冗余代码 &nbsp;-&nbsp; by @honghuangdc [<samp>(0e783)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0e783bc)
  - 修复面包屑数据 &nbsp;-&nbsp; by @honghuangdc [<samp>(28b5d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/28b5d22)
  - 修复vertical-mix布局、重构初始化的loading &nbsp;-&nbsp; by @soybeanjs [<samp>(579e0)</samp>](https://github.com/honghuangdc/soybean-admin/commit/579e074)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - 登录模块由query变更为动态路由params &nbsp;-&nbsp; by @honghuangdc [<samp>(225c4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/225c4fe)
  - 精简版+动态路由权限初步 &nbsp;-&nbsp; by @soybeanjs [<samp>(de205)</samp>](https://github.com/honghuangdc/soybean-admin/commit/de2057f)
  - 单独一级路由相关逻辑重构 &nbsp;-&nbsp; by @honghuangdc [<samp>(ab9a6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ab9a6a2)
  - 单独路由逻辑重构、路由转换函数优化 &nbsp;-&nbsp; by @soybeanjs [<samp>(b36a6)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b36a62b)
  - 恢复pinia默认写法 &nbsp;-&nbsp; by @soybeanjs [<samp>(b2a4d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/b2a4ddf)
- **styles**:
  - 样式调整 &nbsp;-&nbsp; by @honghuangdc [<samp>(f2910)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f29106e)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(659e4)</samp>](https://github.com/honghuangdc/soybean-admin/commit/659e460)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(90ddf)</samp>](https://github.com/honghuangdc/soybean-admin/commit/90ddf98)
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(5eddb)</samp>](https://github.com/honghuangdc/soybean-admin/commit/5eddb49)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**:
  - 升级依赖 &nbsp;-&nbsp; by @soybeanjs [<samp>(ae7ec)</samp>](https://github.com/honghuangdc/soybean-admin/commit/ae7ec99)
  - 升级依赖 &nbsp;-&nbsp; by @soybeanjs [<samp>(e755c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e755caa)
  - 升级依赖 &nbsp;-&nbsp; by @honghuangdc [<samp>(f3c86)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f3c86ef)
  - 升级依赖 &nbsp;-&nbsp; by @honghuangdc [<samp>(e776d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e776df4)
  - 升级依赖 &nbsp;-&nbsp; by @soybeanjs [<samp>(777cf)</samp>](https://github.com/honghuangdc/soybean-admin/commit/777cf8e)
- **projects**:
  - 环境变量获取方式变更 &nbsp;-&nbsp; by @honghuangdc [<samp>(21c2f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/21c2f5a)
  - 修改vscode配置 &nbsp;-&nbsp; by @honghuangdc [<samp>(0c577)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0c5770d)
  - 添加vercel打包的环境 &nbsp;-&nbsp; by @honghuangdc [<samp>(371fa)</samp>](https://github.com/honghuangdc/soybean-admin/commit/371fad4)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**: 0.1.1 精简版发布 &nbsp;-&nbsp; by @soybeanjs [<samp>(db3c2)</samp>](https://github.com/honghuangdc/soybean-admin/commit/db3c25e)

### &nbsp;&nbsp;&nbsp;🎨 Styles

- **projects**: 路由相关文件夹简化 &nbsp;-&nbsp; by @honghuangdc [<samp>(e5793)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e5793e1)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;

## [v0.0.5](https://github.com/honghuangdc/soybean-admin/compare/v0.0.4...v0.0.5) (2021-11-28)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **projects**: 新增组件页面：按钮、卡片示例 &nbsp;-&nbsp; by @soybeanjs [<samp>(bdc39)</samp>](https://github.com/honghuangdc/soybean-admin/commit/bdc39af)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**: 修复HorizontalLayout布局 &nbsp;-&nbsp; by @soybeanjs [<samp>(9fb64)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9fb641f)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - 重构路由类型和路由元数据类型，重构多级菜单路由写法 &nbsp;-&nbsp; by @soybeanjs [<samp>(d6838)</samp>](https://github.com/honghuangdc/soybean-admin/commit/d683894)
  - 优化路由导入页面写法，页面路由调整 &nbsp;-&nbsp; by @soybeanjs [<samp>(0b10b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0b10b50)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**: 升级依赖 &nbsp;-&nbsp; by @soybeanjs [<samp>(a6bdc)</samp>](https://github.com/honghuangdc/soybean-admin/commit/a6bdc38)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**: 0.0.5 &nbsp;-&nbsp; by @soybeanjs [<samp>(e53e7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e53e793)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;

## [v0.0.4](https://github.com/honghuangdc/soybean-admin/compare/v0.0.3...v0.0.4) (2021-11-25)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **components**: 添加多页签Tab点击后自动往中间滚动 &nbsp;-&nbsp; by @soybeanjs [<samp>(8ce62)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8ce627a)
- **projects**: 新增网址导航页面 &nbsp;-&nbsp; by @honghuangdc [<samp>(32aa5)</samp>](https://github.com/honghuangdc/soybean-admin/commit/32aa5ee)
- **storage**: local存储增加有效期 &nbsp;-&nbsp; by @yanbowe [<samp>(e6c9b)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e6c9b35)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **components**:
  - 修复多页签Tab自动滚动问题 &nbsp;-&nbsp; by @soybeanjs [<samp>(20aa3)</samp>](https://github.com/honghuangdc/soybean-admin/commit/20aa39f)
  - 修复多页签按钮风格的tab滚动问题 &nbsp;-&nbsp; by @soybeanjs [<samp>(c429c)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c429cd0)
- **projects**:
  - 修复打包构建时图标错误 &nbsp;-&nbsp; by @soybeanjs [<samp>(93f9a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/93f9aa9)
  - 添加西瓜视频实例在onUnMounted的销毁，多页签居中距离精确 &nbsp;-&nbsp; by @soybeanjs [<samp>(73896)</samp>](https://github.com/honghuangdc/soybean-admin/commit/738964a)
- **types**:
  - 添加dotEnv类型的非空判断 &nbsp;-&nbsp; by @soybeanjs [<samp>(cff11)</samp>](https://github.com/honghuangdc/soybean-admin/commit/cff11d9)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **components**:
  - blankLayout引入GlobalContent &nbsp;-&nbsp; by @soybeanjs [<samp>(1ffb7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1ffb75a)
- **projects**:
  - axios处理的请求结果去除网路状态 &nbsp;-&nbsp; by @honghuangdc [<samp>(05696)</samp>](https://github.com/honghuangdc/soybean-admin/commit/0569666)
  - 文件夹位置规范 &nbsp;-&nbsp; by @honghuangdc [<samp>(f5a5f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/f5a5f44)
  - 细节完善 &nbsp;-&nbsp; by @honghuangdc [<samp>(62611)</samp>](https://github.com/honghuangdc/soybean-admin/commit/6261156)

### &nbsp;&nbsp;&nbsp;📖 Documentation

- **projects**:
  - update README.md &nbsp;-&nbsp; by @soybeanjs [<samp>(54577)</samp>](https://github.com/honghuangdc/soybean-admin/commit/54577f1)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(1b346)</samp>](https://github.com/honghuangdc/soybean-admin/commit/1b3463d)
  - update README.md &nbsp;-&nbsp; by @honghuangdc [<samp>(98a7d)</samp>](https://github.com/honghuangdc/soybean-admin/commit/98a7d25)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**: 0.0.4 &nbsp;-&nbsp; by @soybeanjs [<samp>(8b27f)</samp>](https://github.com/honghuangdc/soybean-admin/commit/8b27fc8)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![yanbowe](https://github.com/yanbowe.png?size=48)](https://github.com/yanbowe)&nbsp;&nbsp;

## [v0.0.3](https://github.com/honghuangdc/soybean-admin/compare/v0.0.2...v0.0.3) (2021-11-23)

### &nbsp;&nbsp;&nbsp;💅 Refactors

- **projects**:
  - 请求函数重构初步 &nbsp;-&nbsp; by @soybeanjs [<samp>(9f643)</samp>](https://github.com/honghuangdc/soybean-admin/commit/9f64321)
  - axios封装：文件夹规范，错误处理完善 &nbsp;-&nbsp; by @honghuangdc [<samp>(451c7)</samp>](https://github.com/honghuangdc/soybean-admin/commit/451c754)
  - axios封装完成 &nbsp;-&nbsp; by @soybeanjs [<samp>(03b39)</samp>](https://github.com/honghuangdc/soybean-admin/commit/03b398a)

### &nbsp;&nbsp;&nbsp;📦 Build

- **deps**:
  - 升级依赖 &nbsp;-&nbsp; by @soybeanjs [<samp>(4e04a)</samp>](https://github.com/honghuangdc/soybean-admin/commit/4e04a8f)
  - 升级依赖 &nbsp;-&nbsp; by @soybeanjs [<samp>(c8122)</samp>](https://github.com/honghuangdc/soybean-admin/commit/c81221e)

### &nbsp;&nbsp;&nbsp;🏡 Chore

- **release**: 0.0.3 &nbsp;-&nbsp; by @honghuangdc [<samp>(e1dac)</samp>](https://github.com/honghuangdc/soybean-admin/commit/e1dacdb)

### &nbsp;&nbsp;&nbsp;❤️ Contributors

[![honghuangdc](https://github.com/honghuangdc.png?size=48)](https://github.com/honghuangdc)&nbsp;&nbsp;[![soybeanjs](https://github.com/soybeanjs.png?size=48)](https://github.com/soybeanjs)&nbsp;&nbsp;



