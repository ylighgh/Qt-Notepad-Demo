# Notepad
This is a notepad example from Qt getting started.
https://doc.qt.io/qt-5/qtwidgets-tutorials-notepad-example.html

# Usage

*编译*
```
# 创建文件夹
mkdir -p ~/workspace/qt

# 克隆目录
cd ~/workspace/qt && git clone https://github.com/ylighgh/Qt-Notepad-Demo.git

# 进入文件夹并编译
cd Qt-Notepad-Demo && qmake -o dist/ && cd dist && make
```

*运行*
```
# 进入dist文件夹
cd Qt-Notepad-Demo/dist/

# 运行项目
./Notepad
```
