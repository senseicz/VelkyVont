# Plán: Vodní cesta

Velký příběh, do kterého **organicky doroste** stávající dobrodružství *Slepé rameno*
(29 uzlů ve Stínadlech). Stávající hra přestává být samostatnou kapitolou a stává se
**prostředkem** příběhu — sedmou kapitolou, kterou hráč objeví až po tom, co už zná
kus trasy.

---

## 0. Rozhodnutí, která jsou daná

| Otázka | Rozhodnutí |
|---|---|
| Voda v kanále | **Kanál je plný a voda protéká volně.** Mezi zdymadly ji drží v klidu, za nimi prudce táhne. |
| Začátek | **Zapomenutý vtok**, ne zavřený. Mříž nad ním je lapač náplavek, vodě nevadí. |
| Mříž | Nikdo ji nezavíral a nikoho nezajímá. Hledá se **samotný vtok**, který z nábřeží není vidět. |
| Otázka příběhu | Ne *odkud*, ale **kudy a kam**. Odkud je jasné — z hlavní řeky. |
| Plavání | Jarek **umí plavat**. Spadnutí do vody není konec hry, ale ztráta času, mokré šaty, výčitka, někdy odvedení dospělými. |
| Konec „běžný kluk“ | **Úplně na začátku** — jako volba „nezačít“ a tři uzly rozmyšlení. |
| Tajemná postava | **Krátká vedlejší cesta v uhelném dvoře**, bez vlivu na výsledek, s jednou odpovědí navíc. |
| Inventář | **15 položek**, část věcí a znalostí sloučena do jedné položky. |
| Výbava | **Není jedna položka.** Lampa, baterie, provaz a křída se shánějí zvlášť; kompletní výbava je podmínkou prvního vstupu do tunelu. |
| Světlo | **Bateriová svítilna**, ne svíčka. Svíčka je do podzemí nevhodná. |
| Muž v tmavém kabátě | **Ta samá osoba** jako neoznačený pomocník v uhelném dvoře. |
| Smůla dne | Volitelná kapitola se dá přeskočit. Jádrová kapitola má opakovatelný rozhodující úsek. |
| Název dobrodružství | **Vodní cesta** (`velky-vont-vodni-cesta`) — neprozradí předem, co hráč objeví |
| Hrdina | **Jarek** |
| Kamarád ze třídy | **Lukáš** (Bílé domy) |
| Pomocníci | **Oba** — Ema „Špunt“ uvnitř Stínadel, Lukáš venku. Každý drží jednu stranu. |

## 1. Fyzická trasa kanálu

```
řeka ──▶ VPUŠŤ (zapomenutý vtok, pod nábřežím, mimo Stínadla)
      ──▶ HORNÍ ZDYMADLO
      ──▶ úsek pod Rozdělovací třídou (volný průchod, o kterém se neví)
      ──▶ STÍNADLA (pod domy a dvory)          ← tady žije stávající dobrodružství
      ──▶ DOLNÍ ZDYMADLO
      ──▶ UHELNÝ DVŮR A TEPLÁRNA             ← budoucí samostatné dobrodružství
      ──▶ SPLAV → hraniční potok → řeka
```

Příběh postupuje **od nejbližšího místa k nejvzdálenějšímu**: od okna, přes cizí dvůr
a dolní konec, ven ze Stínadel, až k zapomenutému vtoku u řeky. Stínadla přitom přijdou
až poté, co už hráč umí jít po kanálu — současný graf tak přestává být „první kapitolou“,
ale zůstává použitelný v podstatě beze změny.

## 2. Duch příběhu

> Touha **zmapovat věc, na kterou se zapomnělo**.

Odkud voda přichází, nikdo nerozporuje — je to hlavní řeka. Neznámé je to, jakou
cestou prochází pod městem, kde se láme a kam odtéká, a kdo o tom kdysi rozhodl.
Jarek nemá odznak ani kroniku. Má tužku, čas po vyučování a prázdná Stínadla.

## 3. Úvod a volba „nezačít“

