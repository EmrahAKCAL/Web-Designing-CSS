<h1>Flexbox Nedir</h1>
Flex özelliği elemanları çok esnek bir şekilde hareket ettirmemizi sağlayan özelliktir. <br><br>

![flex1](https://user-images.githubusercontent.com/48285856/147812162-38f9d120-fb54-4528-a351-285e44d62bdf.png)
<br><br>
<b><i>display: inline-block;</i></b> yerine <b><i>display: flex</i></b> yapmamız yeterlidir. Böylelikle istediğimiz elemanları esnek bir şekilde hizalama işlemini yapabiliriz. <br>
<table>
<thead>
<tr>
<th>CSS Kodu</th>
<th>Açıklama</th>
</tr>
</thead>
<tbody>
<tr>
<td><b><i>display: flex;</i></b></td>
<td>Elemanları bir satırda yanyana getirir(inline-block)</td>
</tr>
<tr>
<td><b><i>flex-direction:</i></b></td>
<td>Elemanları sıralama<br>
<b><i>row-reverse;</i></b> elemanları satırda tersten sıralar.<br>
<b><i>column;</i></b> elemanları alt alta getirir. <br>
<b><i>column-reverse;</i></b> colum sıralamayı tersten yapar.<br>
</td>
</tr>
<tr>
<td><b><i>flex-wrap:</i></b></td>
<td>Tarayıcı genişliği daraltıldığında elemanların hizalaması.<br>
<b><i>wrap;</i></b> container küçüldükçe sığmayan eleman alta gelir.<br>
<b><i>wrap-reverse;</i></b>container küçüldükçe sığmayan eleman üste gelir.</td>
</tr>
<tr>
<td><b><i>justify-content: </i></b></td>
<td>Elemanların satır içerisindeki konumu.<br>
<b><i>center;</i></b>Elemanları ortada hizalar.<br>
<b><i>flex-start;</i></b> elemanları solda hizalar.<br>
<b><i>flex-end;</i></b> elemanları sağda hizalar.<br>
<b><i>space-between;</i></b> elemanlar arasında eşit mesafe bırakır ve elemanlar tarayıcıya sığdırır.<br>
<b><i>space-evenly;</i></b> elemanların sağında ve solunda eşit mesafe bırakır.<br>
</td>
</tr>
<tr>
<td><b><i>align-items:</i></b></td>
<td><b><i>stretch;</i></b> Dikeyde varsayılan özellik.<br>
<b><i>flex-start;</i></b> dikeyde en üstte hizalanır.<br>
<b><i>center;</i></b> dikeyde ortada hizala<br>
<b><i>flex-end;</i></b> dikeyde en altta hizalanır.<br>
<b><i>baseline;</i></b> içeriğindeki yazıların en alt sınırında hizalama yapar.</td>
</tr>
<tr>
<td><b><i>align-content:</i></b></td>
<td>Her satır arası mesafe</td>
</tr>
</tbody>
</table>
