python安装nuitka
pip install --upgrade nuitka

nuitka --standalone --mingw64 --show-memory --show-progress --nofollow-imports --plugin-enable=qt-plugins --follow-import-to=need  --output-dir=输出文件夹 你的.py

依赖环境
mingw64 下载地址

https://github.com/GorvGoyl/MinGW64/releases

解压后把bin加入环境变量里

ccache.exe

下载地址: https://github.com/a1802lzw/ccache.exe.git

加入环境变量
