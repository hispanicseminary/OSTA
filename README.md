# OSTA - [*Old Spanish Textual Archive*](https://osta.oldspanishtextualarchive.org/)
## Repository of the semi-paleographical transcriptions
[![DOI](https://zenodo.org/badge/1175500014.svg)](https://doi.org/10.5281/zenodo.18931375)

## Tables
This folder contains two Excel tables with metadata about the transcriptions, one with codicological and bibliographical data, and one with content descriptions.

`tabla-codices.xlsx`: contains the metadata of each of the codices included in OSTA.
* **HSMS-ID:** codex identifier `HSMS-0003`
* **abreviatura HSMS:** alphanumeric sequence used by HSMS to identify each of the transcriptions `AXP`, `LOP5`
* **BETA manid:** identification number assigned by [PhiloBiblon](https://philobiblon.cog.berkeley.edu/ui-fg/en/wiki/Welcome) to each of the manuscripts or printed works where a work appears
* **BETA copid:** record number assigned by [PhiloBiblon](https://philobiblon.cog.berkeley.edu/ui-fg/en/wiki/Welcome) to a specific copy of a printed book)
* **biblioteca:** current location of the manuscript or printed edition
* **signatura:** signature of the manuscript or printed edition
* **SPDT-inicio:** specific production date, corresponding to the *earliest* date of the copy of a manuscript or the printing of an edition
* **SPDT-fin:** specific production date, corresponding to the *latest* date of the copy of a manuscript or to the printing of an edition
* **lugar específico:** name of the place where the codex was written or printed
* **productor específico:** name of the copyist or printer when this is known
* **formato:** format of the codex, it can be *manuscrito*, *incunable* (1478-1500), *post-incunable* (1501-1520), or *raro* (1521 and later)
* **número de folios:** total number of folios in the codex
* **PhiloBiblon:** link to the codex entry in  [PhiloBiblon](https://philobiblon.cog.berkeley.edu/ui-fg/en/wiki/Welcome)
* **facsímil digital:** link to the digital facsimile of the codex when it exists
* **subcorpus:** 
*  **transcriptor:** the name of the transcriber(s)

`tabla-obras.xlsx`: contains the metadata of each of the works included in OSTA.
* **abreviatura HSMS:** alphanumeric sequence used by HSMS to identify each transcription `AXP`, `LOP5`
* **BETA manid:** registration number assigned by [PhiloBiblon](https://philobiblon.cog.berkeley.edu/ui-fg/en/wiki/Welcome) to each of the manuscripts or printed works where a work appears
* **BETA copid:** record number assigned by [PhiloBiblon](https://philobiblon.cog.berkeley.edu/ui-fg/en/wiki/Welcome) to a specific copy of a printed book
* **HSMS-ID:** codex identifier `HSMS-0003`
* **Obra ID:** work identifier `HSMS-0003-0001`
* **BETA cnum:** control number for each entry
* **Autor:** name of the author when this is known, otherwise it appears as "desconocido"
* **Traductor:** name of the translator when it is known, otherwise it appears as "desconocido"
* **Título:** general or standardized title, following the rules established in [PhiloBiblon](https://philobiblon.cog.berkeley.edu/ui-fg/en/wiki/Welcome)
* **folio:** the sequence of folios that each work occupies within the codex
* **OPDT-inicio:** original production date, corresponding to the *earliest* known or supposed date of writing of the original of each work
* **OPDT-fin:** original production date, corresponding to the *latest* known or supposed writing date of the original of each work
* **lengua-1, lengua-2:** language or languages used in a given work
* **tipo textual:** basic typology of the work, can be verse or prose
* **materia-1, materia-2, materia-3:** taxonomic classification of works by subject matter

## Transcriptions
This folder contains the semi-paleographical transcriptions.

### Metadata
At the start of each transcription there are six metadata fields:

> \{RMK: *codex identifier*.}<br>
> \{RMK: *author*.}<br>
> \{RMK: [*alphanumeric sequence used by HSMS to identify each transcription*] *tittle*.}<br>
> \{RMK: *city* | *printer* | *date of printing*.}<br>
> \{RMK: *city* | *library* | *signature*.}<br>
> \{RMK: *name of transcriptor(s)*.}

For manuscript texts, the printer field is blank

> \{RMK: HSMS-0114.}<br>
> \{RMK: Ruy González de Clavijo.}<br>
> \{RMK: [TAM] Historia del gran Tamorlán.}<br>
> \{RMK: .}<br>
> \{RMK: Madrid | Biblioteca Nacional de España | MSS/9218.}<br>
> \{RMK: Juan Luis Rodríguez Bravo, María del Mar Martínez Rodríguez.}<br>

while printed texts have information in all six

> \{RMK: HSMS-0161.}<br>
> \{RMK: desconocido.}<br>
> \{RMK: [VLT] Gran conquista de Ultramar.}<br>
> \{RMK: Salamanca | Hans Giesser | 1503.}<br>
> \{RMK: Madrid | Biblioteca Nacional de España | R/518, R/519.}<br>
> \{RMK: Ray Harris-Northall.}<br>

Additionally, before each work in a transcription, there is an metadata field with the work identifier and standardized title

> [fol. 17v]<br>
> {CB2.<br>
> con tu Paresc'er<br>
> & por en cobraria<br>
> el bjen que perdi<br>
> **{RMK: HSMS-0248-0051: En muy esquivas montañas.}** Razona<n>do ./ en tal figura<br>
> las aues /. fueron bolando<br>
> yo aprez. de vna verdura<br>
> me falle /. triste cuyda<n>do<br>
> & luego en aquella ora<br>

### HSMS tags

All paleographic transcriptions by HSMS contributors follow the method established by David Mackenzie and Kenneth Buelow in [*A Manual of Manuscript Transcription for the Dictionary of the Old Spanish Language*](http://hispanicseminary.org/docs/OSTA-manual.pdf) (1977; revised 1981, 1984, 1986, 1997), whose initial purpose was to establish the transcription standards used by the *Dictionary of the Old Spanish Language*. According to these standards, the text is transcribed line by line, respecting the layout of the text on the page and each of its elements (headings, columns, rubrics, glosses, miniatures, etc.), maintaining the spelling of the text and the system of abbreviations, and identifying the interventions (additions and deletions) of copyists and editors. To this end, a series of tags or mnemonics are used.

The computer technology available when the programs used to compile the *Dictionary of the Old Spanish Language* were developed imposed two significant limitations that affected the format of the transcriptions: the available character set and the markup language. The existing character set was US-ASCII, based on the Latin alphabet as used in modern English, which only has 128 characters available, 32 of which are non-printable, meaning that only 95 characters can actually be used.

`A`   `B`   `C`   `D`   `E`   `F`   `G`   `H`   `I`   `J`   `K`   `L`   `M`   `N`   `O`   `P`   `Q`   `R`   `S`   `T`   `U`   `V`   `W`   `X`   `Y`   `Z`

`a`   `b`   `c`   `d`   `e`   `f`   `g`   `h`   `i`   `j`   `k`   `l`   `m`   `n`   `o`   `p`   `q`   `r`   `s`   `t`   `u`   `v`   `w`   `x`   `y`   `z`

`0`   `1`   `2`   `3`   `4`   `5`   `6`   `7`   `8`   `9`

`!`   `"`   `#`   `$`   `%`   `&`   `(`   `'`   `-`   `)`   `*`   `,`   `.`   `/`   `:`   `;`   `?`   `@`   `[`   `/`   `]`   `^`   `_`   `` ` ``   `{`   `|`   `}`   `~`   `+`   `<`   `=`   `>`

Consequently, the limitations of US-ASCII forced the use of creative solutions to represent the varied spelling of medieval texts as faithfully as possible:

* c' for ç
* s' for σ
* z' for ƽ
* n~ for ñ
* h~ for ħ
* %	for ¶

As for the markup language used to encode tags, which always appear enclosed in `{ }`, it is an adaptation of IBM Generalized Markup Language (GML), which, unlike modern markup languages (HTML or XML), only differentiated opening tags, using `}` to close all of them.

The following tables list all HSMS tags that are still used today in the paleographic transcription of new texts.

### Structural Tags
|   |   |
|  --- | ---  |
|  `[fol. ]` | folio, leave of a manuscript or book, consisting of a recto and verso: `[fol. 7r]`, `[fol. 7v]`  |
|  `{HD. }` | running title, or head, often found at the top of a folio side: `{HD. LEVITICUS}`  |
|  `{CB1. }` | folio with a one column layout  |
|  `{CB2. }` | folio with a two column layout  |
|  `{RUB. }` | rubric, heading or title preceding a section of text  |
|  `{IN3.}` | initial, the numeral indicates the lines of text it spans: `{IN3.} Esos`  |
|  `{CW. }` | catchword, word or syllable placed at the end of each page, and was the same as the one with which the next page had to begin  |
|  `{SG. }` | signature,  mark consisting of letters of the alphabet or Roman numbers placed at the bottom of the front pages of sheets or quires.  |
|  `{ILL. }` | illumination, purely ornamental element without meaningful content, either textual or pictorial  |
|  `{=ILL.}`  | relation to the preceding texts  |
|  `{ILL=.}`  | relation to the following text  |
|  `{=ILL=.}`  | relation to the surrounding text  |
|  `{MIN.}`  | miniature, element with pictorial content that generally illustrates the accompanying text  |
|  `{=MIN.}`  | relation to the preceding texts  |
|  `{MIN=.}`  | relation to the following text  |
|  `{=MIN=.}`  | relation to the surrounding text  |
|  `{DIAG.}` | diagram, graphic element that complements the written text  |
|  `{=DIAG.}` | relation to the preceding texts  |
|  `{DIAG=.}`  | relation to the following text  |
|  `{=DIAG=.}`  | relation to the surrounding text  |
|  `{GL. }` | gloss, explanation of a term or passage in the text  |
|  `{AD. }` | addendum, scribal expansion of the content of the original text  |
|  `{SYMB.}` | symbol that cannot be transcribed directly  |
|  `{BLNK.}` | blank space, area intended for text was left blank in a manuscript or printed text  |
|  `{RMK: .}` | brief editorial comment on a physical or textual feature: `{RMK: folio has been cut.}`  |

### Editorial Tags
|   |   |
|  --- | ---  |
|  `[ ]` | editorial emendation: `enel ascen[den]te`  |
|  `< >` | expansion of scribal abbreviation: `q<ue>`, `cap<itu>lo`, `u<er>dad`  |
|  `<< >>` | characters appear in a raised or superscript position: `q<u><<i>>en`, `q<u><<a>>les`  |
|  `( )` | editorial deletion: `pugnicion de (de) dios`  |
|  `[^ ]`   | scribal emendation: `& [^a]matala en`, `otra [^ma]nera`  |
|  `[^#2 ]`   | scribal insertion in a non-original hand: `en la [^2#segu<n>d<a>] casa`  |
|  `(^ )`   | scribal deletion: `uini(^ni)eron`, `ymagen(^es)`  |
|  `(^#2 )`  | scribal deletion in a non-original hand: `los cauall(^2#eros)[^2#os]`  |

### Language Tags
|   |   |
|  --- | ---  |
|  `{ARB.}` | Arabic  |
|  `{ARG.}` | Aragonese (not to be used in text written in Aragonese)  |
|  `{ARM.}` | Arameic  |
|  `{BAS.}` | Basque  |
|  `{CAT.}` | Catalan  |
|  `{ENG.}` | English  |
|  `{FRN.}` | French  |
|  `{GAL.}` | Galician  |
|  `{GER.}` | German  |
|  `{GRK.}` | Greek  |
|  `{HEB.}` | Hebrew  |
|  `{ITL.}` | Italian  |
|  `{LAM.}` | Languages from America  |
|  `{LAT.}` | Latin  |
|  `{PRT.}` | Portuguese  |
|  `{PRV.}` | Provençal  |

### Special Characters
|   |   |
|  --- | ---  |
|  `\`  | precedes old folio notation included in the heading tag: `{HD. Prologo. \ 3}`  |
|  `*`  | marks reconstruction of illegible text: `[*d]esde cabo`  |
|  `$`  | the following (type) character has been editorially deleted because it was inverted in the text: `($h)[h]onrra perdida`  |
|  `[??]` | denotes the presence of *part of a word* which is illegible:: `fueron a po[??] &`  |
|  `[??]` | surrounded by a single space denotes the presence of a *full word* which is illegible: `estrellas [??]`  |
|  `[???]` | denotes the presence of a _phrase_, the combination of two or more illegible words: `[?? ???] quisieres obrar conestas estrellas [??]` |
| `\|` | denotes physical divisions separating segments of text (in a diagram, etc.) |
|  `[+]` | links a prefix to its lexical base when they are written separately in the text: `en[+]comjenda`  |
|  `+`   | used when the logical reading flow of the text contained in a tag is interrupted  |
|  `(( ))` |  double parentheses, represent the parentheses that appear in the text: `E ((lo q<ue> es peior)) muy aparejado a dar`  |
|  `%`   | calderón, ¶ , indicates divisions of text which may be akin to paragraphs  |
| `2%` | calderón two, the text which follows constitutes the concluding portion of the previous line  |
| `3%` | calderón three, the text which follows it to the end of the line constitutes the concluding portion of the following line  |

## Letter Characters
|   |   |
|  --- | ---  |
| `c'` | ç |
| `n~` | ñ |
| `h~` | ħ |
| `t'` | ţ |
| `x~ | ẍ |
| `s'` | σ |
| `S'` | Σ |
| `z'` | ϛ |
| `Z'` | Ϛ |
|  `&` | tironian note  |
|  `&'` | capital tironian note  |
|  `a@'`<br>`e@'`<br>`i@'`<br>`o@'`<br>`u@'`<br>   | acute orthographic accent: `confesso@'` confesó  |
|  ```a@` ```<br>```e@` ```<br>```i@` ```<br>```o@` ```<br>```u@` ```<br>   | grave orthographic accent: ``a@`lguno`` àlguno |
|  `a@^`<br>`e@^`<br>`i@^`<br>`o@^`<br>`u@^`<br>   | circumflex orthographic accent: `o@^` ô  |

### Contributors
Over the years, the following individuals have contributed to preparing these transcriptions.

|       |      |        |        |
|----------------|----------------|----------------|----------------|
| Aaron C. Taylor | Dwayne Carpenter | José Luis Herrero Prado | Monserrat Piera |
| Abby Connolly | Edward Baranowski | José Manuel Fradejas Rueda | Moshe Lazar |
| Abraham Quintanar | Elena Carrillo | José P. da Cruz | Nadia Lassel Sopeña |
| Aengus Ward | Enrica J. Ardemagni | Josephine Jiménez | Nancy Lea Paine |
| Águeda Rodríguez Molina | Enrique Jerez | Jsabel Berardi | Nancy Marino |
| Ahana Nagakartti | Enrique Jiménez Ríos | Juan Carlos Temprano | Naomy Zúniga |
| Alan Hastings | Eric W. Naylor | Juan Fernández Jiménez | Neus Oliver Manera |
| Alba María Fierro Vega | F. Javier Pueyo Mena | Juan Luis Rodríguez Bravo | Nick Leonard |
| Alejandra Piñeyrúa | Fabián Alejandro Campagne | Juan Pablo Rodríguez Argente del Castillo | Noemí Alonso Nicolás |
| Alicia Esperesate | Fan Bingying | Judith Zoll | Oscar Martín |
| Ally Grzybinski | Fernando Tejedo Herrero | Judy Krieger | Osvaldo Martínez-Morones |
| Álvaro Cuéllar González | Fiona Maguire | Julia Wadolkowski | Pablo Ancos García |
| Ana Belen Granados Lopera | Francisco Gago Jover | Julio F Hernando | Pablo Pastrana Pérez |
| Ana María Rodríguez Rodríguez | Francisco J. Martín | Kathryn Bares | Patricia Chacón |
| Ana María Romera Manzanares | Franklin Waltman | Katie Nossa | Patricia de Forteza |
| Ana Maroto Bueno | Fu Xiaoqiang | Kristin M. Neumayer | Patricia Giménez |
| Andrea L. Arismendi | G. Iacavano | Kristin Neumayer | Patricia Gubitosi |
| Andrea María Bau | Gabriela Castro-Barrientos | Kristin Piazza | Patricia Martínez de la Vega Mansilla |
| Andrea Redondo Nebreda | Gabriela Cerghedean | Kyle T. Kendall | Pau Cañigueral Batllosera |
| Andrea Sánchez Vicente | Gabriela Fernanda Canavese | Laura del Arroyo González | Paula Abad Jiménez |
| Andrés Enrique-Arias | Georgina Balbontin | Lauren Brinsdon | Paula Rodgers |
| Anthony J. Cárdenas | Georgina Olivetto | Lidia Ciapparelli | Phil Gericke |
| Antonio Cortijo Ocaña | Gina Gammage-Sikora | Lindsay Riordan | Polly Duxfield |
| April Flak | Gloria Cuesta | Lindsay Spallone | Porter Conerly |
| Asha Nagaraj | Gloria Martínez-Reséndiz | Lloyd A. Kasten | Priscila Ponce Jovel |
| Ashlee Holmes | Gonzalo Águila Escobar | Lluïsa Castillo Rosselló | Rachel Knighten |
| Avellana Ross | Grace Philpott | Loreto Catoira | Ray Harris-Northall |
| Avery Faires | Gracia Lozano López | Louis Cooper | Raymond G. Feilner Jr. |
| B. Zachariah | Greg Kaplan | Lourdes Laguna | Rebecca Monlague |
| Beth Markowitz | Gustavo Riva | Lucas Giarrusso | Regina Af Geijerstam |
| Borja Gama de Cossío | Harriet Goldberg | Luis de la Fuente Arranz | Reinaldo Ayerbe-Chaux |
| Brian Catlos | Harvey L. Sharrer | Lydia Carrascal Cuadrado | Ricardo Pichel |
| Carmen Sáez | Hermila E. Torres de Siegrist | Lynn M. Leazer | Robert A. MacDonald |
| Catherine Ramírez | Herminia Provencio Garrigós | Madita Rahel Klein | Robert Folger |
| Cecilia Estela Incarnato | Irene Rodríguez Cachón | Magdalena Rodríguez Beltrán | Robert G. Black |
| César Vaquero González | Isabel Acero Durantez | Manuel Ostos | Rocío Rubio Moirón |
| Charles B. Faulhaber | Isabel Zurrón | Marcela López Hernández | Rod Diman |
| Cheche Pérez de Hita | Isabella  Davis | Margaret Franzen | Rossano Dalla Valle |
| Christian Giacomini | Israel Sanz-Sánchez | Margaret Parker | Rubén Venzón |
| Christian Kusi-Obodum | Ivy A. Corfis | Margarita Ochoa | Ruth López Espinosa |
| Christina Seipelt | Michele S. de Cruz-Sáenz | María Acebes Veganzones | Ruth M. Richards |
| Cindy Abrego | J. Carnahan | María Carmen Villar | Ryan Lynch |
| Connie L. Scarborough | J. Routh | María del Carmen de la Cal | Sally Zinsner |
| Constança Prohens Rosselló | Jacqueline Martin | María del Mar Martínez Rodríguez | Samantha Vargas |
| Courtney Monahan | James B. Larkin | María Estela González de Fauve | Samuel Munguía López |
| Covadonga Arango | James R. Maedke | María Isabel Montoya Ramírez | Samuel Toledano |
| Craig Frazier | Jaqueline Martín Álvarez | María Jesús Mancho | Sara Hayes |
| Cristina González | Jason Thompson | María Jesús Sánchez | Silvia Yusta Fernández |
| Cynthia Kauffeld | Javier Coca | María Lourdes Casas | Sonia Kania |
| Cynthia Legg | Javier Rodríguez Molina | María Morrás | Stacy Bryant |
| Cynthia M. Wasick | Jeremy Jordan | María Nieves Sánchez | Stephanie Noll |
| D. Berry | Jeremy Lawrance | María Purificación Zabía | Stephen D. Johnson |
| D. Morales | Jeremy Loscheider | María Rodríguez | Steve Kirby |
| Daniel Armenti | Jerry R. Craddock | Maria San José García | Steven Hutchinson |
| Daniel Stiles | Jerry R. Rank | María Teresa Herrera | Steven R. Fondow |
| Danny Fernando Murillo | Jessi Aaron | Mariem Girgis | Sylvia Fernández |
| Darian Corona | Jessie Kielur | Mario Antonio Cossío Olavide | Terrence A. Mannetter |
| David Arbesú Fernández | Johanna Brait | Mark Littlefield | Thomas D. Spaccarelli |
| Mario Antonio Cossío Olavide | John Becker | Matt Mayers | Thomas M. Capuano |
| David G. Burton | John Beusterien | Matthew Bailey | Tracy Van Bishop |
| David J. Hildner | John Cull | Mercedes Alcalá | Vanessa Attaya |
| David Korfhagen | John Dagenais | Michael Agnew | Victoria A. Burrus |
| David Mackenzie | John Nitti | Michael L. Dangerfield | Victoria de León |
| Dawn Prince | John O'Neill | Michael R. Solomon | Victoria García-Serrano |
| Dayle Seidenspinner-Núñez | John S. Geary | Michel Garcia | Wilhelmina Jonxis-Henkemans |
| Déborah Dietrick Smithbauer | John Zemke | Miguel Torrens | William Palmer |
| Dennis Seniff | Jonathan Burgoyne | Mikel Valladares | Zhao Zhili |
| Derek Carr | Jordan Robbins | Mirta Alejandra Balestra | Zoraida Sánchez |
| Dolores Juan Moreno | Jorge Sastre | Molly Kerrigan |  |
| Dorothy S. Severin | José Antonio Oliver Marroig | Monica Zborowski |
