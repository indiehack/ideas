# Internal Stackshare

Chybi mi pekny prehled projektu a technologii v CN. Hrozne rad bych videl neco jako http://stackshare.io/ebay/ebay.

Aplikace by zobrazovala projekty, technologie na nich pouzite a klicove lidi, kteri se o ony technologie na projektu staraji (guru level).

V idealnim pripade by do aplikace stacilo nahrat pom.xml, build.xml, seznam knihoven, package.json a podobne a aplikace by sama zakladni stack vygenerovala. Samozrejme by melo byt mozne pridavat aplikace i rucne.

Vedle toho by existovala propojena DB lidi, ktery dane technologie ovladaji.

### Tech

Vazby Projekt x Technologie x Clovek

Technologie maji zavislosti : Spring JPA je zaroven Spring JPA, Spring a JPA - jak tohle modelovat? :)



###Deliverables
#### Web app
*   Aplikace, ktera mi nabidne prehledne informace o projektech a technologiich z ruznych pohledu
	*   tech cloud - nejpouzivanejsi technologie
	*   cesta od technologii k projektum a lidem
	*   cesta od projektu k technologiim a lidem
*   Editace projektu, technologii, lidi   

#### Data crunchers
Jednotlive crunchery, ktere analyzuji vstup (package.json), identifikuji technologie a priradi k projektu. Idealne by mely ulozit artefakt (package.json) aby se pote, co se aktualizuje DB technologii nebo samotny crucher, mohl analyza pustit znovu

**Maven cruncher**
Vstup : pom.xml
Pres XPath najdu //dependency


	<dependencies>
	    <dependency>
	        <groupId>org.springframework.data</groupId>
	        <artifactId>spring-data-jpa</artifactId>
	        <version>1.8.0.RELEASE</version>
	    </dependency>
	</dependencies>


=> Vytvarim technologii Spring Data s verzi 1.8.0 




 




