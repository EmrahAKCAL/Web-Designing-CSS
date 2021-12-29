<h1>Responsive Nedir?</h1>
Responsive; Bir html sayfasının tarayıcının genişliğine göre ölçeklendirme işlemidir. Html sayfalarının mobil veya tablet gibi farklı tarayıcılarda daha güzel gözükmesi için bu işlem mutlaka yapılmalıdır. <br>
Bu ölçeklendirme işlemlerini <b><i>@media screen and (min-width: tarayıcıgenişliği){ gerçekleşecek olaylar } </i></b> CSS kodunu kullanılarak yapılır. <br>
Örneğin:<br> <br><b><i>
p{<br>
font-size: 1.5rem; <br>
}</i></b><br>
başlangıçtaki yazı boyutu 15px(<b><i>1.5rem</i></b>) olan p etiketi tarayıcının minimum genişliği 700px olduğunda p etiketindeki yazı boyutu 15px(1.5rem) olması için aşağıdaki CSS kodu yazmamız gerekir.<br><br> <br>
<b><i>@media screen and (min-width: 700px){ <br>
    p{<br>
        font-size: 1.5rem;<br>
    }<br>
    }</i></b><br>
  
HTML ve CSS codlarını derlemek için <a href="https://codepen.io/pen/">HTML-CSS</a> tıklayınız..
