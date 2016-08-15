# emotion_classification_based_on_rules
基于规则的情绪分类方法<br>

##简介
&#160; &#160; &#160; &#160;基于规则的情绪分类方法主要依赖于情感词， 如“兴高采烈”、“惶然不安”。
emotion_classification_based_on_rules根据微博的特点构建了表情词典和卡方词典，并制定了规则进行情绪分类，

##文件说明
* chi_square_dictionary_contruction<br>
  互信息法计算一个表情与某个类别的紧密程度。
* facial_expression_dictionary_construction<br>
  卡方值计算的方法得到一个词与某个类别的关联程度。
* emotion_classification_method<br>
  统计文本中属于同一类别的情感词个数，计算出整个文本的情绪。
