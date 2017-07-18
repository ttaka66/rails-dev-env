# Rails environment by docker-compose pushtest

## Usage

### Build(bundle install/update)

```bash
$ docker-compose build
```

### Start

```bash
$ docker-compose up -d
```

### Stop

```bash
$ docker-compose stop
```

### Command

```bash
$ docker-compose exec app {command}
```

e.g. $docker-compose exec app rake db:create

### Confirm logs

```bash
$ docker-compose logs -f app
```
