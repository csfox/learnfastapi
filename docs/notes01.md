## 1. 相同路由 就近执行

## 2. 命令行
```bash
# 虚拟环境
.venv/Scripts/activate
# 启动fastapi, reload 自动 reload
uvicorn main:app --reload
```

## 3. 笔记
a.b 访问 b， a 是类的实例
a['b'] 访问 b， a 是 dict
将 pydantic 数据 改为 dict, 注意，原 new_post 类型不会改变
```python
new_dict = new_post.model_dump()
```

## video timestamp
1:22:51
