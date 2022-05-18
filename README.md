# LetMeHack

- Docker based Cyber Security Training Web Platform (Docker tabanlı Siber Güvenlik Web Eğitim Platformu)

# Gereksinimler 🕵️‍♂️

- Docker kurulu bir işletim sistemi gereklidir. (Linux-Windows-Mac)
  
# Kurulum ⏳

  1. Öncelikle projeyi indiriniz :  ``` git clone https://github.com/istec-iuc/letmehack.git ```
 
  2. Ardından projedeki labların çalışır hale getirmek için (sql labları hariç) :
  
     - **labs** klasörü içerisine girin, içerisinde **labları ve isimlerini** göreceksiniz.
     
     - Çalıştırmak istediğiniz labın olduğu dizinde ``` docker build -t  <labismi> . ```  şeklinde çalıştırınız. Örnek : ``` docker build -t  ce1 . ``` gibi

     - **Sql Labları için :** 
  
     - _sqli1 labı için_ : İlk önce lab klasörünün( /labs/sqli1 ) içerisindeki **db** klaörünün içerisine girip ``` docker build -t sql_db . ``` komutunu çalıştırın,   daha sonra aynı lab klasörünün içerisindeki **web** klaörünün içerisine girip``` docker build -t sqli1. ``` komutlarını çalıştırınız. 


     - _sqli2 labı için_ : İlk önce lab klasörünün( /labs/sqli2 ) içerisindeki **db** klaörünün içerisine girip ``` docker build -t sql_db2 . ``` komutunu çalıştırın,   daha sonra aynı lab klasörünün içerisindeki **web** klaörünün içerisine girip``` docker build -t sqli2. ``` komutlarını çalıştırınız. 


  3. Ardından ana dizine geri dönün ( indirdiğiniz letmehack klasörünün içerisine )  
  
  4. Şu komutu çalıştırın: ``` docker compose up -d ```
  
  5. ``` Localhost:80 ``` üzerinden projeye tarayıcınızdan erişebilirsiniz.
 

# Projenin Görünümü 📸

<img width="1307" alt="1" src="https://user-images.githubusercontent.com/60710585/169040587-6882df58-69cd-43a3-b9f0-917e6d29f646.png">
<img width="1307" alt="2" src="https://user-images.githubusercontent.com/60710585/169040682-3d17bf27-57da-4d2c-a892-3c08e387eeb5.png">


# Kullanıcı Kayıdı 📝

- Projedeki lablara kayıt olmadan erişmeye çalıştığınızda aşağıdaki gibi bir görüntüyle karşılaşırsınız. LetMeHack projesinde kullanıcı kaydı olmadan lablara erişim mümkün değildir.

<img width="1307" alt="3" src="https://user-images.githubusercontent.com/60710585/169040923-99153b0b-79bc-4768-ab05-a06baed40cb8.png">


- Bunu çözmek için sitenin sağ üst tarafındaki kayıt butonuna tıklayıp gerekli bilgileri doldurduktan sonra ücretsiz bir şekilde kaydolabilirsiniz. Sonrasında aşağıdaki resimdeki gibi giriş ekranından kullanıcı girişinizi yapabilirsiniz.

<img width="1307" alt="4" src="https://user-images.githubusercontent.com/60710585/169040943-5b309095-d29f-4849-abbd-fea62f81e32c.png">


- Artık platformdaki lablara eriştiğinizde aşağıdaki resimdeki gibi lab başlat butonu aktif olacaktır. 

<img width="1307" alt="5" src="https://user-images.githubusercontent.com/60710585/169040971-102de1f4-8c66-48a2-b14c-8e8fb34c7b03.png">

- Butona tıkladığınızda size atanan **link:port** şeklindeki url ye tıklayarak labları çözmeye başlayabilirsiniz.

<img width="1307" alt="6" src="https://user-images.githubusercontent.com/60710585/169041030-fd185dea-4cd4-46a6-ae4d-18242744b84a.png">


# İletişim ☎️

## LinkedIn:  
  - [Zeynep GÖK](https://www.linkedin.com/in/zeynepgok/)
  - [Emrah YILDIRIM](https://www.linkedin.com/in/emr4h//)
  - [Ömer KELEŞ](https://www.linkedin.com/in/%C3%B6mer-kele%C5%9F-377801175/)
  - [Tugba DÖLEK](https://www.linkedin.com/in/tu%C4%9Fba-d%C3%B6lek/)
  - [Ekin YAZICI](https://www.linkedin.com/in/ekin-yzc-0621b11b3/)
  
  
  
  
  
  
  
  
  






  

                          
                              
    
 
          
  

