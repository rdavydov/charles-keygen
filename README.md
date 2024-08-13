## 🫙 Charles KeyGen

### 🫙 Charles KeyGen JS web version

This implementation is based on the [Java version on Gitee](https://gitee.com/thom/charles-keygen) browser-native JS (ES2020+) implementation.

### 🔗 Online usage
https://rdavydov.github.io/charles-keygen

### 🛠 Developer

- install
~~~bash
yarn 
# or npm i
~~~

- dev
~~~bash
yarn dev 
# or npm run dev
~~~

- build
~~~bash
yarn build 
# or npm run build
~~~

### 📦 Others

Because the original Java source code uses long type numbers, using traditional Number in JS will overflow, so we have to use ES2020+'s BigInt type, so when we packaged it with `vite`, we set `target = esnext` directly.

### 📄 LICENSE
MIT License

Copyright (c) 2024 Roman Davydov

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

<hr>

Original repo: https://github.com/ydq/charles-keygen
