Analys - laddningstid
=========

Codeschool
--------------
####Resultat från Pagespeed och devtools
Det var främst bilder som inte var komprimerade. Det skulle kunna minska laddtiden ytterligare.

Värt att kommentera är också det usla betyget på Pagespeed för sidan 'courses'. Kommentarerna från Pagespeed var främst:

* Optimera bilder
* Aktivera komprimering
* Ta bort JavaScript- och CSS-kod som blockerar renderingen från innehåll ovanför mitten

<div class="tablediv">
    <table class="table3 striped">
        <thead>
            <tr>
                <th></th>
                <th style="text-align: center;" colspan="2">PAGESPEED</th>
                <th colspan="3"></th>
            </tr>
            <tr>
                <th>SIDA</th>
                <th align="center">MOBILE</th>
                <th align="center">DESKTOP</th>
                <th align="center">LADDTID</th>
                <th align="center">ANTAL RESURSER</th>
                <th align="center">STORLEK</th>
            </tr>
        </thead>
        <tr>
            <td class="side-name"><a href="https://www.codeschool.com/">codeschool.com</a></td>
            <td align="center">56</td>
            <td align="center">71</td>
            <td align="center">6,60 s</td>
            <td align="center">108</td>
            <td align="center">2412,80 kB</td>
        </tr>
        <tr>
            <td class="side-name"><a href="https://www.codeschool.com/pricing">codeschool.com/pricing</a></td>
            <td align="center">58</td>
            <td align="center">71</td>
            <td align="center">8,93 s</td>
            <td align="center">94</td>
            <td align="center">2214,18 kB</td>
        </tr>
        <tr>
            <td class="side-name"><a href="https://www.codeschool.com/courses">codeschool.com/courses</a></td>
            <td align="center">47</td>
            <td align="center">0</td>
            <td align="center">7,03 s</td>
            <td align="center">148</td>
            <td align="center">11630,73 kB</td>
        </tr>
    </table>    
</div>
<br>
<hr>

Eveonline
------------
####Resultat från Pagespeed och devtools
Framför allt vissa stora bilder skulle minska laddtiden ytterligare. Det var dessutom inte alla js-filer som var minifierade.

<div class="tablediv">
    <table class="table3 striped">
        <thead>
            <tr>
                <th></th>
                <th style="text-align: center;" colspan="2">PAGESPEED</th>
                <th colspan="3"></th>
            </tr>
            <tr>
                <th>SIDA</th>
                <th align="center">MOBILE</th>
                <th align="center">DESKTOP</th>
                <th align="center">LADDTID</th>
                <th align="center">ANTAL RESURSER</th>
                <th align="center">STORLEK</th>
            </tr>
        </thead>
        <tr>
            <td class="side-name"><a href="https://www.eveonline.com/">eveonline.com</a></td>
            <td align="center">49</td>
            <td align="center">67</td>
            <td align="center">3,48 s</td>
            <td align="center">87</td>
            <td align="center">7916,79 kB</td>
        </tr>
        <tr>
            <td class="side-name"><a href="https://secure.eveonline.com/buy/">eveonline.com/buy/</a></td>
            <td align="center">51</td>
            <td align="center">72</td>
            <td align="center">2,68 s</td>
            <td align="center">59</td>
            <td align="center">2056,52 kB</td>
        </tr>
        <tr>
            <td class="side-name"><a href="https://secure.eveonline.com/PLEX/">eveonline.com/PLEX/</a></td>
            <td align="center">52</td>
            <td align="center">73</td>
            <td align="center">1,65 s</td>
            <td align="center">47</td>
            <td align="center">1890,62 kB</td>
        </tr>
    </table>    
</div>
<br>
<hr>

Skype
----------
####Resultat från Pagespeed och devtools
Skype fick bäst betyg av Pagespeed av de fyra sidor som analyserats.

Det var inte så resurskrävande sidor. Men några js-filer var inte miniferade och vissa filer som hämtades tog tid att hämta och blockerade, vilket utökade laddtiden.

