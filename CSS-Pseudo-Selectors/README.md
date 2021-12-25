<h1>Pseudo Selector</h1>
Bazen bir paragrafın belli bir bölümüne bazı özellikler vermek isteriz. Örneğin bir paragrafın ilk harfine veya bir öğe üzerine geldiğinde bazı değişiklikler olamsını isteriz. Paragraf önecesine veya sonrasına bir şeyler eklemek için pseudo özellikleri kullanılır.<br><br><br>
<table>
<thead>
<tr>
<th>CSS Kodu</th>
<th>Açıklama</th>
</tr>
</thead>
<tbody>
<tr>
<td>h1, h2{text-align: center;}</td>
<td><b>h1</b> ve <b>h2</b> etiketlerinin yazılarını ortala.</td>
</tr>
<tr>
<td>p::first-line {word-spacing: 2px; letter-spacing: 1px; color: blue;}</td>
<td>Tüm <b>p</b> etiketlerinin <b>ilk satırına(first-line)</b> uygula.<br> <b>word-spacing:</b> kelimeler arası boşluk <br><b>letter-spacing:</b> harfler arası boşluk verilmektedir.</td>
</tr>
<tr>
<td>p.parag3::first-line{ background-color: gray;}</td>
<td><b>class="parag3"</b> olan <b>p</b> etiketinin <b>ilk satırını(first-line)</b> arka plan rengini ayarlamak</td>
</tr>
<tr>
<td>p::first-letter{font-size: 30px; color: gold;}</td>
<td>Tüm <b>p</b> etiketlerinin <b>ilk harfini(first-letter)</b></td>
</tr>
<tr>
<td>p::after{content:"--Paragraf Sonu"; color: teal;}</td>
<td>Tüm <b>p</b> etiketlerinden hemen <b>sonra(after) "--Paragraf Sonu"(content)</b> ekle</td>
</tr>
<tr>
<td>p::before{content: "Paragraf Başlangıcı--"; color: yellow;}</td>
<td>Tüm <b>p</b> etiketlerinden <b>önce(before) "Paragraf Başlangıcı--"(content)</b> ekle</td>
</tr>
<tr>
<td>ul li:first-child{color: red;}</td>
<td><b>ul</b> etiketinin içerisinde bulunan <b>ilk(first-child)) li</b> etiketinin yazı rengi</td>
</tr>
<tr>
<td>ul li:last-child{color: gold}</td>
<td><b>ul</b> etiketinin içerisinde bulunan <b>son(last-child) li</b> etiketinin yazı rengi</td>
</tr>
<tr>
<td>ul li:nth-of-type(even){border: 2px solid brown; padding: 3px; background-color: gold; color: blue;}</td>
<td><b>ul</b> etiketinin içerisinde bulunan çift(<b>nth-of-type(even)</b>) sıralamasında bulunan <b>li</b> etiketler</td>
</tr>
<tr>
<td>ul li:nth-of-type(odd){border: 2px solid gold; padding: 3px; background-color: red; color: wheat;} </td>
<td><b>ul</b> etiketinin içerisinde bulunan tek(<b>nth-of-type(odd)</b>) sıralamasında bulunan <b>li</b> etiketleri</td>
</tr>
<tr>
<td>a:link{background-color: red;}</td>
<td>Link tıklanılmamış hali arka plan rengi kırmızıdır.</td>
</tr>
<tr>
<td>a:hover{background-color: yellow;}</td>
<td> Mause ile linkin üzerine(<b>hover</b>) geldiğinde arka plan rengi sarı olacak</td>
</tr>
<tr>
<td>a:active{background-color: blue;}</td>
<td>Linke tıklandığı(<b>active</b>) zaman arka plan rengi mavi olacak</td>
</tr>
<tr>
<td>a:visited{background-color: purple;}</td>
<td>Link tıklanılmış(<b>visited</b>) hali arka plan rengi</td>
</tr>
<tr>
<td>div:hover span{display: block; color: blue;}</td>
<td><b>div</b> üzerine geldiğinde(<b>hover</b>) <b>span</b> etiketi içerisinde bulunan yazıyı görünür yap ve yazı rengi mavi olacak.</td>
</tr>
<tr>
<td>a{display: block; padding: 5px 8px; text-decoration: none; width: 80px; border: 1px solid blue; margin-bottom: grey; color: wheat;}</td>
<td>Tüm <b>a</b> etiketlerinin içerisinde bulunanları blok(display: block) haline getir.</td>
</tr>
</tbody>
</table>
<br><br>
HTML ve CSS codlarını derlemek için <a href="https://codepen.io/pen/">HTML-CSS</a> tıklayınız..
