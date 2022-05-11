# plant_leaf_diease
## 植物叶片病害识别数据集！
由于ai_challenger 比赛关闭，数据集已经无法获取。网上也找不到的相应数据集。
所以……本人根据kaggle数据集中的图片，自己手打了一些标签，使用轻量级json文件，供各位炼丹师使用。
kaggle数据集中有许多植物，只打了与自己实验相关的番茄数据集，时间精力有限，也只打了**1016**张(256*256)。
标签共有十个类别(十种病，包括健康)
## 附录：
- 训练集：700 张 （每种类别70张）
  train.json
- 验证集：300 张  （每种类别30张）
  val.json
- 测试集：16 张  
 test.json

**image_id:图片名**
**diease_class:病害类别**
- "**1**":"Tomato Bacterial spot"
番茄细菌性斑点
- "**2**":"Tomato Early blight"
番茄早疫病
- "**3**":"Tomato healthy"
番茄健康
- "**4**":Tomato Late blight
番茄晚疫病
- "**5**":Tomato Leaf Mold
番茄叶霉病
- "**6**":Tomato Septoria leaf spot
番茄斑叶病
- "**7**": Tomato spider mite double spotted spider mite
番茄蜘蛛螨双斑点蜘蛛螨
- "**8**":Tomato Target Spot
番茄靶斑病
- "**9**":Tomato mosaic virus
番茄花叶病毒
- "**10**":Tomato Yellow Leaf Curl Virus
番茄黄曲叶病毒
