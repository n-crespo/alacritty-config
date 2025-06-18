To fix undercurl:

1. use `term = "alacritty"` in `[env]` section of config

2. take alacritty.info from the [alacritty source code](https://github.com/alacritty/alacritty/blob/master/extra/alacritty.info)

3. run the following command

```sh
tic -xe alacritty,alacritty-direct alacritty.info
```

Note: This causes `<C-space>` to not be sent to alacritty.
