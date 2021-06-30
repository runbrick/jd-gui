# JD-GUI 克隆版本,此版本可以直接复制中文和导出没有多余的注释信息

JD-GUI，一个独立的图形实用程序，显示来自 CLASS 文件的 Java 源代码。

原始版本 [https://github.com/java-decompiler/jd-gui](https://github.com/java-decompiler/jd-gui)

## Description
JD-GUI 是一个独立的图形实用程序，它显示“.class”文件的 Java 源代码。您可以使用 JD-GUI 浏览重构的源代码，以便即时访问方法和字段。

## 编译教程
```
> git clone https://github.com/runbrick/jd-gui.git
> cd jd-gui
> ./gradlew build 
```
## 编译后软件位置
- _"build/libs/jd-gui-x.y.z.jar"_
- _"build/libs/jd-gui-x.y.z-min.jar"_
- _"build/distributions/jd-gui-windows-x.y.z.zip"_
- _"build/distributions/jd-gui-osx-x.y.z.tar"_
- _"build/distributions/jd-gui-x.y.z.deb"_
- _"build/distributions/jd-gui-x.y.z.rpm"_

## How to extend JD-GUI ?
```
> ./gradlew idea 
```
generate Idea Intellij project
```
> ./gradlew eclipse
```
generate Eclipse project
```
> java -classpath jd-gui-x.y.z.jar;myextension1.jar;myextension2.jar org.jd.gui.App
```
launch JD-GUI with your extensions

## How to uninstall JD-GUI ?
- Java: Delete "jd-gui-x.y.z.jar" and "jd-gui.cfg".
- Mac OSX: Drag and drop "JD-GUI" application into the trash.
- Windows: Delete "jd-gui.exe" and "jd-gui.cfg".

## License
Released under the [GNU GPL v3](LICENSE).


