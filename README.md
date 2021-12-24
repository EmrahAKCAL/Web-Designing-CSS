<h1> CSS Nedir?</h1>
CSS, bir HTML belgesine stil vermek için kullandığımız dildir. CSS, HTML öğelerinin nasıl görüntülenmesi gerektiğini açıklar.
HTML sayfalarına farklı şekillerde CSS stilleri verebiliriz.
<ul>
  <li><b>Inline CSS:</b> Satır içerisinde kullanmak.</li>
  Örneğin < p style="background-color:red">
  <li><b>Internal CSS:</b> Html sayfasının head bölümünde style etiketi kullanılarak sayfaya stil verebiliriz.</li>
  <li><b>External CSS:</b> CSS kodlarını .css uzantılı bir dosyada yazarak html sayfasında <i>head</i> bölümünde <b><i>< link rel="stylesheet" href="dosyaadı.css"></i></b> css dosyasını konumlandırılara kullanmak.</li>
</ul>
CSS kodları için<b>{ }</b> süslü parantezler kullanılır.<br>
Selector { CSS Cod} şeklinde yazılır.<br><br>
Selector Çeşitleri
<table>
  <thead>
    <tr>
      <th> Etiket </th>
      <th> HTML < > </th>
      <th> CSS { } </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Etiket isminini kullanılarak </td>
      <td>< p> Paragraf < /p> </td>
      <td>p {color: red} </td>
    </tr>
      <tr>
      <td> Class etiketi kullanılarak </td>
      <td>< p class="blog1"> Paragraf < /p> </td>
      <td>.blog1 {color: red} </td>
    </tr>
    <tr>
      <td> Id kimliğini kullanılarak </td>
      <td>< p id="blog1"> Paragraf < /p> </td>
      <td>#blog1 {color: red} </td>
    </tr>
       <tr>
         <td> Sayfanın bütün etiketlere uygulamak için <br><b>*</b> selector </td>
      <td>< p> Paragraf < /p></td>
      <td>* {color: red} <br>sayfadaki tüm yazıları kırmızı yapar. </td>
    </tr>
  </tbody>
</table>
<br><br><h2>CSS'de Etiketlerin Önceliği</h2>
Aynı etiket ismi(selector)kullanıldığında en baskın olan en son yazılan etiket olur.<br>
Örneğin <i>style</i> etiketinin içerisine;<br><b>h1 {background-color: red;}</b><br><b> h1 {background-color: blue;}</b><br>
Şeklinde yazdığımız css kodların en baskını en son satırdaki olur. Yani bu durumuda sayfanın arka plan rengi <b>mavi</b> olacaktır.
<br><br> <b>Öncelik Etiket Sıralaması</b>
<ul>
  <li><b>Inline Selector:</b> < p style=""></li>
  <li><b>Id Selector:</b> #Selector{ }</li>
  <li><b>Class Selector:</b> .Selector{ }</li>
  <li><b>Tag Selector:</b> p { }</li>
</ul>
<br><br><br>
HTML ve CSS codlarını derlemek için <a href="https://codepen.io/pen/"> HTML-CSS-JavaScript</a> tıklayınız.
