# rocket.chat

## Usage

```
docker-compose up -d
```

## Match it with environment

```yaml:docker-compose.yml
    ports:
      - 8090:3000
    environment:
      - ROOT_URL=https://chat.xxxxx.com
```
