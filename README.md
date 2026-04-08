# cloud-scripts

Automation scripts for cloud server provisioning and management across multiple providers.

## Features
- Automated server creation and teardown
- Multi-region deployment with failover
- Server type rotation and resource optimization
- Bulk operations (create, delete, list, count)

## Supported Providers
- Hetzner Cloud
- Linode / Akamai
- DigitalOcean

## Stack
- Python 3
- Provider REST APIs
- Bash for server bootstrapping

## Usage

```bash
python3 provision.py --provider hetzner --region nbg1 --count 10
```

## License
MIT