Úvod jsou tři uzly (okno, škola a Lukáš, večer a zákaz rodičů) a pak **rozcestník startu**,
který nabízí čtyři možnosti:

1. vstoupit do cizího dvora,
2. jít po proudu od splavu,
3. vyrazit s Lukášem ven za Rozdělovací třídu,
4. **nezačít** — jen si říct, že je pozdě.

Volba 4 vede přes tři uzly (`nic-1`, `nic-2`, `nic-3`), kde se Jarek postupně ptá sám
sebe, co vlastně chce, a pokaždé mu nabídka znovu přiblíží — a také možnost zůstat
doma. Když ji odmítne i potřetí, končí hráč v konci **„Běžný chlapec“** (viz §7).
Když ji v kterémkoli uzlu přijme, vstupuje do rozcestníku dní jako obvykle. Tak je
konec dostupný během tří kliknutí, ale není zkrácen — a čtenář si ho musí vybrat.

## 4. Struktura: večerní rozcestník

Dny nejsou seřazené. Jarek si zapisuje do mapy a každý večer vybírá, kam jít zítra.
Tím vzniká volitelnost kapitol i možnost pátrání ukončit kdykoliv — a žádná kapitola
nemůže hráče uvěznit.

```
ÚVOD (3 uzly) → ROZCESTNÍK STARTU → ROZCESTNÍK ⇄ K1 … K9
                                            ⇄ denní zápis (8x)
                                            └─> BILANCE → konce
```

### Kapitoly a uzly

| # | Kapitola | Uzly | Typ | Jádro |
|---|---|---|---|---|
| Úvod | Okno, škola, večer | 3 | — | zvuk, který neodpovídá tomu, co vidí; zákaz rodičů; Lukáš jako zároděk |
| — | Rozcestník startu + volba „nezačít“ | 1 + 3 | — | konec „Běžný kluk“ je dostupný od první minuty |
| K0 | **Výbava** | 6 | jádro | provaz v Provaznické, baterie u Lukáše, křída v Kotlách — kompletace výbavy před prvním vstupem |
| K1 | **Za cizím dvorem** | 5 | jádro | první vstup do kanálu; proud, hloubka, první setkání s vodou |
| K2 | **Splav a hraniční potok** | 7 | jádro | dolní konec kanálu, výjezd za hranici okrsku, zjištění, že voda u Stínadel *končí*, ne začíná |
| K3 | **Třída a Lukáš** | 3 | odbočka | co se venku říká o kanálu, a že je někdo, kdo s tebou půjde — pomocník venku |
| K4 | **Vetešník** | 4 | jádro | kdo plavbu pamatuje, co se dá koupit |
| K5 | **Dolní zdymadlo** | 6 | jádro | první logická hádanka; komora, vrata, pořadí kroků |
| K6 | **Uhelný dvůr a teplárna** | 9 | **volitelná** | velký industriální prostor, zatopená vykládka, vedlejší cesta s tajemnou postavou |
| K7 | **Stínadla** | 29 | jádro | **stávající dobrodružství**, vložené sem — Ema jako pomocnice uvnitř |
| K8 | **Horní zdymadlo** | 5 | jádro | druhá hádanka, jiný typ závory |
| K9 | **Vpusť u řeky** | 5 | jádro | zapomenutý vtok; kruh se zavírá |
| — | **Bilance** | 1 | — | volba konce |

Nových uzlů: **~54**, přebratých: 29, celkem ~83 (po přesunu úvodu z grafů).

### Kam stávající 29 uzlů sedne

Prose se přepíše, struktura (graf, dice, inventář) zůstane:

- „stoka“ → **kanál**; zvuk pod podlahou je zpočátku chápán jako voda v zemi, ne jako
  plavební kanál — to je objev, ne předpoklad.
- Suché římsy a „suchý přepad“ musí respektovat, že **voda proudí**: ledny jsou
  úzké a nad hladinou, propusti částečně zatopené, hladina po dešti mění hloubku.
