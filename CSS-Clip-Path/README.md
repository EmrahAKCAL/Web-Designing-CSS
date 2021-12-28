   height: 70vh; /*Tarayıcının 70% lik kısmını kaplar*/
    background-image: 
    linear-gradient(rgba(153, 255, 204, 0.4),rgba(0, 204, 102, 0.4)), /*Resmin üzrine linear renk verildi*/
     url(images/sultan-sazligi.jpg) ; 
    background-size: cover; /*Resmi sayfaya olduğu gibi sığması için kırpar.*/
    clip-path: polygon(0 0, 100% 0, 100% 70%, 0 70%); /*Resmi x-y eksenlerinde kesme işlemidir. (sol üst köşe, sağ üst köşe, sağ alt köşe, sol alt köşe)*/