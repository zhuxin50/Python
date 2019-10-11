# Python
#### 创建虚拟环境
**使用 pip 安装 Pipenv**
```
#pip install pipenv
```
**为当前项目创建一个虚拟环境**
```
#pipenv install
```
*这个命令执行的过程包含下面的行为：*

* 为当前目录创建一个 Python 解释器环境，安装 pip、setuptool、virtualenv 等工具库。
* 如果当前目录有 Pipfile 文件或 requirements.txt 文件，那么从中读取依赖列表并安装。
* 如果没有发现 Pipfile 文件，就自动创建。

**激活虚拟环境**
```
#pipenv shell
```
*注意：*

>如果你不想每次都激活虚拟环境，可以在命令前添加 pipenv run 前缀，比如 pipenv run pip list 即表示在虚拟环境内执行 pip list 命令。

---