- `vodocet` (vodopád) zůstává — přepad přes práh mezi dvěma hladinami.
- `hranice-*` (hraniční kámen) zůstává, ale zjištění se mění: **za hranicí Stínadel kanál
  pokračuje**, nejde o slepé rameno řeky.
- Končící uzly `slepe-rameno` / `castecny-konec` / `mapa-konec` se přemění na **denní
  zápis** K7 (vedou zpět do rozcestníku). `zakaz-konec` zůstává jediným opravdu
  konečným koncem dne.

## 4b. K0 — Výbava: čtyři předměty, které musí opatřit

Kompletní výbava je **podmínkou prvního vstupu do tunelu**. Hráč si ji musí poskládat
z různých míst, protože doma má jen část:

| Předmět | Kde ho Jarek sežene | Proč |
|---|---|---|
| `lampa` — bateriová svítilna | **doma**, v šuplíku | Zdědil ji, ale nikdo ji nepoužíval. |
| `baterie` — náhradní baterie | **u Lukáše ve škole** (K3) | Školní sklad, nebo Lukášovo přání vyměnit za službu. |
| `provaz` | **v Provaznické** (vlastní uzel) | Musí se poptat, což je první malá společenská daň za to, že jde sám. |
| `kreda` | **v Kotlách** (vlastní uzel) | Kotly jsou v kánonu zdrojem křídy, nářadí a spojenců. |

Každý z těch uzlů je malý obchod nebo prosba, ne podnikání. Hráč si tak před prvním
vstupem **třikrát promyslí, koho na to potřebuje** — což je zároveň úvod do světa,
v němž se všechno dělá přes lidi.

Křída je součástí výbavy ne náhodou: bez ní nelze vstoupit do tunelu, ze kterého se
člověk musí vrátit ve tmě a bezpečně najít cestou ven. Je to pravidlo příběhu, ne
požadavek na hráčovu přípravu.

### Gate a jeho obejití

Vstup do tunelu v K1 má `requires: ["lampa", "baterie", "provaz", "kreda"]`. Když něco
chybí, panel ukáže přesně co („Chybí: Provaz“), a rozcestník zůstává nedosažený jen
do té doby, ne do mrtvola — hráč má kam jít.

**Osobní vstup — jeden uzel a zpět.** Jarek může do tunelu vlézt i bez vybavení. Vchází
v noci, potichu a zadním dvorem, právě proto, že s výbavou by ho slyšel. To je první
ochutnání zákazu rodičů: jde se z něj ven potichu.

Následuje **jeden jediný uzel** a v něm **povinná volba zpět**. Ne hod, ne pohroma,
ne konec: v okamžiku, kdy voda dojde po pas a zvuk zhasne, Jarek sám pochopí,
že bez světla nemá kam dojít a bez provazu se nevrátí, a vyleze ven. Uzel nic
neuděluje, neodebírá a nepřidává — jen ho vrátí do rozcestníku s vědomím, že to tak
jde. Je to lekce, ne cena.

Volba z rozcestníku zní: **„V noci zadním dvorem, potichu, bez vybavení“**. Je vidět
vždy, i s kompletní výbavou — a to je v pořádku: kdo má všechno, v této volbě prostě
nechá vybavení doma, aby nebyl slyšet. Uzel pak funguje pro všechny stejně a nemusí
řešit, kdo už je připravený a kdo ne.

**Svíčka ne.** Místo svíčky je ve výbavě bateriová svítilna. Svíčka do podzemí
neslouží, a baterie je konečná: rozsvícená baterie je zdroj světla, který někdy
dojde. Když dojde, je to ticho, tma a okamžitá volba — ne konec dne.

## 5. Vedlejší cesta v K6 (poslední Velký Vont)

V uhelném dvoře pracuje na něčem **poslední Velký Vont** — Jarek o tom neví a nesmí
se to dozvědět. Nejde o spojence, pomocníka ani pomoc. Postava přijde na Jarka dřív,
než Jarek dojde k ní, a nabídne výměnu: pomůže jí s tím, co umí (voda, úzký prolaz,
něco, co se dá udělat ve dvou), a ona mu za to odpoví na **jednu otázku**.

