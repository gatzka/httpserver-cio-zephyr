# Meta project for building httpserver test using cio on zephyr OS.

## Howto Build
```
west init -m git@github.com:gatzka/httpserver-cio-zephyr.git httpserver-cio-zephyr
cd httpserver-cio-zephyr
west update
west build -b native_posix httpserver-cio-zephyr/
```


