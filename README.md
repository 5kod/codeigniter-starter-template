# Codeigniter Starter Template

CodeIgniter 4.4.5 Temiz Kurulum. 
Sıfır Starter. 
Başlangıç. At çalıştır şablonu.


# xampp için extension hatası verirse php.ini içerisinden ilgili extension etkinleştirilmeli.
# extension=intl extension=pdo_sqlite vb. 
# apache restart edilmeli.
/app/Config/App.php
public string $baseURL = 'http://localhost/codeigniter-starter-template/';


# spark serve ile ekstra işlem yok
php spark serve 
PHP 8.3.2 Development Server (http://localhost:8080) started


# İlk işlem
git init 
git add . 
git commit -m "ilk işlem" 
git branch -M main 
git remote add origin https://github.com/5kod/codeigniter-starter-template.git 
git push -u origin main 


# Değişiklikler
git add . 
git commit -m "ufak değişklikler" 
git push -u origin main 