Struktura — **5 uzlů** (počet lze při psaní ještě upravit):

- `k6-1` **setkání** — postava je tady dřív, než dojde Jarek.
- `k6-2` **podmínka výměny** — co chce, než řekne jednu věc.
- `k6-3` **první pomoc** — cesta, kterou by sám nešel; tady se Jarek potopí nebo
  dostane strach z výšky a vůbec se nepozná pořadí.
- `k6-4` **druhá pomoc** — něco, co by sám nezvládl, například voda, kterou nepustí.
- `k6-5` **loučení** — pět otázek, odpověď na jednu.

Pravidla:

- **Bez vlivu na výsledek hlavního pátrání.** K6 jde projít i bez ní; vedlejší cesta
  se dá přeskočit.
- **Jedna odpověď, podle volby hráče.** V `k6-5` je pět možností, každá je jiná
  otázka, a **všechny pět jsou otevřené otázky z `world.md`**, aby odpověď nemohla
  být vymyšlená:

  1. Kdo byl poslední Velký Vont?
  2. Otevře nově vypilovaný odznak zámek Kronik?
  3. Co přesně znamená západní znamení na trati?
  4. Byl závěsník zdymadla členem Vontů?
  5. Kdo držel plavební řád, když ještě platil?

  Postava odpoví **jen na jednu** a řekne, že řekla, co věděla. Když se Jarek zeptá
  na druhou, slyší: *„Jednou jsem řekl, co jsem věděl.“* — a musí odejít. Čtyři z pěti
  otázek zůstanou v této hře nezodpovězené, i když o nich hráč přemýšlel.
- **Odpověď nesmí nic vyřešit.** Ani ta nejlepší odpověď neodemkne Zákaz Kronik, neprokáže
  kdo byl Velký Vont a nezmění žádný konec. Je to jediné místo, kde hráč dostane
  informaci, kterou jinde v příběhu nedostane.

Totožnost postavy se ve světě nerozhoduje (viz `world.md`, Open questions). **Je to ale
ta samá osoba** — muž v tmavém kabátě z K7. Dvě kapitoly, dvě podoby, žádná jistota,
a ani jedno setkání ho neprozradí.

**Podmínka pořadí:** protože hráč vybírá dny libovolně, obě setkání musí fungovat
v obou pořadích. Postava se nesmí divit, že Jarka už potkal, ani připomínat první
setkání. Při druhé otázce řekne „Jednou jsem řekl, co jsem věděl.“ — ať přišel
odkud přišel. Postava je ve všech uzlech popsána stejně: tmavý kabát, žádné jméno.

## 6. Inventář: 15 položek

Výbava a znalosti se slučují, aby panel zůstal přehledný. Přesuny proti dnešní verzi
(`adventure.json` má 15) a proti plánu (+9) jsou vyznačeny:

| # | Klíč | Název | Počet z čeho |
|---|---|---|---|
| 1 | `mapa` | Rozkreslená mapa | sbírá průběžně: pohled z okna, zvuk pod mostem, Stínadla, hranice |
| 2 | `lampa` | Bateriová svítilna | doma, ve šuplíku |
| 3 | `baterie` | Náhradní baterie | u Lukáše ve škole (K3) |
| 4 | `provaz` | Provaz | v Provaznické, vlastní uzel |
| 5 | `kreda` | Modrá křída | v Kotlách, vlastní uzel |
| 6 | `pruchody` | Průchody, o kterých se neví | suchá krysa stola + sklepní obchvat |
| 7 | `doklady` | Co se dá ukázat | opis hraničního kamene + vzorek říčního písku + tři vlnovky |
| 8 | `denik-zavesnika` | Závěsníkův deník | — |
| 9 | `kredova-znacka` | Cizí modrá značka | — |
| 10 | `vetechnik-balicek` | Klíč, lístek a tyč od Vetešníka | klíč + pořadí + tyč v jednom |
| 11 | `vpust` | Vpusť u řeky | závěrečný bod |
| 12 | `splav` | Splav a hraniční potok | závěrečný bod |
| 13 | `vysoky` | Výhled shora | strach z výšek — k vypočtení, že to zvládne |
| 14 | `svědctvi-emy` | Emino svědectví | stojí za tebe u rodičů a u domovníka |
| 15 | `svědctvi-lukase` | Lukášovo svědectví | stojí za tebe venku, kde se dospělí neptají |

