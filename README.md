# ustc-auto-eval-edu

USTC 自动评教脚本

## Language

Python on JupyterLab

## Usage

首先安装 Python 依赖：

```bash
pip install -r requirements
```

此脚本基于 Selenium 实现，还需要安装 Selenium Web Driver，详见官方文档

例如使用 yay 经 AUR 安装：

```bash
yay -S chromedriver
```

之后开启 JupyterLab：

```bash
jupyter lab
```

在弹出的浏览器界面中选中 `evaledu.ipynb` 文件，填写 `username` 和 `password` 后一个一个 Cell 运行该脚本

此脚本仅仅是用 Selenium 模拟了手动评教的过程，代码相当简单，可依需求自行修改

USTC 评教系统有访问频率限制，但重置较快，脚本中的注释对此情况下的操作有所说明

## License

MIT
