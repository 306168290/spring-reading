## 👋 简介
<img align='right' src='https://octodex.github.com/images/hula_loop_octodex03.gif' width='200'>

![status](https://img.shields.io/badge/status-up-brightgreen) ![Gender](https://img.shields.io/badge/gender-%F0%9F%A4%B5-lightgrey) ![](https://img.shields.io/static/v1?label=wechat&message=xcs19930428&color=7BB32E&logo=wechat) ![](https://visitor-badge.lithub.cc/badge?page_id=github.com/xuchengsheng)

大家好呀，我是Lex。我是一名拥有8年经验的Java 后端开发人员，也是一个对 Spring 框架充满热情的程序员。为了帮助那些希望深入了解 Spring 框架的程序员们，我创建了这个 “Spring 源码阅读系列”。通过这个系列，我希望能够与你们共同探索 Spring 的内部工作机制。如果您有同样的兴趣或问题，请联系我！

## 🙏顺手点个星？

亲爱的朋友们，我真的花了很多心思去研究和整理这个“Spring 源码阅读系列”。如果你觉得这东西还不错，或者给你带来了一点点帮助，麻烦点一下星星吧🌟。这真的对我意义重大，每一颗星都能让我觉得所有的努力都是值得的。我知道这是小事一桩，但你的那一下点击，对我来说就是最好的鼓励。无论如何，都要感谢你抽时间阅读我的内容，真的很感激！

## ⚡技术

![Docker](https://img.shields.io/badge/-Docker-000?&logo=Docker)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-000?&logo=Kubernetes)
![Linux](https://img.shields.io/badge/-Linux-000?&logo=Linux)
![Node.js](https://img.shields.io/badge/-Node.js-000?&logo=node.js)
![React](https://img.shields.io/badge/-React-000?&logo=React)
![Redis](https://img.shields.io/badge/-Redis-000?&logo=Redis)
![Spring](https://img.shields.io/badge/-Spring-000?&logo=Spring)
![MySQL](https://img.shields.io/badge/-MySQL-000?&logo=MySQL)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github)

## 📫与我联系

✉️ [Email](xuchengshengsuper@163.com) | 💬 [Issue](https://github.com/xuchengsheng/spring-reading/issues) | 🌐 [CSDN](https://blog.csdn.net/duzhuang2399?type=blog)  Me about everything!

## ⛵欢迎贡献！

如果你发现任何错误或者有改进建议，欢迎提交 issue 或者 pull request。你的反馈对于我非常宝贵！

## 🌱Spring 源码阅读系列

### 🌱 IOC容器

*探索 Spring 的核心部分，并理解其对象管理的高级策略。*

- [**深入理解IOC容器**](spring-core-ioc/README.md) - 探寻 Spring 如何实现控制反转，提供强大的依赖管理。

### 💡 后置处理器与初始化

*深入 Spring 的后置处理技巧，揭示它如何优雅地初始化和管理 beans。*

- [**动态修改Bean定义BeanDefinitionRegistryPostProcessor**](spring-interface/spring-interface-beanDefinitionRegistryPostProcessor/README.md) - 揭示如何修改应用的 bean 定义。
- [**动态调整Bean配置BeanFactoryPostProcessor**](spring-interface/spring-interface-beanFactoryPostProcessor/README.md) - 理解 Spring 如何在 bean 初始化之前进行微调。
- [**调整Bean属性BeanPostProcessor**](spring-interface/spring-interface-beanPostProcessor/README.md) - 探索如何在 bean 实例化后进行拦截。
- [**Bean实例拦截InstantiationAwareBeanPostProcessor**](spring-interface/spring-interface-instantiationAwareBeanPostProcessor/README.md) - 理解它如何在实例化 bean 之前进行操作。
- [**管理Bean销毁周期DestructionAwareBeanPostProcessor**](spring-interface/spring-interface-destructionAwareBeanPostProcessor/README.md) - 揭露它如何管理 bean 的销毁生命周期。
- [**Bean定义的动态处理MergedBeanDefinitionPostProcessor**](spring-interface/spring-interface-mergedBeanDefinitionPostProcessor/README.md) - 理解如何合并 bean 的定义。
- [**调整Bean实例化策略SmartInstantiationAwareBeanPostProcessor**](spring-interface/spring-interface-smartInstantiationAwareBeanPostProcessor/README.md) - 深入了解其智能实例化的策略。
- [**属性设置后的初始化操作InitializingBean**](spring-interface/spring-interface-initializingBean/README.md) - 揭露如何在 bean 初始化后进行操作。
- [**资源清理与销毁DisposableBean**](spring-interface/spring-interface-disposableBean/README.md) - 探查它如何确保 bean 的正确销毁。
- [**所有单例Beans完全初始化后SmartInitializingSingleton**](spring-interface/spring-interface-smartInitializingSingleton/README.md) - 理解它如何在所有单例 bean 初始化后进行操作。

### 🛠 Aware接口

*探索 Spring 的自我感知能力，如何赋予 beans 更多的上下文感知特性。*

- [**深究BeanNameAware**](spring-aware/spring-aware-beanNameAware/README.md) - 当一个 bean 需要知道其在容器中的名字时。
- [**BeanClassLoaderAware的探查**](spring-aware/spring-aware-beanClassLoaderAware/README.md) - 揭示如何为 bean 提供类加载器的引用。
- [**深度了解BeanFactoryAware**](spring-aware/spring-aware-beanFactoryAware/README.md) - 探索 bean 如何与其工厂互动。
- [**环境感知EnvironmentAware**](spring-aware/spring-aware-environmentAware/README.md) - 了解 bean 如何感知并与其运行的环境互动。
- [**嵌入式值解析EmbeddedValueResolverAware**](spring-aware/spring-aware-embeddedValueResolverAware/README.md) - 探查如何提供字符串值解析策略给 bean。
- [**资源加载策略ResourceLoaderAware**](spring-aware/spring-aware-resourceLoaderAware/README.md) - 理解如何为 bean 提供一个资源加载器。
- [**事件发布感知ApplicationEventPublisherAware**](spring-aware/spring-aware-applicationEventPublisherAware/README.md) - 揭露 bean 如何发布事件到应用上下文。
- [**消息源感知MessageSourceAware**](spring-aware/spring-aware-messageSourceAware/README.md) - 深入了解 bean 如何访问消息源。
- [**应用启动感知ApplicationStartupAware**](spring-aware/spring-aware-applicationStartupAware/README.md) - 理解 bean 如何感知应用的启动过程。
- [**上下文感知ApplicationContextAware**](spring-aware/spring-aware-applicationContextAware/README.md) - 探索 bean 如何访问其运行的应用上下文。
- [**导入感知ImportAware**](spring-aware/spring-aware-importAware/README.md) - 揭露 bean 如何知道与其关联的导入元数据。

### 🎖 核心注解

*了解 Spring 如何通过注解驱动开发，简化和加强代码。*

- [**解析@Configuration的力量**](spring-annotation/spring-annotation-configuration/README.md) - 揭露如何使用 Java 配置定义 beans。
- [**组件扫描的魅力@ComponentScan**](spring-annotation/spring-annotation-componentScan/README.md) - 探索如何自动检测和注册 beans。
- [**深入@Bean的秘密**](spring-annotation/spring-annotation-bean/README.md) - 理解如何通过 Java 方法定义 beans。
- [**@Import的高级策略**](spring-annotation/spring-annotation-import/README.md) - 揭示如何导入其他配置类或组件。
- [**属性源探查@PropertySource**](spring-annotation/spring-annotation-propertySource/README.md) - 深入了解如何为应用上下文添加属性源。
- [**掌控顺序@DependsOn**](spring-annotation/spring-annotation-dependsOn/README.md) - 精确控制 Spring Beans 的加载顺序。
- [**条件注册解密@Conditional注解**](spring-annotation/spring-annotation-conditional/README.md) - 从基础使用到源码分析，全方位理解Spring的条件注册策略。
- [**深入探究@Lazy注解**](spring-annotation/spring-annotation-lazy/README.md) - 如何优雅地实现 Spring Beans 的延迟加载。
- [**属性绑定@Value**](spring-annotation/spring-annotation-value/README.md) - 如何在Spring中优雅地注入配置属性。
- [**依赖注入@Autowired**](spring-annotation/spring-annotation-autowired/README.md) - 了解如何通过@Autowired实现依赖管理和连接组件。

## 🔄持续更新中

为了给大家提供最新、最有价值的内容，我会坚持每天更新这个仓库。每一天，你都可以期待看到一些新的内容或者对已有内容的改进。如果你有任何建议或反馈，欢迎随时联系我。我非常珍视每一个反馈，因为这是我持续改进的动力。

## 💻我的 GitHub 统计

[![Star History Chart](https://api.star-history.com/svg?repos=xuchengsheng/spring-reading&type=Date)](https://star-history.com/#xuchengsheng/spring-reading&Date)