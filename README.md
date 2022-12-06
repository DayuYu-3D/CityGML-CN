# OGC CityGML 2.0中文版本

## Introduction

The CityGML2.0 Chinese version translated by OGC China.

[PDF](./output/OGC中国联盟--OGC城市地理标记语言编码标准中文版.pdf) 
and [HTML](http://geos.whu.edu.cn/ogc/citygml/)

## How to contribute

此仓库包含了OGC CityGML 2.0中文版本的所有内容

此仓库的组织方式如下:

* index.adoc - 无内容，但是是一个必要的文件
* CityGML - 白皮书文档的主要内容文件夹
  - 按多个部分和目录组织
  - 这是创建白皮书文件所需的唯一文件夹
  - 白皮书没有固定的结构，所以要按照最适合你的目的组织内容

此仓库的请求以下环境:

* Ruby 2.6.7+  （apt安装）

* asciiDoctor 2.0.15+ （apt安装）

* asciiDoctor-pdf 1.6.0+ （gem安装）

* coderay （gem安装）

* asciidoctor-pdf-cjk

* asciidoctor-mathematical : 用于pdf中公式的生成，若只生成html，可不安装，安装如下：
- sudo apt install ruby-dev

- sudo apt-get -qq -y install bison flex libffi-dev libxml2-dev libgdk-pixbuf2.0-dev libcairo2-dev libpango1.0-dev fonts-lyx cmake

- sudo gem install asciidoctor-mathematical

