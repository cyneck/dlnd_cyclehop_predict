# dlnd-cycle-hop

背景介绍：因为投入共享单车太少，会失去潜在用户而赔钱；而投入的车太多，就会因大量自行车闲
         置而赔钱，所以需要从历史数据中预测未来需要多少辆自行车投放市场；
实现介绍：读取并预处理数据，利用深度学习中的三层神经网络和BP算法实现对权重的更新，观察训练好的模型的 training loss，
Validation loss，调试并进行参数优化来达到最佳训练模型，预测共享单车数。
