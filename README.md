1.Kök dizinde "src" isminde bir dizin oluşturun ve içerisine "app.js" adında bir dosya oluşturun.

2."src" dizini altına "lib" adında başka bir dizin açın ve bu dizinde "service.js" adında bir dosya oluşturun.

3."service.js" dosyası içinde "getData" adında bir fonksiyon oluşturun. - Bu fonksiyon "async" olarak tanımlanmalı ve default olarak dışa aktarılmalıdır. Fonksiyonun içindeki asenkron fonksiyonlar "await" ile tanımlanmalıdır. - Fonksiyon Number tipinde tek parametre alır. Bu parametre user id'yi belirtir. - Fonksiyonun görevi aşağıdaki endpoint'e giderek parametrede verilen user id ile ilgili kullanıcının verilerini çekmek olmalı. İstekleri "axios" kütüphanesini kullanarak yapmanız gerekiyor. İsteği yaparken aşağıdaki endpointin sonundaki rakamı parametrede gelen user id'ile değiştirmeniz gerekiyor.

4."app.js" dosyasına yazmış olduğunuz "getData" isimli fonksiyonu "import" edin.


5.Bir alt satırda bu fonksiyonu çalıştırın ve gelen sonucu log'layın.