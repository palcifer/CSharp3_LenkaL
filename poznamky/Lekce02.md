Základy webovych technologii
- Internet: Distribuovana sit ruznych pocitaci, routeru a serveru, ktora nema centralizovaneho majitele
- IP Adresa: Internet Protocol Address
- Kazda strana komunikace ma svoju IP adresu
- Je to jenom cislo. Ale maju maximalne cislo, repzretentovane pomocou 32 bit - rychle nam dochazi
- ale bude migrace na novou verzi IP adresy (128 bit)
- DNS - Domain Name System - aby sme nemuseli mat "telefonny zoznam" adries - ale DNS dam meno webu, na ktory sa chcem pripojit a on mi "da" IP adresu
- prohlizece: URL - Uniform Resource Locator
- struktura: protocol (https), doména (example.com), port na domene (vychozi je 80), cesta, query parametry, fragment/anchor (napr navigace v ramci cele webove stranky)
- na stranke - developer tools -> Network - vidim tam requesty atd (dev mode ctrl + shift + i)
- port je jeden z pristupovych bodov tej domey - reprezentovany 16bity - ruzne porty pujdou na jinych serverech. http pouziva 80, ale nasa lokalna aplikace bude pouzivat iny a lokalne si pustat nekolik aplikaci zaraz
- http: HyperText Transfer Protocol - format, ktorym sa na internete kominukuje - posielame nim informace zo serveru na klienta a tak
- browser nemusi byt jediny klient, ktory k internetu pristupuje
- html - HyperText Markup Language - jazyk, ktorym definujeme strukturu webu
- potom css, javascript
- "Browser publishes the DOM" (Document Object Model) - interni struktura dokumentu v ramci prohlizece - udela si strom objektu, jak su do sebe zanorene
- POST request - ked sa snazime poslat nove data
- Web API: Application Programming Interface
- zpusob, jak mozeme data requestovat a posielat
- klient (prohlizec, aplikace...cokoliv, co ma pristup k internetu) -> request na server (to bezi na inom pocitaci na internete)
- API je nejake rozhrani, cez ktore mozeme komunikovat
- REST api - REpresentational State Transfer
- URI - Uniform Resource Identifier - ale to už neviem, čo má byť
- HTTP metody: operace Create = POST
- Read = GET
- Update = PUT
- Delete = DELETE
- ked posleme http request, pride nam naspatek Status Code: 200 je OK, 400 je chyba na nasej strane, 500 nieco sa fatalne pokazilo
- existuje plny seznam status kodov
