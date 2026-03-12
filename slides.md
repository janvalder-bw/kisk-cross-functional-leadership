---
marp: true
theme: default
paginate: true
style: |
    :root {
        --kisk-yellow: #f2c94c;
        --kisk-blue: #0000DC;
        --text-main: #333333;
    }
    * {
        font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", Arial, sans-serif;
        color: var(--text-main);
    }
    h1, h2, h3  {
        color: var(--kisk-blue);
    }
    pre {
        padding: 1em;
        background: #F0F0F0;
        border: 1px solid #CCC;
        border-radius: 1em;
    }
    section.teaser {
        background: var(--kisk-yellow);
        color: #FFF;
    }
    section.teaser h1 {
        color: var(--text-main);
    }
    section.title-slide, section.chapter {
        background: var(--kisk-blue);
    }
    section.title-slide *, section.chapter * {
        color: #FFF;
    }
    /* Simple top line / section header on content slides
       (all except title / chapter / teaser) */
    section:not(.title-slide):not(.chapter):not(.teaser) h1::before,
    section:not(.title-slide):not(.chapter):not(.teaser) h2::before {
        content: "";
        display: block;
        width: 40%;
        height: 4px;
        margin-bottom: 0.6em;
        background: var(--kisk-blue);
    }
    /* Quote / highlight slide tweak */
    section.quote {
        border-left: 6px solid var(--kisk-yellow);
        padding-left: 1.5em;
    }
---

<!-- _class: title-slide -->

# xF Leadership

Design Management & Leadership Masterclass
Jan Torsten Valder, KISK, Březen 2026

---

<!-- _class: title-slide -->

# Before we begin

- bude to občas trochu ostřejší
- některé formulace jsou nadsázka a zkratka
- mluvím reálné dynamice práce bez formální moci
- cílem je odnést si užitečné principy

---

# Mostly happy times

<!--
SPEAKER NOTES:
- Včera jsem byl kvůli ptákovině na jednom ministerstvu – mohl to být email
- Vtipkoval jsem s personálem na recepci, s ochrankou když mě vedli do kanceláře, pochválil jsem asistence kafe, podrbali jsme, vyřídil jsem co jsem potřeboval, cestou zpátky zase vtípky + zásek a drbání na recepci.
- Výsledek? Sedm+ lidí mělo fajn konec dne, já měl měl co potřeboval, o kamarádce za kterou jsem šel budou říkat, že za ní choděj super týpci.
- Večer jsem řešil situaci, kdy se někdo rozhodl, že bude kretén. Zkaženej večer, nic se nikam neposunulo, nic se nevyřešilo.
_ Jestli něco preferuju, tak je to zážitek z ministerstva - drivovat pozitivní experience pro všechny zůčastněné
- Doufám že si dneska odnesete, že to je fajn přístup

Příběh: Včera jsem během jednoho dne zažil dva typy spolupráce. 
V jednom případě lehkost, humor, respekt a všechno šlo dopředu. 
V druhém napětí, ego a nulový posun. 
A přesně o tom dneska je xF leadership: jak dělat věci tak, aby se pohnuly a zároveň nespálily lidi okolo.

-->

---

# Honza Valder

```
2000    Auto, Media, Ticketing, Fintech – Agency designer
2010+   Moneta, KB, ČS – Korporátní lead
2022+   Livesport - Globální manager
Teď     Orbiso - Product Navigator
        Sabbatical, Consulting and Mentoring
```

<!--
SPEAKER NOTES:
- Ahoj, jsem Honza
- Mám za sebou 25 let v různých rolích
- To o čem dneska mluvíme – XF leadership – není o konkrétní roli nebo zadání (není např. jen pro manažery)
- V jakékli – ať už IC, lead nebo manažer – roli můžete jej můžete – a potřebujete – úspěšně uplatňovat a doručovat věci nad rámec toho co vy sami umíte nebo dokážete – spojením se s jinejma lidma
- ...kteří nejsou vaši direct reports

