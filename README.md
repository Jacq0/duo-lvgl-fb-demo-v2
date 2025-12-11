# duo-lvgl-fb-demo

lv_port_linux_frame_buffer from:
```
git clone https://gitcode.com/lvgl/lv_port_linux_frame_buffer.git
cd lv_port_linux_frame_buffer
git submodule update --init --recursive
```

**Note:** Patch for V1 contained modifications for the fbtft driver c files, however from a quick look buildroot-v2 already contains these changes. (Also removing the last line breaks it for some reason :/)
