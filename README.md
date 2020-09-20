# MSc thesis Image Compression with WebAssembly



### This is an app that compress images with retaining best quality.

In our first attempt we will use mozjpeg_enc.

The above codec is written in cpp and providers a library jpeglib.h. 

We will use (emscripten)[https://emscripten.org/] and we will create a wasm output in order to run it in browser.


