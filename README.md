# azure-container-apps_2026-07
Alguns conteúdos envolvendo novidades ao trabalhar com Azure Container App (Julho-2026).

Novo Portal do Azure Container Apps: **https://containerapps.azure.com/login**

Um pouco mais sobre o Azure Contaer Express: **https://techcommunity.microsoft.com/blog/appsonazureblog/introducing-azure-container-apps-express/4519150**

## Testes

Imagem (**docker.io**):

```
renatogroffe/aspnetcore10-apicontagem-simulacaofalhas:1
```

Environment Variables:

| Variável | Valor |
|---------|-------|
| `ConnectionStrings__ApplicationInsights` | String de Conexão do Application Insights |
| `SimularFalhas` | `true` \| `false` |

Logs em tempo real no portal do Azure Container Apps:

![Logs no portal do Container Apps](img/portal-01.png)

Dashboards with Grafana:

![Dashboards with Grafana 1](img/grafana-01.png)

Resultados em dashboard do Grafana:

![Dashboards with Grafana 2](img/grafana-02.png)

Dashboard do Grafana no Azure DevOps, após execução de testes de carga com k6:

![Resultados do k6 1](img/azure-devops-01.png)

Resumo com métricas após execução de testes de carga com k6:

![Resultados do k6 2](img/azure-devops-02.png)