# python example with ci

以python为例子，了解github actions 以及 gitlab ci 的使用

## 内容准备

准备一个符合pytest要求的python文件。

* 文件以 `test_`开头，或者以 `_test.py`结尾
* 文件内待测函数以 `test_` 开头

Action 所需的 `.github/workflows/xxx.yml`文件，可以通过点击Actions后选择合适的模板生成。

Gitlab CI文件 `.gitlab-ci.yml`

> 初步感觉，Github 对Windows支持比 Gitlab 强不少。

