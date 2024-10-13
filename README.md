# timezone

The simple role which installs `tzdata` package and sets timezone.

## Usage (examples)

### The tzdata package installation only

```yaml
    - role: timezone
```

### The timezone setup only (without package installation)

```yaml
    - role: timezone
      timezone_setup: configure
      timezone_zone: Europe/Moscow
```

## Available parameters

| Param | Default | Description |
| -------- | -------- | -------- |
| `timezone_setup`| `full` | Setup mode |
| `timezone_zone` | - | Timezone. See [list](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) |

## TODO

...
