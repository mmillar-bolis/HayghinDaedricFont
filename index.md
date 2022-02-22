<style>
@font-face {
    font-family: HayghinDaedric;
    src: url('./assets/fonts/ttf/HayghinDaedric.ttf') format('truetype');
    font-weight: medium;
    font-style: normal;
}
</style>
<style>
@font-face {
    font-family: HayghinDaedric-Dozenal;
    src: url('./assets/fonts/ttf/HayghinDaedric-Dozenal.ttf') format('truetype');
    font-weight: medium;
    font-style: normal;
}
</style>

---

<center>
<a href="https://github.com/mmillar-bolis/HayghinDaedricFont">GitHub</a>
&emsp;&nabla;&emsp;
<a href="https://github.com/mmillar-bolis/HayghinDaedricFont/releases/">Downloads</a>
&emsp;&nabla;&emsp;
<a href="#other-daedric-fonts">More Fonts</a>
</center>

---

This is a simple Daedric character font based upon [Ayembedt][1] for the letter glyphs, the number system documented by [Llevndryn Sershilavu][2] (a.k.a. *Naka*), and some additional punctuation marks from [Source Han Serif][3] to produce a font that is somewhat comfortable to read and write with.

The word *hayghin* comes from [Casual Dumneris][4] and means *simple*, to denote the sparse features of this font. I have admittedly only added glyphs that suit my needs in Markdown.

#### Download on [GitHub][5]


|                     The quick brown fox jumps over the lazy dog.                      |
|:-------------------------------------------------------------------------------------:|
| <span style="font-family:Daedric">The quick brown fox jumps over the lazy dog.</span> |

[1]: https://github.com/georgd/OpenMW-Fonts
[2]: https://arador-dayn.fr/viewtopic.php?f=16&t=482
[3]: https://github.com/adobe-fonts/source-han-serif
[4]: https://casualscrolls.fandom.com/wiki/Dunmeri_language
[5]: https://github.com/mmillar-bolis/HayghinDaedricFont/releases/

---

## Table of Glyphs

| Ayem | Bedt | Cess | Doht | Ekem | Hefed | Geth | Hekem | Iya | Jeb | Koht | Lyr | Meht |
|:----:|:----:|:----:|:----:|:----:|:-----:|:----:|:-----:|:---:|:---:|:----:|:---:|:----:|
|   A  |   B  |   C  |   D  |   E  |   F   |   G  |   H   |  I  |  J  |   K  |  L  |   M  |
| <span style="font-family:HayghinDaedric">A</span> | <span style="font-family:HayghinDaedric">B</span> | <span style="font-family:HayghinDaedric">C</span> | <span style="font-family:HayghinDaedric">D</span> | <span style="font-family:HayghinDaedric">E</span> | <span style="font-family:HayghinDaedric">F</span> | <span style="font-family:HayghinDaedric">G</span> | <span style="font-family:HayghinDaedric">H</span> | <span style="font-family:HayghinDaedric">I</span> | <span style="font-family:HayghinDaedric">J</span> | <span style="font-family:HayghinDaedric">K</span> | <span style="font-family:HayghinDaedric">L</span> | <span style="font-family:HayghinDaedric">M</span> |


| Neht | Oht | Payem | Quam | Roht | Seht | Tayem | Yoodt | Vehk | Web | Xayah | Yahkem | Zyr |
|:----:|:---:|:-----:|:----:|:----:|:----:|:-----:|:-----:|:----:|:---:|:-----:|:------:|:---:|
|   N  |  O  |   P   |   Q  |   R  |   S  |   T   |   U   |   V  |  W  |   X   |    Y   |  Z  |
| <span style="font-family:HayghinDaedric">N</span> | <span style="font-family:HayghinDaedric">O</span> | <span style="font-family:HayghinDaedric">P</span> | <span style="font-family:HayghinDaedric">Q</span> | <span style="font-family:HayghinDaedric">R</span> | <span style="font-family:HayghinDaedric">S</span> | <span style="font-family:HayghinDaedric">T</span> | <span style="font-family:HayghinDaedric">U</span> | <span style="font-family:HayghinDaedric">V</span> | <span style="font-family:HayghinDaedric">W</span> | <span style="font-family:HayghinDaedric">X</span> | <span style="font-family:HayghinDaedric">Y</span> | <span style="font-family:HayghinDaedric">Z</span> |

Traditionally, the script is [unicase][6], however this font utlizes several alternate Daedric glyphs in the lower-case range.

The alternate glyphs:

| Doht | Hekem | Jeb | Yoodt | Yahkem |
|:----:|:-----:|:---:|:-----:|:------:|
|   d  |   h   |  j  |   u   |    y   |
| <span style="font-family:HayghinDaedric">d</span> | <span style="font-family:HayghinDaedric">h</span> | <span style="font-family:HayghinDaedric">j</span> | <span style="font-family:HayghinDaedric">u</span> | <span style="font-family:HayghinDaedric">y</span> |

[6]: https://en.wikipedia.org/wiki/Unicase

---

## Font Punctuation

