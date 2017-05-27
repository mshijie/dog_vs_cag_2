# Dogs vs Cats

## 环境

Python 2.7.12
Mac OS X 10.11.6
CUDA 8.0.47
cuDNN 5.1

## python库

- keras 1.1.2
- NumPy 1.11.2
- OpenCV 3.1.0
- tensorflow gpu 0.11.0
- matplotlib 1.5.1
- tqdm 4.7.6
- sklearn 0.18.1
- seaborn 0.7.1
- pandas 0.19.1

## 数据集

[Kaggle Dog vs Cats DataSet](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data)

数据集包含两个文件夹*test* 和 *train*

*preprocessing.ipynb*  中把 *train* 拆分为两个目录，最终的数据目录如下：

- mytrain 
	- cat
	- dog
- myvalid 
	- cat
	- dog

### 训练时间

- 每个epoch30s
- 总共40个epoch，20分钟
- CPU i7 6700K
- GPU GTX 980 Ti
- Memory 32GB