# 3TIE-2022-2023
HTML - HyperText Markup Language - <br>
Hipertekst - 
Markup - TAG - 
Domena - 
Hosting -
Link - 
HTML 4 vs XHTML vs HTML 5
deprecated
javaScript
CSS - Cascading Style Sheets
<br><br>
<h1>Znaczniki</h1>
<code>< br ></code> -znacznik nowej linii, przestarzałe < br /> <br>
<code>< html > i < /html > </code> - początek i koniec dokumentu html <br>
<code>< head > i < /head > </code> - początek i koniec nagłówka html <br>
<code>< body > i < /body > </code> - początek i koniec ciała(zawartości) dokumentu html <br>
<code>&lt;p&gt; i &lt;/p&gt; </code> - paragraf <br>
<code>&lt;html lang="pl"&gt;</code><br>
  <code>&lt;meta charset="UTF-8"&gt;</code> polskie znaki na stronie kodowanie UTF-8 lub iso-8859-2<br>
<code>&lt;b&gt; i &lt;/b&gt;</code><b>pogrubienie</b><br>
<code>&lt;i&gt; i &lt;/i&gt; </code><i>pochylenie</i><br>
<code>&lt;i title="opis tekstu"&gt; i &lt;/i&gt; </code><i title="opis tekstu">pochylenie tekstu razem z opisem podczas najechania myszką</i><br>
pozycjonowanie stron - <br>
<code>&lt;span title="opis tekstu"&gt; i &lt;/span&gt; </code><p> To jest paragraf.<span title="opis tekstu"> tekst razem z opisem podczas najechania myszką</span>. Koniec paragrafu</p><br>
<h1><code>&lt;h1&gt; i &lt;/h1&gt; </code>nagłówek 1 stopnia</h1><br>
 <h2> <code>&lt;h2&gt; i &lt;/h2&gt; </code>nagłówek 2 stopnia</h2><br>
 <h3> <code>&lt;h3&gt; i &lt;/h3&gt; </code>nagłówek 3 stopnia</h3><br>
 <h4> <code>&lt;h4&gt; i &lt;/h4&gt; </code>nagłówek 4 stopnia</h4><br>
 <h5> <code>&lt;h5&gt; i &lt;/h5&gt; </code>nagłówek 5 stopnia</h5><br>
  <h6><code>&lt;h6&gt; i &lt;/h6&gt; </code>nagłówek 6 stopnia</h6><br>
  <code>&lt;body bgcolor="red"&gt;  </code><body bgcolor="red">kolor tła strony - w HTML5 nie używać</body><br>
<code>& nbsp;</code> więcej niż jedna   &nbsp;&nbsp;&nbsp;&nbsp;     spacja<br>
<code>&lt;hr&gt;  </code> linia horyzontalna<br><hr><br>
  <code>&lt;strong&gt; i &lt;/strong&gt;  </code> <strong>pogrubiony tekst</strong> wygląda tak samo jak znacznik &lt;b&gt; ale nadaje wieksze znaczenie dla tekstu - ważne w przypadku pozycjonowania<br>  
  <code>&lt;em&gt; i &lt;/em&gt;  </code> <em>pochylony tekst</em> wygląda tak samo jak znacznik &lt;i&gt; ale nadaje wieksze znaczenie dla tekstu - ważne w przypadku pozycjonowania  (ang. emphasize – podkreślenie, uwypuklenie)<br>   
  <code>&lt;small&gt; i &lt;/small&gt;  </code> Zmniejszenie tekstu <small> mniejszy tekst <small> jeszcze mniejszy tekst</small></small><br>
  <code>&lt;mark&gt; i &lt;/mark&gt;  </code> wyróżnienie tekstu, tak jak <mark>zakreślaczem</mark><br>
  <code>&lt;sup&gt; i &lt;/sup&gt;  </code> indeks górny 10<sup>23</sup><br>
    <code>&lt;sub&gt; i &lt;/sub&gt;  </code> indeks dolny H<sub>2</sub>O<br>
    <code>&lt;s&gt; i &lt;/s&gt;  </code> przekreślenie tekstu <s>2000</s>ZOO<br>
  <code>&lt;del&gt; i &lt;/del&gt;  </code> przekreślenie tekstu - zaznaczenie, że coś zostąlo usuniete ze strony <del>2000</del>ZOO<br>
  <code>&lt;ins&gt; i &lt;/ins&gt;  </code> fragment został dodany do poprzedniego tekstu<ins>2000</nss>ZOO<br>
<hr>
<h3>Listy</h3>
<code>&lt;ol&gt; i &lt;/ol&gt;  </code> początek i koniec listy uporządkowanej<br>
<code>&lt;ul&gt; i &lt;/ul&gt;  </code> początek i koniec listy nieuporządkowanej<br>
<code>&lt;li&gt; i &lt;/li&gt;  </code> element listy<br>
<h4>Przykłady</h4>
<ol>
  <li>Danila</li>
  <li>Łukasz</li>
  <li>Paweł</li>
</ol>

<ul>
  <li>Danila</li>
  <li>Łukasz</li>
  <li>Paweł</li>
</ul>
  <h3> lista definicji</h3>
<code>&lt;dl&gt; i &lt;/dl&gt;  </code> początek i koniec listy deficji<br>
<code>&lt;dt&gt; i &lt;/dt&gt;  </code>definition term -  definicja<br> 
<code>&lt;dd&gt; i &lt;/dd&gt;  </code>definition descryption -  opis pojęcia<br> 
  <h4>Przykłady</h4>
 <dl>
   <dt>HTML</dl>
   <dd>Język hipertekstowy opisu stron internetowych</dd>
 </dl>
