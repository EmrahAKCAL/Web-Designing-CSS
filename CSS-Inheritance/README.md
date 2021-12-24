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
            <td><b>em</b> etiketinin içerisinde bulunan metni de border(kenarlık) özelliğine dahil et.</td>
        </tr>
        <tr>
            <td>b{color:initial;}</td>
            <td><b>b</b> etiketinin içerisindeki yazı rengini(color) dahil etme. Yani varsayılan olarak kalsın demektir.</td>
        </tr>
    </tbody>
</table> 


