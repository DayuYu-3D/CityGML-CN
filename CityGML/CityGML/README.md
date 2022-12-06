# OGC China CityGML

## 内容

这个文件夹包含用于创建CityGML 2.0编码标准的中文版本

* OGC_China_White_Paper.adoc - 主要的文件入口，包括所有章节和参考资料
* remaining adocs - 标准/白皮书文件的每个部分都在一个单独的文件中
* figures - figures go here
* images - 只在这里放置不在figures目录的图像（例如，作为表格的一部分，logo，等等）。
* requirements - directory for requirements and requirement classes to be referenced in clause_7_normative_text.adoc
* code - 如果需要，可提供与标准配套的示例代码
* abstract_tests - 抽象测试套件包括每个需求的一个测试，可选
* UML - UML图，如果需要的话

## 构建

为了产生html文件（编译image到html中，html文件极大，适合测试），请运行 asciidoctor -a stylesheet=./stlyeSheets/asciidoctor.css -a data-uri --trace -o ../../output/test.html CityGML_Chinese.adoc  

为了产生html文件（不编译image，适合生产发布）asciidoctor -a stylesheet=./stlyeSheets/asciidoctor.css --trace -o ../../output/Product/Product.html CityGML_Chinese.adoc  

为了产生pdf文件，请运行 asciidoctor -r asciidoctor-pdf -r asciidoctor-mathematical --trace -b pdf  -a scripts=cjk -a pdf-theme=KaiGenGothicCN-theme.yml -o ../../output/test.pdf -a pdf-fontsdir=./fonts CityGML_Chinese.adoc  

请注意，若要生成带右侧导航目录的html，请在OGC_China_White_Paper文件中，注释掉:toc-placement!:
但是这也会导致pdf目录位置异常