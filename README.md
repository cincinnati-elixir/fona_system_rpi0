# Raspberry Pi Model Zero

This is a nerves custom system based off of `nerves_system_rpi0` with gadget support and ppp support for the Fona and other board based off the SIM8xx series of GSM modem chips.

For more information about `nerves_system_rpi0`, see [nerves_system_rpi0](https://github.com/nerves-project/nerves_system_rpi0)

## Using

To use this system, add it as a dependency to your nerves application mix.exs by modifying the rpi0 `system` function:

```
  defp system("rpi0"), do: [{:fona_system_rpi0, "~> 1.0.0", runtime: false}]
```

See [nerves-project.org](http://nerves-project.org) for more information about the Nerves Project.
