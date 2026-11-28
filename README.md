# M625A Power Supply · Power

Ward-Beck Systems M625A, 1978|11. Wiki page: [M625A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.POWER.M625A-Power-Supply/)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 12 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 2 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 132 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 2 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 27 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [15 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1978 - M625A - P002 - 1-1.jpg](MANUALS/1978%20-%20M625A%20-%20P002%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Dc output** | +25 volts amperes load currents from |
| **Line regulation** | 1% for Line variations from 105 volts ac |
| **Load regulation** | for full Load load variations from zero |
| **Ripple and noise** | Less than 500 microvolts RMS for all Line and load conditions specified above. |
| **Input impedance** | Less than ohm from 20 kHz. |
| **Stability** | volts measured over an period, after minutes warmup hour |
| **Protection** | Overcurrent and short circuit foldback. Overvoltage crowbar |
| **Ac input** | 125 volts ac, input power: 525 VA. Hz. Maximum |
| **Ambient temperature** | degrees Celsius at rated output. |
| **Dimensions** | 8.45&quot; wide 5.1&quot; high 13.7&quot; deep 214.6 mm 130 Mm 348 mm) |
| **Accessories** | MF6A mounting frame (accommodates [wo M625A power supplies) |

## Circuit description

From [1978 - M625A - Power Supply (2).pdf](MANUALS/1978%20-%20M625A%20-%20Power%20Supply%20(2).pdf) pages 3-8 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M625 Ais a +25 \lolt dc powers u p ply which is capable of del i\l ering curreflt s-of up to 5 amperes.

The primary winding o f the power transformer T1 is designed for operation from a 120 \lolt e c, 60 Hz line.

The bridger ectifi er CRI and filter capacitors C3 and C4 follow the second a r y transformer winding. The unregulated output of approx lm&quot;t ely +40 vo tr sIs &quot;pplied to these ri es regulator transistors 01 to 04. Together with the primary regulator cIl&quot;Cui t oft h e 1-1 11 printed circuit card, transistors 01 to 0 4 pro\l lde the ~ g u la ted dc outputs as they &quot;ppe&quot;r on connector P2.

The LEO pilot light Is connected across the full 50 volt output and indicate s the presence of the output voltages.

A seven -po siti on meter selectors witch (SW2), tog ether with meter jacks J land J2, are provided on the front panel to &quot;I low metering of the output functions of the powers u p ply.

With thea id of a digital multimet er, output voltages and currents o f the powers u p ply can b e checked In the following manner:

SWITCH POSITION DMM FUNCTION CONVERSION FACTOR

Meter OFF Neg. current

(2) -I Cur ~n t 10 uA/ A Neg. \lol t age (3) -25 Current 10 u A/V Offset \lo lt age (4) OFFSET Voltage None (5) +25

Cur ~nt 10 uA /V (6) +1 Cur ~nt 10 u A/A Meter OFF 171 to illustrate, when measuring positive \lo lt age (s w i lCh position 5), a reading of +2 50 uAw ill indicate a volt age of +25 V. When measuring positive output current (switch posH ion 6), a ~a d l n g of 30 u A will indicate a cur ~nt of 3 A. In the OFFSET position, the

meter will read the differential voltage bet we efl the positive and then e g ative supply \loltages. A differential voltage of up to +0.1 V

isp erml s s ibi e.

WARD -BEC K SYSTEMS l.TD.

**TEST &amp; SETUP PROCEDURE**

1) _R emov &quot;, PCB 1 ~117.

