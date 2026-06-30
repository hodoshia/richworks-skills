# richworks-skills

[🇬🇧 English](README.md) | [🇸🇰 **Slovenčina**](README.sk.md)

Knižnica 18 marketingových zručností vytvorených z reálnej praxe v **RichWorks** - marketingovej agentúre zameranej na výsledky, sociálne médiá, obsahovú stratégiu a rast poháňaný umelou inteligenciou.

Toto nie sú generické tipy stiahnuté z internetu. Sú to skutočné frameworky, pracovné postupy a playbooki používané s klientmi, zabalené ako jednoduché Markdown súbory, ktoré fungujú s **ľubovoľným AI asistentom** - Claude, ChatGPT, Gemini, Copilot, Cursor alebo akýmkoľvek nástrojom, ktorý vám umožňuje pridávať kontext alebo vlastné inštrukcie.

Každý súbor je samostatný. Načítajte ten, ktorý zodpovedá vašej úlohe, a AI píše so správnym frameworkom namiesto generických rád.

---

## Kto to vytvoril

**Adam Hodoši** - Social Media Lead v RichWorks, špecialista na AI a marketing. Buduje brand presence, obsahové systémy a stratégie sociálnych médií pre klientov z rôznych odvetví. Tieto zručnosti odrážajú to, čo skutočne prináša výsledky: rast sledovateľov, obsahové systémy, ktoré sa škálujú, video, ktoré funguje, a copy, ktoré konvertuje.

---

## Čo obsahuje

18 úzko zameraných zručností pokrývajúcich celý pracovný postup v oblasti sociálnych médií a marketingu.

| Skill | Čo pokrýva |
|-------|-----------|
| `profile-optimization` | Nastavenie Instagram profilu - formula pre bio, highlights, handle, pole mena |
| `profile-growth` | Diagnostika a oprava rastu sledovateľov - traffic vs. konverzný lievik |
| `tone-of-voice` | Cvičenia na brand voice - hodnoty, osobnosť, brand kódy |
| `reels-video` | Stratégia krátkeho videa - hooks, štruktúra, VTR, audio |
| `sales-posts` | Predaj na sociálnych médiách bez straty dosahu - techniky copy, formáty |
| `landing-page-copy` | Web copy, ktoré konvertuje - USP, námietky, dôkazy, jednoduchosť |
| `headlines` | 100 šablón nadpisov na doplnenie |
| `seasonal-campaigns` | Black Friday / Q4 stratégia - zahrievanie kontaktov, remarketing, FOMO |
| `content-planning` | Kompletný pracovný postup pre obsah - banka nápadov, kalendár, popisky, rutina zverejňovania |
| `content-principles` | Základy obsahovej stratégie - čo zverejňovať a prečo |
| `ai-automation` | AI prompting, Custom GPTs, Make automatizácie, emailové toky |
| `linkedin-templates` | 5 overených štruktúr LinkedIn príspevkov na budovanie autority |
| `viral-script-formula` | Psychológia za virálnym videom - 3 konceptuálne frameworky |
| `hashtag-strategy` | Pravidlá hashtagov 2026, limit 5 tagov, zoznam zakázaných hashtagov |
| `reel-diagnosis` | 7-krokový AI post-mortem pre podvýkonné videá |
| `foundation-layer` | Naučiť AI váš brand voice, cieľovú skupinu a pozicionovanie |
| `content-flywheel` | Jeden záznam - všetky formáty, automatizovane |
| `creative-techniques` | Frameworky pre reklamné kreatívy a strategický model 4C |

Každá zručnosť sa nachádza v `skills/<name>/SKILL.md`. Súbor začína krátkym blokom metadát (názov, popis, spúšťacie slová) nasledovaným frameworkom v obyčajnom Markdowne. Metadáta pomáhajú nástrojom, ktoré zručnosti načítavajú automaticky; všetko pod nimi je čitateľné pre každého človeka alebo AI.

---

## Ako to používať (vyberte si nástroj)

