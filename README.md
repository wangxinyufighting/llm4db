# llm4db

## 数据准备：

在这里进行测试相关qa数据。如./data/qa.json格式，如下图所示，

```json
[
  {
    "q":"1+1=？",
    "a":"2"
  },
  {
    "q":"3-1=？",
    "a":"2"
  }
]
```

准备好qa的json数据后，运行

```shell
python prepare_data.py
```

进行数据准备

## 测试：

运行

```shell
python main.py
```

即可进行测试。
