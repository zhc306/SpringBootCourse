# 第11章 单元测试与热部署

单元测试是对软件或程序的基本（最小）组成单元的测试，可以让你在软件开发的早期阶段发现 Bug，而不必到集成测试的时候才发现，完善的单元测试，能够在打包之前完成自动化的代码级白盒测试，保证程序代码在方法级的逻辑正确。

日常的开发过程中，通常伴随着修改，重启，测试，验证，再修改的过程。这一重复性过程导致了工作中较多的“无效”工作时间。热部署机制能够监控项目中的修改点（页面，代码，配置等），适时选择重新加载或重新启动应用的方式，帮助开发人员较为流程的完成业务逻辑的开发或修改。

本章，我们学习Spring Boot集成JUnit对应用进行单元测试和通过spring-boot-devtools依赖启动器对项目提供的热部署机制。

