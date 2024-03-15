# pyjirou
pyjirouは緯度経度で、その場所から最も近いラーメン二郎を返すpythonライブラリです。

## 使い方
### インストール
```sh
pip install git+https://github.com/s1f10210273/pyjirou.git
```

### インポート
```python
import pyjirou
```

### 使い方
```python
pyjirou.jiro([経度], [緯度])
```
## 例
```python
import pyjirou

print(pyjirou.jiro(139.698318, 35.696323))
```
```sh
shop_name    ラーメン二郎 新宿小滝橋通り店
address       東京都新宿区西新宿7-5-5
lat                35.696323
lon               139.698318
distance                 0.0
Name: 21, dtype: object
```