Výbava **zůstává rozdělená** na čtyři položky (`lampa`, `baterie`, `provaz`, `kreda`),
protože právě jejich opatření je hlavní herní hodnotou první třetiny příběhu: každý je
z jiného místa a jiného člověka. Sloučení výbavy do jedné položky by tento účel zničilo.
Ušetřeno jinde: `doklady` spojuje tři důkazy (hraniční kámen, říční písek, vlnovky)
do jediné položky, protože všechny tři slouží té samé funkci — dát je na stůl.
Zrušeno: `chleb`, `svoleni`, `sucha-stola`, `sklepni-obchvat`, `neznamy-clovek`,
`sirky`, `svicka`. `chleb` a `svoleni` jediné dvě věci, které se úplně ztratí.

Svědectví jsou **dvě položky, ne jedna**, protože `requires` umí jen AND — a protože
je to thematicky důležité: Ema je případ pro dnešní pravidlo 12, Lukáš pro to opačné.

## 7. Končná uzlárna `bilance` a konec „běžný kluk“

Konec je volba s `requires`, takže hráč dostane vědět, co mu chybí, ale nikdy nezůstane
uvězněný — vždy je tu i „Jít zítra zase“.

| Konec | Podmínka |
|---|---|
| **Celá trasa** | `mapa` + `vpust` + `splav` |
| **Mapa předaná — po stínadelsku** | `mapa` + `svědctvi-emy` |
| **Mapa předaná — přes Rozdělovací** | `mapa` + `svědctvi-lukase` |
| **Vyplavený** | dostane ho při ztrátě ve vodě, ne jako volbu |
| **Konec — Voda za hranicí** | `hranicni-kamen` |
| **Konec — Mapa podzemní vody** | `mapa` |
| **Běžný chlapec** | není v `bilance` — je na začátku, viz §3 |

„Mapa předaná“ existuje ve dvou verzích a obě jsou správné: mapa, která zůstane
ve Stínadlech, a mapa, která přejde přes Rozdělovací třídu. Dobrodružství tím neříká,
které pravidlo 12 je původní — říká jen, koho Jarek potřeboval, když byl sám.
| **Zákaz** | jen při vědomém porušení zákazu rodičů |

## 8. Opakování: smůla dne

| Kapitola | Co když to nevyjde |
|---|---|
| volitelná (K3, K6) | Dá se přeskočit, vrátit se později nebo jít jinudy. |
| jádrová (K1, K2, K5, K7, K8, K9) | Den se **nezapočte** — žádný denní zápis, žádná položka. Hráč se vrací do rozcestníku a kapitolu zkusí znovu. |

Opakování je **rozumně omezené**: opakuje se jen rozhodující úsek kapitoly (dvě až
tři uzly), ne celý den od začátku. Každý nezdařený pokus má jinou variantu (třetí
pokus je už jiný, horší — pozdě večer, tma, rodiče si všimli), a po dvou neúspěších
zůstane jen možnost jít jinudy nebo odejít. Něco vyjde na první dobrou, něco ne.

**Strach jako způsob selhání.** Nejčastější „nevyjde“ není hod, ale zastavení. Jarek
se v konkrétním místě v den D zve (výška pod železnou lávkou, tma v zatopené štole,
hlasitá komora) dostane do uzlu, kde je jediná volba **„Dnes ne“**. Až příště — s
`vysoky` nebo s odvahou — je tam uzel znovu a volba je „Zkusit to“. Výška je
jediné místo, kde se podmínka dá číst jako *postup*, ne jako *hod*.

## 9. Rozdělení souborů

