<h1>Mixin Ve Extend Özelliği</h1>
<b><i>Mixin:</i></b>  Tekrarlanan css kodları tek bir <b><i>@mixin</i></b> parametresi altında toplayarak bunları kullanmak istediğimiz etiketlerde <b><i>@include</i></b> parametresiyle çağrılmasına olanak veren bir özelliktir.<br>
<b><i>Extend:</i></b> Mixin özelliğine benzemekle birlikte var olan bir sınıfı genişletme işlemi olarak düşünebiliriz. Aynı CSS kodlarını birçok yerde tekrar tekrar yazmak yerine <b><i>%box</i></b>(etiket ismi değiştirebilirsiniz) gibi bir etiket altında yazarak ilgili etikette sadece ek kodlar yazmak yeterli olacaktır. Bu kodları <b><i>@extend %box</i></b> kullanılarak etikete çağrılır.<br>
Bu iki özellik arasındaki temel fark mixin sınıfının içerisindeki css kodların özellikleri @include ile değiştirillebilirken extend de böyle bir özellik olmamasıdır. <br>
<h2> Mixin Kullanımı</h2>
@mixin box($width, $color){<br>
width:$width;<br>
background-color: red;<br>
color:$color;<br>
}<br>
#first{<br>
@include box(300px, blue);<br>
}<br><br>
Burada id="first" olan etiketin genişliği 300px, yazı rengi blue ve arka planı red olacaktır. Dikkat edecek olursanız arkaplan rengi sabit kabul edi genişliğini ve yazı rengini değiştirdik.<br><br>
<h2>Extend Kullanımı</h2>
%box{<br>
width:300px;<br>
background-color: red;<br>
color:blue;<br>
}<br>
#first{<br>
@extend %box;<br>
}<br><br>
Şeklinde olacaktır. Çünkü extend özelliğinde etiket içerisinde değiştirme özelliği yoktur. Sadece kopyala-yapıştır şeklindedir.<br><br>

HTML ve CSS codlarını derlemek için <a href="https://codepen.io/pen/">HTML-CSS</a> tıklayınız..
