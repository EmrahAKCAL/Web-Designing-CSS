<h1>CSS Positioning</h1>
<b>Position:</b> Bir element için kullanılan yerleştirme yöntemi türünü belirtir.<br>
Beş farklı konum değeri vardır.
<ul>
<li><b>static:</b> Varsayılan konumu belirtir.</li>
<li><b>relative:</b> Bulunduğu konumdan ötele</li>
<li><b>fixed:</b> Tarayıcıda sabit bir yerde konumlandırır.</li>
<li><b>absolute:</b> Tarayıcıya göre konumlandırılır.</li>
<li><b>sticky:</b> Scroll barın durumuna göre konumlanrılmasını sağlar. Genellikle sayfaların menü kısımları için kullanılmaktadır.</li>
</ul><br><br>
<table>
    <thead>
        <tr>
            <th> CSS Kodu</th>
            <th> Açıklama</th>
        </tr>
    </thead>
    <tbody>
         <tr>
        <td>.box{ width: 150px;}</td>
        <td><b>class="box"</b> olan etiketlere genişlik verilmiştir.</td>
        </tr>
         <tr>
        <td>#container{float: left; width: 1180px;}</td>
        <td><b>id="container"</b> olan etiketi sola hizala ve genişlik verilmiştir.</td>
        </tr>
         <tr>
        <td>#first-div{background-color: 	#EEE8AA; width: 70%;}</td>
        <td><b>id="first-div"</b> olan etikete arka plan rengi verilmiştir ve tarayıcının %70 lik kısmını kaplasın.</td>
        </tr>
         <tr>
        <td>#second-div{background-color: #FFFFE0; width: 70%;} </td>
        <td><b>id="second-div"</b> olan etikete arka plan rengi verilmiştir ve tarayıcının %70 lik kısmını kaplasın.</td>
        </tr>
         <tr>
        <td>#block{background-color: #FFE4B5; height: 600px; width: 300px; position:fixed; top: 100px; right: 100px;}</td>
        <td><b>id="block"</b> olan etikete arka plan rengi, yükseklik-genişlik değerleri verilmiştir. Bu etiketi konumlandırılacak yerde sabitle(<b>position:fixed;</b>), konumu üstten(<b>top</b>) ve sağdan(<b>right</b>) 100px ötele.</td>
        </tr>
         <tr>
        <td>#data{position: relative; float: right; right: 10px;} </td>
        <td><b>id="data"</b> olan etiketi bulunduğu konumdan ötele(<b>position: relative;</b>), sağa konumlandır(<b>float: right</b>), sağ tarafından 10px ötele</td>
        </tr>
         <tr>
        <td>#container2{position: absolute; left: 60px; top: 20px;}</td>
        <td><b>id="container2"</b> olan etiketi tarayıcıya göre konumlandır.</td>
        </tr>
         <tr>
        <td>#user{position:relative; top: 30px; text-align: center; margin-bottom: 10px;}</td>
        <td><b>id="user"</b> olan etiketi bulunduğu konumdan ötele(<b>position: relative;</b>)</td>
        </tr>
         <tr>
        <td>.links{display: block; margin-top: 10px; position:relative; left: 30px;}</td>
        <td> <b>class="links"</b> olan etiketleri blok haline getir(<b>display:block</b>) ve bulunduğu konumdan ötele(<b>position: relative;</b>)</td>
        </tr>
         <tr>
        <td>.links:hover{background-color: 	#CFD8DC;}</td>
        <td><b>class</b> etiketi <b>links</b> olan etikelerin üzerine gelindiğinde(<b>hover</b>) arka plan rengi ayarlanılmıştır ve kenarlık yuvarlatılmıştır.</td>
        </tr>
         <tr>
        <td>li{list-style: none; display: inline-block;  padding: 25px;}</td>
        <td><b>li</b> etiketinin içerisindekilerin ön işaretini(<b>list-style</b>) kaldır(<b>none</b>),listeleri blok haline getir ve özellik vermeye izin ver(b>display: inline-block;</b>), kutu ile yazı arasındaki boşluğu 25px yap.</td>
        </tr>
          <tr>
        <td>a{ display: inline-block; margin-right: 50px;}</td>
        <td><b>a</b> etiketlerin sağ tarafına 5px boşluk yarat.</td>
        </tr>
          <tr>
        <td>ul{background-color: 	#ECEFF1; height: 70px; overflow:hidden; border-radius: 20px; }</td>
        <td><b>ul</b> etiketinin arka plan rengi ve yükseklik ayarlanmıştır.<br> <b>overflow:hidden;</b> özelliğiyle taşan kısmı kaybedilir. <br><b> border-radius</b> özelliğiyle kenarlıkları yuvarlatılmıştır.</td>
        </tr>
          <tr>
        <td>li:hover{background-color: 	#CFD8DC; border-radius: 10px;} </td>
        <td><b>li</b> etikelerin üzerine gelindiğinde(<b>hover</b>) arka plan rengi ayarlanılmıştır ve kenarlık yuvarlatılmıştır.</td>
        </tr>
          <tr>
        <td>li:active{background-color: #64B5F6;}</td>
        <td><b>li</b> etiketine tıkladığı anda arka plan rengi ayarlanmıştır.</td>
        </tr>
          <tr>
        <td>nav{position: sticky; top: 0px;}</td>
        <td><b>nav</b> etiketliyi üstten konumu sıfır olduğunda(<b>top: 0px;</b>) scroll barda sabitle(<b>position: sticky;</b>).</td>
        </tr>
    </tbody>
</table> <br><br>
<h2>Çalışmanın Görüntüsü Aşağıdaki Gibidir.</h2><br>

![position](https://user-images.githubusercontent.com/48285856/147415674-f0c78922-1717-47e2-a449-b8bffbd84d7a.png)
<br><br>
HTML ve CSS codlarını derlemek için <a href="https://codepen.io/pen/">HTML-CSS</a> tıklayınız..
