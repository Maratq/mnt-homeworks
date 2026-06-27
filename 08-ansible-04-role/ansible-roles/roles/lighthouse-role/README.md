# Lighthouse Role

Ansible role for installing and configuring Lighthouse.

## Requirements

- Ansible >= 2.9
- Ubuntu 20.04/22.04

## Role Variables

| Variable | Description | Default |
|----------|-------------|---------|
| `lighthouse_repo` | Lighthouse repository URL | `https://github.com/VKCOM/lighthouse.git` |
| `lighthouse_dir` | Installation directory | `/var/www/lighthouse` |
| `nginx_port` | Nginx port | `80` |

## License

MIT
