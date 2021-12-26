<h1>Overflow-Float-Display Özellikleri</h1>
<h2>Overflow Özelliği</h2>Tarayıcının genişliği değiştirdiğimizde satırların durumunu belirtir.<br>
<b>overflow: scroll;</b> Tarayıcının boyutunda değişiklik yapıldığı zaman ilgili etiketteki bölüm aştığı zaman scroll bar içerisine koymasını sağlar.<br>
<b>overflow: hidden;</b> Taşan kısmı kaybedilir.<br>
<b>overflow: auto;</b> Bir taşma olduğu zaman scroll bar gözüksün anlamındadır. <br><br>
<h2>Float Özelliği</h2>
Bir niteliğin durumunu belirtmek için kullanılan bir özniteliktir.<br>
<b>float: left;</b> Tarayıcının soluna hizala<br>
<b>float: right;</b> Tarayıcının sağında hizala<br><br>
<h2>Display Özelliği</h2>
Bir öğenin nasıl görüntüleneceğini belirtir.<br>
<b>display: none;</b> Bir öğeyi gizleme özelliğidir.<br>
<b>display: inline;</b> Tarayıcının özellikleri geçerli olmasını sağlar.<br>
<b>display: block;</b> Elemanları blok haline getirmesini sağlar.<br>
<b>display: inline-block;</b> Hem tarayıcının özelliklerine hem de belirlediğimiz özelliklere izin vermesini sağlar.<br><br>
<table>
<thead>
<tr>
<th> CSS Kodu</th>
<th> Açıklama</th>
</tr>
</thead>
<tbody>
  <tr>
   <td>.text1, .text2{color: brown}</td>
   <td><b>class</b> etiketi <b>text1</b> olan ve <b>text2</b> olan etiketlerinin yazı rengi</td>
  </tr>
  <tr>
   <td>img[src="images/ari-ile-papatya.jpeg"]{width: 200px; float: left; margin-right: 20px;}</td>
   <td><b>src="images/ari-ile-papatya.jpeg"</b> olan <b>img</b> etiketinin resmin genişliği, sola hizala ve sağ tarafına 20px boşluk yarat.</td>
  </tr>
  <tr>
   <td>.text2{overflow: auto;}</td>
   <td>Bu paragrafı içerisinde boyutu hangisi büyük ise ona göre ayarla. Yani resmi boyutu paragraf alanından fazlaysa resmin <b>taşmasını önle</b>.</td>
  </tr>
  <tr>
   <td>li{list-style: none; display: inline-block;  padding: 25px;}</td>
   <td><b>li</b> etiketinin içerisindekilerin ön işaretini(<b>list-style</b>) kaldır(<b>none</b>),listeleri blok haline getir ve özellik vermeye izin ver(<b>display: inline-block;</b>), kutu ile yazı arasındaki boşluğu 25px yap.</td>
  </tr>
  <tr>
   <td>a{ display: inline-block; margin-right: 50px;}</td>
   <td><b>a</b> etiketlerin sağ tarafına(<b>margin-right: </b>) 5px aralık yap.</td>
  </tr>
  <tr>
   <td>ul{background-color: 	#ECEFF1; height: 70px; overflow:hidden; border-radius: 20px;}</td>
   <td><b>ul</b> etiketinin arka plan rengi ve yükseklik ayarlanmıştır.<br> <b>overflow:hidden</b> özelliğiyle taşan kısmı kaybedilir<br> <b>border-radius</b> özelliğiyle kenarlıkları yuvarlatılmıştır.</td>
  </tr>
  <tr>
   <td>li:hover{background-color: 	#CFD8DC; border-radius: 10px;}</td>
   <td><b>li</b> etikelerin üzerine gelindiğinde(<b>hover</b>) arka plan rengi ayarlanılmıştır ve kenarlık yuvarlatılmıştır.</td>
  </tr>
  <tr>
   <td>li:active{background-color: #64B5F6;}</td>
   <td><b>li</b> etiketine tıkladığı anda arka plan rengi ayarlanmıştır.</td>
  </tr>
</tbody>
</table>
<br>
<h3>Çalışmanın görüntüsü</h3><br><br>

![overflow-float-display](https://user-images.githubusercontent.com/48285856/147390580-2d36f8ab-9b34-42da-9cd2-84f9a45d0884.png)

<br><br>
HTML ve CSS codlarını derlemek için <a href="https://codepen.io/pen/">HTML-CSS</a> tıklayınız..>