```
adventure.json                    (metadata, labels, inventory, úvod, rozcestníky, bilance)
chapters/uvod-a-kanal.json        (K1–K2)
chapters/kanal-vnitr-mesto.json   (K3–K5)
chapters/kanal-teplarna.json      (K6)
chapters/kanal-stinadla.json      (K7 — stávající 29 uzlů)
chapters/kanal-vtok.json          (K8–K9)
```

Node keys musí být unikátní napříč soubory; runtime kapitoly sloučí při startu
a validuje *sloučené* dobrodružství.

## 10. Otevřené rozhodnutí

V této session je uzavřeno vše: pět uzlů vedlejší cesty, jeden uzel a povinná volba
zpět při vstupu bez výbavy. Zbývá jen doladit přesný počet a pořadí uzlů při psaní, když
se ukáže, že některý potřebuje místo navíc.

## 11. Stav dopsaného

### Hotovo

| Uzly | Obsah |
|---|---|
| `intro` (titulní stránka) | tři stránky, 903 slov — okno, škola a Lukáš, večer a zákaz. Už to není uzel, běží to jako průvodní próza nad tlačítkem Začít. |
| `rozcestnik-start` | čtyři volby, z toho gate do tunelu s `requires` a volba „nezačít“ |
| `nic-1`, `nic-2`, `nic-3`, `kino` | větev „běžný chlapec“ — tři uzly rozmyšlení a konec |
| `vstup-po-temu` | jeden uzel, povinná volba zpět, nic neuděluje |
| `k0-1`, `k0-hotovo` + 3x4 uzly poběhů | K0 výbava (14 uzlů) — provaz, křída, baterie (každý má výchozí uzel + čistý úspěch, úspěch s prací/závazkem a neúspěch s nutností opakovat) |
| `k0-hotovo` | kompletace a první rozhodnutí |
| `k1-1`, `k1-voda`, `k1-2b`, `k1-3`, `k1-4` | K1 — první vstup, první hod, první zjištění |
| `rozcestnik` | denní rozcestník (zatím jen dvě volby) |

### Dočasné stavy, které je potřeba spravit při pokračování

1. **`rozcestnik` má dvě volby.** Ostatní kapitoly se přidají, až budou napsané; do té
   doby je hra hratelná jen přes K7.
2. ~~**Uzly K7 nejsou přepsané.**~~ Hotovo — viz §13.
4. **K0 rozpadnuto na podkroky (14 uzlů)**: každý ze tří poběhů má výchozí uzel
   s volbou přístupu a tři samostatné vyúsťující uzly (čistý úspěch, úspěch s prací/závazkem
   a neúspěch s nutností opakovat). Tím volby nejsou jen kosmetické a hráč může selhat.
5. **`rozcestnik` má čtyři volby** (K1, K2, K3, K7); další přibydou s kapitolami.
6. **Soubor nerozdělený na kapitoly.** Rozdělení do `chapters/` je mechanická úloha na
   závěr; dělat ho teď by zbytečně zvětšilo každou další dávku.
5. **`requires` v K7 fungují i s novými klíči** (`lampa`, `provaz`, `kreda`) — ty teď
   pocházejí z K0, takže větve „bez výbavy“ zůstávají konzistentní.

### Nové schéma runtime (2026-09)

Runtime má `grant` i na volbách, `remove` na uzlech i volbách a `requiresAny` (OR).
V tomto dobrodružství se použije hned:

- K0: původně zredukováno na 4 uzly, následně rozepsáno do plnohodnotných 14 uzlů
  s podkroky (každá varianta má vlastní text i důsledky) a možností selhání.
- Vedlejší cesta v K6: pět voleb v jednom uzlu, každá dá jinou znalost a všechny vedou
  do téhož uzlu loučení. Bez `option.grant` by to vyžadovalo pět sourozenců.
- Ztráty: baterie, která dojde, je `node.remove`; provaz, který zůstane u zámku, je
  `option.remove`.
- `requiresAny` pro branu do K1 se zatím nepotřebuje (výbava je AND), ale přijde
  v den, kdy bude potřeba „svítilna **nebo** provaz“.

## 12. Prolog na titulní stránce