-->

---

<!-- _class: teaser -->

# Jak teda na ten xF leadership?

---

<!-- _class: teaser -->

# 1. Dávej úplatky
# 2. Začni kouřit
# 3. Nauč se lhát

<!--
SPEAKER NOTES:
- Zní to děsivě, ale je to zkratka pro tři reality:
- Vztahy jsou kapitál
- Neformální přístup je často účinnější
- Framing a diplomacie jsou někdy účinnější než čistá pravda
-->

---

<!-- _class: chapter -->

# 0. Jak jsi se tady ocitl*a

<!--
SPEAKER NOTES:
- Ještě než divneme do těch třech topics, pojďme kouknout na to, kde tu je zakopanej pes.
-->

---

## Nikdo tu na tebe nečekal

- Hromada lidí s různými cíli
- (Design, výzkum etc.) často bez mandátu

→ Přesto (z)odpovědnost

<!--
SPEAKER NOTES:
- 
- Jsi v situaci kdy máš rozhýbat lidi, kteří mají jiné cíle, jiný jazyk, jiné KPI a často žádný důvod poslouchat.
- Design a výzkum se pohybují na hraně systému: bez přímé moci, bez rozpočtu, bez jasného mandátu.
- A přesto musí iniciovat, koordinovat a občas zachraňovat projekty.
- Odpovědnost (vnější; klidně bez zdrojů jak to mají CEO radí) vs. zodpovědnost (vnitřní)
-->

---

## Každej*á bojuje svůj battle

- priority, budget, výpovědi...
- často rozbité incentivy

→ jsi 5 % jejich focusu

<!--
SPEAKER NOTES:
- Každý chrání svůj backlog, budget, reputaci a tempo – má spoustu svých vlastních problémů.
- To, co je dobré pro tebe nebo firmu, nemusí být dobré pro konkrétní tým (tipicky může vést k oslabení jejich pozice)
- Hlavní tenze celé disciplíny je jednoduchá: vedeš lidi, kteří ti nereportují.
-->

---

## Bouchání do stolu tady nepomůže

- autorita vs. vliv
- mandát nemáš, buduješ si ho

→ leaduješ do stran a nahoru

<!--
SPEAKER NOTES:
- V klasickém vertikálním managementu/leadership máš formální autoritu a teoreticky můžeš cokoli.
- Tohle je jiný sport – influence management.
- Tady vyjednáváš – eskalace je drahá a většinou neefektivní (pro mě poslední/žádná volba).
- Mandát si průběžně buduješ kredibilitou.
- A jak jsem zmiňoval na začátku, nedělají to jen manažeři – kdokoli, kdo propojuje více týmů.
- Klidně i junior nebo stážista.

Příběh: launch velkého projektu, schůzka desítek lidí napříč korporátem, dorazil velmi seniorní manažer. Neuvědomil si, že nejsme jeho podřízení, začal řvát, že zpoždění je neakceptovatelné. Všichni koukali jak puk. On po pěti minutách řvaní odešel, a od té doby si o něm celá firma myslela (oprávněně), že je úplný kretén.
-->

---

<!-- _class: chapter -->

# 1.  Zmapuj terén, investuj do vztahů

<!--
SPEAKER NOTES:
- Vztahy jsou kapitál. Než budete potřebovat pomoc, musíte vědět, kde se rozhoduje, a investovat do lidí kolem.
-->

---

<!-- _class: teaser -->

# Dávej úplatky

<!--
SPEAKER NOTES:
- v bance si nás první týden zavolal manager benefitního programu, uspořádal nám zábavnou soutěž, a zařídil, že každý z nás vyhrál nějakou drobnost – lahev na vodu apod.
- tu lahev na vodu jsem pak měl pár let na stole
- co myslíte, že se stalo, když za mnou dotyčný manažer přišel, a něco drobného potřeboval?
- tuhle strategii jsem zcela adaptoval, a v dobrém a rád v ní pokračuju 
- vývojářstvo z banky jsem dlouho zásoboval Nerf pistolema
- lidi na payments mají rády nugát a rafaelo
- lidi ze startupu se můžou utlouct po višňový bublanině s mascarpone (teď znova dorazily do Lidlu mražený višně)
-->

