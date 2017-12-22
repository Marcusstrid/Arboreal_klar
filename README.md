# Arboreal_klar
Startup-företaget Arboreal behöver en ny hemsida för sin affärsidé. Ni har fått i uppdrag att skapa denna sida.

Arboreal är en prenumerationstjänst för företag. Tjänsten innebär att man får sitt kontor inrett med växter med hjälp av experter från Arboreal. Sedan betalar man en månadskostnad för att få nya växter levererade och placerade på kontoret varje månad eller vecka beroende på vilken prisplan man har valt. Arboreal har sin kundgrupp bland små till medelstora IT-företag i stockholmsområdet.

KRAV

Sidan använder sig av en fler-kolumns-layout. Du använder dig av semantisk HTML för att strukturera upp ditt innehåll.

ska enbart användas för styling-syfte. Du använder dig inte av id för att styla din sida. Styling ska ske med class eller . Det ska heller inte förekomma inline styling med style-attributet i HTML. Du använder dig huvudsakligen utav flexbox för att positionerna ditt innehåll men andra positioneringstekniker får även förekomma (såsom float). Du använder i majoritet relativa måttenheter: % och rem/em. Användandet av enheterna ska vara konsekvent, dina marginaler och padding ska inte ha massor av spridda px-värden (såkallade magic numbers). Sidan har en meny där man kan gå till de olika undersidorna. Sidan får vara en one page där det inte finns några undersidor (pricing, themes, about, contact t.ex.) men då ska menyn länka till de olika rubrikerna på sidan (scrolla till rubriken). Sidan innehåller all information ovan om företaget, logotyp, slogan, pricing etc. Hur det är strukturerat är dock upp till dig. Tabellen behöver t.ex. inte se exakt ut som den ser ut i detta dokument utan det viktiga är att man tydligt ser innehållet och att det är väl grupperat så man ser vilken information som hör till vad. Tabellen behöver inte heller vara av typen table. Sidan innehåller ett korrekt formaterat kontaktformulär som ska vara en där man kan fylla i namn, telefonnummer, email, företag och meddelande. Inputfälten ska vara av rätt type och ha labels.
Mina val av breakpoints på min webbsida utgick jag ifrån att min Header text "Arboreal" och logotypen vart för stora, så objekten ändrade position. detta åtgärdade jag genom att minska storleken på vardera. utifrån det krävdes det inte fler media queries för att göra sidan responsiv.

Utifrån den feedback jag fick åtgärade jag i css mycket dubbel kommando på storlek, samt att jag ändrade en fast text där det stod First name, Surname, email etc. till att ha placeholders så att texten försvinner när man börjar skriva i den inputen.
