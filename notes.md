# liammcinroy.github.io

## setup

```bash
[apt-get|brew] install npm
npm install -g n
n 11.15.0
n exec 11.15.0 npm install -g npm@6.7.0
n exec 11.15.0 npm install \
  gulp@3.9.1 \
  gulp-browser@2.1.9 \
  reactify@1.1.1 \
  del@2.2.2 \
  gulp-size@3.0.0 \
```

then run `gulp` in the project directory while developing to auto-compile
any react.
