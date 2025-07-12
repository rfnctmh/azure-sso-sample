# Azure App Service SSO 測試專案

此專案包含：

- `index.html`：用於測試 Azure App Service 單一登入是否正確導向
- `.github/workflows/azure.yml`：GitHub Actions 自動部署設定
- `README.md`：說明文件

## 使用方式

1. Fork 或 clone 此專案到您的 GitHub 帳號
2. 在 Azure App Service 中設定部署來源為 GitHub
3. 將 Azure 發行設定檔（Publish Profile）存為 GitHub Secret：`AZUREAPPSERVICE_PUBLISHPROFILE`
4. Push 後 GitHub Actions 會自動部署

