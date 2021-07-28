1) inventory dosyası düzenlenir.

2) gitlab/gitlab-installation.yml daki "Copy GitLab configuration file" playindeki ip adresi düzenlenir.

----------------------------------------------------------

1) Runner kurulduktan sonra, gitlab-runner kullanıcısında ssh-keygen oluşturarak public keyini server2 rootu ile paylaş

2) Sunucu redhat ise paketler içerisindeki epel-release yi çıkarabilirsin.

3) Son olarak gitlab üzerinden server2 deki prometheus ve alertmanager ile ilgili olan ipleri değiştir.