Obsah je všade rovnaký. Líši sa len spôsob načítania.

### Claude Code (plugin s automatickým načítavaním)

V Claude Code sa zručnosti aktivujú automaticky na základe konverzácie - nikdy si nemusíte vyberať.

```bash
# 1. Add the marketplace
claude plugin marketplace add hodoshia/richworks-skills

# 2. Install the skills you want (or all of them)
claude plugin install headlines@richworks-skills
claude plugin install reels-video@richworks-skills
claude plugin install content-planning@richworks-skills
# ...one line per skill, see the table above for names
```

Začnite konverzáciu o hashtagoch a `hashtag-strategy` sa načíta. Opýtajte sa na neúspešný reel a `reel-diagnosis` sa zapojí. Žiadne príkazy na pamätanie.

### ChatGPT (Custom GPT alebo Project)

1. **Custom GPT:** vytvorte nový GPT, potom v časti **Knowledge** nahrajte súbory `SKILL.md`, ktoré má poznať. Do inštrukcií GPT pridajte: "Keď úloha zodpovedá niektorej z nahratých zručností, postupuj podľa frameworku tejto zručnosti."
2. **Projects:** vytvorte Project, otvorte **Instructions** a vložte obsah jednej zručnosti (alebo niekoľkých súvisiacich). Všetko v danom projekte potom používa daný framework.
3. **Jednorazové použitie:** vložte zručnosť priamo do chatu pred svojou požiadavkou.

### Google Gemini (Gem)

1. Otvorte **Gems** a vytvorte nový Gem.
2. Vložte obsah zručnosti do inštrukcií Gemu.
3. Voliteľne pripojte súvisiace súbory zručností cez Google Drive, aby ich Gem mohol referencovať.

Gemini je tiež užitočný pre kroky analýzy videa v `content-flywheel` a `reel-diagnosis`.

### Cursor, Copilot a ďalšie nástroje pre kódovanie a agentov

Vložte obsah `SKILL.md` do súboru pravidiel alebo vlastných inštrukcií nástroja (napríklad súbor `.cursorrules`, súbor inštrukcií Copilot alebo systémový prompt). Nástroj potom aplikuje framework vždy, keď je to relevantné.

### Ľubovoľný AI chat (kopírovanie a vkladanie)

Žiadne nastavenie: otvorte zručnosť v tomto repozitári, skopírujte ju, vložte do zvoleného AI a položte svoju otázku. Funguje s akýmkoľvek modelom.

### Obsidian, Notion alebo jednoduchá vedomostná báza

Naklonujte alebo stiahnite repozitár a otvorte priečinok `skills/` ako vault alebo ho importujte do svojich poznámok. Každá zručnosť je bežný Markdown súbor, takže slúži aj ako referenčná knižnica, ktorú si môžete priamo prečítať.

```bash
git clone https://github.com/hodoshia/richworks-skills.git
```

---

## Ako to funguje

Každá zručnosť obsahuje:
- Základný framework alebo metodológiu
- Doslovné prompty a šablóny (v slovenčine, kde je originál v slovenčine)
- Krížové referencie na súvisiace zručnosti
- Konkrétne príklady z reálnych kampaní

Zručnosti sú zámerne rozdelené jedno zameranie na súbor, aby ste načítavali len to, čo je relevantné - žiadna nadváha, žiadne protichodné rady z nesúvisiacich playbookov.

---

## Poznámka k jazyku

Väčšina zručností predvolene generuje **slovenský výstup** - boli vytvorené pre slovensky hovoriacu cieľovú skupinu. Frameworky a metodológie sú univerzálne; prepnite na akýkoľvek jazyk jednoduchou poznámkou v prompte.

---

## Aktualizácie

Zručnosti sa pridávajú a aktualizujú s vývojom praxe. Sledujte repozitár alebo ho aktualizujte, aby ste mali najnovšiu verziu. Príspevky a adaptácie pre iné nástroje sú vítané.
