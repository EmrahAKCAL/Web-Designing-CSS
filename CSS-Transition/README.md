<h1>Geçiş Efekleri</h1>
<b><i>Taransition:</i></b> Hover olayının belli bir süre içerisinde gerçekleşme olayıdır.<br>
Geçiş efekti vermek istediğimiz olay tanımlanır ve kaç sn'de gerçekleşeceğini belirtiriz. Daha sonra etiketin hover kısmına olacak olaylar tanımlanır.<br><br><br>
<i>Örneğin:</i> <br>
.box{ <br>
width: 200px;<br>
height: 200px;<br>
<b><i>transition: width 2s, height 3s;</i></b> (burada genişlik ve yükseklik değişeceğini ve genişlik 2 saniyede yükseklik ise 3saniyede gerçeklemesini tanımladık)<br>
}<br>
.box:hover{<br>
width: 250px; (hover olduğunda box etiketlinin genişliği belirtildi)<br>
height: 250px; (hover olduğunda box etiketlinin yüksekliği belirtildi)<br>
} <br><br><br>
<b><i>transition-timing-function: ease;</i></b> Geçiş efekti başlangıçta ve sonda yavaş ortada ise hızlı olur(varsayılandır).
<ul>
<li> <b><i> linear; </i></b> Geçiş efekti hep aynı hızda devam eder.</li>
<li> <b><i> ease-in; </i></b> Geçiş efekti başlangıçta yavaş sonra hızlanır.</li>
<li> <b><i> ease-out; </i></b> Geçiş efekti başlangıçta hızlı sonra yavaşlar.</li>
</ul><br><h3>Çalışmanın Görüntüsü</h3><br>

![transition](https://user-images.githubusercontent.com/48285856/147561419-896127bd-b019-4cff-9905-35f884826a41.png)

<br><br>
HTML ve CSS codlarını derlemek için <a href="https://codepen.io/pen/">HTML-CSS</a> tıklayınız..



