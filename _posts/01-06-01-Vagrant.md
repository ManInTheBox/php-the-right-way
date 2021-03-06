---
isChild: true
---

## Vagrant {#vagrant_title}

Pokretanje vaše aplikacije u različitim okruženjima prilikom razvoja i produkcije može dovesti do čudnih bagova koji 
iskaču kada radite uživo. Takođe je nezgodno održavati ažurnim različita razvojna okruženja sa istom verzijom za sve 
korišćene biblioteke kada radite sa timom programera. 

Ako razvijate na Windowsu a objavljujete na Linux (ili bilo čemu što nije Windows) ili razvijate u timu, trebalo bi da 
razmotrite korišćenje virtuelne mašine. Ovo zvuči komplikovano, ali korišćenjem [Vagrant-a][vagrant] možete podesiti 
jednostavnu virtuelnu mašinu u samo par koraka. Ovi osnovni boksevi onda mogu da se podese ručno, ili pomoću 
"provisioning" softvera kao što je [Puppet][puppet] ili [Chef][chef] koji će ovo uraditi umesto vas. Provisioning 
osnovnog boksa je sjajan način da obezbedite da će višestruki boksevi biti podešeni na identičan način i eliminiše 
potrebu da održavate komplikovane komandne spiskove za podešavanje. Možete takođe i da "uništite" vaš osnovni boks i da 
ga rekonstruišete bez mnogo ručnih koraka, čime olakšavate pravljenje "sveže" instalacije.

Vagrant kreira šerovane foldere koji služe za deljenje koda između hosta i virtuelne mašine, što znači da možete da 
kreirate i editujete vaše fajlove na host mašini a onda pokrenete kod na virtuelnoj mašini.

[vagrant]: http://vagrantup.com/
[puppet]: http://www.puppetlabs.com/
[chef]: http://www.opscode.com/
