<style>
@font-face {
    font-family: Daedric;
    src: url('./assets/fonts/ttf/HayghinDaedric.ttf') format('truetype');
    font-weight: medium;
    font-style: normal;
}
</style>
<style>
@font-face {
    font-family: DaedricDozenal;
    src: url('./assets/fonts/ttf/HayghinDaedric-Dozenal.ttf') format('truetype');
    font-weight: medium;
    font-style: normal;
}
</style>

# The Hayghin Daedric Script

This is a simple Daedric character font based upon [Ayembedt](https://github.com/georgd/OpenMW-Fonts) for the letter glyphs, the number system documented by [Llevndryn Sershilavu](https://arador-dayn.fr/viewtopic.php?f=16&t=482) (a.k.a. *Naka*), and some additional punctuation marks from [Source Han Serif](https://github.com/adobe-fonts/source-han-serif) to produce a font that is somewhat comfortable to read and write with.

The word *hayghin* comes from [Casual Dumneris](https://casualscrolls.fandom.com/wiki/Dunmeri_language) and means *simple*, to denote the sparse features of this font. I have admittedly only added glyphs that suit my needs in Markdown.

| The quick brown fox jumps over the lazy dog. |
|:--------------------------------------------:|
| <span style="font-family:Daedric">The quick brown fox jumps over the lazy dog.</span> |

---

## Table of Glyphs

Traditionally, the script is [unicase](https://en.wikipedia.org/wiki/Unicase).

| Ayem | Bedt | Cess | Doht | Ekem | Hefed | Geth | Hekem | Iya | Jeb | Koht | Lyr | Meht |
|:----:|:----:|:----:|:----:|:----:|:-----:|:----:|:-----:|:---:|:---:|:----:|:---:|:----:|
|   A  |   B  |   C  |   D  |   E  |   F   |   G  |   H   |  I  |  J  |   K  |  L  |   M  |
| <span style="font-family:Daedric">A</span> | <span style="font-family:Daedric">B</span> | <span style="font-family:Daedric">C</span> | <span style="font-family:Daedric">D</span> | <span style="font-family:Daedric">E</span> | <span style="font-family:Daedric">F</span> | <span style="font-family:Daedric">G</span> | <span style="font-family:Daedric">H</span> | <span style="font-family:Daedric">I</span> | <span style="font-family:Daedric">J</span> | <span style="font-family:Daedric">K</span> | <span style="font-family:Daedric">L</span> | <span style="font-family:Daedric">M</span> |

| Neht | Oht | Payem | Quam | Roht | Seht | Tayem | Yoodt | Vehk | Web | Xayah | Yahkem | Zyr |
|:----:|:---:|:-----:|:----:|:----:|:----:|:-----:|:-----:|:----:|:---:|:-----:|:------:|:---:|
|   N  |  O  |   P   |   Q  |   R  |   S  |   T   |   U   |   V  |  W  |   X   |    Y   |  Z  |
| <span style="font-family:Daedric">N</span> | <span style="font-family:Daedric">O</span> | <span style="font-family:Daedric">P</span> | <span style="font-family:Daedric">Q</span> | <span style="font-family:Daedric">R</span> | <span style="font-family:Daedric">S</span> | <span style="font-family:Daedric">T</span> | <span style="font-family:Daedric">U</span> | <span style="font-family:Daedric">V</span> | <span style="font-family:Daedric">W</span> | <span style="font-family:Daedric">X</span> | <span style="font-family:Daedric">Y</span> | <span style="font-family:Daedric">Z</span> |

---

## Font Punctuation

The font implements the Japanese [single quotation marks](https://en.wikipedia.org/wiki/Japanese_punctuation#Single_quotation_marks) and [full stop](https://en.wikipedia.org/wiki/Japanese_punctuation#Full_stop). The left and right quote marks are respectively mapped to the square braket keys, `[` and `]`. (Regular quotation marks are not visible with this font.)

Instead, the single-quote key serves as the critical apostrophe mark.

| Apostrophe | Period | Comma | Left Quote | Right Quote |
|:----------:|:------:|:-----:|:----------:|:-----------:|
|      '     |    .   |   ,   |    \[      |      \]     |
| <span style="font-family:Daedric">'</span> | <span style="font-family:Daedric">.</span> | <span style="font-family:Daedric">,</span> | <span style="font-family:Daedric">[</span> | <span style="font-family:Daedric">]</span> |

There are further english marks that have been adapted to fit the font, and to aid with writing expression.

| Question | Exclamation | Colon | Semicolon | Septims |
|:--------:|:-----------:|:-----:|:---------:|:-------:|
|     ?    |      !      |   :   |     ;     |    $    |
| <span style="font-family:Daedric">?</span> | <span style="font-family:Daedric">!</span> | <span style="font-family:Daedric">:</span> | <span style="font-family:Daedric">;</span> | <span style="font-family:Daedric">$</span> |

---

## Numbers

The dozenal system has been employed for this version of Daedric, but a more common decimal version is available as well.

### Dozenal

A system of counting that groups numbers in sets of *twelve*.

| Zero | One | Two | Three | Four | Five | Six | Seven | Eight | Nine | Dek | El | Ten |
|---|---|---|---|---|---|---|---|---|---|----------|----------|----|
| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | &#x218a; | &#x218b; | 10 |
| <span style="font-family:DaedricDozenal">0</span> | <span style="font-family:DaedricDozenal">1</span> | <span style="font-family:DaedricDozenal">2</span> | <span style="font-family:DaedricDozenal">3</span> | <span style="font-family:DaedricDozenal">4</span> | <span style="font-family:DaedricDozenal">5</span> | <span style="font-family:DaedricDozenal">6</span> | <span style="font-family:DaedricDozenal">7</span> | <span style="font-family:DaedricDozenal">8</span> | <span style="font-family:DaedricDozenal">9</span> | <span style="font-family:DaedricDozenal">&#x218a;</span> | <span style="font-family:DaedricDozenal">&#x218b;</span> | <span style="font-family:DaedricDozenal">1'0</span> |

To attach another digit, use an apostrophe (<span style="font-family:Daedric">'</span>).

| 10 | 11 | 12 | 25 | 50 | 192 | 1024 | 12345 | 144000 | 1000000 |
|----|----|----|----|----|-----|------|-------|--------|---------|
| <span style="font-family:DaedricDozenal">1'0</span> | <span style="font-family:DaedricDozenal">1'1</span> | <span style="font-family:DaedricDozenal">1'2</span> | <span style="font-family:DaedricDozenal">2'5</span> | <span style="font-family:DaedricDozenal">5'0</span> | <span style="font-family:DaedricDozenal">1'9'2</span> | <span style="font-family:DaedricDozenal">1'0'2'4</span> | <span style="font-family:DaedricDozenal">1'2'3'4'5</span> | <span style="font-family:DaedricDozenal">1'4'4'0'0'0</span> | <span style="font-family:DaedricDozenal">1'0'0'0'0'0'0</span> |

### Decimal

Original source for number glyphs is [*L'alphabet Daedrique en Dunmeris*](https://arador-dayn.fr/viewtopic.php?f=16&t=482) by [*Naka*](https://www.deviantart.com/naka117).

| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
|---|---|---|---|---|---|---|---|---|---|
| <span style="font-family:Daedric">0</span> | <span style="font-family:Daedric">1</span> | <span style="font-family:Daedric">2</span> | <span style="font-family:Daedric">3</span> | <span style="font-family:Daedric">4</span> | <span style="font-family:Daedric">5</span> | <span style="font-family:Daedric">6</span> | <span style="font-family:Daedric">7</span> | <span style="font-family:Daedric">8</span> | <span style="font-family:Daedric">9</span> |

To attach another digit, use an apostrophe (<span style="font-family:Daedric">'</span>).

| 10 | 11 | 12 | 25 | 50 | 192 | 1024 | 12345 | 144000 | 1000000 |
|----|----|----|----|----|-----|------|-------|--------|---------|
| <span style="font-family:Daedric">1'0</span> | <span style="font-family:Daedric">1'1</span> | <span style="font-family:Daedric">1'2</span> | <span style="font-family:Daedric">2'5</span> | <span style="font-family:Daedric">5'0</span> | <span style="font-family:Daedric">1'9'2</span> | <span style="font-family:Daedric">1'0'2'4</span> | <span style="font-family:Daedric">1'2'3'4'5</span> | <span style="font-family:Daedric">1'4'4'0'0'0</span> | <span style="font-family:Daedric">1'0'0'0'0'0'0</span> |

---

## Other Daedric Fonts


- [Daedric Runes](https://www.ffonts.net/Daedric-Runes.font) by Erwin Denissen (*High-Logic*)
- [Oblivion](http://download.fliggerty.com/download-128-515) by Steve Deffeyes (*dongle*)
- [Daedric Runes](https://morroblivion.com/forums/skyrim-general-chat/allis-daedric-runes-opentype-font-kit) by *Alli*
- [Daedra](http://www.pixelsagas.com/?download=daedra) by Neale Davidson (*Pixel Sagas*)
- [Ayembedt](https://github.com/georgd/OpenMW-Fonts) by Georg Duffner
- [Daedric Font Resources](https://www.nexusmods.com/morrowind/mods/45458/) by *Yar-Yulme*
- [Better Daedric Font](https://www.nexusmods.com/morrowind/mods/44540) by *hardek*
- [Daedric Letters Gold](https://www.deviantart.com/yagellonica/art/Daedric-Letters-GOLD-741405288) by *Yagellonica*
- [Shebbz Daedric](https://twitter.com/t00thpasteface/status/1291107593432293376) by *Shebbz*

---

| In the darkest days Azura sent her great champion to reform the Broken Promise Blessing. Moon-and-Star, to sing peace, the unbreakable soul of the lost Chimer, would silence devils mad first. So the Hortator challenged Dagoth Ur's army as no god could. The Five Great Houses and Ashland tribes heard the battlecall. Joined as one voice, the Dunmer screamed an end for the blasphemous undead. All come and see in Resdayn old, a newborn dawn. We prayed for your triumphant soul's return, Nerevar. |
|---|
| Gher iam gah'dun siin Azura nesi'ag eal gah'amer Biridad as reymo winol shoksuna. Luhn'silvar, belid flur, as kogo sul en am as errat Chimer, almardar as sharmaat malshok alna. Et as Hortator sorilke'ag Dagoth Ur'm shaldmas, lakor bahr panthi mugakar. As arc gah'thiil en arador meriaal leyshe'ag as cornayn. Humore'ag lakor aln yivohn as Dunmer gire'ag ot dimi sut as demigi bahrdrar. Hadik yagla en talje gher Resdaynia ald, ot muhrhag dayn. Osuhn almese'ag abahr sut ohm yalif sul'm devahr, Nerevar. |
| <span style="font-family:Daedric">Gher iam gah'dun siin Azura nesi'ag eal gah'amer Biridad as reymo winol shoksuna. Luhn'silvar, belid flur, as kogo sul en am as errat Chimer, almardar as sharmaat malshok alna. Et as Hortator sorilke'ag Dagoth Ur'm shaldmas, lakor bahr panthi mugakar. As arc gah'thiil en arador meriaal leyshe'ag as cornayn. Humore'ag lakor aln yivohn as Dunmer gire'ag ot dimi sut as demigi bahrdrar. Hadik yagla en talje gher Resdaynia ald, ot muhrhag dayn. Osuhn almese'ag abahr sut ohm yalif sul'm devahr, Nerevar.</span> |

#### Credits:
Wiki for [Casual Dunmeris](https://casualscrolls.fandom.com/wiki/Dunmeri_language)\
Lyrics by Luther Weiser\
Translation by [Will Jordan](https://soundcloud.com/smitehammer)\
Soundcloud of [Liz Katrin \(Katarzyna Bonikowska\)](https://soundcloud.com/liz-katrin/hortator-skywind)\
Skywind Soundtrack by [Fredrik Jonasson](https://jonassonfredrik.bandcamp.com)

---

