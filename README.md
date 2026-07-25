# FreeDNS Shared Domains Dataset

A CSV dataset containing publicly shared domains from **FreeDNS (freedns.afraid.org)** that can be used as subdomain bases.

This dataset provides information about shared domains, including usage statistics, ownership metadata, registration dates, categories, and availability status.

## Dataset File

- `freedns_shared_domains.csv` — Complete CSV dataset of FreeDNS shared domains.

## Use Cases

This dataset can be used for:

- DNS research and analysis
- Subdomain enumeration research
- Domain availability analysis
- DNS automation tools
- Security research
- Statistical analysis of shared domain usage

## CSV Fields

| Field | Description |
|---|---|
| `domain` | Shared domain name available for subdomain creation |
| `hosts_in_use` | Number of active hosts/subdomains currently using the domain |
| `category` | Domain category |
| `status` | Domain visibility/status (public or private) |
| `owner` | FreeDNS account owner name |
| `owner_profile_url` | FreeDNS owner/contact profile URL |
| `age_days` | Number of days since domain registration |
| `registered_date` | Domain registration date |
| `website_url` | Website associated with the shared domain |
| `edit_domain_id` | FreeDNS domain identifier |
| `source_page` | Source reference identifier |

## Example Data

```csv
domain,hosts_in_use,category,status,owner,registered_date
mooo.com,860174,website,public,josh,03/15/2001
chickenkiller.com,441886,website,public,josh,01/02/2001
strangled.net,117303,website,public,josh,01/03/2001
```

## Dataset Statistics

The dataset includes:

- Shared domains from FreeDNS
- Domain popularity metrics
- Public/private status information
- Registration age data
- Ownership references

## Source

Data collected from:

https://freedns.afraid.org/
