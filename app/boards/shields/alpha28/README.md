my alpha28 board and shield configuration

https://github.com/PyrooL/Alpha

Build using

```
west build --pristine -b nice_nano_v2 -- -DSHIELD=alpha28
```

Flash by copying `build/zephyr/zmk.uf2` to the NICENANO.
