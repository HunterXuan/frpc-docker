# frpc-docker
frpc running in docker
## How to use
Here's an simple docker-compose.yml example.
```yaml
version: "3.4"
services:
  frpc:
    image: hunterxuan/frpc-docker
    volumes:
      - /path/to/your/frpc.ini:/usr/local/frpc/frpc.ini
    restart: always
    network_mode: host
```
