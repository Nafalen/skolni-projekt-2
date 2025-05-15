# Školní-projekt/2

# 1. Cíl projektu 
Cílem projektu bylo vytvořit jakou si topologii určité sítě která by mohla být v praxi použitelná. 
# 2. Stav projektu
Projekt je ve stavu dokončenný, ale dal by se klidně dále rozšiřovat a zdokonalovat jsou zde udělány dvě sítě main a branch a je zde naznačený cloud.
 
# 3. Popis projektu
Zde je obrázek mého projektu:
<img width="1446" alt="Image" src="https://github.com/user-attachments/assets/36805fb0-041f-4cf5-ac69-e589c91823eb" />
Jsou zde popsané kde a jaké jsou VLAN, adresy, místnosti a další.
## Popis:
Popis určitých věcí zde osekám o části které jsem vysvětloval v minulém projektu jen je zde zmíním že tu jsou ale znova je vysvětlovat nebudu zmíním jenom ty které jsou nové a ty které jsem změnil za něco jiného.
### Zařízení a propojení:
Je zde jedna hlavní síť a jedna vedlejší + cloud hlavní síť a vedlejší síť má jeden L3 switch na který jsou napojeny klasické switche jsou zde virtuálně odděleny do podsítí a pod každým switchem jsou zařízení jako počítač tiskárna a někde i server.
Všechny routery jsou propojeny DCE kabelem s nastaveným časováním a zbylá klasickými mohly by zde být i klidně další zařízení jako AP atd.

### Aresace a Virtuální LAN: 
Adresace je zde mezi routery 10.10.10.x/30 standartní adresa mezi routery a v cloudu je podobná 20.0.0.0/30. pak zde mámé klasické soukromé 192.168.x.x.
Na každem L2 switchi je udělán VLan pro oddělení sítě.

### Konfigurace a funkce:
Jak jsem zmínil je zde VLAN který je vysvětlen v minulém projektu i konfigurace.
Je zde i DHCP, DNS a zbytek jako ssh zde není protože to není důležité.
Co jsem vyměnil je ale OSPF protokal za RIP který je jednoduší narozdíl od OSPF ktrerý sleduje rychlost komunikace v sítí rip protokol se jen zaměřuje na vzdálenost mezi routery chtěl jsem zde využít aspoň něco jiného než minule tak jsem použil tento i když jedna výhoda se zde najde a to je menší využití paměti a CPU.

### Závěr:
Tento projekt nebyl až tak propracovaný jako ten minulý ale nechtělo se mi dělat něco zvlášt složité tak jsem chtěl jen vytvořil něco co by mohlo připomínat reálnou topologii sítě pokud by jste něco nepochopil řekněte mi ve škole a doporučuji se podívat na můj minulý projekt zde mužete více najít vysvětlení okolo třeba VLAN atd.  

### Dodatečné obrázky 
![Image](https://github.com/user-attachments/assets/cf446f70-0c9b-43f1-8214-a36ecd511596)
<img width="655" alt="Image" src="https://github.com/user-attachments/assets/76d2e429-5926-4643-a05c-f6fff9b58e86" />
# 4. členi
Pracoval jsem sám níže jsou uvedeny zdroje a citace. 
# 5. Citace
[1] Cisco. Online. S. 1. Dostupné z: https://www.cisco.com/#tabs-35d568e0ff-item-194f491212-tab. [cit. 2025-01-06].

[2] Cisco. Online. S. 1. Dostupné z: https://www.cisco.com/c/en/us/solutions/small-business/resource-center/networking/how-to-setup-network-switch.html. [cit. 2025-01-06].

[3] Gurutech Networking Training. Online. Dostupné z: https://www.youtube.com/@gurutechnetworks. [cit. 2025-01-06].

# 6. Zdroje 
Při vytváření projektu jsem částečně výcházel z mého minulého projektu.

Zdroje: 

https://www.cisco.com/#tabs-35d568e0ff-item-194f491212-tab   
https://www.cisco.com/c/en/us/solutions/small-business/resource-center/networking/how-to-setup-network-switch.html
https://www.cisco.com/c/en/us/td/docs/routers/access/800M/software/800MSCG/routconf.html
https://www.youtube.com/@gurutechnetworks 