The font implements the Japanese [single quotation marks][7] and [full stop][8]. The left and right quote marks are respectively mapped to the square braket keys, `[` and `]`. (Regular quotation marks are not visible with this font.)

Instead, the single-quote key serves as the critical apostrophe mark.

| Apostrophe | Period | Comma | Left Quote | Right Quote |
|:----------:|:------:|:-----:|:----------:|:-----------:|
|      '     |    .   |   ,   |    \[      |      \]     |
| <span style="font-family:HayghinDaedric">'</span> | <span style="font-family:HayghinDaedric">.</span> | <span style="font-family:HayghinDaedric">,</span> | <span style="font-family:HayghinDaedric">[</span> | <span style="font-family:HayghinDaedric">]</span> |

There are further english marks that have been adapted to fit the font, and to aid with writing expression.

| Question | Exclamation | Colon | Semicolon |
|:--------:|:-----------:|:-----:|:---------:|
|     ?    |      !      |   :   |     ;     |
| <span style="font-family:HayghinDaedric">?</span> | <span style="font-family:HayghinDaedric">!</span> | <span style="font-family:HayghinDaedric">:</span> | <span style="font-family:HayghinDaedric">;</span> |

[7]: https://en.wikipedia.org/wiki/Japanese_punctuation#Single_quotation_marks
[8]: https://en.wikipedia.org/wiki/Japanese_punctuation#Full_stop

---

## Numbers

The dozenal system has been employed for this version of Daedric, but a more common decimal version is available as well.

### Decimal

The default variant of this font, simply because of number convention. However, the *dozenal* system is better for interpretation of numbers among texts related to Morrowind.

