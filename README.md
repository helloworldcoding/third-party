
### Try it now

如果你想找寻好的第三方工具，或提交你的作品，请移步到 [Discussion](https://github.com/seedsnote/third-party/discussions/categories/ideas-tools)

### Documentation

Seeds API采用典型的POST请求方法，支持将文本和图片发送到Seeds

1. 如果是文本，请使用content字段名，发送json格式

```
POST https://seedsnote.com/api/msg/yourApiAddress
Content-type: application/json
{
    "content": "Hello, #flomo https://flomoapp.com"
}
```

2. 如果是图片，请选择form-data格式，并将字段名

```

POST https://seedsnote.com/api/msg/yourApiAddress
Content-type: application/form-data
{
    "file": "drawing.jpg"
}
```


![Frame 46](https://user-images.githubusercontent.com/67967374/123350924-96fa7200-d58e-11eb-9410-d8015228e57e.png) 

🌱 Seeds思记，一款优雅智能的笔记应用。我们为每一位用户提供专属的API地址，以便于你从不同的地方更好地采集想法到Seeds。

轻快的随时记，智能的知识网 ｜Write，Think，and Grow