<hr>
<h3>Linki HTML</h3>
<code>&lt;a&gt; i &lt;/a&gt;  </code> początek i koniec linka np. <a>LINK</a><br>
<code>&lt;a href=""&gt; i &lt;/a&gt;  </code> początek i koniec linka z przekierowaniem do innej lokalizacji np. <a href="https://onet.pl">LINK</a><br>
<code>&lt;a target=""&gt; i &lt;/a&gt;  </code> początek i koniec linka z określeniem w jakim miejscu ma zostać otwarty link np. <a href="https://onet.pl" target="_blank">LINK</a><br>
<hr>
<h3>Grafika na stronie<h3>
<code>&lt;img src=""&gt;  </code>  - wyświetlanie obrazu(grafiki) na stronie <img src="https://waskiel.pl/wp-content/uploads/2017/09/jak-zrobic-dobre-zdjecie-z-wykorzystaniem-warunkow-atmosferycznych-1024x683.jpg"> <br>
<code>&lt;img src="" width="" height=""&gt;  </code>  - wyświetlanie obrazu(grafiki) na stronie wraz z podaniem wymiarów grafiki - grafika zostanie zeskalowana, nie zostanie oryginał zmniejszony<br> <img src="https://waskiel.pl/wp-content/uploads/2017/09/jak-zrobic-dobre-zdjecie-z-wykorzystaniem-warunkow-atmosferycznych-1024x683.jpg"   width="100" height="100"> <br>
  <code>&lt;img src="" alt=""&gt;  </code>  - wyświetlanie obrazu(grafiki) na stronie wraz z tekstem alternatywnym - wyświetli się kiedy nie będzie dostępny obraz <br><img src="https://waskiel.pl/wp-content/uploads/2017/09/jak-zrobic-dobre-zdjecie-z-wykorzystaniem-warunkow-atmosferycznych-10283.jpg"  alt="obraz sie nie załadował"> <br>
 <code>&lt;img src="" title=""&gt;  </code>  - wyświetlanie obrazu(grafiki) na stronie wraz z tekstem, który pojawia się po najechaniu kursorem <br><img src="https://waskiel.pl/wp-content/uploads/2017/09/jak-zrobic-dobre-zdjecie-z-wykorzystaniem-warunkow-atmosferycznych-1024x683.jpg"  title="tekst wyswietlajacy sie po najechaniu kursorem"> <br>
   <code><pre>&lt;figure&gt;<br>
 &lt;img src=""&gt;
 &lt;figcaption&gt; Podpis obrazu&lt;/figcaption&gt;
&lt;/figure&gt;</pre></code>  - wyświetlanie podpisu pod obrazem <br>
  <figure>
    <img src="https://waskiel.pl/wp-content/uploads/2017/09/jak-zrobic-dobre-zdjecie-z-wykorzystaniem-warunkow-atmosferycznych-1024x683.jpg"  title="tekst wyswietlajacy sie po najechaniu kursorem">
    <figcaption>Podpis obrazu</figcaption>
    </figure>
  
  <p>Co to jest JPG i jakie ma cechy - zadanie domowe</p>

<code>&lt;table&gt; i &lt;/table&gt;  </code> początek i koniec tabeli<br>
<code>&lt;tr&gt; i &lt;/tr&gt;  </code> początek i koniec wiersza tabeli<br>
<code>&lt;td&gt; i &lt;/td&gt;  </code> początek i koniec komórki tabeli<br>
  <table>
    <tr>
      <td>komórka</td>
      <td>komórka 2</td>
    </tr>
    <tr>
      <td>komórka3</td>
      <td>komórka 4</td>
    </tr>
  </table>
  <br>
  <code>&lt;th&gt; i &lt;/th&gt;  </code> początek i koniec nagłówka wiersza/kolumny tabeli. Można dodać atrybut "scope" informujący czy nagłówek dotyczyny wiersza (row) czy też kolumny (col) <br>
  <table>
    <tr>
      <th scope="col">Nagłówek</th>
      <th scope="col">Nagłówek 2</th>
    </tr>
    <tr>
      <th scope="row">Nagłówek</th>
      <td>Tekst</td>
    </tr>
    <tr>      
      <th scope="row">Nagłówek</th>
      <td>komórka 4</td>
    </tr>
  </table>
  <br>
  <code>&lt;td colspan=""&gt; i &lt;/td&gt;  </code> początek i koniec komórki tabeli, która jest połączona według kolumny<br>
  <table>
    <tr>
      <td colspan="2"> połączone dwie komórki</td>
    </tr>
    <tr>
      <td>komórka3</td>
      <td>komórka 4</td>
    </tr>
  </table>
  <br>
<code>&lt;td rowspan=""&gt; i &lt;/td&gt;  </code> początek i koniec komórki tabeli, która jest połączona po wierszach<br>
  <table>
    <tr>
      <td>komórka</td>
      <td rowspan="3">komórka 2</td>
    </tr>
    <tr>
      <td>komórka3</td>
    </tr>
    <tr>
      <td>komórka 4</td>
    </tr>
  </table>
  <br>
  <code>&lt;thead&gt; i &lt;/thead&gt;  </code> początek i koniec sekcji nagłówka tabeli<br>
  <code>&lt;tbody&gt; i &lt;/tbody&gt;  </code> początek i koniec sekcji głównej tabeli<br>
  <code>&lt;tfoot&gt; i &lt;/tfoot&gt;  </code> początek i koniec sekcji stopki tabeli<br>
  
  <h2>Elemeny blokowe i liniowe</h2>
![obraz](https://user-images.githubusercontent.com/85030649/201650854-f000c16b-8f89-4eac-a01a-39a83cc729f1.png)