Runtime má nové pole `intro` — próza nad tlačítkem „Začít“, ve stejném markdownu jako text
uzlu a ve vlastním scrollovacím rámci, takže délka je bezpečná. Třístránkový úvod už není
první uzlem: sedí v `adventure.json` jako `intro` a prvním uzlem je `rozcestnik-start`, který
přebírá odměny prvních dvou uzlů (`lampa`, `mapa`).

Co tím zbylo z úvodu v grafu: nic. Volba „zeptat se ještě jednou, kdo ten zákaz zavedl“
zůstala jako věta v próze (otec to neřekl, nikdo to neřekl), protože v titulní stránce nejsou
volby a nepatří tam.

### Zbývá do úprav

1. **Názvy konců v K7** — uzel `slepe-rameno` má v textu „Nejlepší konec — Slepé rameno“.
   To je jméno objevu ze starého kánonu a po přepisu K7 (plavební kanál, ne slepé rameno
   řeky) neobstojí.
2. **`author`** v `adventure.json` je prázdný.

### K2 a K3 (dopsáno)

- **K2 — 7 uzlů** `k2-1` ulice nad kanalem → `k2-2` u vody → (`k2-voda` vplavat do proudu)
  → `k2-3` splav → `k2-4` rampa a nezastavěná krajina → `k2-5` návrat (hod) →
  (`k2-vytopeny`) → `k2-6` zápis, *grant: `splav`*. Jádrová, vstup z rozcestníku stačí
  `lampa` — ostatní věci nepotřebuje, jde po ulici a po kamenech.
- **K3 — 3 uzly** `k3-1` pondělí ve třídě → `k3-2` přestávka s Lukášem → `k3-3` plán.
  Odbočka: nic neuděluje, ale odemyká možnost vzít si ho s sebou později.
- **Zjištění K2 je záporné a to je schválené**: voda u Stínadel *odtéká*, takže odpověď
  leží proti proudu. Bez toho by plavba dolů byla jen další stejná kapitola.

## 13. K7 přepsáno do kanonu

Graf K7 zůstal stejný (29 uzlů), změnil se text, hrany a to, kam vedou selhání.

### Co se změnilo v logice

| Bylo | Je |
|---|---|
| Hod na úzké římse v `krysy` → konečný Zákaz | Hod (1–3) → `zakaz-mapa`, tedy *chycení*, ne konec hry. **Konečný Zákaz je teď jen za úmyslné porušení zákazu rodičů** — tedy když z něj po chycení řekneš „tajně vyjdu ještě téže noci“ nebo v noci bez vědomí dospělých. |
| Šachta v `soutok-pripraveny` → `zakaz-ema` (kde stojí Ema) | → `zakaz-mapa`. `zakaz-ema` je teď jen pro cestu, kde je Ema skutečně s tebou. |
| `slepe-rameno`, `castecny-konec`, `mapa-konec` jako konce | **Denní zápisy** — koncový je, že mají jednu volbu zpět do rozcestníku. Každý popisuje, co ten den přinesl, ne že tím příběh končí. |
| `priprava` = „jít domů pro výbavu“ | **Večer doma** — rodiče, stará věc o zákazu, mapa na stole jako důkaz, a volba: říct pravdu / spát / vyjít v noci. |
| `pripraven-sam` = „vzít lampu a provaz, jít sám“ | **Vyjít v noci, nikomu neříct** — totéž, co porušení zákazu. |
| `svědctvi-emy` udělováno v `druha-vyprava` | Uděluje se v `zakaz-ema`, tedy když tě opravdu zastaví spolu s Emou a ona dosvědčí. Když jdeš sám, svědectví nemáš. |

### Co se změnilo v kánonu textu

- „stoka“ → plavební kanál. Soutok pod Barvířským náměstíčkem je teď místo, kde se
  kanály **sbíhají**, ne místo, kde někdo vodu sevřel.
- Voda **proudí a je v ní zvuk**: krysy u římsy, kamenné stupnice s čárkami výšek, které
  psal někdo s tužkou při napouštění, a opakované zazdívání, protože „voda tady byla dřív
  než cihly“.
