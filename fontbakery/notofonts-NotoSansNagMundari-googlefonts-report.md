## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[9] NotoSansNagMundari[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Does the font have any invalid script tags? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.layout.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following invalid script tags were found in the font: nagm</p>
 [code: bad-script-tags]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- ninenagmundari.alt

- zeronagmundari.001
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansNagMundari/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: syriac, todhri, canadian-aboriginal, math, duployan, tifinagh, coptic, malayalam, hebrew, tai-le, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0964 DEVANAGARI DANDA: try adding one of: grantha, mahajani, oriya, gurmukhi, dogra, tamil, limbu, takri, multani, gujarati, khudawadi, telugu, masaram-gondi, bengali, syloti-nagri, malayalam, kannada, gunjala-gondi, ol-onal, tirhuta, sinhala, devanagari, nandinagari</li>
<li>U+0965 DEVANAGARI DOUBLE DANDA: try adding one of: grantha, gurung-khema, mahajani, oriya, gurmukhi, dogra, tamil, limbu, takri, multani, gujarati, khudawadi, telugu, masaram-gondi, bengali, syloti-nagri, malayalam, kannada, gunjala-gondi, ol-onal, tirhuta, sinhala, devanagari, nandinagari</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: elbasan, tibetan, grantha, old-permic, modi, bassa-vah, soyombo, hanifi-rohingya, tamil, manichaean, adlam, masaram-gondi, pahawh-hmong, syloti-nagri, lao, tirhuta, psalter-pahlavi, meetei-mayek, buginese, zanabazar-square, kayah-li, thaana, thai, myanmar, saurashtra, khmer, sundanese, javanese, warang-citi, gurmukhi, duployan, dogra, brahmi, new-tai-lue, yi, math, tagalog, marchen, armenian, malayalam, caucasian-albanian, mandaic, tai-viet, balinese, wancho, devanagari, hebrew, tai-le, bhaiksuki, rejang, nko, sogdian, mahajani, tai-tham, batak, cham, mende-kikakui, tifinagh, coptic, limbu, takri, ahom, khudawadi, bengali, canadian-aboriginal, mongolian, kannada, chakma, music, gunjala-gondi, newa, sinhala, symbols, lepcha, tagbanwa, kaithi, siddham, phags-pa, buhid, khojki, oriya, syriac, gujarati, kharoshthi, telugu, miao, hanunoo, sharada, osage</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>nag-mundari</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Nzakara (Latn, 50,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Heiltsuk (Latn, 300 speakers), Bete-Bendi (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Vute (Latn, 21,000 speakers), Ejagham (Latn, 120,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers), Nateni (Latn, 100,000 speakers), Avokaya (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ebira (Latn, 2,200,000 speakers), Gulay (Latn, 250,478 speakers), Basaa (Latn, 332,940 speakers), Zapotec (Latn, 490,000 speakers), Igbo (Latn, 27,823,640 speakers), Mundani (Latn, 34,000 speakers), Ekpeye (Latn, 226,000 speakers), Dii (Latn, 71,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Bafut (Latn, 158,146 speakers), Dan (Latn, 1,099,244 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Han (Latn, 6 speakers), Aghem (Latn, 38,843 speakers), Mfumte (Latn, 79,000 speakers), Makaa (Latn, 221,000 speakers), Navajo (Latn, 166,319 speakers), Fur (Latn, 1,230,163 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* ongnagmundari (U+1E4D4) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 2 | 7 | 98 | 7 | 137 | 0 | 
| 0% | 0% | 1% | 3% | 39% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
