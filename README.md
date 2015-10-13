# CSS för Prologs anmälningssystem

Vi kom fram till att det är lite coolare att jobba med CSS i ett Git-repository, så vi gör det från nu.

## Attackguide Git

Git har en viss vokabulär, det gör insteget lite högre, men också att saker blir lättare att googla.

Jag tänker konsekvent skriva på svengelska i den här guiden, för att förhoppningsvis minska förvirringen lite.

### Komma igång

För att ändra på filerna i ett repository, skapa en klon av det på din lokala maskin. För att skapa en klon av det här repot, gör såhär:

```bash
git clone git@github.com:Rembane/a-style-of-prolog.git
```

Ändra på filer som vanligt med din favorittexteditor, när du börjar känna dig nöjd kan du committa dina förändringar lokalt. Så kommer Git ihåg dem åt dig.

Metoden jag använder här är en av många, så om du ser andra varianter fungerar de förmodligen också bra, men jag trivs med den här.

Den kommer att be dig skriva ett meddelande som förklarar vad du gjort, det får du väldigt gärna göra för att jag ska kunna lista ut vad du gjort, men det är inte dödsviktigt.

```bash
git commit -a
```

För att skicka ändringarna online, så behöver de pushas dit med hjälp av det här kommandot:

```bash
git push
```

Jag tror ovanstående är det du behöver för att komma igång, sen kommer det hända lustiga saker och då är det bara att hojta så tar vi det därifrån.

Apropå commit-meddelanden: https://xkcd.com/1296/

En lite längre attackguide: https://rogerdudler.github.io/git-guide/