---

## Orgchart je fan fiction

- oficiální titul je jasný, vliv je často jinde
- poznej a zmapuj si organizaci

→ vybuduj si vlastní

<!--
SPEAKER NOTES:
- Každá organizace má dvě struktury: formální a neformální 
- Zmínil jsem holky z payments – pokud řídíte budget, je to superdůležité oddělení. stejně tak procurement. stejně tak HR. tam chcete mít kamarády a kamarádky
- I když nevedete velký tým, hodí se vědět kdo co řeší, jaké průsery se na vás chystají a ovlivní vaši roadmapu
- Existuje věc jako neformální orgchart (často se o tom mluví jako o tom kdo s kým spí, kdo koho nenávídí, kdo všechno zablokuje, kdo je úplně neschopný) - to je důležitý
- Co je klíčový je vybudovat si uvnitř organizace vlastní orgchart; a co nejširší
-->

---

## Stakeholdeři*ky nejsou publikum

```

        Nízký vliv      Vysoký zájem     =      Ambasador*ka

        Vysoký vliv     Vysoký zájem     =      Partner*ka

        Vysoký vliv     Nízký zájem      =      Blokátor*ka

```

<!--
SPEAKER NOTES:
- Super – orgchart máme, kámoše napříč firmou, ale na stůl přistál konkrétní projekt – ale tam jsou úplně jiný lidi
- Většinu z nich můžeme definovat jako stakeholdery, většinou unikátní per projekt / iniciativu
- Můžete si je oklasifikovat podle toho, jaký mají vliv a zájem.
- Nízký vliv plus vysoký zájem může být budoucí ambasador - často tvůj orchart – můžou ti pomoct protlačit sidequesty
- Vysoký vliv plus vysoký zájem je partner – to jsou miláčci
- Vysoký vliv plus nízký zájem je potenciální blokátor – to je super nebezpečné, můžet ti zabít projekt.
- Velmi často mají konkurenční nápad, projekt, potřebujou tvoje lidi a zdroje
-->

---

## Vztah na počkání neexistuje

- důvěra
- reciprocita

→ koukejte kolem sebe, a buďte vidět

<!--
SPEAKER NOTES:
- Cross-functional vliv stojí na tom, že už vztah máš – když ho potřebuješ, je pozdě ho budovat.
- Nezapomínejte:
- Důvěra je budovaná průběžně a ztracená rychle.
- Reciprocita funguje napříč kulturami i senioritou.
- A přítomnost znamená být vidět i mimo formální struktury.
-->

---

## Všechny typy "úplatků" fungují

- sdílej, zmiň, oceň, poděkuj
- každý chce, aby to šlapalo

→ posiluješ svůj chart +  zlepšuješ kulturu


<!--
SPEAKER NOTES:
- Reciprocita je prehistorická a funguje bez ohledu na kulturu, senioritu nebo titul.
- Sdílej zajímavý článek.
- Zmiň jejich práci na meetingu, kde nejsou.
- Poděkuj veřejně, konkrétně a brzy.
- Cena skoro nulová. Návratnost asymetrická.
- Cíleně a veřejně chval lidi z okolních týmů, kteří byli helpful.
- Na all-hands, ve Slacku, v mailu, kde je i jejich manažer!!!
- Buď konkrétní: co udělali a jaký to mělo dopad.
- Efekt je silný: jejich manažer ví, že jsou cenní, oni ví, že si toho vážíš, a ostatní vidí, že spolupráce s tebou se vyplácí.
-->

---

<!-- _class: chapter -->

# 2. Lidi jsou divní, najdi neformální cesty

