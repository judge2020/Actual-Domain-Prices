# Actual Domain Prices
The real cost of each TLD (top-level-domain). Find out how much your registrar marks up your domain prices.

This list is in **US Dollars**.

|TLD|price (USD)|
|---|---|
|academy|20|
|accountants|66|
|actor|25|
|agency|13|
|apartments|33|
|associates|20|
|auction|20|
|band|15|
|bar|50|
|bargains|20|
|bet|10.99|
|bike|20|
|bingo|33|
|black|34.99|
|blue|10.99|
|boutique|20|
|builders|20|
|business|5|
|cab|20|
|cafe|20|
|camera|33|
|camp|33|
|capital|33|
|cards|20|
|care|20|
|careers|33|
|cash|20|
|casino|99|
|catering|20|
|center|13|
|ceo|70|
|chat|20|
|cheap|20|
|church|20|
|city|13|
|claims|33|
|cleaning|33|
|clinic|33|
|clothing|20|
|coach|33|
|codes|33|
|coffee|21.50|
|college|45|
|com|7.85|
|community|20|
|company|5|
|computer|20|
|condos|33|
|construction|20|
|consulting|20|
|contractors|20|
|cool|20|
|coupons|33|
|credit|66|
|creditcard|99|
|cruises|33|
|dance|15|
|dating|33|
|deals|20|
|delivery|33|
|democrat|20|
|dental|33|
|design|33|
|diamonds|33|
|digital|20|
|direct|20|
|directory|13|
|discount|20|
|doctor|66|
|dog|33|
|domains|20|
|education|13|
|email|13|
|energy|66|
|engineering|33|
|enterprises|20|
|equipment|13|
|estate|20|
|events|20|
|exchange|20|
|expert|33|
|exposed|13|
|express|20|
|fail|20|
|family|15|
|fans|50|
|farm|20|
|finance|33|
|financial|33|
|fish|20|
|fitness|20|
|flights|33|
|florist|20|
|football|13|
|forsale|20|
|foundation|20|
|fun|15|
|fund|33|
|furniture|33|
|futbol|8|
|fyi|13|
|gallery|13|
|games|12|
|gifts|20|
|glass|33|
|gmbh|20|
|gold|66|
|golf|33|
|graphics|13|
|gratis|13|
|green|50|
|gripe|20|
|group|13|
|guide|20|
|guru|20|
|haus|20|
|healthcare|33|
|hockey|33|
|holdings|33|
|holiday|33|
|hospital|33|
|host|65|
|house|20|
|immo|20|
|immobilien|20|
|industries|20|
|info|10.84|
|ink|19|
|institute|13|
|insure|33|
|international|13|
|investments|66|
|io|45|
|irish|10|
|jetzt|13|
|jewelry|33|
|kaufen|20|
|kim|10.99|
|kitchen|33|
|land|20|
|lease|33|
|legal|33|
|lgbt|29.95|
|life|20|
|lighting|13|
|limited|20|
|limo|33|
|live|15|
|loans|66|
|love|20|
|ltd|13|
|maison|33|
|management|13|
|marketing|20|
|mba|20|
|media|20|
|memorial|33|
|mobi|12.99|
|moda|20|
|money|20|
|movie|200|
|net|9.77|
|network|13|
|news|15|
|ninja|12|
|online|25|
|org|9.93|
|partners|33|
|parts|20|
|pet|10.99|
|photography|13|
|photos|13|
|pictures|7|
|pink|10.99|
|pizza|33|
|plumbing|33|
|plus|20|
|press|49|
|pro|10.99|
|productions|20|
|promo|10.99|
|properties|20|
|pub|20|
|recipes|33|
|red|10.99|
|reise|66|
|reisen|13|
|rent|45|
|rentals|20|
|repair|20|
|report|13|
|republican|20|
|rest|25|
|restaurant|33|
|reviews|15|
|rip|12|
|rocks|8|
|run|13|
|sale|20|
|salon|33|
|sarl|20|
|school|20|
|schule|13|
|security|2000|
|services|20|
|shoes|33|
|shopping|20|
|show|20|
|singles|20|
|site|20|
|soccer|13|
|social|20|
|solar|33|
|solutions|13|
|space|15|
|storage|500|
|store|40|
|studio|15|
|style|20|
|supplies|13|
|supply|13|
|support|13|
|surgery|33|
|systems|13|
|tax|33|
|taxi|33|
|team|20|
|tech|35|
|technology|13|
|tennis|33|
|theater|33|
|theatre|500|
|tienda|33|
|tips|13|
|tires|66|
|today|13|
|tools|20|
|tours|33|
|town|20|
|toys|33|
|training|20|
|university|33|
|vacations|20|
|ventures|33|
|viajes|33|
|video|15|
|villas|33|
|vin|33|
|vision|20|
|voyage|33|
|watch|20|
|website|15|
|wiki|19|
|wine|33|
|works|20|
|world|20|
|wtf|20|
|xyz|8|
|zone|20|


This repo is an effort to list the *real* costs that registries put on their TLDs. Since almost all registrars are for-profit operations, they usually increase the price of domains by a few dollars to turn a profit. Another tactic is drastically lowering the price for new customers (*cough* godaddy, 1and1) then effectively performing a bait-and-switch with expensive renewal costs.

This list is aggregated from prices shown via the [Cloudflare Registrar](https://cloudflare.com/registrar), which guaranteed to only charge you what the registry charges (+ icaan fee) for the domain. Unfortunately, [as said here](https://developers.cloudflare.com/registrar/domain-registration/tld-support/), Cloudflare can't directly show each TLD price in their marketing material, so I made this list.

For programmatic use, there is a text file named `list.txt` in the format of `tld:price`.

#### Disclaimer

There *is* a big asterisk here.  In general, all [gTLDs](https://newgtlds.icann.org/en/applicants/global-support/faqs/faqs-en) have to be fair about the pricing they charge registrars. BUT, ccTLDs (country code TLDs) like `.io` **are NOT required to be fair about the pricing** they charge registrars. It is very likely that CF's `.io` price is higher than other registrars because the io registry decided to give other registrars a huge discount, or hiked the price Cloudflare pays because they don't like CF or something of the sorts. See [the discussion about this](https://community.cloudflare.com/t/io-domain-price-not-wholesale-price/54709?u=judge).

To add, there might be price disparities if CF is including the fees the credit card companies/paypal charge (eg. if the registry charges CF $10, CF might charge you $10.61 to cover the 2.9% + $0.30. the formula is `x=(y - (y * 0.029)) - 0.30`, where x is the price of the domain and y is the output price to charge the user), however, it's unknown if CF does this.

#### Terminology: 

- **Registry**: https://icannwiki.org/Registry This is who actually runs a TLD. They choose how much to charge registrars for purchasing domains for their TLDs.
- **Registrar**: https://icannwiki.org/Registrar The company/website where you purchase a domain. Facilitates actually getting your domain registered with the Registry operators.

#### Unsupported TLDs

Some TLDs are not supported by Cloudflare, so we won't be able to get every TLD's wholesale price. See https://www.cloudflare.com/tld-policies/

#### Contributing

To contribute, make a pull request by editing this file AND `list.txt` with the TLD and the TLD's price.

Please ensure the price is USD. If the CF transfer page shows a different currency, use a currency converter and make a note in your PR what currency you converted from.
