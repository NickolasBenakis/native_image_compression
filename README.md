# MSc thesis Image Compression with WebAssembly



### This is an app that compress images with retaining best quality.

In our first attempt we will use [mozjpeg_enc](https://github.com/mozilla/mozjpeg).

The above codec is written in cpp and provides a library [jpeglib.h](https://dev.w3.org/Amaya/libjpeg/jpeglib.h). 

We will use [emscripten](https://emscripten.org/) and we will create a wasm output in order to run it in browser.