<!--
SPEAKER NOTES:
- Neformální přístup je často účinnější než formální. Ale nejdřív musíš pochopit, že lidi nefungují tak, jak bys čekal.
-->

---

## Lidi nejsou spreadsheet

- logika často nefunguje
- zájem, důvěra, emoce

→ zjisti, co potřebují

<!--
SPEAKER NOTES:
- Lidi nereagují primárně na logiku.
- Reagují na vlastní zájem, důvěru a emoce.
- Resistance k tvému nápadu málokdy znamená špatný nápad.
- Většinou znamená risk, workload nebo strach ze ztráty kontroly.
- Tvůj job není vyhrát argument.
- Tvůj job je zjistit, co oni potřebují, a najít překryv.
-->

---

## Každé*mu co jeho jest

- engineering, design, sales
- uživatel, peníze, compliance

→ komunikaci přizpůsob kontextu

<!--
SPEAKER NOTES:
- Liší se vztah k času, hierarchii, přímočarosti i autoritě.
- A neplatí to jen mezi zeměmi, ale i uvnitř firmy.
- Engineering chce přesnost a explicitní zadání.
- Design snese iteraci a ambiguitu.
- Sales žije v urgenci a vztazích.
- Obhajoba designu se mění podle kontextu: v B2C uživatel produkt přímo zažije, v B2B často obhajuješ rozhodnutí lidem, kteří produkt nikdy nepoužijí.
- Tam je jazyk ROI, risku a času implementace.
- Když tvůj způsob komunikace nefunguje, zkus jiný. Není to kapitulace, je to inteligence.
-->

---

<!-- _class: teaser -->

# Začni kouřit

<!--
SPEAKER NOTES:
- Když jsem vedl tým v bance, kouřilo se na terase
– Byl to naprosto standardní prostor pro to zajít za někým a něco rychle domluvit (a často se to stihlo už ve výtahu na terasu)
- Byly to krátké, minutové iterace, 1:1 nebo "hej pocem my tady s Kubou něco řešíme"
- Neskutečně efektivní – pak jen pošleš mailem výsledek FYSA a jednáš
- Jak efektivní tohle je mi došlo za covidu – najednou jsem měl kalendář zaflákaný schůzkama 9-5, který by jinak byly právě ten neformální minutovej talk na terase
- Díky bohu stále spousta lidí kouří nebo vapuje. Dost často senior management, kteří jsou jinak nedostupní.
- Hledejte si tyhle momenty a využívejte je – výtah. terasa. kafe. oběd. Velmi často je pět minut s správným stakeholderem víc, než pět schůzek.
-->

---

## Hijackni jejich radar

- jejich urgence
- společný překryv

→ řeš i jejich problém

<!--
SPEAKER NOTES:
- To, že s tebou nespolupracují, často neznamená odpor.
- Jen nejsi na jejich radaru.
- Zjisti, co je pro ně urgentní.
- Najdi překryv s tím, co potřebuješ ty
- Já  MILUJU synergie
- Přijď s návrhem, který řeší jejich problém a mimochodem i tvůj.
- Vztah předem znamená možnost hijacku. Bez vztahu jsi šum.
-->

---

<!-- _class: chapter -->

# 3. Framuj, přelož, komunikuj

<!--
SPEAKER NOTES:
- Tak a poslední kapitola – už máte kámoše v orgu, máte jejich pozornost, našli jste překryv, a co teď
-->

---

<!-- _class: teaser -->

# Nauč se lhát

<!--
SPEAKER NOTES:
- Framing a diplomacie jsou někdy účinnější než čistá pravda
- Tohle není o manipulaci, ale o překladu a strategii.
- Message delivered – ať je to pitch jak řešit problém, prosba o zdroje, doporučení – musí být v jazyce příjemce
-->

---

## První obrázek vyhraje

- pozor na jazyk
- vizuální kotvy

→ nezamotej to!

