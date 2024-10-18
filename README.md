# Extract-source-in-folder
提取文件夹中的源代码保存到word文件中。

#### 介绍
通过python脚本来提取文件夹中的源代码，包括  `.java` `.py`, `.java`, `.c`, `.cpp`, `.js`, `.html`, `.css`, `.rb`, `.go`, `.vue` 等类型的源代码来方便的重复操作。

#### 安装教程

1.  打开 PyCharm Community Edition 或者其他的可以运行 Python 的应用环境。
2.  在 PyCharm Community Edition 打开命令框输入以下命令安装 python-docx 库：
    ```bash
    pip install python-docx
    ```

#### 使用说明

1.  设置文件夹路径：
    ```python
    folder_path = r'*********\src\views'  # 这个为文件夹的路径，可以直接复制文件路径粘贴
    ```
2.  设置输出的 Word 文件名：
    ```python
    output_file = 'qianduan_code.docx'    # 输出Word文件名
    ```
3.  可以在 Python 软件中的命令框中输入以下命令直接获取源代码：
    ```bash
    git clone https://gitee.com/G88ra/extract-source-in-folder.git
    ```

#### Credit
[888Ra/Extract-source-in-folder](https://github.com/888Ra/Extract-source-in-folder)