# Helm User and Developer's Guide - Helm 用户与开发者指南

本指南是官方 Kubernetes 的 github 库下，helm 子目录下的文档的翻译，依照 https://docs.helm.sh/ 的文档架构和组织，当前非常粗糙的翻译了一版（剩余命令参考和术语表两部分还没有翻译），后续会陆续更新优化，用于给刚接触 Helm 这个工具的朋友一个参考。

备注：（如果有朋友知道如何更好的在 gitbook 里面处理花括弧 - 模板里的值引用，欢迎告知我）！！

电子书下载链接 https://github.com/whmzsu/helm-doc-zh-cn/releases

# 目录

### 前言

  - [序言](README.md)

### 用户指南

- [快速入门](quickstart/quickstart-zh_cn.md)
- [安装](quickstart/install-zh_cn.md)
- [Kubernetes 各发行版 Helm](quickstart/kubernetes_distros-zh_cn.md)
- [安装 FAQ](quickstart/install_faq-zh_cn.md)
- [使用](quickstart/using_helm-zh_cn.md)
- [插件](quickstart/plugins-zh_cn.md)
- [RBAC](quickstart/rbac-zh_cn.md)
- [使用 SSL](quickstart/tiller_ssl-zh_cn.md)
- [安全安装](quickstart/securing_installation-zh_cn.md)

### Helm 命令参考
### Charts

- [Charts](chart/charts-zh_cn.md)
- [Hooks](chart/charts_hooks-zh_cn.md)
- [提示和技巧](chart/charts_tips_and_tricks-zh_cn.md)
- [存储库 repository](chart/chart_repository-zh_cn.md)
- [同步 repository](chart/chart_repository_sync_example-zh_cn.md)
- [验证出处和完整性](chart/provenance-zh_cn.md)
- [测试](chart/chart_tests-zh_cn.md)
- [Repository FAQ](chart/chart_repository_faq-zh_cn.md)

### 开发 chart 模板

- [介绍](chart_template_guide/index-zh_cn.md)
- [入门](chart_template_guide/getting_started-zh_cn.md)
- [内置对象](chart_template_guide/builtin_objects-zh_cn.md)
- [Values 文件](chart_template_guide/values_files-zh_cn.md)
- [函数和管道](chart_template_guide/functions_and_pipelines-zh_cn.md)
- [控制结构](chart_template_guide/control_structures-zh_cn.md)
- [变量](chart_template_guide/variables-zh_cn.md)
- [命名模板](chart_template_guide/named_templates-zh_cn.md)
- [访问文件](chart_template_guide/accessing_files-zh_cn.md)
- [忽略不需要的文件和文件夹](chart_template_guide/helm_ignore_file-zh_cn.md)
- [notes 文件](chart_template_guide/notes_files-zh_cn.md)
- [子 chart 和全局值](chart_template_guide/subcharts_and_globals-zh_cn.md)
- [调试模板](chart_template_guide/debugging-zh_cn.md)
- [总结](chart_template_guide/wrapping_up-zh_cn.md)
- [附录 1：Yaml 技巧](chart_template_guide/yaml_techniques-zh_cn.md)
- [附录 2：数据类型](chart_template_guide/data_types-zh_cn.md)

### chart 最佳实践
- [介绍](chart_best_practices/README-zh_cn.md)
- [通用约定](chart_best_practices/conventions-zh_cn.md)
- [Values](chart_best_practices/values-zh_cn.md)
- [Templates](chart_best_practices/templates-zh_cn.md)
- [Requirements](chart_best_practices/requirements-zh_cn.md)
- [Labels 和 Annotations](chart_best_practices/labels-zh_cn.md)
- [Pods 和 PodTemplates](chart_best_practices/pods-zh_cn.md)
- [资源定义定制](chart_best_practices/custom_resource_definitions-zh_cn.md)
- [RBAC](chart_best_practices/rbac-zh_cn.md)

### 相关项目和文档
- [相关项目和文档](related-zh_cn.md)

### Kubernetes Helm 架构
- [Kubernetes Helm 架构](architecture-zh_cn.md)

### 开发者指南
- [开发者指南](developers-zh_cn.md)

### 项目历史
- [项目历史](history-zh_cn.md)

### 术语表
- [术语表](glossary-zh_cn.md)

### [何处寻找 Charts](https://hub.kubeapps.com/)

### Helm 版本发布 checklist
- [版本发布checklist](release_checklist-zh-cn.md)
