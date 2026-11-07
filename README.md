# Jemná pauza — produkční statický web

Statický jednostránkový web pro nasazení na GitHub + Vercel. Není potřeba instalovat knihovny, nastavovat build command ani připojovat analytické/cookie nástroje.

## Nasazení

1. Nahrajte obsah tohoto ZIPu do kořene GitHub repozitáře.
2. Ve Vercelu importujte repozitář jako statický web (preset Other; bez build command).
3. Před indexací nahraďte všechny výskyty `https://your-domain.example` v `index.html`, `robots.txt` a `sitemap.xml` skutečnou veřejnou doménou. Jde o záměrný placeholder, protože produkční doména zatím nebyla zadána.
4. V patičce doplňte provozovatele a IČO; obě položky jsou označené `[OVĚŘIT]`.
5. Po nasazení odešlete `https://VAŠE-DOMÉNA/sitemap.xml` do Google Search Console.

## Soubory

- `index.html` — obsah, lokální SEO, JSON-LD pro Liberec a Prahu, nabídka a rezervace
- `site.css` — lokální styly, bez externích fontů
- `site.js` — lehký vanilla JavaScript pro výběr salonu a služby
- `assets/jemna-pauza-touch.webp` — hero fotografie
- `robots.txt`, `sitemap.xml` — připravené pro doplnění finální domény

Rezervace vedou do Reservia. Telefonní odkazy jsou nativní `tel:+420702961365`; zprávy vedou přes WhatsApp. Web neobsahuje cookie lištu ani analytické/marketingové skripty třetích stran.
