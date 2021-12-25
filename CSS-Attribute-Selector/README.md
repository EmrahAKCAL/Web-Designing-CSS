<h1>CSS'de Özellik Seçici</h1>
Bazı etiketlere daha kolay şekilde ulaşmak veya daha alt etiketlerine ulaşmak için kullanılan bir css özelliğidir.
<br><br>

<table>
    <thead>
        <tr>
            <th> CSS Kodu</th>
            <th> Açıklama</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>p[title]{border: 2px solid brown;}  </td>
            <td><b>title</b> etiketi olan bütün <b>p</b> etiketleri</td>
        </tr>
        <tr>
            <td>p[title="birinci paragraf"]{color: red;}  </td>
            <td><b>title="birinci paragraf"</b> olan bütün <b>p</b> etiketleri</td>
        </tr>
        <tr>
            <td>p[title~="birinci"]{background-color: gold;} </td>
            <td><b>title</b> etiketin içerisinde <b>"birinci"</b> kelimesi olan bütün <b>p</b> etiketleri</td>
        </tr>
        <tr>
            <td>p[title="ikinci paragraf"]{color: green;} </td>
            <td><b>title="ikinci paragraf"</b> olan tüm <b>p</b> etiketleri</td>
        </tr>
        <tr>
        <td>p[title~="ikinci"]{background-color: grey;}</td>
        <td><b>title</b> etiketin içerisinde <b>"ikinci"</b> kelimesi olan tüm <b>p</b> etiketleri</td>
        </tr>
        <tr>
        <td> p {font-size: 20px;} </td>
        <td>Bütün <b>p</b> etiketlerinin yazı boyutu </td>
        </tr>
        <tr>
        <td>a[href^="https"]{color: orange;}</td>
        <td><b>href</b> etiketi <b>https</b> ile başlayan tüm <b>a</b> etiketleri</td>
        </tr>
        <tr>
        <td>a[href$="net"]{color: aqua;} </td>
        <td><b>href</b> etiketi <b>net</b> ile biten bütün <b>a</b> etiketleri</td>
        </tr>
         <tr>
        <td>a[href="http://www.google.net"][target="_blank"]{background-color: blue;}</td>
        <td>Hem<b>href="http://www.google.net"</b> olan hem de <b>target="_blank"</b> olan bütün <b>a</b> etiketleri</td>
        </tr>
         <tr>
        <td>*{padding: 20px;}</td>
        <td>Tüm etiketlerin kenarlık ile yazı arasındaki mesafeyi artır.</td>
        </tr>
    </tbody>
</table> 
<br><br>
HTML ve CSS codlarını derlemek için <a href="https://codepen.io/pen/">HTML-CSS</a> tıklayınız..
