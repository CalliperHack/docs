# CallibreHack docs

## Set up

Burn the Udoo image.

```console
$ sudo dd if=UDOObuntu_neo_v2.0rc1.img of=/dev/mmcblk0 bs=4M
```

Install packages.

## Wire protocol Arduino/Linux

Arduino sends through the serial port two kinds of messages:

- A measurement: `M 100\n`

- A button: `BTN A\n`

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License](http://creativecommons.org/licenses/by-sa/4.0/).

![CC BY-SA](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)