<!--
SPEAKER NOTES:
- Vizuál zaframuje realitu
- První silný vizuál, který ukážeš, často definuje, jak lidé o problému přemýšlí dál.
- To je i nebezpečný – pak se lidi velmi složitě přeučují
- Naučte se je – vrstvy. Jednoduché diagramy. Vztahy. Všechno po třech!
- Pojmenovávej věci jazykem, který mají rádi.
- Když už něco mají v hlavě, využij to a stav na tom – to máš zadarmo podporu.
- Pokud je zmateš, prohraješ.

Příklad: pokud někdo vymyslel X, a ty připravíš prezentaci kde to X není, protože to vlastně přišlo lepší to pojmenovat Y, jak asi ten člověk bude reagovat?
-->

---

## Než zatlačíš, usnadni jim next step

- celý příběh
- WIIFM

→ varianty, pojmenování rizik

<!--
SPEAKER NOTES:
- Tvoje agenda je komplexní. Jejich čas je nulový.
- Přeformátuj to do příběhu, přirovnání, něčeho co znají. Nemusíš manipulovat. Musíš přeložit.
- What's in it for me musí být jasné velmi rychle – do 30 sekund.
- Kdo zjednodušuje, ten vede. Clarity is a form of authority.
- Přijď s variantami, ne s jedním řešením.
- Pojmenuj jejich riziko dřív, než oni, a nabídni, jak ho snížit.

Příběh: taktika násobných mucholapek – schováš do prezentace pár věcí které jsou na první pohled kontroverzní/konfliktní, ale to že se jich vzdáš, pro tebe nic neznamená
-->

---

## Vyber si bitvu

- definuj si, přes co nejede vlak
- nemusíš mít všechny informace

→ ústup jako investice

<!--
SPEAKER NOTES:
- Prosazuj ve chvíli, kdy jde o kvalitu produktu, uživatelský dopad nebo precedens, který se bude opakovat.
- Ustup, když je vztah cennější než konkrétní bitva nebo když druhá strana má legitimní kontext, který ty nemáš.
- Ustoupení není prohra.
- Je to investice do budoucí spolupráce.

Příběh: nedávno jsem si vzpoměl na legendární kolegyni Janu, která při opravdu heated diskusi při mergeru dvou finančních institucí zařvala na callu "Takhle to tady neděláme." – diskuse se vrátila do kolejí.

-->

---

## Když místnost zamrzne

- vizualizuj, reframuj
- dej časový box

→ posuň se – klidně stranou, ale někam

<!--
SPEAKER NOTES:
- Naopak se může stát, že místnost zamrzne.
- Když nikdo nechce vzít rozhodnutí nebo inicitativu, je to moment pro facilitaci (mám rád označení emergency leadership)
- Extrémně důležité – zakresli, co slyšíš, aby bylo vidět, kde je shoda a kde ne. 
- Reframuj otázku: co potřebujeme rozhodnout dnes a co může počkat?
- Dej tomu časový rámec: pojďme se shodnout na 30 dnech a pak to vyhodnotit.
- To je leadership bez titulu v nejčistší formě.
-->

---

## Nezapomeň se pochlubit

- nástěnky fungujou i v 21 století
- je to začarovaný kuh  

→ Buď na očích

<!--
SPEAKER NOTES:
- komunikuj stav i úspěchy
- neustále - dolů jako pochvalu, do stran s oceněním jejich zapojení, nahoru aby se vědělo že existuješ a makáš
- když buděš vidět, bude se vědět že seš užitečnej/á, posílí to tvoji pozici
- a usnadní ti to další xF task

Příběh: když jsme udělali v Livesportu persony, ospamovali jsme jima celej barák, vobrovská prezentace. Výsledek? Celej barák tím rok žil, včetně majitelů. To chceš.
-->

---

<!-- _class: teaser -->

# Bonus: ELI5

