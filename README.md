UE5.6+ StarterContent 补充包
简介
针对 Unreal Engine 5.6 及以上版本新建项目时，默认不再内置 StarterContent 初学者内容包的问题，本仓库提供完整的官方 StarterContent 资源包，可直接导入你的UE项目中使用。

包含基础材质、静态模型、粒子特效、道具资产、基础形状、通用纹理，以及两张示例地图（StarterMap、Advanced_Lighting），适合新手入门学习、快速搭建原型场景和光照测试。

目录结构
压缩包内根目录为 StarterContent 文件夹，解压放入项目Content目录后结构完全匹配官方标准：

Content/
└── StarterContent/
    ├── Materials/
    ├── Meshes/
    ├── Particles/
    ├── Props/
    ├── Shapes/
    ├── Textures/
    └── Maps/
        ├── StarterMap
        └── Advanced_Lighting
安装使用步骤
完全关闭你的UE项目，避免资源加载冲突或材质丢失
下载 StarterContent.zip 压缩包
若压缩包通过 Releases 分发，请前往本仓库的 Releases 页面下载最新版本
打开你的UE项目根目录，进入 Content 文件夹
参考路径：你的项目名称/Content/
将 StarterContent.zip 解压到当前 Content 目录内
解压完成后，Content 文件夹下会出现完整的 StarterContent 子文件夹
重新打开UE项目，在内容浏览器中即可看到 StarterContent 目录下的全部资源
注意事项
兼容 UE 5.6 / 5.7 及更高版本，UE5.0-5.5也可通用
若你的项目中已有同名 StarterContent 文件夹，请先备份原有资源后再解压覆盖
若打开项目后资源显示红色丢失，可在内容浏览器右键 StarterContent 文件夹，选择「重新导入」或重启项目
