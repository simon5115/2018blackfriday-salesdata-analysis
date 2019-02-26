# 2018blackfriday-salesdata-analysis
2018黑色星期五销售数据分析及用户画像、购买力预测报告

黑色星期五在美国是一个购物狂潮期。在这个时期，各个商店会进行一次大规模的促销，从而引起群众大量购买物资。在购物盛典中将会产生大量的销售数据，这些数据具有非常大的商业价值，对其的挖掘可以给商家提供非常有效的建议让其提高销售额。我们尝试分析了Analytics Vidhya公司公布的2018年黑色星期五部分销售数据，用Apriori算法挖掘商品的关联规则，以此给商家商品捆绑销售提供建议。用随机森林模型用年龄、性别、职业、定居时间、居住城市、婚姻状态等属性对用户购买力进行预测，以此给商店为老顾客促销提供建议，并用线性回归模型进行比较，在十折交叉验证的框架下使用RMSE衡量模型。用随机森林、KNN、朴素贝叶斯和决策树等多种模型用购买记录预测用户性别、年龄，达到部分用户画像的功能，给精准营销提供建议，并比较这些模型的优劣，使用准确率衡量模型。我们对结果进行了合理的可视化表示，方便商户通过结果进行决策。
