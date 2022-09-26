Docker-Compose-Nginx-Reverse-Proxy-Multiple-Containers

-İlk olarak terraform dan alt yapı adına içinde docker ve docker compose olan iki ubuntu server AWS de kaldırdım.

-Ardından yapıyı gitub reposuna gönderdim ve oradan pull işlemi ile locale aldım.

-3 adet microservis dosyaların da oluşturduğum docker-compose komutları ile microserviceleri ayağa kaldırdım.

-Diğer sunucuda Reverse proxy yapmadan önce oluşturdumuz domain ve ip görme adına ect/host/ dosyasına ip ve domainleri atadım. -->

-Sonrasında reverse proxy dosyasına gelerek ngnix-reverse proxy dosyasında compose komutları ile ayağa kaldırdım. -->

-curl komutu ile proxy serverden yapıda bulunan microservice çekebildim ama browser üzerinden bu işlemlerde tam istediğim gibi olmadı.

-Netcore projesi olarak yapılan projeleri inceledim ve ekte bulunan Dockerfile ile çalışılabilir.

-Genel olarak çok farklı yöntemler mevcut ama bana verilen task çok daha özel bir proje olduğunu gördüm.

-Sonuç olarak çok araştırdım ve çok videolar izledim. İstediğim gibi olmasa da çok şey öğrendim. 

Teşekkürler.....



