# KubeApps Plus 开发文档

### KubeApps Plus 仪表板

仪表板是 KubeApps Plus 项目的主要 UI 组件。 仪表板使用 Javascript 编写, 使用 Vue.js 库作为前端。

请参阅 [仪表板开发指南](dashboard/README.md) 中的开发设置。

### chartsvc

“chartsvc” 组件是一个微服务, 可创建 API 端点来访问在 MongoDB 服务器中的 Helm 图表存储库中图表的元数据。

请参阅 [Chartsvc 开发指南](chartsvc.md) 中的开发设置。

### chart-repo

“chart-repo” 组件是一种工具, 可扫描 Helm 图表存储库并在 MongoDB 服务器中的图表元数据。 然后, 由 “chartsvc” 组件提供此元数据。

请参阅 [chart-repo 开发指南](chart-repo.md) 进行开发设置。

### tiller-proxy

“tiller-proxy”组件是一种服务, 既用作 Tiller 的客户端, 又提供一种授权用户在不同名称空间中部署, 升级和删除图表的方法。

请参阅 [tiller-proxy 开发指南](tiller-proxy.md) 进行开发设置。
