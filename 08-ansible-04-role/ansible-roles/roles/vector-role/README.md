# Vector Role

Ansible role for installing and configuring Vector.

## Requirements

- Ansible >= 2.9
- Ubuntu 20.04/22.04

## Role Variables

| Variable | Description | Default |
|----------|-------------|---------|
| `vector_version` | Vector version | `0.37.0` |
| `vector_config_dir` | Config directory | `/etc/vector` |
| `vector_port` | Exporter port | `8383` |

## License

MIT
