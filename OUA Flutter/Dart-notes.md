`import 'package:flutter/material.dart';`

`void main()`

`{`

`  const DART101 = "hello world!";`

`  print(DART101);`

`  final DART102 = "goodbye world!";`

`  print(DART102);`

`}`

**Const** ile **final** arasında bir değişiklik olmayacak. Tek fark const sabitler kod compiler olurken sabit olarak koda ekleniyor, final değişkenler run time’da kod çalışırken sabit olarak koda ekleniyor. Uygulama içinde değişmeyecek bir yer varsa bunlar const ile oluşturabiliriz ama varsayalım ki bir butonumuz var bu butonu çağırırken rengi …. olacak, buton çalışır durumda olduğu sürece atanan renkte olacak. Bu sabitlere atanmış değerler varken yeni değerler atanamaz.

---

`import 'package:flutter/material.dart';`

`void main()`

`{`

`  const DART101 = "hello world!";`

`  print(DART101);`

`  final DART102 = "goodbye world!";`

`  print(DART102);`

`  var DART103 = "N'aber?";`

`  print(DART103);`

`  DART103 = "Nasılsın?";`

`  print(DART103);`

`}`

**var sabiti** ile tanımlanan bir değişkene atanmış bir ifade varken yeni bir ifade atanabilir.
