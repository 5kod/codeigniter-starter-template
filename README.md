# Codeigniter Starter Template

CodeIgniter 4.4.5 Temiz Kurulum. \
Sıfır Starter. \
Başlangıç. \
At çalıştır şablonu. 


### spark 
spark serve ile ekstra işlem yok 
```git
php spark serve
``` 
PHP 8.3.2 Development Server (http://localhost:8080) started 

---


### xampp
#### codeigniter
- /app/Config/App.php dosyasında yol belirtilmeli.
```git
public string $baseURL = 'http://localhost/codeigniter-starter-template/';
```
>Apache start sonrası linke git: http://localhost/codeigniter-starter-template/

extension hatası verirse php.ini içerisinden ilgili extension etkinleştirilmeli.\
etkinleştirme için **;extension=intl** satır önündeki **;** silinmeli.

- extension=intl
- extension=pdo_sqlite
- vb. 
- apache restart edilmeli.
