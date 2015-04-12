This repository is just sample of [kobole](https://github.com/yahoo/kobold).

## How to use
### Setup
```
$ npm install
```

### Run test
```
$ ./run-test.sh
```

## About
### Global setting
- `/config/global_settings.js` is global setting.
- `global_settings.js` is read in `run-test.sh`.

### Setting only for `test_fail` files
- `config/test_fail.js` affects only `test_fail.png` under `approved` and `build` directories.
