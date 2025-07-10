# İlk Web Sitesi  

## Bu uygulama Bootstrap kullanılmıştır.
## Github page ile yayınlandı.
### [Bu link ile ulaşabilirsiniz](https://kubilaydin.github.io/Odev-1_Ilk_Web_Site/).
## Aşağıdakı sıra ile oluşturuldu.
* `index.html` eklendi.
* Başlık kısmı eklendi. 
    ```
    <h1>Kubilay Aydın</h1>
    ```
* Bootstrap class'ı ile `text-center` resim ortalandı.
* Resim `div` içerisine `img-fluid` sıkıştırıldı. 
* Resime `alt` oluşturuldu.
```
    <div class="text-center">
        <img src="img/Grey BG.png" alt="pp" class="img-fluid">
    </div>
```
* `section` ile Özgeçmiş ve Tanıtma kısmı oluşturuldu.
* `section` kısmına özel id eklendi.
```
    <section id="cv">
    <h2>Özgeçmiş</h2>
    <p>Mezun olduktan sonra bir fırsat görüp AutoCad eğitimi aldım.
    Elve Luxury Mobilya’da çizim alanında bir staj gördüm.
    Birkaç ay ingilizce kursu aldım. Satış alanında Casper Bilgisayar
    Sistemleri A.Ş’de Satış Danışmanlığı yaptım.
    Front-End tarafında kendimi geliştirip web siteleri tasarlıyorum.</p>
    </section>
```
* `div` ile Eğtim bilgileri eklendi.
* `div` özel id eklendi.
* `ol` liste oluşturuldu.
* Bootstrap ile style oluşturuldu. `list-group` `list-group-item`
```
    <div id="education">
    <h2>Eğitim</h3>
    <p>Doğuş Üniversitesi Bilgisayar Programcılığı mezunuyum.</p>
    <ol class="list-group">
        <li class="list-group-item list-group-item-warning" >Doğuş Üniversitesi Bilgisayar Programcılığı Ağustos 2019 - Haziran 2021</li>
        <li class="list-group-item list-group-item-warning">Patika.dev Haziran 2024 - Ekim 2024</li>
    </ol>
    </div>
```
 * `div` ile İş Deneyimi kısmı eklendi.
 * `div` için özel id oluşturuldu.
 * `ol` ile liste oluşturuldu.
 * Bootstrap ile style oluşturuldu.`list-group` `list-group-item`
 * Bootstrap ile class'i ile renklendirildi. 
 ```
    <div id="skills">
    <h2>Yetenekler</h2>
    <p>Front End ve teknik çizim alanında kurslar aldım.</p>
    <ul class="list-group">
        <li class="list-group-item list-group-item-primary">AutoCAD</li>
        <li class="list-group-item list-group-item-secondary">Alphacam</li>
        <li class="list-group-item list-group-item-danger">Cabinet Vision</li>
        <li class="list-group-item list-group-item-success">CSS</li>
        <li class="list-group-item list-group-item-warning">Javascript</li>
        <li class="list-group-item list-group-item-info">React</li>
    </ul>
    </div>
```   
* `div` ile İletişim kısmı eklendi.
* `div` için özel id oluşturuldu.
* `ol` ile liste oluşturuldu.
* `a` ile link bilgileri oluşturuldu.
* `target="blank"` ile yeni sekmede açılması sağlandı.
```
    <div id="communication">
    <h2>İletişim</h2>    
    <p>Bana aşağıdaki linklerden ulaşabilir ve projelerimi görebilirsiniz.</p>
    <ol class="list-group">
        <li class="list-group-item list-group-item-success"><a href="https://www.linkedin.com/in/kubilaydin/" target="_blank">LinkedIn</a></li>
        <li class="list-group-item list-group-item-success"><a href="https://github.com/KubilAydin" target="_blank">GitHub</a></li>            
    </ol>
    </div>  
```
* `div` ile Lokasyon bilgisi oluşturuldu.
* `div` için özel id oluşturuldu.
* Bootstrap kullanılarak container oluşturuldu. Flex ile responsive tasarlandı. Sayfayı ortalayacak şekilde konumlandırıldı.
```
    <div id="location" class="container d-flex justify-content-center mt-3">
    <iframe src="https://www.google.com/maps/embed?pb=!1m17!1m12!1m3!1d752.5434080418518!2d29.021984394086914!3d41.021457084818685!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m2!1m1!2zNDHCsDAxJzE4LjgiTiAyOcKwMDEnMTguNiJF!5e0!3m2!1str!2str!4v1752074929126!5m2!1str!2str" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>    
```
* `style` kısmı oluşturuldu.
* `*` sayfanın font değiştirildi.
* `iframe` hizalandı ve genişlik verildi.
* `h2` margin kullanılarak üsten boşluk oluşturuldu.
* `h1,h2,p,a` belirtilen öğeler hizalandı altan boşluk bıraktırıldı.
* `ol,ul,li` belirtilen  öğeler hizalandı ve font kalınlaştırıldı.
* `a` öğeleri için otomatik tanımlanan alt çizgi kaldıırldı.
```
    <style>
        * {
            font-family: 'Courier New', Courier, monospace;
        }
        iframe {
            text-align: center;
            width: 100%;
        }
        h2 {
            margin-top: 10px;
        }
        h1,h2,p,a {
            text-align: center;
            margin-bottom: 5px;
        }
        ol,ul,li {
            text-align: center;
            font-weight: bolder;
        }
        a{
            text-decoration: none;
        }
    </style>
```
* Github page ile yayınlandı. [Bu link ile ulaşabilirsiniz](https://kubilaydin.github.io/Odev-1_Ilk_Web_Site/).