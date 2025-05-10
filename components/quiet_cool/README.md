```yaml
# example configuration:

fan:
  - platform: quiet_cool
    name: QuietCool fan
    output: gpio_d1

output:
  - platform: gpio
    pin: D1
    id: gpio_d1
```
