# 聊天机器人

聊天机器人的 PyTorch 实现。


## 依赖
- Python 3.5
- PyTorch 0.4

## 数据集

小黄鸡聊天语料

## 用法

### 数据预处理
提取训练数据：
```bash
$ python extract.py
$ python pre_process.py
```

### 训练
```bash
$ python train.py
```

可视化训练过程，执行：
```bash
$ tensorboard --logdir path_to_current_dir/logs
```

### 演示

```bash
$ python demo.py
```

不正经的语料只能训练不正经的聊天机器人 ╮（﹀_﹀）╭

![image](https://github.com/foamliu/Chatbot/raw/master/images/result-1.jpg)
![image](https://github.com/foamliu/Chatbot/raw/master/images/result-2.jpg)
![image](https://github.com/foamliu/Chatbot/raw/master/images/result-3.jpg)
![image](https://github.com/foamliu/Chatbot/raw/master/images/result-4.jpg)
![image](https://github.com/foamliu/Chatbot/raw/master/images/result-5.jpg)
![image](https://github.com/foamliu/Chatbot/raw/master/images/result-6.jpg)
