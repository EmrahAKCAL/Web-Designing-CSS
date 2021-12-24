<h1>Grup Selector Nedir?</h1>
CSS kodlarının sayfada fazla yer kaplamaması için aynı css kodlarını bir grup şeklinde yazabiliriz. Grup selectors aynı özellikteki etiketlere ayrı ayrı css kodu yazmak yerine aynı grup içerisinde vermeyi sağlar.
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
            <td>div{color: red;} </td>
            <td><b>div</b> içerisindeki tüm etiketlerin yazı rengini belirlemek için kullanılır.</td>
        </tr>
        <tr>
            <td>div p{background-color: sandybrown;} </td>
            <td><b>div</b> etiketinin altındaki tüm <b>p</b>(paragraf) etkiketlerinin arka plan rengini ayarlamak için kullanılır.</td>
        </tr>
        <tr>
            <td>.etiket1 div{border: 1px solid black;}</td>
            <td><b>class="etiket1"</b> altındaki <b>div</b> etiketlerinin kenarlığını ve rengini belirle.</td>
        </tr>
        <tr>
            <td>.etiket1 div.box1{text-align: center;} </td>
            <td><b>class="etiket1"</b> etiketli <b>class="box1"</b> etiketli <b>div</b> etiketlerinin yazılarını ortala.</td>
        </tr>
        <tr>
        <td> div,p{font-style: italic;} </td>
        <td>Sayfadaki tüm <b>div</b> ve <b>p</b> etiketlerinin yazı stilini ayarla.(bir nevi CSS'de toplama özelliği olarak düşünebiliriz.) </td>
        </tr>
        <tr>
        <td> div.box1, p{font-size: 20px;} </td>
        <td><b>class="box1"</b> olan <b>div</b> leri ve tüm <b>p</b>(paragraf) etiketlerinin yazı boyutunu ayarla. </td>
        </tr>
        <tr>
        <td> div>p{line-height: 60px;} </td>
        <td>Bir üst etiketi <b>div</b> olan <b>p</b> etiketlerinin genişliğini belirlemek. </td>
        </tr>
        <tr>
        <td> p+div{font-variant: small-caps;} </td>
        <td><b>p</b> etiketinden hemen sonra gelen ilk <b>div</b>in karakterlerini büyük yap.</td>
        </tr>
    </tbody>
</table> 
<br><br>
HTML ve CSS codlarını derlemek için <a href="https://codepen.io/pen/">HTML-CSS</a> tıklayınız..
