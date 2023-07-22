# 2 - Verilerin Yüklenmesi
```python
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd

veri = pd.read_csv('veriler.csv') # pd. yazınca bu kütüphane ile kullanabileceğimiz fonksiyonlar açılır

print(veri)  # bütün listeyi yazar

boy = veri[['boy']]
print(boy) # sadece boy değişkenini alır

boykilo = veri[['boy','kilo']]
print(boykilo) #boy ve kiloyu alır
```

- `read_csv()` işlevi, CSV dosyalarındaki verileri bir pandas DataFrame'ine yüklemek(yani verileri spyder'da veriable explorer kısmına atar) için kullanılır. 

- `CSV dosyaları`, satırların ve sütunların virgül (,), noktalı virgül (;), tab vb. gibi belirli bir ayraç karakteri ile ayrıldığı metin tabanlı dosyalardır. Bu tür dosyalar, verileri düzenli bir yapıda saklamak ve paylaşmak için sıkça kullanılır.

- Tekil Köşeli Parantez[]: Bir sütunu seçmek için tekil köşeli parantez kullanılır.

- Çift Köşeli Parantez [['']]: Birden fazla sütunu seçmek için çift köşeli parantez kullanılır.