- Hraniční kámen: místo zjištění „slepé rameno řeky“ nyní říká, že **kanál pokračuje ven
  z čtvrti proti proudu, směrem k řece**, a že nikdo ho nepřestěhoval, někdo jen přestal
  stavět. To je most k K9.
- Záporné zjištění má v plánu funkci i v K7: za kamenem je *začátek otázky*, ne její konec.
- `zamceny-dvur`: nejde už o „řeku blízko“ (kánon to nepotvrzuje), ale o jistotu, že voda
  jde z řeky a že proti proudu je k ní blíž.
- `slepe-rameno` jako zápis objevuje **kamenné ústí s háky a lávkami** — stejné, na které
  Jarek narazil v K2 u hraničního potoka. Dvě kapitoly se potkají na jednom místě.
- Nově: `vodocet` (čárky výšek, zazdívali dvakrát), `cizi-podzemi` (hnědá čára = bývalá
  hladina), `ricni-mriz` (hlasitý kanál = cesta zpátky do města).
- Zákaz rodičů je **stávající**, ne následek. Chycení už není začátek zákazu, ale
  zveřejnění zákazu: „zákaz tu byl dřív, teď má jméno a datum“.
- `druha-vyprava` používá **slovo** z kánonu světa: podmínka, kterou otec vysloví jednou.

## 14. Příběh dopsán celý

| Kapitola | Uzly | Stav |
|---|---|---|
| Úvod | `intro` (titulní stránka, 903 slov) | hotovo |
| Rozcestník startu + „nezačít“ | 1 + 3 + `kino` | hotovo |
| K0 Výbava | 14 | hotovo — rozpadnuto na podkroky (3 poběhy po 4 uzlech + `k0-1` + `k0-hotovo`) |
| K1 Za cizím dvorem | 5 | hotovo |
| K2 Splav a hraniční potok | 7 | hotovo |
| K3 Třída a Lukáš | 3 | hotovo |
| K4 Vetešník | 9 | hotovo — cena je bedna, kterou nese přes Rozdělovací za svou tvář |
| K5 Dolní zdymadlo | 9 | hotovo — pořadí kroků + lístek od Vetešníka jako zkratka |
| K6 Uhelný dvůr | 19 | hotovo — vedlejší cesta `k6-6`…`k6-9d` + 5 uzlů s odpověďmi |
| K7 Stínadla | 29 | hotovo (§13) |
| K8 Horní zdymadlo | 10 | hotovo — jiné vrata (zavírají se samy) + zátka a propust |
| K9 Vpusť | 8 | hotovo — poslední díl, kámen v otvoru, chlapec s kamínky |
| Bilance + konce | 6 | hotovo — 5 konců podle `requires` |
| **Celkem** | **136 uzlů, ~20 500 slov, 7 konců** | |

### Co se při psaní rozhodlo samo

1. **K9 nevzniklo jako „poslední kapitola“, ale jako odpověď na otázku z K2.** V K2
   zjistil, že voda u Stínadel odtéká, a tím se otázka posunula proti proudu. K9 je
   poslední díl, ne hledání začátku.
2. **K8 má jiná vrata než K5.** K5 se otevírají tahem a potřebují pořadí, K8 se zavírají
   sama při vysoké vodě a potřebují poznat, co je voda a co závora. Dva různí závěsníci.
3. **Vedlejší cesta má pět uzlů plus pět uzlů s odpověďmi**, ne pět položek v katalogu.
   Statický popis položky se nedá přizpůsobit tomu, kterou otázku hráč položil, takže
   každá odpověď dostala vlastní uzel. Katalog zůstává na 15.
4. **K4 stojí mimo plavbu** — Vetešník neprodává klíče, prodává znalosti, a jeho cena je
   morální (tvář na Rozdělovací), ne finanční. Balíček (`vetechnik-balicek`) odemyká
   K5, K6 a je zkratkou v hádance K5.

### Zbývá

- Rozdělení na `chapters/` (mechanická úloha, §9).
- Průchod celou hrou v prohlížeči.
- `author` je pořád prázdný.
