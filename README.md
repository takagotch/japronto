### japronto
---
https://github.com/squeaky-pl/japronto

```py
from japronto import Application

def hello(request):
  return request.Response(text='Hello world!')

app = Application()
app.router.add_route('/', hello)
app.run(debug=True)
```

```
```

```
```

