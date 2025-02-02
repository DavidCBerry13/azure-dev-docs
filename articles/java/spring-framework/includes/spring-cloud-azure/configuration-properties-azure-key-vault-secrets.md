---
ms.date: 04-26-2022
ms.author: v-yonghuiye
---

## Azure Key Vault Secrets properties

> [!div class="mx-tdBreakAll"]
> |Property | Description|
> |---------|------------|
> |spring.cloud.azure.keyvault.secret.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.keyvault.secret.client.connect-timeout | Amount of time the request attempts to connect to the remote host and the connection is resolved. |
> |spring.cloud.azure.keyvault.secret.client.connection-idle-timeout | Amount of time before an idle connection. |
> |spring.cloud.azure.keyvault.secret.client.headers | Comma-delimited list of headers applied to each request sent with client. |
> |spring.cloud.azure.keyvault.secret.client.logging.allowed-header-names | Comma-delimited list of allowedlist headers that should be logged. |
> |spring.cloud.azure.keyvault.secret.client.logging.allowed-query-param-names | Comma-delimited list of allowedlist query parameters. |
> |spring.cloud.azure.keyvault.secret.client.logging.level | The level of detail to log on HTTP messages. |
> |spring.cloud.azure.keyvault.secret.client.logging.pretty-print-body | Whether to pretty print the message bodies. |
> |spring.cloud.azure.keyvault.secret.client.maximum-connection-pool-size | Maximum connection pool size used by the underlying HTTP client. |
> |spring.cloud.azure.keyvault.secret.client.read-timeout | Amount of time used when reading the server response. |
> |spring.cloud.azure.keyvault.secret.client.response-timeout | Amount of time used when waiting for a server to reply. |
> |spring.cloud.azure.keyvault.secret.client.write-timeout | Amount of time each request being sent over the wire. |
> |spring.cloud.azure.keyvault.secret.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.keyvault.secret.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.keyvault.secret.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.keyvault.secret.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.keyvault.secret.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.keyvault.secret.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.keyvault.secret.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.keyvault.secret.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.keyvault.secret.endpoint | Azure Key Vault endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.keyvault.secret.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.keyvault.secret.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.keyvault.secret.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.keyvault.secret.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.keyvault.secret.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.keyvault.secret.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.keyvault.secret.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.keyvault.secret.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.keyvault.secret.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.keyvault.secret.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.keyvault.secret.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.keyvault.secret.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.keyvault.secret.property-source-enabled | Whether to enable the Key Vault property source. The default value is `true`. |
> |spring.cloud.azure.keyvault.secret.property-sources | Azure Key Vault property sources. |
> |spring.cloud.azure.keyvault.secret.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.keyvault.secret.proxy.non-proxy-hosts | A list of hosts or CIDR to not use proxy HTTP/HTTPS connections through. |
> |spring.cloud.azure.keyvault.secret.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.keyvault.secret.proxy.port | The port of the proxy. |
> |spring.cloud.azure.keyvault.secret.proxy.type | Type of the proxy. |
> |spring.cloud.azure.keyvault.secret.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.keyvault.secret.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.keyvault.secret.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.keyvault.secret.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.keyvault.secret.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.keyvault.secret.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.keyvault.secret.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.keyvault.secret.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.keyvault.secret.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.keyvault.secret.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.keyvault.secret.service-version | Secret service version used when making API requests. |
