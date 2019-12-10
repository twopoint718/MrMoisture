# Mr. Moisture

When he senses moisture he shouts! This uses the development board from https://github.com/MalphasWats/hawk

## Building

Compile this mess with:

```shell
make -f gcc/Makefile
```

## TODO

- Use the PTC interrupt (is there one?) to react to detected moisture.
- Generate a sound using the DAC
- Heartbeat to the onboard LED?
