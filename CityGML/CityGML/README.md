# OGC China CityGML

## ����

����ļ��а������ڴ���CityGML 2.0�����׼�����İ汾

* OGC_China_White_Paper.adoc - ��Ҫ���ļ���ڣ����������½ںͲο�����
* remaining adocs - ��׼/��Ƥ���ļ���ÿ�����ֶ���һ���������ļ���
* figures - figures go here
* images - ֻ��������ò���figuresĿ¼��ͼ�����磬��Ϊ����һ���֣�logo���ȵȣ���
* requirements - directory for requirements and requirement classes to be referenced in clause_7_normative_text.adoc
* code - �����Ҫ�����ṩ���׼���׵�ʾ������
* abstract_tests - ��������׼�����ÿ�������һ�����ԣ���ѡ
* UML - UMLͼ�������Ҫ�Ļ�

## ����

Ϊ�˲���html�ļ�������image��html�У�html�ļ������ʺϲ��ԣ��������� asciidoctor -a stylesheet=./stlyeSheets/asciidoctor.css -a data-uri --trace -o ../../output/test.html CityGML_Chinese.adoc  

Ϊ�˲���html�ļ���������image���ʺ�����������asciidoctor -a stylesheet=./stlyeSheets/asciidoctor.css --trace -o ../../output/Product/Product.html CityGML_Chinese.adoc  

Ϊ�˲���pdf�ļ��������� asciidoctor -r asciidoctor-pdf -r asciidoctor-mathematical --trace -b pdf  -a scripts=cjk -a pdf-theme=KaiGenGothicCN-theme.yml -o ../../output/test.pdf -a pdf-fontsdir=./fonts CityGML_Chinese.adoc  

��ע�⣬��Ҫ���ɴ��Ҳർ��Ŀ¼��html������OGC_China_White_Paper�ļ��У�ע�͵�:toc-placement!:
������Ҳ�ᵼ��pdfĿ¼λ���쳣