<!--
SPEAKER NOTES:
- tohle je nejdůležitější věc, co vám dneska řeknu
- s každým, opravdu každým, a hlavně s top managementem, komunikujte, jako by jim bylo pět let
- prostě fucking kindergarten, doslova ELI5
- je to super cheat na to, jak předat informaci do mozku zaflakanejch high priority agendou
- je to super zpětná vazba na to co chcete komunikovat / dosáhnout - jestli to neumíte vysvětlit pětiletýmu, nevíte ani sami co chcete
-->

---

<!-- _class: chapter -->

# 4. Co v pondělí

<!--
SPEAKER NOTES:
- Přepínáme z inspirace do akce.
- Tady jsou konkrétní nástroje, které můžeš použít okamžitě.
-->

---

## Když chybí Áčka

```
    R = kdo to dělá
    A = kdo za to ručí
    C = kdo radí předem
    I = kdo to má vědět
```

<!--
SPEAKER NOTES:
- Teď vám udělám zmatek v písmenkách
- RACI je nudný nicméně užitečný model
- Spousta cross-functional konfliktů není osobních, ale strukturálních – chybí tam specifická role
- Responsible je ten, kdo to opravdu dělá.
- Accountable je ten, kdo ručí / je owner
- Consulted je někdo, koho se máš zeptat předem.
- Informed je někdo, komu to jen oznámíš.
- u xDept tasku často chybí, nebo není jasně určený accountable – měl by to být jeden C-level člověk, ne dva nebo žádný
(Nejčastější problém je, že A tam není. Nebo jsou tam dvě.)
- Když zaměníš C za A, tak ti dá spoustu rad, a na dalším boardu tě utopí na lžíci vody
-->

---

## Protokol pro zaseklý meeting

- co rozhodujeme
- kdo rozhodne
- do kdy to platí

→ vyřeš další bezpečný krok

<!--
SPEAKER NOTES:
- Tohle už jsem naznačoval, pojďme pro jsitotu ještě jednou
- Když se věc zasekne, projeď jednoduchou sekvenci.
- Co přesně dnes potřebujeme rozhodnout?
- Kdo je ownuje, kdo to udělá?
- Jaké riziko brání rozhodnutí, co musíme eskalovat?
- Na jak dlouho tohle rozhodnutí platí, než ho znovu otevřeme?
- Neřeš všechno. Vyřeš další bezpečný krok.
-->

---

## Health check nastavení projektu

```
Máme společný cíl?
Máme jasno v rolích?
Řešíme stejný problém?
Je tu prostor pro nesouhlas?
Jsme loajální misi, ne jen své funkci?
```
<!--
SPEAKER NOTES:
- Pět jednoduchých otázek:
- Víme, co je společný cíl a podle čeho poznáme úspěch?
- Je jasné, kdo rozhoduje a kdo jen radí?
- Mluvíme o stejném problému, nebo každý o jiném?
- Má tým dost důvěry na otevřený nesouhlas?
- Je mezi týmy víc loajality k funkci, nebo k misi?
- Když na dvě z nich neumíš rychle odpovědět, problém není v produktivitě. Je v designu spolupráce.
- Diagnostika GRPI: začni u goals, pak roles, pak process, až potom relationships. Častá chyba je, že problém v goals nebo roles se tváří jako problém v osobnosti.
-->

---

<!-- _class: chapter -->

# xF Leadership

- vybudujte si autentický vztahy
- preferujte neformální řešení problémů
- překládejte a komunikujte
- ego nechte před dveřma

<!--
SPEAKER NOTES:
- Leadership mindset shift je od "my team" k "the mission".
- Autorita v cross-functional práci nevychází primárně z titulu.
- Vychází z kredibility, schopnosti překládat mezi světy a z toho, že rozumíš systému.
- Když tě ostatní chtějí následovat i bez formální moci, jsi přesně tam, kam míříme.
-->

---

## Honza Valder

jan.valder@gmail.com

linkedin @janvalder