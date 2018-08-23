# opencvwasm

Compiled opencv origin/3.4 wasm

Instructions from https://docs.opencv.org/3.4.2/d4/da1/tutorial_js_setup.html

```bash
cd opencv
git checkout origin/3.4
python2 ./platforms/js/build_js.py build_wasm --build_wasm --build_test
cd build_wasm/bin
npm install
node test.js
```

## 20180823 
1 test failed in Image Processing > test_filter
build_wasm/bin/test_imgproc.js:484:16