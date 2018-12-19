# -实践的项目整理

# planet_understanding_the_amazon_from_space.ipynb  
Kaggle亚马逊丛林卫星图识别项目，识别天气和地理类型。Notebook编辑，使用tensorflow框架，CNN网络，corlab平台（GPU）训练。  
数据：训练样本为40479张卫星图片，label为两类（weather_labels	ground_labels），每一个训练样本对应两个one-hot标签。  
只下载了训练集，最终没有进行测试集测试，只在训练集验证模型传递正确性，有时间补充测试集测试。  
模型结构：两层卷积和两层池化->全连接层->两层隐藏层（0.2 droupout）->输出层（两类输出）。  