2) -A p ply pow&quot;''' and ch...,k fa,. p,. &quot;,s &quot;,nc&quot;, o f app ro&quot; lma t&quot;,l y -+-40 vee e t th &quot;, OUlput s ld&quot;' s o f fuses F2 and F J.

J) -R emov e powe,.. Ins l all 01 and 02. (Left &quot; Id '&quot; heals ink wh.... facing pow &quot;,,. supply).

4) to sr en a lempora,.y jump e,. e c-es s R l 1 o n 1-11 7 10 dl s ~b lethe compl em en la,.y &quot; loss o f volt age&quot; d &quot;,IeclO,..

5) ln SI all 1 _ 1 17 c a,.d.

6) - Mon i l o &quot; I h '&quot; -+-25 V oulpul a l J2-I and J2 ~5. Apply p,. ima,.y ac powe&quot; slowly using ava,.lac. If th &quot;, o ul p u l should no l 90 l n lo,.&quot;,gul a l lon by Ih e I i &quot;&quot;&quot; II,.ea c hes -+-27 V, adjust R 14 (on 1 -117) 10 r-educ e Ih e voltage 10 -+-25 V.

7) _Remov &quot;, p ow&quot;,r and i n Sl al1 OJ and 04. {Ri g hIs ld '&quot; heats ink when facing pow e&quot; sup p ly}.

a) -Manito,. Ih e ~ 2 5 V o u lpu l e r J 2_9 and J2-5. The -25 V oulpul should go in lo r egu lal ion b efo,.&quot; Ihe vollage e ecee s _ 27 V.

9) ~R emov &quot; p owe,.. Remov &quot; jump&quot;,. from Rt1 on 1_1 17.

(0) _App ly pow &quot;,. and check bOlh outpUI voltages. If Ih &quot;,.egul a lor is operating co,.rec l ly, t h &quot; -+-25 Van d Ih e _25 V ou l puts should b e w ilhl nap p ro&gt;d mate l y 2 vall &quot; of s p &quot;cl fie d OUlput. Adj u sI R14 (1 ~ 1 1 7) 10 &quot; ais e 0&quot; low &quot;,,. Ih &quot; -+-2 5 V output. Adj us l RIa (1_ 1 17) 10 equal i z e I he diff &quot;,.e n t ial b &quot;Iwe.... the two vo ll age&quot;. A&quot; lt Is imp o,. tan t that Ih e two vol lag &quot; &quot; be ide n tic a l, use a OMM to check both voll age &quot;.

11) - Set Ih e mel &quot;,. l ng &quot; wilch on m e fron l panel 10 OFFSET and plug Ih '&quot; DMM Into I h &quot;, me le,. jack &quot;.

~Adju!il the call b r-a l lon control R2a (1 _ 1 17) 10 read 0 volls al

I h e 0&quot;1&quot;1.

p s.

TEST fJ SETUP PROCEDURE

12) - Set the metering switch to +25 and se l the OMM to a CURRENT

-Adj us t I h e c...llb..atlon control R39 (1-1 17) to..ee e +250 u A a l the DMM.

-Set Ih e mete.. lng switch 10 -25.

~~!U ~~~~e call b..at lon control R31 1 1-1 17) to..ee c -250 u A a l

13) - Remove po we r-.

-ccoeec ran a mme l e &quot; In se.. les w l lh a 25 ohm load r-esis tor (min. 100 W) between J2-1 and J2-9.

-Slo wly apply power and observe load current. The load cu.... en t should stab il i ze a t 2 A.

14) -C h ange the load -es tet e o ce to 10 ohms (m in. 250 W). - Slowly apply po we.. and ob se..ve load cu....en t. It should stabIlize a t 5 A.

-ser mete.. ing switch to +1.

P lug I h e OMM inlo mel e.. lng jacks.

- Adjus l I he calib..e uco cco n-o r R33 (1_1 17)..e&quot;din g of +50 uA.

-Se t me le.. ln g s w l l c h to - I.

-~~u~~. m e cal ib..atlon cont..ol R34 (1_1 17)

15) -Rem ov e ttt e DMM from the mete.. lng jacks. -L eave the amm e ler In I h e load Circuit andre c c ce the lo...d..e &quot; i stances lowly. Foldb ac k cu..r e n t limitings ho u l d se lIna lapp rox i male l y 6 A.

Sho.. t circuli the output completely. Load cur N!nt should be 1.25 A 0 rl e ss.

16) -op e&quot;at e the supply withal o ad cu..r ent of 5 A. - Measure the noise across each half of the pow e&quot; supply output, as well a sec r-css Ihe !:25 V terminals. Noises ho uld b e ~:~~II:~7:ns:00 uV RMS. Use oscilloscope to check fo rposs ibl e

17) - Remove po we'&quot;

-6~in.;. ~2.10 to 25 ohm r esl s to.., sho.. t eml tt e r-10 collec to.. on

-Pla ce a vo ltmet e&quot; e c r-c est he +25 V output (J2_ 1 &amp;&lt; J2-5).

TEST uSE TUP PROCEDURE

S lowly apply a c input with ave.. t ec • When the voltage..ea c h e5 app ro xi mate ly 28 to 30 volts, Ih e 'c..o wba.. ' SCR 09 (1-111) 5hould fi&quot;e and 5 ho.. t circuit the 5u p ply output. - Repeat above fo.. then eg &quot;live output of the supply.

18) -Set theme le.. ing 5 witch to OFFSET and connect the DMM 10 the mete.. jack 5. Switch DMM to VOLTAGE.

-Apply po we.. to the supply.

-Intermitl en ll y connect and..emov e the 10 ohm load. change in mete....e.. dings bo vld note x c e e d.: 100 mV.

**19) DC VOLTAGE CHART**

The follow ing dc voltage s....e lypic.. 1 lind e r-e obtaln ed und e.. ' n o 101ld ' conditions, with thea c inpu l.. d ju5ted such &quot; 5 to..e5 u l lin &quot; nun..e g u lll ied voltllge of &quot;'40 Vdc. The vol tme le.. u 5ed 5ho ut d h&quot;v e II minimum impedance of 20,000 ohm s/volt.

0' &quot;'25.5

&quot;'25.5 _3 9.5 0' -39.5

Pin 51 &quot;'24.00 -12.00 2 &quot;'4 0.00 _37.00,3 &quot;'40.00 0.00 -39.00 -37.00 5 &quot;' 1.65 -39.00 s +1.75 -38.00

r &quot;'24.50 _ 26.00

&quot;'25.00 -25.00

0.00

to 0.00

WARD - • • C K av.Te M. LTD.

TEST t&quot; SE.TUP PROCEDURE

+40.0 +40.0 +25.5 -o., 0.0 &quot;.S -12.0

**.J 0.0 0.0**

-40.0 _39.5 _25.0

25.0 -25.0 0.0 +25.0 -25.5 _ 24.0

0.0 -39.5 -25.5 -25.0 -25.0

20) - Remo&quot;e power lind load.

R ei se input to 140 &quot;Qlt, ee • Th l l will r lli lethe u n~gulllled &quot; allege to IIPpro ximet el y · 50 &quot;o lls.

-~7t~:&quot;st.h&quot; t power supply mlll n ill ins r eg u let lon under mese con

p s.

**M62~ A POWER SUPPLY**

cr Capacitor 0.033 u F!400 V Ph:/ iP S 281COA33K C2 0.1 uF ! 400 V 28 1COAlOOK C2 9,600,~ F!50 V Ma,I, lor y CGS962U0500Fl

CRl Rectifier Assembly ED, PBOO CR2 Diode Motorola 1~4003

LED Assembly

lOA, S6 3 13.010

**1A, FB**

Dale RS-5

**20W 0.5**

ss '20W

**OW 0.5**

0.25

R6,. RS-26

</details>

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRkp6NUJFUmNPMVU/view?resourcekey=0-05be1f157sNnNodnX8U2Rw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRkp6NUJFUmNPMVU&resourcekey=0-05be1f157sNnNodnX8U2Rw" width="240" alt="1978 - M625A - 1-117-06-001 - KAEY REGULATOR.jpg"></a><br><sub>1978|11 · 1-117-06-001 - KAEY REGULATOR · <a href="SCHEMATICS/1978%20-%20M625A%20-%201-117-06-001%20-%20KAEY%20REGULATOR%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKclM3U2hqaGh1bEU/view?resourcekey=0-tXZlv79cBVn55cALz_65VA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKclM3U2hqaGh1bEU&resourcekey=0-tXZlv79cBVn55cALz_65VA" width="240" alt="1978 - M625A - 117-02-001 - IRCUIT ADCED IISSUEJDATE REVISION.jpg"></a><br><sub>1978|11 · 117-02-001 - IRCUIT ADCED IISSUEJDATE REVISION · <a href="SCHEMATICS/1978%20-%20M625A%20-%20117-02-001%20-%20IRCUIT%20ADCED%20IISSUEJDATE%20REVISION%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcHVvYmNFeF9oWWc/view?resourcekey=0-s-YuAGgVUhU2Nz9rWeoR1Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcHVvYmNFeF9oWWc&resourcekey=0-s-YuAGgVUhU2Nz9rWeoR1Q" width="240" alt="1978 - M625A - 625-06-001 - ENER POWER SURTTY.jpg"></a><br><sub>1978|11 · 625-06-001 - ENER POWER SURTTY · <a href="SCHEMATICS/1978%20-%20M625A%20-%20625-06-001%20-%20ENER%20POWER%20SURTTY%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTUxza3A0LUZkZjA/view?resourcekey=0-vc7T6GoU1UCAe2Mo1NbimA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTUxza3A0LUZkZjA&resourcekey=0-vc7T6GoU1UCAe2Mo1NbimA" width="240" alt="1978 - M625A - DOC - WBS eng memo 4.jpg"></a><br><sub>1978|11 · DOC - WBS eng memo 4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUHFxMWxFUXFhWFE/view?resourcekey=0-2s7ZGQFAoOlXMYUQy1j5SA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUHFxMWxFUXFhWFE&resourcekey=0-2s7ZGQFAoOlXMYUQy1j5SA" width="240" alt="1978 - M625A - DOC - WBS eng memo 5.jpg"></a><br><sub>1978|11 · DOC - WBS eng memo 5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRkVFZVlRaXE4b1k/view?resourcekey=0-vPddbR6Q9iM_ToLUPyxIqA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRkVFZVlRaXE4b1k&resourcekey=0-vPddbR6Q9iM_ToLUPyxIqA" width="240" alt="1978 - M625A - DSMOD IICKD USD MTI.jpg"></a><br><sub>1978|11 · DSMOD IICKD USD MTI</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMGUzU3NtTjdZMFU/view?resourcekey=0-rNd_o_jf6YO0w96VL8ktPQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMGUzU3NtTjdZMFU&resourcekey=0-rNd_o_jf6YO0w96VL8ktPQ" width="240" alt="1978 - M625A - P001 - Title Page.jpg"></a><br><sub>1978|11 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMFJfT1ZHanMwZ2s/view?resourcekey=0-PItwJXRH4eaJp4Z2f7-Nrw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMFJfT1ZHanMwZ2s&resourcekey=0-PItwJXRH4eaJp4Z2f7-Nrw" width="240" alt="1978 - M625A - P002 - 1-1.jpg"></a><br><sub>1978|11 · P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQUZRZmFvTDRvNms/view?resourcekey=0-EMmUigzQhq8aVyWvLfGfpg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQUZRZmFvTDRvNms&resourcekey=0-EMmUigzQhq8aVyWvLfGfpg" width="240" alt="1978 - M625A - P003 - 2-1.jpg"></a><br><sub>1978|11 · P003 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdklmUWY3MXpBODg/view?resourcekey=0-lnOTWO7jfA25vesARtvDFQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdklmUWY3MXpBODg&resourcekey=0-lnOTWO7jfA25vesARtvDFQ" width="240" alt="1978 - M625A - P004 - 3-1.jpg"></a><br><sub>1978|11 · P004 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTGdkUFhNeWotYVk/view?resourcekey=0-B2xCl3M7kJa2XVqtbcmdUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTGdkUFhNeWotYVk&resourcekey=0-B2xCl3M7kJa2XVqtbcmdUw" width="240" alt="1978 - M625A - P005 - 3-2.jpg"></a><br><sub>1978|11 · P005 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHQ4bHplaEdjOG8/view?resourcekey=0--WMicmT2BMIeyGj3tqDTHw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHQ4bHplaEdjOG8&resourcekey=0--WMicmT2BMIeyGj3tqDTHw" width="240" alt="1978 - M625A - P006 - 3-3.jpg"></a><br><sub>1978|11 · P006 - 3-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa3pFbk9BQTBTRVU/view?resourcekey=0-0QVnA12OVkFV7TCvpdQAOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa3pFbk9BQTBTRVU&resourcekey=0-0QVnA12OVkFV7TCvpdQAOw" width="240" alt="1978 - M625A - P007 - 3-4.jpg"></a><br><sub>1978|11 · P007 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWHFVSGVta3BlbTQ/view?resourcekey=0-Vc2BlbcX8ILiM3ydrKMtCQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWHFVSGVta3BlbTQ&resourcekey=0-Vc2BlbcX8ILiM3ydrKMtCQ" width="240" alt="1978 - M625A - P008 - 4-1.jpg"></a><br><sub>1978|11 · P008 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQlo3M2t2UWtKTXc/view?resourcekey=0-8obtx8EHnkGEtdfpWmLHpw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQlo3M2t2UWtKTXc&resourcekey=0-8obtx8EHnkGEtdfpWmLHpw" width="240" alt="1978 - M625A - P009 - 4-2.jpg"></a><br><sub>1978|11 · P009 - 4-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcnVvZXlRbVh4Ym8/view?resourcekey=0-wZVgVIAaUcXHOo2o7VOX3Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcnVvZXlRbVh4Ym8&resourcekey=0-wZVgVIAaUcXHOo2o7VOX3Q" width="240" alt="1978 - M625A - P010 - 1-117-1-1.jpg"></a><br><sub>1978|11 · P010 - 1-117-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWWxEbWVfRlZqazg/view?resourcekey=0-EuQZgWUInDe1BXU2HV9N0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWWxEbWVfRlZqazg&resourcekey=0-EuQZgWUInDe1BXU2HV9N0Q" width="240" alt="1978 - M625A - P011 - 1-117-1-2.jpg"></a><br><sub>1978|11 · P011 - 1-117-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZjViUWc1S3dSX2M/view?resourcekey=0-mwNRG4HDpSnerO5zax8kSQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZjViUWc1S3dSX2M&resourcekey=0-mwNRG4HDpSnerO5zax8kSQ" width="240" alt="1978 - M625A - P012 - 1-117-2-1.jpg"></a><br><sub>1978|11 · P012 - 1-117-2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeEJrTWh5d3l4VjQ/view?resourcekey=0-IMV8xg46h_ADiti6ef1VJA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeEJrTWh5d3l4VjQ&resourcekey=0-IMV8xg46h_ADiti6ef1VJA" width="240" alt="1978 - M625A - P013 - 1-117-2-2.jpg"></a><br><sub>1978|11 · P013 - 1-117-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRk4zSng1TFF5TG8/view?resourcekey=0-uI7uP0hGF3Kqdv0R6QmXCg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRk4zSng1TFF5TG8&resourcekey=0-uI7uP0hGF3Kqdv0R6QmXCg" width="240" alt="1978 - M625A - P014 - 1-117-2-3.jpg"></a><br><sub>1978|11 · P014 - 1-117-2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcUJ3TVgtTTlia3c/view?resourcekey=0-zkyEqdoCr6MrhC9HfjqIIQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcUJ3TVgtTTlia3c&resourcekey=0-zkyEqdoCr6MrhC9HfjqIIQ" width="240" alt="1978 - M625A - Power Supply (2).pdf"></a><br><sub>1978|11 · Power Supply (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVC1HMkw1eUJROUU/view?resourcekey=0-r0P0j10RHo2eGBm0QCsBrQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVC1HMkw1eUJROUU&resourcekey=0-r0P0j10RHo2eGBm0QCsBrQ" width="240" alt="1978 - M625A - Power Supply.pdf"></a><br><sub>1978|11 · Power Supply</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMXBMODhOSWxsdWM/view?resourcekey=0-TNsML2Vo6Odj3UFAHIPC8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMXBMODhOSWxsdWM&resourcekey=0-TNsML2Vo6Odj3UFAHIPC8w" width="240" alt="1979 - M625A - DOC - WBS eng memo 7a.jpg"></a><br><sub>1979|12 · DOC - WBS eng memo 7a</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNjNJY0E0WDJQZGc/view?resourcekey=0-doDIns5zf5qaJ_342MLrpg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNjNJY0E0WDJQZGc&resourcekey=0-doDIns5zf5qaJ_342MLrpg" width="240" alt="1979 - M625A - DOC - WBS eng memo 7b.jpg"></a><br><sub>1979|12 · DOC - WBS eng memo 7b</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZkNNdlpPcmU0LWM/view?resourcekey=0-E_vjEZWmjI4zXD8QpocRHw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZkNNdlpPcmU0LWM&resourcekey=0-E_vjEZWmjI4zXD8QpocRHw" width="240" alt="19xx - M625A - DOC - L2042 - P05.jpg"></a><br><sub>19xx - M625A - DOC - L2042 - P05</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTUh0YVhIN2hjclE/view?resourcekey=0-5BbrKsqSG2dcdybh1CqyLg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTUh0YVhIN2hjclE&resourcekey=0-5BbrKsqSG2dcdybh1CqyLg" width="240" alt="19xx - M625A - DOC - L3242 - P05.jpg"></a><br><sub>19xx - M625A - DOC - L3242 - P05</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM1ZUc05mNllNM1U/view?resourcekey=0-iG8RBRupfekSrUdybuCH8g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM1ZUc05mNllNM1U&resourcekey=0-iG8RBRupfekSrUdybuCH8g" width="240" alt="19xx - M625A - DOC - L3242 - P11.jpg"></a><br><sub>19xx - M625A - DOC - L3242 - P11</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - M625A - 117-02-001 - IRCUIT ADCED IISSUEJDATE REVISION.kicad_sch](KICAD/1978%20-%20M625A%20-%20117-02-001%20-%20IRCUIT%20ADCED%20IISSUEJDATE%20REVISION.kicad_sch)
- [M625A.kicad_sym](KICAD/M625A.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
