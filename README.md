# web-scaling-reference
Various tables helpful for making estimates on project infrastructure.

## Contributing

If you have a an additional spec/datapoint/suggestion to make:

0. Open issue in the issue tracker
1. Fork the repo on Github
2. Make your changes in your fork
3. Open a PR, referencing your issue from (0)

### Standard units

TBD

### Basic static blog

Specs:

* Blog made of static HTML files (generated via Jekyll, Octopress, etc.)
* No comments
* No CMS

| Pageviews/day | RAM | Disk storage | Bandwidth | Needs dedicated hardware? |
|---------------:|-----|--------------|----------|--------------|
|1 | 1GB | 20GB | 1TB/month | No. |
|1e3 | ? | ? | ? | No. |
|1e6 | ? | ? | ? | No. |
|1e9 | ? | ? | ? | No. |

### VOIP Chat

| Active Users | Protocol | RAM | Disk | Bandwidth | Needs dedicated hardware? |
|--------------|----------|-----|------|-----------|---------------------------|
| 20 | Mumble | 512mb | 20GB | 1TB/month | No | 