Original source for number glyphs is [*L'alphabet Daedrique en Dunmeris*][9] by [*Naka*][10].

| Zero | One | Two | Three | Four | Five | Six | Seven | Eight | Nine | Ten |
|---|---|---|---|---|---|---|---|---|---|----|
| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
| <span style="font-family:HayghinDaedric">0</span> | <span style="font-family:HayghinDaedric">1</span> | <span style="font-family:HayghinDaedric">2</span> | <span style="font-family:HayghinDaedric">3</span> | <span style="font-family:HayghinDaedric">4</span> | <span style="font-family:HayghinDaedric">5</span> | <span style="font-family:HayghinDaedric">6</span> | <span style="font-family:HayghinDaedric">7</span> | <span style="font-family:HayghinDaedric">8</span> | <span style="font-family:HayghinDaedric">9</span> | <span style="font-family:HayghinDaedric">1'0</span> |
| __Bahr__ | __Aln__ | __Asc__ | __Cahn__ | __Cin__ | __Arc__ | __Tahn__ | __Sahn__ | __Daskhor__ | __Ent__ | __Alnahn__ |

To attach another digit, use an apostrophe (<span style="font-family:Daedric">'</span>).

| 11 | 12 | 25 | 50 | 192 | 1024 | 12345 | 144000 | 1000000 |
|----|----|----|----|-----|------|-------|--------|---------|
| <span style="font-family:HayghinDaedric">1'1</span> | <span style="font-family:HayghinDaedric">1'2</span> | <span style="font-family:HayghinDaedric">2'5</span> | <span style="font-family:HayghinDaedric">5'0</span> | <span style="font-family:HayghinDaedric">1'9'2</span> | <span style="font-family:HayghinDaedric">1'0'2'4</span> | <span style="font-family:HayghinDaedric">1'2'3'4'5</span> | <span style="font-family:HayghinDaedric">1'4'4'0'0'0</span> | <span style="font-family:HayghinDaedric">1'0'0'0'0'0'0</span> |

[9]: https://arador-dayn.fr/viewtopic.php?f=16&t=482
[10]: https://www.deviantart.com/naka117

### Dozenal

A system of counting that groups numbers in sets of *twelve*.

| Zero | One | Two | Three | Four | Five | Six | Seven | Eight | Nine | Dek | El | Ten |
|---|---|---|---|---|---|---|---|---|---|----------|----------|----|
| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | &#x218a; | &#x218b; | 10 |
| <span style="font-family:HayghinDaedric-Dozenal">0</span> | <span style="font-family:HayghinDaedric-Dozenal">1</span> | <span style="font-family:HayghinDaedric-Dozenal">2</span> | <span style="font-family:HayghinDaedric-Dozenal">3</span> | <span style="font-family:HayghinDaedric-Dozenal">4</span> | <span style="font-family:HayghinDaedric-Dozenal">5</span> | <span style="font-family:HayghinDaedric-Dozenal">6</span> | <span style="font-family:HayghinDaedric-Dozenal">7</span> | <span style="font-family:HayghinDaedric-Dozenal">8</span> | <span style="font-family:HayghinDaedric-Dozenal">9</span> | <span style="font-family:HayghinDaedric-Dozenal">&#x218a;</span> | <span style="font-family:HayghinDaedric-Dozenal">&#x218b;</span> | <span style="font-family:HayghinDaedric-Dozenal">1'0</span> |
| __Bahr__ | __Aln__ | __Asc__ | __Cahn__ | __Cin__ | __Arc__ | __Tahn__ | __Sahn__ | __Daskhor__ | __Ent__ | __Xayn__ | __Lyrn__ | __Alnahn__ |

To attach another digit, use an apostrophe (<span style="font-family:Daedric">'</span>).

| 11 | 12 | 25 | 50 | 192 | 1024 | 12345 | 144000 | 1000000 |
|----|----|----|----|-----|------|-------|--------|---------|
| <span style="font-family:HayghinDaedric-Dozenal">1'1</span> | <span style="font-family:HayghinDaedric-Dozenal">1'2</span> | <span style="font-family:HayghinDaedric-Dozenal">2'5</span> | <span style="font-family:HayghinDaedric-Dozenal">5'0</span> | <span style="font-family:HayghinDaedric-Dozenal">1'9'2</span> | <span style="font-family:HayghinDaedric-Dozenal">1'0'2'4</span> | <span style="font-family:HayghinDaedric-Dozenal">1'2'3'4'5</span> | <span style="font-family:HayghinDaedric-Dozenal">1'4'4'0'0'0</span> | <span style="font-family:HayghinDaedric-Dozenal">1'0'0'0'0'0'0</span> |

---

## Other Daedric Fonts

- [Daedric Runes][11] by Erwin Denissen (*High-Logic*)
- [Oblivion][12] by Steve Deffeyes (*dongle*)
- [Daedric Runes][13] by *Alli*
- [Daedra][14] by Neale Davidson (*Pixel Sagas*)
- [Ayembedt][15] by Georg Duffner
- [Daedric Font Resources][16] by *Yar-Yulme*
- [Better Daedric Font][17] by *hardek*
- [Daedric Letters Gold][18] by *Yagellonica*
- [Shebbz Daedric][19] by *Shebbz*
- [Handwritten Daedric][20] by *Orsimeris*

[11]: https://www.ffonts.net/Daedric-Runes.font
[12]: https://en.uesp.net/wiki/File:Obliviontt.zip
[13]: https://morroblivion.com/forums/skyrim-general-chat/allis-daedric-runes-opentype-font-kit
[14]: http://www.pixelsagas.com/?download=daedra
[15]: https://github.com/georgd/OpenMW-Fonts
[16]: https://www.nexusmods.com/morrowind/mods/45458/
[17]: https://www.nexusmods.com/morrowind/mods/44540
[18]: https://www.deviantart.com/yagellonica/art/Daedric-Letters-GOLD-741405288
[19]: https://twitter.com/t00thpasteface/status/1291107593432293376
[20]: https://www.reddit.com/r/teslore/comments/a3jnm8/handwritten_daedric_script_ttfotf/

---

## Example

| In the darkest days Azura sent her great champion to reform the Broken Promise Blessing. Moon-and-Star, to sing peace, the unbreakable soul of the lost Chimer, would silence devils mad first. So the Hortator challenged Dagoth Ur's army as no god could. The Five Great Houses and Ashland tribes heard the battlecall. Joined as one voice, the Dunmer screamed an end for the blasphemous undead. All come and see in Resdayn old, a newborn dawn. We prayed for your triumphant soul's return, Nerevar. |
|---|
| Gher iam gah'dun siin Azura nesi'ag eal gah'amer Biridad as reymo winol shoksuna. Luhn'silvar, belid flur, as kogo sul en am as errat Chimer, almardar as sharmaat malshok alna. Et as Hortator sorilke'ag Dagoth Ur'm shaldmas, lakor bahr panthi mugakar. As arc gah'thiil en arador meriaal leyshe'ag as cornayn. Humore'ag lakor aln yivohn as Dunmer gire'ag ot dimi sut as demigi bahrdrar. Hadik yagla en talje gher Resdaynia ald, ot muhrhag dayn. Osuhn almese'ag abahr sut ohm yalif sul'm devahr, Nerevar. |
| <span style="font-family:HayghinDaedric">Gher iam gah'dun siin Azura nesi'ag eal gah'amer Biridad as reymo winol shoksuna. Luhn'silvar, belid flur, as kogo sul en am as errat Chimer, almardar as sharmaat malshok alna. Et as Hortator sorilke'ag Dagoth Ur'm shaldmas, lakor bahr panthi mugakar. As arc gah'thiil en arador meriaal leyshe'ag as cornayn. Humore'ag lakor aln yivohn as Dunmer gire'ag ot dimi sut as demigi bahrdrar. Hadik yagla en talje gher Resdaynia ald, ot muhrhag dayn. Osuhn almese'ag abahr sut ohm yalif sul'm devahr, Nerevar.</span> |

#### Example Credits:
Wiki for [Casual Dunmeris][21]\
Lyrics by Luther Weiser\
Translation by [Will Jordan][22]\
Soundcloud of [Liz Katrin \(Katarzyna Bonikowska\)][23]\
Skywind Soundtrack by [Fredrik Jonasson][24]

[21]: https://casualscrolls.fandom.com/wiki/Dunmeri_language
[22]: https://soundcloud.com/smitehammer
[23]: https://soundcloud.com/liz-katrin/hortator-skywind
[24]: https://jonassonfredrik.bandcamp.com

---
