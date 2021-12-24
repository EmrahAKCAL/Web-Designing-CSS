<h1>CSS'de Inheritance Nedir?</h1>
CSS koduyla bir metne özellik vermek istediğimizde metin <em>içerisinde kapsam dışı bırakmak</em> isteidğimiz bölümler olabilir. Bunun için etiketi <b>inherit</b> veya iptal etmek için ise <b>initial</b> yapmamız gerekir. <br>
<table>
    <thead>
        <tr>
            <th> CSS Kodu</th>
            <th> Açıklama</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>body{ color: mediumblue; font-size: 15px;}</td>
            <td><b>body</b> etiketi içerisinde bulunan tüm yazı renkleri ve yazı boyutu ayarlanmıştır.</td>
        </tr>
        <tr>
            <td>p{color: green; border: 1px solid red; background-color: yellow;}</td>
            <td>Tüm <b>p</b> etiketlerinin yazı rengi, kenarlık ve kenar rengi, arka plan rengi ayarlanmıştır.</td>
        </tr>
        <tr>
            <td>em{border: inherit;}</td>
            <td><b>em</b> etiketinin içerisinde bulunan metnine de kenarlık ekle. Yani ayrı bir border ekler.</td>
        </tr>
        <tr>
            <td>b{color:initial;}</td>
            <td><b>b</b> etiketinin içerisindeki yazı rengi varsayılan olarak ayarla.</td>
        </tr>
    </tbody>
</table> 


