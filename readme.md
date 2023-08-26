# Vefforritun 1, 2022: Verkefni 2, HTML #2

## Markmið

- Vinna með og velja HTML element.
- Nota HTML validator og huga að því hvernig HTML er skrifað.
- Huga að aðgengi og nota aXe tólið.

## Verkefni 2–6

Í verkefnum 2–6 munum við vinna áfram með sama verkefni og byggja ofan á það:

- [Verkefni 2](https://github.com/vefforritun/vef1-2023-v2) skilgreinir grunn HTML og síður.
- [Verkefni 3](https://github.com/vefforritun/vef1-2023-v3) bætir við grunn viðmóti.
- [Verkefni 4](https://github.com/vefforritun/vef1-2023-v4) setur upp útlit (e. layout).
- [Verkefni 5](https://github.com/vefforritun/vef1-2023-v5) setur upp grind og gerir útlit skalanlegt (e. responsive).
- [Verkefni 6](https://github.com/vefforritun/vef1-2023-v6) setur upp tól til að hjálpa við skipulag og vinnu.

## Lýsing

Setja skal upp fjórar síður fyrir veitingarstað, aðgengilegar af internetinu (gegnum Netlify):

- Forsíða.
- Um veitingarstaðinn síða.
- Matseðilssíða.
- Pöntunarsíða með formi.

## Síður

### Efni

Gefið efni er í textaskrám undir `gogn/` og er Markdown formi. Ekki á að birta nákvæmlega það efni sem kemur fram heldur fylgja leiðbeiningum í hverri skrá fyrir sig.

Gefnar myndir eru í `myndir/` og skal vísa í þær þar (nota þarf relative vísun úr `sidur/` yfir í `myndir/` þar sem við á.)

### Sameiginlegt

Allar síður skulu innihalda valmynd sem vísar á allar aðrar síður og merkja valda síðu á einhvern hátt. Athugið að allar síður fyrir utan forsíðu verða að vera undir `sidur/` möppu.

Allar síður skulu hafa fót (gögn neðst á síðunni) með upplýsingum um veitingastaðinn og opnunartíma (sjá `gogn/fotur.md`).

Allar síður skulu hafa lýsigögn skilgreind fyrir `description`, `og:title`, `og:description` og `og:image` (alltaf `myndir/sharing.jpg`).

Allar síður nema forsíða skulu hafa tengil neðst í efni með textanum „Aftur á forsíðu“.

Allar síður skulu hafa fyrisögn og „beint í efni“ hlekk á eftir fyrirsögn, en á undan valmynd.

### Forsíða

`index.html`, forsíða með texta tilgreindum í `gogn/index.md`

Inniheldur inngangstexta og yfirlit með vísunum í aðrar síður.

### Um veitingarstaðinn síða

Síðan skal eiga heima undir `sidur/um.html`, með texta og myndum tilgreindum í `gogn/um.md`.

Leyfilegt er að setja `width` eigindi á mynd til að takmarka breidd.

### Matseðilssíða

Síða með lista af réttum sem skal eiga heima undir `sidur/matsedill.html`, gögn í [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) skjalinu `gogn/rettir.csv`.

Tafla skal vera uppsett með fjórum dálkum: númer (`id`), titill réttar (`titill`), lýsing (`lysing`) og verð (`verd`).

### Pöntunarsíða

Síða með formi til að panta rétti frá veitingarstaðnum _eða_ panta borð, staðsett undir `sidur/pontun.html`, svæði og reitir skilgreindir í `gogn/pontun.md`.

Aðeins á að setja upp formið, **engin** forritun fyrir virkni í formi með JavaScript eða í bakenda.

### Myndir

Myndir frá Unsplash eftir:

- [Connor Wilkins](https://unsplash.com/photos/2crxTr4jCkc?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)
- [Raamin ka](https://unsplash.com/photos/uR51HXLO7G0?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)
- [Philip Martin](https://unsplash.com/photos/man-standing-near-balcony-5aGUyCW_PJw?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)
- [Robert Godwin](https://unsplash.com/photos/cdksyTqEXzo?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)
- [Jason Leung](https://unsplash.com/photos/cdksyTqEXzo?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)

## Útlit

Ekki er gefin forskrift að útliti, þar sem verkefnið snýst um að setja upp merkingarfræðilegt HTML sem snýst um að huga að merkingarfræði _ekki_ útliti.

Ekki þarf eða ætti að gera neitt með CSS. Ef þið viljið fara lengra og byrja á CSS skulið þið passa ykkur á að vanda til verka og helst bera undir kennara eða dæmatímakennara.

## Almennt

- **Nýta skal merkingarfræðilega viðeigandi element**.
- Valmynd skal útfæra með því að afrita og breyta milli síðna, ekki er krafa um neina „forritun“ til að útbúa valmynd.
- Síður skulu nota `utf-8` stafasett.
- Passa skal upp á að hafa snyrtilega uppsettan kóða þar sem inndráttur er samræmdur.
- Allar síður skulu vera villulausar ef prófaðar með [HTML validator](https://validator.w3.org/).
- Allar síður skulu vera án aðgengisvillna ef prófaðar með [aXe](https://www.deque.com/axe/), setjið upp viðbót í vafra.

## Netlify

Setja skal upp verkefni á Netlify með því að hlaða upp skrám með „manual deploy“ _eða_ tengja GitHub repo.

## Mat

- 25% – Merkingarfræðileg element og síður án villna frá HTML validator og aXe validator.
- 15% – Haus, valmynd og fótur eftir forskrift.
- 15% – Forsíða uppsett eftir forskrift.
- 15% – Um síða uppsett eftir forskrift.
- 15% – Matseðilssíða uppsett eftir forskrift.
- 15% – Pöntunarsíða uppsett eftir forskrift.

## Sett fyrir

Verkefni sett fyrir í fyrirlestri mánudaginn 28. ágúst 2023.

## Skil

Skila skal í Canvas, seinasta lagi fyrir lok dags fimmtudaginn 7. september 2023.

Skilaboð skulu innihalda:

- zip skrá með öllum skrám _eða_ hlekkur á GitHub.
- slóð á verkefni keyrandi á Netlify sem athugasemd („Add comment“ eða „Bæta við athugasemd“ á skilaskjá í Canvas).

## Einkunn

Leyfilegt er að ræða, og vinna saman að verkefni en **skrifið ykkar eigin lausn**. Ef tvær eða fleiri lausnir eru mjög líkar þarf að færa rök fyrir því, annars munu allir hlutaðeigandi hugsanlega fá 0 fyrir verkefnið.

Ef stórt mállíkan (LLM, „gervigreind“, t.d. ChatGTP) er notað til að skrifa part af lausn skal taka það fram. [Sjá nánar á upplýsingasíða um gervigreind hjá HÍ](https://gervigreind.hi.is/).

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 5% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

> Útgáfa 0.1
