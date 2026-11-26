## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[13] fonts/ttf/CCOldPressCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* uni0DA5 (U+0DA5): found 1, expected one of: [2, 3, 5]
* uni0DA3 (U+0DA3): found 2, expected one of: [3, 4] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 395 among a set of 4  math glyphs.
The following math glyphs have a different width, though:
width=472: equal [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. (Overriden: Sinhala fonts: U+20B9 is optional (Sri Lanka writes රු / Rs)) [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* viramasinh.alt1 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* uni0D92 (U+0D92)
* uni0D88 (U+0D88)
* uni0DDA (U+0DDA)
* uni0DDD (U+0DDD) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - rasignsinh: X=-647,Y=2 (should be at baseline 0?)
* - rasignsinh: X=-647,Y=2 (should be at cap-height 0?)
* - rasignsinh: X=-115,Y=1 (should be at baseline 0?)
* - rasignsinh: X=-115,Y=1 (should be at cap-height 0?)
* - period (U+002E): X=67,Y=-1 (should be at baseline 0?)
* - period (U+002E): X=67,Y=-1 (should be at cap-height 0?)
* - period (U+002E): X=67,Y=-1 (should be at baseline 0?)
* - period (U+002E): X=67,Y=-1 (should be at cap-height 0?)
* - uni0D9D (U+0D9D): X=529,Y=-2.5 (should be at baseline 0?)
* - uni0D9D (U+0D9D): X=529,Y=-2.5 (should be at cap-height 0?)
* - yasignsinh: X=316,Y=2.5 (should be at baseline 0?)
* - yasignsinh: X=316,Y=2.5 (should be at cap-height 0?)
* - uni0DB7 (U+0DB7): X=529,Y=-2 (should be at baseline 0?)
* - uni0DB7 (U+0DB7): X=529,Y=-2 (should be at cap-height 0?)
* - uni0DB0 (U+0DB0): X=221,Y=2 (should be at baseline 0?)
* - uni0DB0 (U+0DB0): X=221,Y=2 (should be at cap-height 0?)
* - uni0D8D (U+0D8D): X=918,Y=1.5 (should be at baseline 0?)
* - uni0D8D (U+0D8D): X=918,Y=1.5 (should be at cap-height 0?)
* - uni0DB9 (U+0DB9): X=496,Y=2 (should be at baseline 0?)
* - uni0DB9 (U+0DB9): X=496,Y=2 (should be at cap-height 0?)
* - uni0D8B (U+0D8B): X=787,Y=1.5 (should be at baseline 0?)
* - uni0D8B (U+0D8B): X=787,Y=1.5 (should be at cap-height 0?)
* - uni0D89 (U+0D89): X=527,Y=-1.5 (should be at baseline 0?)
* - uni0D89 (U+0D89): X=527,Y=-1.5 (should be at cap-height 0?)
* - uni0D85 (U+0D85): X=369,Y=2 (should be at baseline 0?)
* - uni0D85 (U+0D85): X=369,Y=2 (should be at cap-height 0?)
* - uni0DA5 (U+0DA5): X=1031,Y=-1 (should be at baseline 0?)
* - uni0DA5 (U+0DA5): X=1031,Y=-1 (should be at cap-height 0?)
* - ndIsinh: X=413.5,Y=2 (should be at baseline 0?)
* - ndIsinh: X=413.5,Y=2 (should be at cap-height 0?)
* - ndIisinh: X=503.5,Y=-2.5 (should be at baseline 0?)
* - ndIisinh: X=503.5,Y=-2.5 (should be at cap-height 0?)
* - dUusinh: X=400,Y=2 (should be at baseline 0?)
* - dUusinh: X=400,Y=2 (should be at cap-height 0?)
* - khsinh: X=172.5,Y=2 (should be at baseline 0?)
* - khsinh: X=172.5,Y=2 (should be at cap-height 0?)
* - khIsinh: X=170,Y=2 (should be at baseline 0?)
* - khIsinh: X=170,Y=2 (should be at cap-height 0?)
* - lUusinh: X=283,Y=2 (should be at baseline 0?)
* - lUusinh: X=283,Y=2 (should be at cap-height 0?)
* - lUusinh: X=348,Y=-1 (should be at baseline 0?)
* - lUusinh: X=348,Y=-1 (should be at cap-height 0?)
* - uni0D9F (U+0D9F): X=623,Y=1 (should be at baseline 0?)
* - uni0D9F (U+0D9F): X=623,Y=1 (should be at cap-height 0?)
* - dhsinh: X=231,Y=2 (should be at baseline 0?)
* - dhsinh: X=231,Y=2 (should be at cap-height 0?)
* - dhIisinh: X=232,Y=-1 (should be at baseline 0?)
* - dhIisinh: X=232,Y=-1 (should be at cap-height 0?)
* - mIsinh: X=391,Y=2 (should be at baseline 0?)
* - mIsinh: X=391,Y=2 (should be at cap-height 0?)
* - mbIsinh: X=219,Y=2.5 (should be at baseline 0?)
* - mbIsinh: X=219,Y=2.5 (should be at cap-height 0?)
* - vsinh: X=301.5,Y=2 (should be at baseline 0?)
* - vsinh: X=301.5,Y=2 (should be at cap-height 0?)
* - ndUsinh: X=182,Y=1 (should be at baseline 0?)
* - ndUsinh: X=182,Y=1 (should be at cap-height 0?)
* - nyUsinh: X=856,Y=-2 (should be at baseline 0?)
* - nyUsinh: X=856,Y=-2 (should be at cap-height 0?)
* - nyUsinh: X=1123,Y=-2 (should be at baseline 0?)
* - nyUsinh: X=1123,Y=-2 (should be at cap-height 0?)
* - dUsinh: X=171,Y=1 (should be at baseline 0?)
* - dUsinh: X=171,Y=1 (should be at cap-height 0?)
* - four (U+0034): X=314,Y=2.5 (should be at baseline 0?)
* - four (U+0034): X=314,Y=2.5 (should be at cap-height 0?)
* - four (U+0034): X=198,Y=2 (should be at baseline 0?)
* - four (U+0034): X=198,Y=2 (should be at cap-height 0?)
* - uniE004 (U+E004): X=523,Y=-2 (should be at baseline 0?)
* - uniE004 (U+E004): X=523,Y=-2 (should be at cap-height 0?)
* - nDhasinh: X=828,Y=2 (should be at baseline 0?)
* - nDhasinh: X=828,Y=2 (should be at cap-height 0?)
* - uni0D8E (U+0D8E): X=918,Y=1.5 (should be at baseline 0?)
* - uni0D8E (U+0D8E): X=918,Y=1.5 (should be at cap-height 0?)
* - uni0D8C (U+0D8C): X=787,Y=1.5 (should be at baseline 0?)
* - uni0D8C (U+0D8C): X=787,Y=1.5 (should be at cap-height 0?)
* - uni0D88 (U+0D88): X=369,Y=2 (should be at baseline 0?)
* - uni0D88 (U+0D88): X=369,Y=2 (should be at cap-height 0?)
* - uni0D86 (U+0D86): X=369,Y=2 (should be at baseline 0?)
* - uni0D86 (U+0D86): X=369,Y=2 (should be at cap-height 0?)
* - uni0D87 (U+0D87): X=369,Y=2 (should be at baseline 0?)
* - uni0D87 (U+0D87): X=369,Y=2 (should be at cap-height 0?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* ornament (U+E005): from (45.0, 63.0) to (46.0, 63.0) is colinear with segment from (46.0, 63.0) to (46.0, 63.0)
* ornament (U+E005): from (532.0, 180.0) to (558.0, 231.0) is colinear with segment from (558.0, 231.0) to (600.0, 312.0)
* ornament (U+E005): from (601.0, 314.0) to (601.0, 314.0) is colinear with segment from (601.0, 314.0) to (601.0, 314.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0DC5 (U+0DC5): Quad(QuadBez { p0: (713.5, 99.5), p1: (713.0, 126.0), p2: (713.0, 134.0) })/Quad(QuadBez { p0: (713.0, 134.0), p1: (715.0, 126.0), p2: (722.0, 97.5) }) = 14.036243467926484 degrees
* rAaesinh: Quad(QuadBez { p0: (399.5, 575.5), p1: (365.0, 561.0), p2: (317.0, 552.0) })/Quad(QuadBez { p0: (317.0, 552.0), p1: (325.0, 552.0), p2: (346.5, 549.0) }) = 10.61965527615514 degrees
* uni0D8A (U+0D8A): Quad(QuadBez { p0: (402.0, 575.5), p1: (367.0, 561.0), p2: (320.0, 552.0) })/Quad(QuadBez { p0: (320.0, 552.0), p1: (327.0, 552.0), p2: (349.0, 549.0) }) = 10.840305454330533 degrees
* uni0DA8 (U+0DA8): Quad(QuadBez { p0: (383.5, 116.5), p1: (379.0, 142.0), p2: (378.0, 157.0) })/Quad(QuadBez { p0: (378.0, 157.0), p1: (377.0, 139.0), p2: (370.5, 111.5) }) = 6.993904954154618 degrees
* uni0D9B (U+0D9B): Quad(QuadBez { p0: (368.0, 190.0), p1: (374.0, 193.0), p2: (378.0, 194.0) })/Quad(QuadBez { p0: (378.0, 194.0), p1: (377.0, 194.0), p2: (379.0, 194.0) }) = 14.036243467926484 degrees
* uni0DB0 (U+0DB0): Quad(QuadBez { p0: (362.5, 100.0), p1: (358.0, 122.0), p2: (357.0, 137.0) })/Quad(QuadBez { p0: (357.0, 137.0), p1: (356.0, 121.0), p2: (350.0, 96.5) }) = 7.39040920928769 degrees
* uni0D8D (U+0D8D): Quad(QuadBez { p0: (409.0, 80.0), p1: (394.0, 105.0), p2: (391.0, 115.0) })/Quad(QuadBez { p0: (391.0, 115.0), p1: (394.0, 95.0), p2: (385.0, 76.5) }) = 8.168478624045488 degrees
* uni0D8D (U+0D8D): Line(Line { p0: (704.0, 170.0), p1: (704.0, 172.0) })/Quad(QuadBez { p0: (704.0, 172.0), p1: (698.0, 147.0), p2: (690.0, 131.5) }) = 13.495733280795811 degrees
* uni0D9E (U+0D9E): Quad(QuadBez { p0: (364.5, 101.0), p1: (357.0, 123.0), p2: (356.0, 128.0) })/Quad(QuadBez { p0: (356.0, 128.0), p1: (356.0, 121.0), p2: (354.0, 105.0) }) = 11.309932474020195 degrees
* uni0DC3 (U+0DC3): Quad(QuadBez { p0: (416.0, 83.5), p1: (401.0, 109.0), p2: (398.0, 118.0) })/Quad(QuadBez { p0: (398.0, 118.0), p1: (401.0, 99.0), p2: (392.5, 80.5) }) = 9.462322208025574 degrees
* uni0DBB (U+0DBB): Quad(QuadBez { p0: (402.0, 578.5), p1: (367.0, 564.0), p2: (320.0, 555.0) })/Quad(QuadBez { p0: (320.0, 555.0), p1: (327.0, 555.0), p2: (349.0, 552.0) }) = 10.840305454330533 degrees
* uni0D91 (U+0D91): Quad(QuadBez { p0: (83.0, 419.5), p1: (118.0, 420.0), p2: (153.0, 420.0) })/Quad(QuadBez { p0: (153.0, 420.0), p1: (132.0, 424.0), p2: (122.0, 442.0) }) = 10.784297867562596 degrees
* uni0DA3 (U+0DA3): Quad(QuadBez { p0: (1011.5, 121.0), p1: (1007.0, 146.0), p2: (1007.0, 162.0) })/Quad(QuadBez { p0: (1007.0, 162.0), p1: (1006.0, 144.0), p2: (998.5, 117.0) }) = 3.1798301198641643 degrees
* jhIsinh: Quad(QuadBez { p0: (1007.0, 117.5), p1: (1003.0, 143.0), p2: (1003.0, 158.0) })/Quad(QuadBez { p0: (1003.0, 158.0), p1: (1002.0, 140.0), p2: (994.5, 113.0) }) = 3.1798301198640497 degrees
* jhIisinh: Quad(QuadBez { p0: (1005.5, 116.0), p1: (1001.0, 141.0), p2: (1000.0, 156.0) })/Quad(QuadBez { p0: (1000.0, 156.0), p1: (1000.0, 139.0), p2: (993.0, 111.5) }) = 3.8140748342903783 degrees
* rsinh: Quad(QuadBez { p0: (407.5, 578.5), p1: (373.0, 564.0), p2: (325.0, 555.0) })/Quad(QuadBez { p0: (325.0, 555.0), p1: (333.0, 555.0), p2: (354.5, 552.0) }) = 10.61965527615514 degrees
* tthIsinh: Quad(QuadBez { p0: (383.5, 115.5), p1: (379.0, 140.0), p2: (378.0, 155.0) })/Quad(QuadBez { p0: (378.0, 155.0), p1: (377.0, 138.0), p2: (370.5, 111.0) }) = 7.180535497720157 degrees
* tthIisinh: Quad(QuadBez { p0: (394.0, 116.0), p1: (389.0, 141.0), p2: (389.0, 156.0) })/Quad(QuadBez { p0: (389.0, 156.0), p1: (388.0, 139.0), p2: (381.5, 111.5) }) = 3.36646066342994 degrees
* rIisinh: Quad(QuadBez { p0: (452.0, 653.0), p1: (471.0, 667.0), p2: (491.0, 683.0) })/Quad(QuadBez { p0: (491.0, 683.0), p1: (477.0, 676.0), p2: (452.5, 668.0) }) = 12.094757077012089 degrees
* rIisinh: Quad(QuadBez { p0: (447.5, 575.5), p1: (413.0, 561.0), p2: (365.0, 552.0) })/Quad(QuadBez { p0: (365.0, 552.0), p1: (372.0, 552.0), p2: (394.0, 549.0) }) = 10.61965527615514 degrees
* rIsinh: Quad(QuadBez { p0: (441.0, 578.5), p1: (406.0, 564.0), p2: (359.0, 555.0) })/Quad(QuadBez { p0: (359.0, 555.0), p1: (366.0, 555.0), p2: (388.0, 552.0) }) = 10.840305454330533 degrees
* dhsinh: Quad(QuadBez { p0: (382.5, 108.0), p1: (378.0, 132.0), p2: (377.0, 147.0) })/Quad(QuadBez { p0: (377.0, 147.0), p1: (376.0, 130.0), p2: (369.5, 103.5) }) = 7.180535497720157 degrees
* nnddIisinh: Quad(QuadBez { p0: (370.0, 479.0), p1: (369.0, 479.0), p2: (369.0, 480.0) })/Quad(QuadBez { p0: (369.0, 480.0), p1: (364.0, 454.0), p2: (347.0, 436.5) }) = 10.885527054658743 degrees
* dhIsinh: Quad(QuadBez { p0: (386.5, 116.5), p1: (382.0, 142.0), p2: (381.0, 157.0) })/Quad(QuadBez { p0: (381.0, 157.0), p1: (380.0, 139.0), p2: (373.5, 111.5) }) = 6.993904954154618 degrees
* dhIisinh: Quad(QuadBez { p0: (383.5, 110.0), p1: (379.0, 135.0), p2: (378.0, 150.0) })/Quad(QuadBez { p0: (378.0, 150.0), p1: (377.0, 133.0), p2: (370.5, 105.5) }) = 7.180535497720157 degrees
* logo (U+E002): Quad(QuadBez { p0: (201.0, 399.0), p1: (190.0, 406.0), p2: (186.0, 418.0) })/Quad(QuadBez { p0: (186.0, 418.0), p1: (187.0, 409.0), p2: (179.0, 402.0) }) = 12.094757077012149 degrees
* nDhasinh: Quad(QuadBez { p0: (969.5, 100.0), p1: (965.0, 122.0), p2: (964.0, 137.0) })/Quad(QuadBez { p0: (964.0, 137.0), p1: (963.0, 121.0), p2: (957.0, 96.5) }) = 7.39040920928769 degrees
* uni0D8E (U+0D8E): Quad(QuadBez { p0: (409.0, 80.0), p1: (394.0, 105.0), p2: (391.0, 115.0) })/Quad(QuadBez { p0: (391.0, 115.0), p1: (394.0, 95.0), p2: (385.0, 76.5) }) = 8.168478624045488 degrees
* uni0D8E (U+0D8E): Line(Line { p0: (704.0, 170.0), p1: (704.0, 172.0) })/Quad(QuadBez { p0: (704.0, 172.0), p1: (698.0, 147.0), p2: (690.0, 131.5) }) = 13.495733280795811 degrees
* uni0D93 (U+0D93): Quad(QuadBez { p0: (648.0, 419.5), p1: (683.0, 420.0), p2: (718.0, 420.0) })/Quad(QuadBez { p0: (718.0, 420.0), p1: (697.0, 424.0), p2: (687.0, 442.0) }) = 10.784297867562596 degrees
* rUusinh: Quad(QuadBez { p0: (402.0, 578.5), p1: (367.0, 564.0), p2: (320.0, 555.0) })/Quad(QuadBez { p0: (320.0, 555.0), p1: (327.0, 555.0), p2: (349.0, 552.0) }) = 10.840305454330533 degrees
* rUsinh: Quad(QuadBez { p0: (402.0, 578.5), p1: (367.0, 564.0), p2: (320.0, 555.0) })/Quad(QuadBez { p0: (320.0, 555.0), p1: (327.0, 555.0), p2: (349.0, 552.0) }) = 10.840305454330533 degrees
* uni0D92 (U+0D92): Quad(QuadBez { p0: (83.0, 419.5), p1: (118.0, 420.0), p2: (153.0, 420.0) })/Quad(QuadBez { p0: (153.0, 420.0), p1: (132.0, 424.0), p2: (122.0, 442.0) }) = 10.784297867562596 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* endash (U+2013): Line(Line { p0: (17.0, 71.0), p1: (428.0, 72.0) }) (angle: 0.14 degrees, expected: 0.00 degrees)
* four (U+0034): Line(Line { p0: (391.0, 521.0), p1: (390.0, 228.0) }) (angle: -90.20 degrees, expected: -90.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* jhIisinh: Quad(QuadBez { p0: (1296.0, 434.0), p1: (1296.0, 434.0), p2: (1296.0, 434.0) }) has the same coordinates as a previous segment.
* khsinh: Quad(QuadBez { p0: (691.0, 522.0), p1: (691.0, 522.0), p2: (691.0, 522.0) }) has the same coordinates as a previous segment.
* ddsinh: Quad(QuadBez { p0: (679.0, 419.0), p1: (679.0, 419.0), p2: (679.0, 419.0) }) has the same coordinates as a previous segment.
* nnddsinh: Quad(QuadBez { p0: (748.0, 417.0), p1: (748.0, 417.0), p2: (748.0, 417.0) }) has the same coordinates as a previous segment.
* vIsinh: Quad(QuadBez { p0: (646.0, 460.0), p1: (646.0, 460.0), p2: (646.0, 460.0) }) has the same coordinates as a previous segment.
* logo (U+E002): Quad(QuadBez { p0: (694.0, 134.5), p1: (694.0, 135.0), p2: (694.0, 135.0) }) has the same coordinates as a previous segment.
* ornament (U+E005): Line(Line { p0: (601.0, 314.0), p1: (601.0, 314.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>


</div>
</details>


<details><summary>[1] fonts/ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>


</div>
</details>






### Summary

| ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|
| 14 | 9 | 81 | 51 | 
| 9% | 6% | 52% | 33% | 



