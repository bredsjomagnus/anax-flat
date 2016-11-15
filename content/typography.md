Typography (h1)
============

What is Typography according to Wikipedia (h2)
------------------------------------------
[Wikipedia](https://en.wikipedia.org/wiki/Typography)

Typography is the art and technique of arranging type to make written language legible, readable, and appealing when displayed. The arrangement of type involves selecting typefaces, point sizes, line lengths, line-spacing (leading), and letter-spacing (tracking), and adjusting the space between pairs of letters (kerning[1]). The term typography is also applied to the style, arrangement, and appearance of the letters, numbers, and symbols created by the process. Type design is a closely related craft, sometimes considered part of typography; most typographers do not design typefaces, and some type designers do not consider themselves typographers. Typography also may be used as a decorative device, unrelated to communication of information.

Typography is the work of typesetters (also known as compositors), typographers, graphic designers, art directors, manga artists, comic book artists, graffiti artists, and, now, anyone who arranges words, letters, numbers, and symbols for publication, display, or distribution, from clerical workers and newsletter writers to anyone self-publishing materials. Until the Digital Age, typography was a specialized occupation. Digitization opened up typography to new generations of previously unrelated designers and lay users, and David Jury, head of graphic design at Colchester Institute in England, states that "typography is now something everybody does."[4] As the capability to create typography has become ubiquitous, the application of principles and best practices developed over generations of skilled workers and professionals has diminished. So at a time when scientific techniques can support the proven traditions (e.g. greater legibility with the use of serifs, upper and lower case, contrast, etc.) through understanding the limitations of human vision, typography as often encountered may fail to achieve its principal objective: effective communication.

###Kod (h3)

Man kan skriva `kod på en rad`. Eller skriva kod i ett block.

    @egrep "^# target:" Makefile | sed 's/# target: / /g'

Eller i ett block med flera rader.

    .wrap-all {
        background-color: @wrapAllColor;
        -webkit-box-shadow: 0 0 63px -7px rgba(0,0,0,0.75);
        -moz-box-shadow: 0 0 63px -7px rgba(0,0,0,0.75);
        box-shadow: 0 0 63px -7px rgba(0,0,0,0.75);
    }

Därefter följer vanlig text som följer det "magiska talet".

###Tabeller (h3)

Tabell utan `class`

| Head1         | Head2         | head3 |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Tabell med `class="table2"`

<table class="table2">
    <thead>
    <tr>
        <th>Head1</th>
        <th>Head2</th>
        <th>Head3</th>
        </tr>
    </thead>
    <tr>
        <td>col 1 row 1</td>
        <td>col 2 row 1</td>
        <td>col 3 row 1</td>
    </tr>
    <tr>
    <td>col 1 row 2</td>
    <td>col 2 row 2</td>
    <td>col 3 row 2</td>
    </tr>
    <tr>
    <td>col 1 row 3</td>
    <td>col 2 row 3</td>
    <td>col 3 row 3</td>
    </tr>
</table>

Tabell med `class="table2 striped"`

<table class="table2 striped">
    <thead>
    <tr>
        <th>Head1</th>
        <th>Head2</th>
        <th>Head3</th>
        </tr>
    </thead>
    <tr>
        <td>col 1 row 1</td>
        <td>col 2 row 1</td>
        <td>col 3 row 1</td>
    </tr>
    <tr>
    <td>col 1 row 2</td>
    <td>col 2 row 2</td>
    <td>col 3 row 2</td>
    </tr>
    <tr>
    <td>col 1 row 3</td>
    <td>col 2 row 3</td>
    <td>col 3 row 3</td>
    </tr>
</table>

Har man ett klämmigt citat kan man lägga in det i ett Blockquote
> Cigarren sysselsätter både händer och mun. Därigenom har jag många gånger undgått frestelsen att antingen strypa eller bita folk som har irriterat mig. - *Winston Churchill*