<div class="tablediv">
    <table class="table3 striped">
        <thead>
            <tr>
                <th></th>
                <th style="text-align: center;" colspan="2">PAGESPEED</th>
                <th colspan="3"></th>
            </tr>
            <tr>
                <th>SIDA</th>
                <th align="center">MOBILE</th>
                <th align="center">DESKTOP</th>
                <th align="center">LADDTID</th>
                <th align="center">ANTAL RESURSER</th>
                <th align="center">STORLEK</th>
            </tr>
        </thead>
        <tr>
            <td class="side-name"><a href="https://www.skype.com/en/">skype.com/en/</a></td>
            <td align="center">69</td>
            <td align="center">87</td>
            <td align="center">1,21 s</td>
            <td align="center">40</td>
            <td align="center">2168,28 kB</td>
        </tr>
        <tr>
            <td class="side-name"><a href="https://www.skype.com/en/download-skype/skype-for-computer/">skype.com/en/download-skype/skype-for-computer/</a></td>
            <td align="center">67</td>
            <td align="center">88</td>
            <td align="center">0,91 s</td>
            <td align="center">25</td>
            <td align="center">1169,08 kB</td>
        </tr>
        <tr>
            <td class="side-name"><a href="https://support.skype.com/en/skype/windows-desktop/">support.skype.com/en/skype/windows-desktop/</a></td>
            <td align="center">57</td>
            <td align="center">74</td>
            <td align="center">0,83 s</td>
            <td align="center">23</td>
            <td align="center">1384,99 kB</td>
        </tr>
    </table>    
</div>
<br>
<hr>

Adobe
----------
####Resultat från Pagespeed och devtools
Några av bilderna tog lång tid och var inte komprimerade. En av bilderna fick även statuskod 204 och bromsade upp laddningen. På en av sidorna kom sista delarna först efter 10 sekunder, som om att det fanns en 'plugg' som satt ivägen för delar av resurserna.

<div class="tablediv">
    <table class="table3 striped">
        <thead>
            <tr>
                <th></th>
                <th style="text-align: center;" colspan="2">PAGESPEED</th>
                <th colspan="3"></th>
            </tr>
            <tr>
                <th>SIDA</th>
                <th align="center">MOBILE</th>
                <th align="center">DESKTOP</th>
                <th align="center">LADDTID</th>
                <th align="center">ANTAL RESURSER</th>
                <th align="center">STORLEK</th>
            </tr>
        </thead>
        <tr>
            <td class="side-name"><a href="http://www.adobe.com/se/#">adobe.com/se/#</a></td>
            <td align="center">50</td>
            <td align="center">71</td>
            <td align="center">3,83 s</td>
            <td align="center">36</td>
            <td align="center">2062,85 kB</td>
        </tr>
        <tr>
            <td class="side-name"><a href="http://www.adobe.com/se/creativecloud.html?promoid=GR3XYB9G&mv=other">adobe.com/se/<br>-för enskilda användare</a></td>
            <td align="center">48</td>
            <td align="center">16</td>
            <td align="center">14,69 s</td>
            <td align="center">103</td>
            <td align="center">8750,70 kB</td>
        </tr>
        <tr>
            <td class="side-name"><a href="http://www.adobe.com/se/products/catalog/software._sl_id-contentfilter_sl_catalog_sl_software_sl_mostpopular_se.html?promoid=KLXMI">adobe.com/se/<br>-produkter</a></td>
            <td align="center">41</td>
            <td align="center">59</td>
            <td align="center">11,73 s</td>
            <td align="center">109</td>
            <td align="center">4026,88 kB</td>
        </tr>
    </table>    
</div>

<br>

<hr>

Sammanfattning
---------------
Det som var vanligaste åtgärden för ovanstående sidor var okomprimerade bilder och js-filer som inte var minifierade. Dessutom kunde laddningstiden förlängas rejält om statuskoden var annan än 200 och resursen 'fastnade' och blockerade annat som skulle laddas ner.

Känslan för laddtiden beror på vad som tar lång tid. Även om sidan såg ut att vara färdigladdad, i vissa fall, så fortsatte script och annat laddas ner i bakgrunden. Själva laddtiden var lång men det var inget som användaren märkte av om man inte satt med devtools uppe.

En sida som märkbart tar 5 sekunder eller mer känns långsam och sekunder eller under skulle jag säga är snabbt. Men detta beror som sagt på vilka resurser som dröjer.

####Gruppen
Gruppen består av mig, Magnus Andersson (maaa16).
