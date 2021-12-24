<h1 id="etiket1" class="etiket2" style="color: blue; background-color:green;">CSS Önceliği Nasıldır?</h1>
    <p>CSS'de kullanılan etiketlerin önceliği vardır. Örneğin bir etikete özellik vermek için <b>id</b>, <b>class</b> veya <b>selector</b> şeklinde konumlandırdığımızda bunlardan hangisi daha baskın olduğunu bilmemiz gerekir. Bu öncelikler aşağıdaki tablo gibidir.</p>
    <table border="1">
        <tbody>
            <tr>
                <td>Inline Selector</td>
                <td>< h1 style= "color: red"></td>
            </tr>
            <tr>
                <td>Id Selector</td>
                <td>#etiket{ CSS }</td>
            </tr>
            <tr>
                <td>Class Selector</td>
                <td>.etiket{ CSS }</td>
            </tr>
           <tr>
               <td>Tag Selector</td>
               <td>h1 { CSS }</td>
            </tr>
            <tr>
                <td>Browser Default</td>
                <td></td>
            </tr>
        </tbody>
    </table>