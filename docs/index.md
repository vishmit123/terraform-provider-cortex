---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "cortex Provider"
subcategory: ""
description: |-
  
---

# cortex Provider



## Example Usage

```terraform
provider "cortex" {
  address   = "http://127.0.0.1:8080"
  tenant_id = "example"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- **address** (String) The root URL of Cortex cluster. May alternatively be set via the `CORTEX_ADDRESS` environment variable.
- **api_key** (String, Sensitive) API key, used as basic auth password. May alternatively be set via the `CORTEX_API_KEY` environment variable.
- **tenant_id** (String) The Tenant ID, passed as X-Org-ScopeID HTTP header. May alternatively be set via the `CORTEX_TENANT_ID` environment variable.
