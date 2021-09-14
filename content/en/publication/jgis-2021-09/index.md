---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Prediction of pollen concentration in Beijing the next day based on vegetation remote sensing data"
authors: [Meng Bian, Shuyi Guo, Wei Wang, Yuhui Ouyang, Yingjing Huang, Teng Fei]
date: 2021-09-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-09-01

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "地球信息科学学报"
publication_short: ""

abstract: "中国国土绿化状况公报指出,2010—2020年中国许多城市的绿化面积增加、绿化质量提高,可随之而来的影响人体健康的致敏性花粉风险也逐渐提高。本文利用遥感手段获得北京市乔木和草地生长区域平均植被叶面积指数（LAI）时间序列作为植被物候信息,并将其作为花粉浓度预测因子之一,结合日气象数据,使用具有外部输入的非线性自回归神经网络模型（NARXnet）,进行北京市次日花粉浓度的预测。结果显示:（1）通过逐步回归计算,对于春季数据,日均气温3日平滑,积温,叶面积指数（LAI）和叶面积指数一阶导为次日花粉浓度预测的关键变量;对于秋季数据,日均气温、平均风速、最低日气温、日均气温3日平滑、积温和叶面积指数（LAI）为次日花粉浓度预测的关键变量;（2）加入遥感物候信息可显著地提高NARXnet模型的春秋时段的花粉浓度的预测精度。使用本文提出的结合叶面积指数的NARX模型后,预测模型的总体精度为71%。由此,本研究认为在原有气象因子的基础上,辅之以用遥感技术手段获取的大面积植被物候信息,如叶面积指数动态,可作为预测次日花粉浓度的一种有效手段。"

# Summary. An optional shortened abstract.
summary: "卞萌,郭树毅,王威,欧阳昱晖,黄颖菁,费腾.融合植被遥感数据的北京市次日花粉浓度预测[J].地球信息科学学报,2021,23(09):1705-1713."

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Cite
  url: 'publication/jgis-2021-09/CNKI-20210914170019856.txt'

url_pdf: 'publication/jgis-2021-09/融合植被遥感数据的北京市次日花粉浓度预测.pdf'
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
