# Velký Vont — pravidla a mechaniky

Konkrétní systémy. Příběh v [`pribeh.md`](pribeh.md), koncepce
v [`koncept-hry.md`](koncept-hry.md).

> **Stav dokumentu:** pracovní návrh. **Všechna čísla jsou první nástřel** určený k ladění,
> nikoli vyvážené hodnoty — jsou shromážděná v [§ 13](#13-čísla-k-vyladění).
> [§ 11 Zámek Kronik](#11-zámek-kronik) obsahuje nerozhodnutou otázku, na které závisí
> vyváženost celé druhé poloviny hry.

---

## 1. Slovník

| Pojem | Význam |
|---|---|
| **Večer** | jeden tah strategické vrstvy |
| **Okrsek** | území na strategické mapě; každý drží jeden odznak-klíč |
| **Odznak** | ručně vypilovaný mosazný plíšek se zářezem; jméno, měna i zub klíče |
| **Respekt** | měkký vliv, hlavní „měna" hry; má hodnotu globální i po okrscích |
| **Slovo** | dané slib s mechanickou vazbou; porušení je nejdražší akce ve hře |
| **Křída** | spotřební materiál na značky a zprávy |
| **Průchod** | známá zkratka domem, sklepem nebo přes střechu |
| **Značka** | křídový záznam na zdi; nese pravdivou informaci od začátku hry |
| **Šarvátka** | taktický nesmrtící konflikt |
| **Chytačka** | tichá bezalarmová neutralizace jedné osoby |
| **Klání** | soutěž místo boje: cesta k vlivu bez konfliktu |
| **Rejd** | sněm okrsků; politické potvrzení, nikoli mechanický klíč |
| **Gramotnost** | stupeň schopnosti čist (a nakonec psát) značky |

---

## 2. Odznaky

Nejdůležitější předmět ve hře, protože plní **tři funkce naráz.**

### Anatomie

- Mosazný kotouček velikosti dvouhaléře, **ručně vypilovaný svým nositelem.**
- Na hraně jeden nepravidelný hluboký **zářez ve tvaru zubu klíče.**
- Na zadní straně **jehlou vyryté číslo.** Nižší číslo = dřívější vstup do hnutí = seniorita.
- **Žádné dva zářezy nejsou stejné.** Z toho plyne všechno ostatní.

### Tři funkce

1. **Identita.** Číslo je zapsané v Kronikách. Odznak je jméno v předmětné podobě.
2. **Měna.** Odznaky lze držet, zabavovat, vracet, prodávat a — pravidlem 28 — držet jen
   tehdy, když na to má držitel dost Respektu.
3. **Zub klíče.** Zámek truhly s Kronikami potřebuje několik odznaků současně, po jednom
   z každého okrsku. Viz [§ 11](#11-zámek-kronik).

### Získání a ztráta

| Akce | Efekt |
|---|---|
| Vypilování vlastního | jediný legální způsob, jak nový Vont odznak *získá* (pravidlo 23). Nový zářez ale není v Kronikách zapsaný → [§ 11](#11-zámek-kronik) |
| Zabavení v šarvátce | přechází na vítěze; drží ho, dokud má Respekt (pravidlo 28) |
| Vrácení odznaku | +Respekt, −taktická výhoda; klíčové gesto tradiční cesty |
| Prodej Vetešníkovi | rychlý zdroj prostředků, velká ztráta Respektu, riziko že odznak byl klíč |
| Ztráta bez zajetí | postava přestává být plnohodnotný Vont, dokud si to nevyřeší — *„soft permadeath identity"*, nikdy těla |

### Pečeť na dopise

Kapka vosku pod dopisem posledního Velkého Vonta nese **konkrétní zářez**. Hledání totožnosti
je proto mechanicky **párování předmětu**, ne dialogová hádanka: hráč musí získat do ruky
dost odznaků, aby na ten správný narazil. Až spárováním se otevře stopa k Ježkovi.

---

## 3. Zdroje

Žádné zlato. Pět zdrojů, každý s jinou povahou.

| Zdroj | Typ | Získává se | Utrácí se za |
|---|---|---|---|
| **Respekt** | plynulý, globální + per okrsek | výhra v klání, čestné vítězství, dodržené Slovo, vrácený odznak | nábor, vyjednávání, držení zabavených odznaků, prosazení návrhu na rejdu |
| **Slovo** | diskrétní seznam závazků, ne bodů | nedá se získat — hráč má omezený počet slibů, které smí rozdat | zajištění spolupráce okrsku **teď** za cenu závazku **později** |
| **Křída** | spotřební | Kotly, obchod, nálezy | značení průchodů (trvalý zápis do mapy), zprávy, přepsání či smazání cizí značky |
| **Průchody** | trvalé odemčení | průzkum, obsazení okrsku, výkup informací | nic — jen zkracují pohyb a otevírají obchvaty v taktice |
| **Odznaky** | předměty | viz [§ 2](#2-odznaky) | zámek Kronik, prokázání se, obchod (drahé morálně) |

**Slovo je nejzajímavější zdroj a chce nejvíc ladit.** Návrh: hráč má na celou kampaň
omezený počet Slov (nástřel: 5). Dané Slovo je zapsané v UI jako konkrétní věta („Bílé domy
mezi nás nepustím"). Jeho porušení je jediná akce ve hře, která **plošně srazí Respekt ve
všech okrscích** a trvale zavře některé konce. Dopis pod ginkgem to zdůvodňuje: *„nedá se to
udělat lží ani strachem."*

---

## 4. Strategická vrstva

### Struktura večera

1. **Události** — co se stalo od minule (hlídka zabavila odznak, okrsek se přiklonil,
   Vetešník něco vykoupil, do Ztracené přišly další děti z Bílých domů).
2. **Rozvrh** — hráč přidělí své party na akce. Na začátku má jednu partu, později až tři.
3. **Vyhodnocení** — taktické misie se hrají, ostatní akce se vyhodnotí přímo.
4. **Uzávěrka** — přírůstek Respektu, změna postojů okrsků, posun kalendáře.

### Kalendář a termín

Kampaň běží **od jara k podzimnímu rejdu** (nástřel: 45 večerů). Podzimní rejd je tvrdý
termín, připomínající rejd, na němž poslední Velký Vont před lety neměl mladší děti, kterým by mohl vontství předat.
Nesplnění = konec *Další ztracený rok* ([§ 12](#12-podmínky-vítězství-a-prohry)).

### Akce na mapě

| Akce | Vrstva | Co dělá |
|---|---|---|
| **Průzkum** | taktická | odhaluje značky, průchody, hlídkové rozvrhy okrsku |
| **Nábor** | strategická | přidává Vonty; omezený pravidlem 12 podle frakce |
| **Klání** | minihra / strategická | získání vlivu v okrsku bez konfliktu, viz [§ 6](#6-klání) |
| **Přepad** | taktická | odebrání odznaků, vytlačení cizí hlídky z okrsku |
| **Hlídka** | strategická | obrana vlastního okrsku, snížení rizika událostí |
| **Vyjednávání** | strategická | posun postoje okrsku za Respekt nebo za Slovo |
| **Obchod** | strategická | Vetešník: výkup a odkup; jediná akce s dospělým |
| **Ověření původu** | strategická, **jen tradice** | test pravosti odznaku, obrana proti falzifikátům |
| **Nábor za Rozdělovací** | strategická, **jen reforma** | nábor v Bílých domech, rychlý a levný, s rizikem |

### Postoje okrsků

Každý okrsek má postoj na stupnici a ten je jediné, co se na mapě „obsazuje":

```
odmítá  →  nedůvěřuje  →  nezúčastněný  →  nakloněný  →  dal slovo
```

Pouze okrsek ve stavu **dal slovo** vydá svůj odznak-klíč dobrovolně. Odznak lze získat i
z nižších stavů (krádeží, přepadem, výkupem), ale to nezvedne postoj — a právě proto může
mít hráč nakonec všechny klíče a přesto prázdný rejd.

---

## 5. Rejd

Sněm okrsků na Sirotčím dvoře. **Rejd nedává klíče, dává povolení.**

- Koná se periodicky (nástřel: každý 10. večer) a povinně na konci kampaně.
- Každý okrsek se vyjádří podle postoje. Hráč může před rejdem utrácet Respekt a Slova.
- Rejd na konci aktu II je ten, na kterém **musí hráč vyslovit frakci.** Okrsky se přeskupí
  a část dosavadního zisku přejde k druhé frakci — to není trest, to je cena volby.
- **Ginkgová zahrada** je jediné místo, kde lze s druhou frakcí mluvit i po rozkolu
  (pravidlo 33 — pod ginkgem se neválčí).

---

## 6. Klání

Nekrvavá cesta k vlivu, funkční ekvivalent turnajů z Defender of the Crown.

| Klání | Testuje | Poznámka |
|---|---|---|
| Běh přes střechy | rychlost, znalost průchodů | těží ze zvládnutého průzkumu |
| Šplh | jedna postava, čistá dovednost | |
| Hod | přesnost | |
| Hlavolam | hráčova hlava, ne statistika postavy | přímá linka k Ježkovi v kleci |
| Mlčenlivost | výdrž, sebeovládání | tematicky nejvontštější disciplína |

Klání dává **Respekt a postoj okrsku**, nikdy odznaky. Je to hlavní nekonfliktní cesta pro
hráče, který nechce nikoho přepadat — a ta cesta musí být plně schůdná až do konce.

---

## 7. Taktická vrstva

### Průzkum

- Volný pohyb party (3 postavy, později výběr z větší soupisky) **v reálném čase s pauzou.**
- Kužely dohledu, zvukové okruhy, světlo a tma jako plnohodnotné mechaniky.
- Vertikalita je základ, ne bonus: pavlače, střechy, sklepy, světlíky, kladky.
- **Chytačka** — tichá neutralizace jedné osoby bez alarmu, pokud ji nikdo nevidí. Základní
  nástroj, jak Commandos/MYZ vrstvu vůbec zvládnout.
- Kontakt bez chytačky → přechod do taháček.

### Šarvátka (taháčky)

- **2 akční body** na postavu a tah (pohyb, akce, nebo dvakrát pohyb).
- Iniciativa: kdo šarvátku vyvolal z nepozorovaného stavu, jde první — **pokud to pravidla
  hráčovy frakce dovolují** (pravidlo 4 to zakazuje).
- Krytí, výška, počet, překvapení. Žádné zbraně. Nástroje: provaz, kladka, prak na odvedení
  pozornosti, plachta, dveře, tma.

### Stavy postavy — nikdy smrt

```
V pořádku  →  Zahnaný (dočasně mimo šarvátku)  →  Chycený  →  Bez odznaku
```

| Stav | Následek |
|---|---|
| **Zahnaný** | postava se stáhne, vrací se do hry v témže večeru |
| **Chycený** | odvedena za hranici okrsku; vypadává z misie, vrací se další večer s penalizací |
| **Bez odznaku** | soupeř zabavil odznak; postava přestává platit jako Vont, dokud si ho nevyslouží zpět. **Toto je jediná trvalá ztráta ve hře.** |

Pravidla 1 a 19 určují, **co chycená postava prozradí** — bez nich hráč se zajetím ztrácí
i objevené lokace a polohu vlastního sklepa. Ověřená pravidla tedy nejsou příchuť, ale obrana.

---

## 8. Vetešník a dospělí

- Dospělé **nelze přemoct.** Nemají kužel dohledu jako soupeř, mají ho jako překážka:
  spatření dospělým misi neprohraje, ale nevratně zvýší „pozornost" v okrsku na několik večerů.
- Vetešník je jediná dospělá postava, se kterou se dá interagovat, a to výhradně obchodem
  nebo vypátráním informací o tom, kdo mu co prodal.
- Krádež u Vetešníka je možná a **porušuje pravidlo** → ztráta Slova a Respektu. Musí to být
  reálně lákavé, jinak dilema nefunguje.

---

## 9. Křídové značky a gramotnost

Značky jsou **od první minuty na zdech a od první minuty pravdivé.** Roste jen schopnost
hráče je čist. Tím se odměna za postup vrací do míst, která hráč už zná.

| Stupeň | Co hráč umí | Dopad |
|---|---|---|
| **0** | vidí kresbu, nerozumí | výchozí stav |
| **1** | pozná vontskou značku od čmáranice | ví, *že* tam něco je |
| **2** | čte směr a nebezpečí | základní navigace, „tudy ne" |
| **3** | čte čas | zná hlídkové rozvrhy → plánování večera |
| **4** | značky **píše** | trvalé zápisy do mapy, zprávy pro spojence, **a falešné značky jako zbraň** |

Stupeň 4 je záměrně morálně nejednoznačný. Falešná značka je lež — a dopis pod ginkgem říká,
že lží se to udělat nedá. Falšování značek proto smí být účinné a **smí stát Slovo.**

---

## 10. Pravidla Kronik jako modifikátory

Každé nalezené a **ověřené** pravidlo něco zakáže a něco umožní. Toto je hlavní nástroj, jak
z ideologie udělat mechaniku (pilíř P4).

| # | Rekonstruované znění | Mechanický efekt |
|---|---|---|
| 1 | *Vont neřekne, kde spí druhý Vont.* | Chycená postava neprozradí polohu základny. |
| 4 | *Vont neudeří první.* | **Zakazuje** vyvolat šarvátku útokem. Při obraně +iniciativa, +Respekt. |
| 7 | *Vont nechodí přes Rozdělovací po světle.* | Denní akce mimo Stínadla dražší, noční levnější. |
| **12a** | *Vont nepřijme nikoho, kdo se nenarodil ve Stínadlech.* | **Zakazuje** nábor v Bílých domech. → tradice |
| **12b** | *Vont nepřijme nikoho, kdo Stínadlům nedal slovo.* | Povoluje nábor kdekoli, ale nový Vont skládá Slovo; jeho porušení stojí Respekt celé skupiny. → reforma |
| 19 | *Vont neřekne, co viděl ve sklepě.* | Zajetí neodhalí objevené lokace. |
| 23 | *Odznak se nedává, odznak se vypilováním získá.* | Zakazuje předávání odznaků mezi postavami (brání farmení). |
| 28 | *Kdo vezme odznak, vezme i povinnost.* | Zabavený odznak lze držet jen s dostatkem Respektu, jinak se ztrácí. |
| 31 | *Vont nekřičí ve Ztracené.* | V daném okrsku se zvuk šíří dál — diegetický tutoriál zvukové mechaniky. |
| 33 | *Pod ginkgem se neválčí.* | Ginkgová zahrada je vynuceně neutrální; jediné místo pro jednání s druhou frakcí. |
| 40 | *Velký Vont je ten, kdo najde Ježka v kleci.* | Podmínka vítězství tradiční cesty; reformátoři její platnost popírají. |

### Neověřená pravidla

Cvrčkův sešit a další dochované zápisy se v několika bodech rozcházejí. Děti znají praktický smysl většiny pravidel, ale ne jejich původní znění ani to, která verze platila naposledy. Mechanika:

- Hráč smí **přijmout dosud neověřené znění pravidla** a okamžitě z něj mít bonus (typicky Respekt —
  tradice je vidět).
- Pokud pozdější fragment Kronik potvrdí jiné znění, hráč **ztrácí Respekt** a musí pravidlo změnit.
- Tím se z „věřit tradici, kterou neumíš ověřit" stává hazard s kartami na stole. Tohle je
  levná mechanika s velkým tematickým výnosem — doporučuji ji nevyhazovat při škrtání rozsahu.

**Rozpor pravidla 12 je jádrem celé hry.** Není to chyba v opisu, kterou by šlo opravit;
originál Kronik ho rozhodne teprve v aktu IV, tedy až po tom, co se hráč musel rozhodnout.

---

## 11. Zámek Kronik

Truhla leží v Podstínadlí a je nalezitelná už na konci aktu I. Zámek přijímá **několik
odznaků současně, po jednom z každého okrsku** — poslední Velký Vont je rozdal schválně.

- Počet potřebných odznaků = počet okrsků ([Q5](pribeh.md#q5--kolik-je-okrsků-a-tedy-odznaků-klíčů), nástřel 8).
- Odznaky **lze získat i nečestně** (přepad, krádež, výkup). Zámek na to nemá názor.
  Postoj okrsků ano — a bez rejdu není z čeho vládnout.

### Nerozhodnutá otázka: pasuje nový, vypilovaný odznak?

Na tomhle stojí, jestli je reformní cesta rovnocenná, nebo tragická. Tři varianty:

| Varianta | Důsledek pro hru | Cena |
|---|---|---|
| **A — ano, pasuje** | obě cesty plně rovnocenné; hra tvrdí, že vontství je to, co si z něj lidé udělají | Podkovin postoj se zpětně jeví jako pouhá pověra; oslabí se tradiční cesta |
| **B — ne, ale reforma má vlastní vítězství** | originál zůstane zamčený navždy; reformátoři sjednotí Stínadla a **napíšou Kroniky nové** | mechanicky nejčistší, ale hráč přijde o obsah, na který se celou hru těšil |
| **C — falešný zub zámek nevratně poškodí** | volba se stává nevratnou ztrátou; Kroniky nepřečte nikdo nikdy | nejsilnější dramaticky, nejhorší pro opakovanou hratelnost a nejnáročnější na férové varování hráče |

**Doporučení k rozhodnutí:** varianta **B** drží obě frakce věcně v právu (Podkova má pravdu
o zámku, Vosk má pravdu o počtech) a zároveň dává reformě skutečné vítězství, ne trest.
Varianta C je nejlepší příběh a nejhorší hra. Rozhodnutí je ale autorské — viz
[`pribeh.md` Q2](pribeh.md#q2--otevře-nově-vypilovaný-odznak-zámek-kronik).

---

## 12. Podmínky vítězství a prohry

| Konec | Podmínky |
|---|---|
| **Velký Vont podle Ježka** | nalezený Ježek + Kroniky otevřené originálními odznaky + potvrzení na podzimním rejdu; žádné porušené Slovo |
| **Velký Vont podle rukou** | většina okrsků *dal slovo* včetně přijatých Bílých domů; Kroniky podle varianty z [§ 11](#11-zámek-kronik) |
| **Oba zámky** | Ježek i Kroniky bez porušeného Slova; má být velmi obtížné — a je [otevřené](pribeh.md#q3--má-existovat-konec-oba-zámky), jestli má vůbec existovat |
| **Cesta síly** | všechny odznaky získané přepadem, krádeží a výkupem, postoje okrsků nízké → truhla se otevře a na rejd nikdo nepřijde |
| **Další ztracený rok** | podzimní rejd proběhne bez sjednocení; epilog cituje poslední odstavec dopisu |

---

## 13. Čísla k vyladění

Všechno níže je nástřel. Nic z toho není ověřené a nic z toho není argument.

| Věc | Nástřel | Co určuje |
|---|---|---|
| Počet okrsků | 8 (+ Bílé domy) | délku aktu II, počet odznaků na zámek |
| Délka kampaně | 45 večerů | tempo, tlak podzimního termínu |
| Frekvence rejdu | každý 10. večer | kadenci politických rozhodnutí |
| Počet Slov na kampaň | 5 | jak drahá je nečestná zkratka |
| Velikost party | 3 (později výběr z 6–8) | složitost taktické misie |
| AP na postavu | 2 | rychlost šarvátky |
| Délka taktické misie | 10–20 min | jak často se vstupuje na mapu |
| Vontů na začátku | 24 | pocit „zbytku" hnutí |
| Vontů před odlivem rodin | 200+ | měřítko toho, co se ztratilo |
| Stupňů gramotnosti | 5 (0–4) | délku hlavní progresní osy |
| Ověřitelných pravidel | ~12 z 40 | kolik toho zůstane navždy neznámé |
