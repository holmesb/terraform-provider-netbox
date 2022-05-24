---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "netbox_cluster_group Resource - terraform-provider-netbox"
subcategory: ""
description: |-
  
---

# netbox_cluster_group (Resource)



## Example Usage

```terraform
resource "netbox_cluster_group" "dc_west" {
  description = "West Datacenter Cluster"
  name        = "dc-west"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String)

### Optional

- `description` (String)
- `slug` (String)

### Read-Only

- `id` (String) The ID of this resource.

