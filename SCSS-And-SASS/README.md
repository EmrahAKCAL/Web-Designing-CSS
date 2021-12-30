<h1> Sass ve Scss Nedir?</h1>
<h2>SASS</h2>
Sass programlama dili mantığında ve yapısında yazdığımız kodları derleyip CSS kodları haline getiriyor.Sass kullanırken CSS’te olduğu gibi noktalı virgül “;” ve parantez “{}” kullanılamamaktadır. 
<br><br><br>
<h2> Scss</h2>
Scss, css’te olmayan özellikleri veren bir css ön işlemcisidir (css-preprocessor). Css kodlarını daha kolay şekilde yazmak ve css'teki karmaşıklığı önüne geçmek için kullanılır.
<br>Scss özellikleri;
<ul>
<li>Variables($)</li>
<li>Nesting(&)</li>
<li>Extend</li>
<li>Mixin</li>
</ul>
<br><b><i>Variables($)-Değişkenler</i></b><br>
(CSS değişkenleri desteklemekte) Scss ile kolayca değişkenler tanımlayabilirsiniz tek yapmanız gereken değişkenin önüne <b><i>$</i></b> işareti koymanız ve bir css değeri atamanız yeterli. 
Örneğin bir aynı özelliği birçok yerde kullanacaksanız bu değişkenle tanımlayarak kullanmak istediğiniz yerlere değişkenin ismiyle çağırmanız yeterli olacaktır.
<br><b><i>Nesting(&)-İç içe aktarım</i></b><br>
Scss css kurallarınız iç içe koymanıza imkan verir böylece daha temiz ve kısa css yazmanıza yardım eder.<br>
Örneğin CSS'te bir alt öğeye özellik vermek için <b><i>ul li{ } </i></b> şeklinde yazılırken burada <b><i>ul{ li{ }} </i></b> şeklinde yazılır.<br>
<table>
<thead>
<tr>
<th>CSS</th>
<th>SCSS</th>
</tr>
</thead>
<tbody>
<tr>
<td><b>.nav-left </b>{<br>
  list-style: none;<br>
  float: left;<br>
}<br>
<b>.nav-left li</b> {<br>
  display: inline-block;<br>
  margin-left: 40px;<br>
}<br>
<b>.nav-left li:first-child</b> {<br>
  margin: 0;<br>
}<br>
<b>.nav-left li a </b>{<br>
  text-decoration: none;<br>
  text-transform: uppercase;<br>
  color: #fff;<br>
  display: inline-block;<br>
  padding: 10px;<br>
  line-height: 60px;<br>
}<br>
<b>.nav-left li a i </b>{<br>
  margin-right: 5px;<br>
}</td><br>
<td>
$color-white:#fff;<br>
<b>.nav-left</b>{<br>
  list-style: none;<br>
  float: left;<br>
  <b>li</b>{<br>
  display: inline-block;<br>
  margin-left: 40px;<br>
    <b>&:first-child</b>{<br>
      margin: 0;<br>
    }<br>
   <b> a</b>{<br>
      text-decoration: none;<br>
      text-transform: uppercase;<br>
      color: $color-white;<br>
      display: inline-block;<br>
      padding: 10px;<br>
      line-height: 60px;<br>
     <b> i</b>{<br>
        margin-right: 5px;<br>
      }<br>
    }<br>
}<br>
  
}</td><br>
</tr>
</tbody>
</table>
<br>
<br>
Yukarıdaki tabloda CSS ve SCSS kodlarını karşılaştırdığımızda kodlarda pek fazla bir fark gözükmese de CSS tarafındaki etiketler oldukça karmaşık gözükmektedir. 
Ancak SCSS kısmında değişkenler(Variables($)) ve iç içe aktarım( Nesting(&)) özellikleri kullanılarak bu karmaşıklığın önüne geçilmiştir.<br><br><br>

![veriables](https://user-images.githubusercontent.com/48285856/147763725-5d334aee-03eb-45a4-8558-38bba126def9.png)


<br><br>
HTML ve CSS codlarını derlemek için <a href="https://codepen.io/pen/">HTML-CSS</a> tıklayınız..






