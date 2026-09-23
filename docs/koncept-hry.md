# Velký Vont — koncept hry

Herní koncepce a rozsah. Příběh v [`pribeh.md`](pribeh.md), mechaniky
v [`pravidla.md`](pravidla.md), próza prologu v [`proza/01-prolog.md`](proza/01-prolog.md).

> **Stav dokumentu:** pracovní. Volby technologie, rozsahu a art directionu jsou
> [otevřené](#10-rizika-a-otevřené-otázky-mimo-design) a nejsou návrhem předjímané.

---

## 1. Pitch

**Velký Vont** je hra o obnově zapomenutého dětského hnutí. Hráč je čtrnáctiletý chlapec, který se vrátí do Stínadel po několikaleté mezeře: za prací v nové továrně a novým bydlením v sousedním městě odešly celé rodiny, včetně dětí, které by vontství předaly dál. Čtvrť stojí, ulice fungují a levné byty už zabydleli mladí lidé, umělci i drobní řemeslníci. Jejich děti právě dorostly. Vontství je však zatím jen zbytek — čtyřiadvacet dětí a několik neúplných sešitů pravidel.

Hra kombinuje **strategickou vrstvu** obnovy a sjednocování okrsků *(inspirace Defender of the
Crown)* s **taktickou vrstvou** tichého průzkumu a nesmrtících šarvátek *(inspirace Commandos
a Mutant Year Zero: Road to Eden)*. Cíle jsou dva a definují právo vládnout každý jinak:
najít **Ježka v kleci** a otevřít **Vontské kroniky**, jejichž zámek potřebuje odznaky
z několika okrsků současně. Uprostřed kampaně si hráč musí vybrat mezi tradicionalisty
a reformátory — a ta volba nezmění barvu na mapě, změní pravidla, podle kterých hraje.

---

## 2. Návrhové pilíře

### P1 — Kultura je hluboká jednu generaci

Hráč neobnovuje budovy ani ekonomiku. Obnovuje **vědění**. Všechny hlavní odměny ve hře jsou
informace: přečtená značka, ověřené pravidlo, objevený průchod, zjištěné jméno. Proto smí být
příběh o „přerušené generaci" bez jakéhokoli fyzického zničení — Stínadla jsou celá, chybí jen
lidé, kteří vědí, co znamenají.

### P2 — Informace je schopnost, ne položka v inventáři

Křídové značky na zdech jsou od začátku vidět a od začátku nesou pravdivou informaci.
Hráč je zpočátku neumí přečíst. Postup ve **gramotnosti** proto neodemyká nová místa, ale
mění to, co hráč vidí na místech, kde už dávno byl. Poslední stupeň gramotnosti je umět
značky *psát* — a tedy lhát jimi.

### P3 — Nikdo neumírá; ztrácí se identita

Šarvátka nekončí smrtí ani zraněním, ale zajetím, odvedením za hranici okrsku a odebráním
odznaku. Protože je odznak zároveň jméno, měna i část klíče, prohra bolí trvale, a přitom
zůstává foglarovský tón nedotčený. Nesmrtící konflikt tu není ústupek, je to zdroj napětí.

### P4 — Ideologie mění pravidla hry

Tradice a reforma nejsou frakce s jinými bonusy. Jsou to **jiné soupisy platných pravidel**.
Pravidlo *„Vont neudeří první"* skutečně zakáže začít šarvátku útokem. Pravidlo 12a skutečně
zakáže nábor v Bílých domech. Hráč, který si vybere tradici, hraje po zbytek kampaně těžší
hru s vyššími Respektem, a to má být na první pohled vidět v UI.

---

## 3. Referenční hry: co bereme a co ne

| Reference | Bereme | Nebereme |
|---|---|---|
| **Defender of the Crown** | mapa dělená na území, přehledný tah, turnaje jako nekrvavá cesta k vlivu, soupeřící vůdci s vlastní agendou, čitelnost celé kampaně na jedné obrazovce | feudální ekonomiku, obléhání, souboje na život a na smrt, náhodu jako hlavní hnací sílu |
| **Commandos** | tichý průzkum v reálném čase, kužely dohledu, plánování cesty po střechách a sklepech, pocit, že každý strážník je smrtelně nebezpečný, i když nemá zbraň | zabíjení, vojenský rámec, nutnost hledat jediné povolené řešení |
| **Mutant Year Zero: Road to Eden** | plynulé přepínání volný průzkum ↔ taháčky, malá parta s vyhraněnými schopnostmi, příprava přepadu před prvním tahem, tichá likvidace hlídky jako klíčová dovednost | zbraně a smrt, postapo estetiku, mutace jako progresi |

---

## 4. Struktura hry: dvě vrstvy a smyčka

```
                 ┌─────────────────────────────────────────┐
                 │      STRATEGICKÁ VRSTVA (večer)         │
                 │  mapa okrsků, Respekt, Slovo, nábor,    │
                 │  klání, rejd, vyjednávání, Vetešník     │
                 └──────────────┬──────────────────────────┘
             vyslání party      │        výsledek mise, odznaky,
             na konkrétní úkol  │        Respekt, nové informace
                                ▼
                 ┌─────────────────────────────────────────┐
                 │       TAKTICKÁ VRSTVA (misie)           │
                 │  volný tichý průzkum v reálném čase     │
                 │        ↓ při kontaktu                   │
                 │  taháčky (šarvátka, 2 AP, bez smrti)    │
                 └─────────────────────────────────────────┘
```

Jeden **večer** = jeden tah strategické vrstvy. Kampaň běží od jara k **podzimnímu rejdu**,
který je tvrdý termín — ten samý rejd, na kterém se před čtyřmi roky poslední Velký Vont
neměl komu odevzdat. Podrobná struktura tahu: [`pravidla.md § 4`](pravidla.md#4-strategická-vrstva).

Poměr: taktické misie mají být **kratší a hustší** než v Commandos (řádově 10–20 minut),
protože se do nich vstupuje často. Strategická vrstva má být čitelná do půl minuty.

---

## 5. Mapa — okrsky

Návrh osmi okrsků Stínadel plus Bílé domy. Počet je [otevřená otázka](pribeh.md#q5--kolik-je-okrsků-a-tedy-odznaků-klíčů),
protože určuje délku aktu II i počet odznaků potřebných na zámek Kronik.

| Okrsek | Charakter prostředí | Taktická specialita | Role ve strategii |
|---|---|---|---|
| **Provaznická** | pavlačové domy, okna do sebe, střecha prádelny | vertikalita, pohyb po pavlačích, klíč od pavlačových dveří | startovní okrsek, hrdinův rodný blok |
| **Kotly** | kotelna, potrubí, pára, trvalý hluk | hluk maskuje pohyb — jediné místo, kde je běh bezpečný | průmyslový uzel, zdroj Křídy a nářadí |
| **Ztracená ulička** | slepá ulice a plot k Bílým domům | úzká hrdla, žádné obchvaty, boj o průchod | hraniční okrsek, tady se rozhoduje o Bílých domech |
| **Sirotčí dvůr** | velký otevřený dvůr, sklep pod ním | špatný stealth, dobré sněmy | politické centrum, místo rejdu |
| **Podzvoniční** | kostel a zvonice, Tleskačovo místo | výškový průzkum, tabu — hlídky tam nechodí, ale je odtud vidět všechno | pozdní obsah, brána k Ježkovi |
| **Podstínadlí** | sklepení propojující celou čtvrť | tma, nutnost světla, zkratky mezi okrsky | infrastruktura pohybu; leží tu truhla s Kronikami |
| **Ginkgová zahrada** | dvůr se stromem | pravidlo 33 — **neutrální zóna, nelze zde bojovat** | jediné bezpečné místo pro vyjednávání s druhou frakcí |
| **Lampářská** | krám Vetešníka, obchod, dospělí | dospělé nelze přemoct, jen se jim vyhnout | výkup a obchod, morálně nejdražší odznaky |
| **Bílé domy** *(za Rozdělovací)* | rovné, světlé, stejné; **není tam stín** | inverze stealthu: krytí téměř neexistuje, řeší se časováním a odvedením pozornosti | **nelze obsadit** — lze je jen přijmout, nebo odmítnout. To je ta volba. |

Ginkgová zahrada jako mechanicky vynucená neutrální zóna a Bílé domy jako záměrná inverze
stealth pravidel jsou dva nejvýraznější kousky návrhu — obojí vychází z fikce a ne
z potřeby varírovat obtížnost.

---

## 6. Progrese

Hráč roste ve čtyřech nezávislých osách. Žádná z nich není „úroveň postavy".

| Osa | Co se zvyšuje | Jak se to získává |
|---|---|---|
| **Gramotnost ve značkách** | kolik informace hráč vidí na už prozkoumaných místech; nejvyšší stupeň umožňuje psát falešné značky | učení od NPC, nalezené fragmenty Kronik |
| **Znalost průchodů** | rychlost pohybu mezi okrsky, možnost obchvatu v taktické misi | průzkum, obsazené okrsky, obchod s informacemi |
| **Soupis pravidel** | počet ověřených pravidel; každé něco zakáže a něco umožní | fragmenty Kronik, svědectví starších, riziková adopce neověřeného pravidla |
| **Parta** | dostupné postavy a jejich dovednosti (šplh, tichá chytačka, značky, mluvení, pilování) | nábor, klání, dodržená Slova |

Detailní pravidla: [`pravidla.md § 9`](pravidla.md#9-křídové-značky-a-gramotnost)
a [`§ 10`](pravidla.md#10-pravidla-kronik-jako-modifikátory).

---

## 7. Frakce v mechanice

Volba frakce (konec aktu II) mění tři věci naráz. Nikdy ne jen čísla.

1. **Soupis platných pravidel** — hlavně pravidlo 12 (kdo smí být přijat). To je tvrdé
   omezení, ne modifikátor.
2. **Dostupné akce na mapě** — reforma odemkne *Nábor za Rozdělovací*, tradice odemkne
   *Ověření původu* (kontrola pravosti odznaků, obrana proti falzifikátům).
3. **Ekonomiku obtížnosti** — tradice: méně lidí, vyšší Respekt, kvalitnější parta,
   pomalejší mapa. Reforma: rychlá expanze, nízká disciplína, riziko prozrazení a falešných
   odznaků.

Před volbou existuje **gradient závazku**: každá pomoc od Podkovy či Voska se platí politikou
(odmítnutím či přijetím dětí z Bílých domů), takže se hráč rozhoduje průběžně a na rejdu už
jen vysloví, co dělal celou dobu. Rejd nemá být první moment, kdy o tom hráč slyší.

---

## 8. Tón, obraz, zvuk

**Tón.** Věcný, ne nostalgický. Vypravěč nikdy nekomentuje, že „takhle už se dnes nežije".
Hra nesmí být pohlednice — děti v ní řeší organizační problém, který mají velmi vážně.
Humor je situační a přichází od Cvrčka.

**Obraz — návrh, nerozhodnuto.** Silná stopa Stínadel je *stín*: čtvrť je definovaná tím, že
se v ní dá být neviditelný, a Bílé domy tím, že ne. Světlo a jeho absence by tedy měly být
hlavní výtvarný i mechanický prostředek. Dvě uvažované cesty:

- **Kreslená linka** v duchu komiksové tradice Rychlých šípů (Marko Čermák) — okamžitě
  čitelné, levnější, riskuje dojem „hry pro děti".
- **Malovaný 2.5D isometrický** vzhled s tvrdými světly a velkými plochami tmy — lépe
  slouží stealthu a atmosféře, dražší.

**Zvuk.** Ticho jako výchozí stav, protože hluk je mechanika. Zdroje zvuku diegetické:
zvon, kotelna, kladka, déšť na plechu, cizí hlasy o dvě patra výš. Hudba spíš skoupá.

---

## 9. Rozsah

Doporučený postup, jestli se má z konceptu stát hra: **nejdřív jeden vertikální řez**, ne
celá kampaň.

**Vertikální řez** (cíl: dokázat, že se ty dvě vrstvy vzájemně vyplácejí):

- 2 okrsky (Provaznická, Kotly) + Ginkgová zahrada jako vyjednávací obrazovka
- 1 hráčská parta o třech postavách, 3–4 taktické misie
- ~8 večerů strategické vrstvy s jedním klání a jedním malým rejdem
- 1 odznak-klíč k nalezení, truhla viditelná a neotevíratelná
- gramotnost stupně 1–2, čtyři pravidla, z toho jedno neověřené a falešné

Co vertikální řez **ověřuje**: (a) je čtení značek samo o sobě odměna? (b) je nesmrtící
šarvátka dost napjatá? (c) chce se hráč vracet na strategickou mapu, nebo je pro něj otrava?
Jestli (a) nebo (b) nesedí, celá koncepce se musí předělat, a je lepší to vědět po dvou
okrscích než po osmi.

---

## 10. Rizika a otevřené otázky mimo design

### R1 — Autorská práva (nutno vyřešit první)

Foglarovo dílo je chráněné do konce roku **2069** (70 let po smrti autora, † 1999). Stínadla,
Vontové, Velký Vont, Ježek v kleci a Jan Tleskač jsou chráněné prvky, ne folklór. Pro
**komerční** vydání je potřeba licence od držitelů práv (dědicové, resp. nakladatel a
Sdružení přátel Jaroslava Foglara). Nekomerční fanouškovský projekt má nižší, ale nenulové
riziko. **Tohle je potřeba mít vyjasněné dřív, než se investuje do artu, hudby nebo
marketingu** — přejmenování světa na pozdní fázi projektu je mnohem dražší než na začátku.

Zálohová varianta, kterou je dobré mít promyšlenou: celý design výše funguje i s vlastním
světem (jiná čtvrť, jiné hnutí, jiný předmět místo Ježka). Vázané na Foglara je **jméno**,
ne mechanika.

### R2 — Otázky, které patří tobě, ne návrhu

| # | Otázka | Proč to nemůže rozhodnout dokument |
|---|---|---|
| **T1** | Engine — Godot / Unity / Unreal / vlastní? | závisí na tvých zkušenostech a na tom, jestli chceš 2D nebo 3D |
| **T2** | 2.5D isometrie, nebo plné 3D? | mění cenu artu i to, jak dobře funguje vertikalita pavlačí a sklepů |
| **T3** | Komerční titul, nebo nekomerční projekt? | rozhoduje R1, a tím i to, jestli svět zůstane foglarovský |
| **T4** | Sólo projekt, nebo tým? | určuje, jestli je vertikální řez otázka měsíců, nebo let |
| **T5** | Cílová platforma a ovládání | myš+klávesnice sedí Commandos vrstvě; gamepad by chtěl jiný návrh výběru party |

Návrhové (nikoli technické) otevřené otázky jsou u [`pribeh.md § Otevřené otázky`](pribeh.md#otevřené-otázky)
a [`pravidla.md § 11`](pravidla.md#11-zámek-kronik).
