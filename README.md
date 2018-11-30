# Actual Domain Prices
The real cost of each TLD (top-level-domain). Find out how much your registrar marks up your domain prices.

This list is in **US Dollars**.

|TLD|price (USD)|
|---|---|
|academy|20|
|accountants|66|
|apartments|33|
|actor|25|
|agency|13|
|associates|20|
|auction|20|
|band|15|
|bike|20|
|bargains|20|
|boutique|20|
|bingo|33|
|builders|20|
|cafe|20|
|business|5|
|cab|20|
|bar|50|
|camera|33|
|camp|33|
|capital|33|
|cards|20|
|care|20|
|catering|20|
|careers|33|
|cash|20|
|casino|99|
|ceo|70|
|center|13|
|church|20|
|chat|20|
|cheap|20|
|city|13|
|cleaning|33|
|claims|33|
|coach|33|
|clothing|20|
|clinic|33|
|codes|33|
|coffee|20|
|company|5|
|computer|20|
|condos|33|
|college|45|
|construction|20|
|consulting|20|
|contractors|20|
|cool|20|
|community|20|
|coupons|33|
|creditcard|99|
|cruises|33|
|credit|66|
|dance|15|
|dating|33|
|delivery|33|
|deals|20|
|design|33|
|democrat|20|
|diamonds|33|
|dental|33|
|digital|20|
|discount|20|
|direct|20|
|directory|13|
|doctor|66|
|dog|33|
|energy|66|
|domains|20|
|education|13|
|email|13|
|enterprises|20|
|engineering|33|
|equipment|13|
|estate|20|
|exchange|20|
|events|20|
|express|20|
|exposed|13|
|fail|20|
|expert|33|
|family|15|
|finance|33|
|farm|20|
|fish|20|
|financial|33|
|fitness|20|
|football|13|
|fans|50|
|florist|20|
|flights|33|
|forsale|20|
|foundation|20|
|fund|33|
|furniture|33|
|gallery|13|
|futbol|8|
|fyi|13|
|games|12|
|fun|15|
|com|7.85|
|university|33|
|wtf|20|
|vacations|20|
|viajes|33|
|voyage|33|
|gifts|20|
|gmbh|20|
|gold|66|
|golf|33|
|gripe|20|
|gratis|13|
|group|13|
|guru|20|
|healthcare|33|
|haus|20|
|holdings|33|
|hospital|33|
|holiday|33|
|house|20|
|immo|20|
|industries|20|
|immobilien|20|
|institute|13|
|info|10.84|
|insure|33|
|irish|10|
|investments|66|
|ink|19|
|jewelry|33|
|land|20|
|kitchen|33|
|kaufen|20|
|lighting|13|
|limited|20|
|lease|33|
|life|20|
|love|20|
|ltd|13|
|limo|33|
|loans|66|
|maison|33|
|marketing|20|
|mba|20|
|media|20|
|net|9.77|
|moda|20|
|money|20|
|movie|200|
|network|13|
|online|25|
|news|15|
|parts|20|
|partners|33|
|org|9.93|
|photography|13|
|photos|13|
|press|49|
|pizza|33|
|plumbing|33|
|properties|20|
|plus|20|
|reise|66|
|recipes|33|
|reisen|13|
|report|13|
|vision|20|
|republican|20|
|rentals|20|
|repair|20|
|rocks|8|
|restaurant|33|
|sale|20|
|salon|33|
|reviews|15|
|rip|12|
|run|13|
|sarl|20|
|schule|13|
|watch|20|
|productions|20|
|school|20|
|shoes|33|
|shopping|20|
|solutions|13|
|soccer|13|
|social|20|
|works|20|
|solar|33|
|singles|20|
|supplies|13|
|studio|15|
|services|20|
|style|20|
|supply|13|
|support|13|
|surgery|33|
|systems|13|
|rest|25|
|tax|33|
|technology|13|
|tennis|33|
|world|20|
|theater|33|
|town|20|
|tires|66|
|toys|33|
|training|20|
|site|20|
|show|20|
|tips|13|
|wine|33|
|team|20|
|today|13|
|vin|33|
|glass|33|
|graphics|13|
|guide|20|
|hockey|33|
|host|65|
|international|13|
|jetzt|13|
|legal|33|
|live|15|
|management|13|
|memorial|33|
|ninja|12|
|pictures|7|
|pub|20|
|rent|45|
|tools|20|
|villas|33|
|taxi|33|
|tienda|33|
|ventures|33|
|zone|20|
|security|2000|
|space|15|
|tech|35|
|store|40|
|video|15|
|storage|500|
|theatre|500|
|wiki|19|
|website|15|
|tours|33|
|xyz|8|


This repo is an effort to list the *real* costs that registries put on their TLDs. Since almost all registrars are for-profit operations, they usually increase the price of domains by a few dollars to turn a profit. Another tactic is drastically lowering the price for new customers (*cough* godaddy, 1and1) then effectively performing a bait-and-switch with expensive renewal costs.

This list is aggregated from prices shown via the [Cloudflare Registrar](https://cloudflare.com/registrar), which guaranteed to only charge you what the registry charges (+ icaan fee) for the domain. Unfortunately, [as said here](https://developers.cloudflare.com/registrar/domain-registration/tld-support/), Cloudflare can't directly show each TLD price in their marketing material, so I made this list.

For programmatic use, there is a text file named `list.txt` in the format of `tld:price`.

#### Terminology: 

- **Registry**: https://icannwiki.org/Registry This is who actually runs a TLD. They choose how much to charge registrars for purchasing domains for their TLDs.
- **Registrar**: https://icannwiki.org/Registrar The company/website where you purchase a domain. Facilitates actually getting your domain registered with the Registry operators.

#### Unsupported TLDs

Some TLDs are not supported by Cloudflare, so we won't be able to get every TLD's wholesale price. See https://www.cloudflare.com/tld-policies/

#### Contributing

To contribute, make a pull request by editing this file AND `list.txt` with the TLD and the TLD's price.

Please ensure the price is USD. If the CF transfer page shows a different currency, use a currency converter and make a note in your PR what currency you converted from.
