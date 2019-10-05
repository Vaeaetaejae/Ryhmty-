# GIT + GitHub ryhmätyö
###### Mikael Martimo, Mikko Väätäjä, Aale Lehtoniemi, Joonas Ahonen, Marika Takalo, Aapo Ahtinen
## Peliohjelmointiyrityksen työkalut

 ### Suunnittelu ja ohjelmointi
 Ohjelmointikieleksi valitsimme C#. Se on helppokäyttöinen ja helposti luettava kieli ja sillä pystyy ohjelmoimaan mitä vain, mutta on erittäin hyvä ja kykenevä eri sovellusten ja pelien ohjelmointiin. C#:lla voi myös tehdä verkkosivuja ja puhelinsovelluksia ja on laajuutensa ansioista nykyään erittäin suosittu kieli. C# tukee myös melkein kaikkia alustoja.
 
 C# on moderni ohjelmointikieli jonka kehitteli Anders Hejsberg 2000 vuonna Microsoftille. Se on pitkälti samanlainen kuin Java- kieli. Javan kehitteli Sun yhtiö mikä muuttui myöhemmin Oracleksi. Sun ei halunnut Microsoftin muokkaavan Javaa, niinpä he loivat oman kielen C#. Sen takia C# ja Java muistuttavat erittäin paljon toisiaan.
 
 C# käytetään paljon pelien valmistamineen Unity pelimoottorilla, joka on kaikista suosituin pelimoottori nykyään. Noin joka kolmas peli toimii ja on valmistettu Unityllä. Unity on kehittäyt myös paljon VR (Virtual Reality) pelejä.
 
 C#:issa on paljon erilaisia ominaisuuksia jotka tekevät sen helpoksi kieleksi. Se on korkealuokkainen ohjelmointikieli mitä on helppo lukea. Siitä on poistettu monia monimutkaisia ominaisuuksia ja ohjelmoitu ne helpommaksi, jotta ohjelmoijan ei tarvitse miettiä niitä. 

 Unity on monialustainen pelimoottori, jolla voidaan ohjelmoida 2d peleistä - VR peleihin. Unity käyttää Nvidian PhysX fysiikkamoottoria. Unityssä voidaan käyttää kolmea eriä ohjelmointikieltä. Javascript (Unityscript), Boo ja C#. UnityScriptiä luullaan monesti JavaScriptiksi, vaikka ne ovatkin eri kieliä. Boo taas muistuttaa Pythonia ja C# taas Javaa. C-kieli on kuitenkin käytetyin kieli Unityssa. C# pärjää paremmin tehokkuudessa kuin UnityScript suorituskykynsä 
 ansioista. 
 
 ### Github
 
 Käytämme Githubia ryhmässä koska, se on paikka missä voi säilyttää ja jakaa ohjelmistoprojekteja ilmaiseksi rajattomia määriä. Siellä voi luoda ykstyisiä tai julkisia ohjelmistoprojekteja. Keskeisin ominaisuus on GIT palvelin, eli hajautettu versionhallinta. Saman projektin kimpussa työskentelevät voivat tehdä samanaikaisesti muutoksia yhteen tai useampaan rinnakkain kehitettävään versioon ja sitten voi helposti nähdä kuka on tehnyt mitäkin muutoksia ja tarvittaessa voidaan ottaa vanha versio esiin tai palauttaa yksittäisiä muutoksia.
 
 Git on avoimen lähdekoodin versionhallinta järjestelmä, jonka loi Linus Trovalds, eli sama henkilö, joka loi myös Linuxin. Nimi Git tarkoittaa brittienglannin slangissa ääliötä, ja Linus Torvalds kertoi ottaneensa ohjelmistolle nimen Git, koska "olen egoistinen paskiainen, ja nimeän kaikki projektini itseni mukaan. Ensin Linux, sitten Git". Kun kehittäjät luovat jotain, he tekevät muutoksia koodiin jatuvasti vapauttaen uusia versioita ensimmäiseen versioon. Versiohallintajärjestelmät pitävät nämä tarkistukset suorina ja tallentavat muutokset keskusrekisteriin. Tämä mahdollistaa kehittäjien helpon yhteistyön, koska he voivat ladata uuden ohjelmistoversion, tehdä muutoksia ja ladata uusimman version. Jokainen kehittäjä näkee nämä uudet muutokset, lataa ne ja osallistuu niihin.
 
 Git on erittäin suosittu versionhallintajärjestelmä, koska siinä on useita etuja verrattuna muihin käytettävissä oleviin järjestelmiin. Se tallentaa muutokset tiedostoihin tehokkaammin ja varmistaa tiedostojen kunnon. 
 
  Git on komentorivityökalu, mutta keskustan, jonka ympärillä kaikki Gitin pyörivät asiat ovat hub-GitHub.com-sivusto, jossa kehittäjät tallentavat projektejaan ja verkostoaan samanmielisten ihmisten kanssa.

 
 ### Jatkuva integraatio
 
 CI (continuous integration) on prosessi jonka tarkoituksena on helopottaa ja korjata koodien eri osien integroimista yhteen ohjelmistokehityksessä niin, että ohjelmisto toimii kokoajan vakaasti. CI-palvelinohjelmistot ovat tärkeitä vaikka jatkuva integraatio ei vaadi itseltään mitään työkaluja.
 
 Jos ohjelmoinnissa ilmenee virhe, CI osaa kertoa mikä on väärin ja jättää kyseisen koodin pois ja kertoo työryhmälle että missä vika on. Tämän jälkeen koodi korjataa ja se laitetaan uudelleen eteenpäin . CI testaa kaikki koodit ennen kuin laittaa ne juoksemaan muitten koodien sekaan. Tämä kaikki mahdollistaa usean koodin yhtenäisen kirjoittamisen yhtä aikaa, jolloin tulosta tulee enemmän.
 
**Kehitys** --> Uusiversio --> **Versionhallinta** --> CI-prosessin käynnistys --> **Koontiversion muodostaminen** -->Testausten aloitus --> **Testaus** --> Raportointi --> **Kehitys** --> ...
 
 CIn käyttöönotto  varmistaa, että ohjelmistotiimi voi tehdä isoja ja monimutkaisia järjestelmiä, jotka ovat helposti hallittavia. Kuitenkaan yksinään CI ei riitä pelkästään täydellisen koodin jatkuvaan ja ketterään juoksuun.
 
 Jatkuva integraatio koostuu pääasiallisesti versiohallinnasta, automatisoidusta koostamisesta sekä testauksesta.
 
 ### Jenkins
 
 CI:ksi valitsimme Jenkinsin. Jenkins on avoimeen lähdekoodiin perustuva CI. Jenkins mahdollistaa sen että vaikka koodia kirjoitetaan jatkuvasti, se tarkistaa että, koodi toimii silti eikä kaada ohjemia. Jenkins on yteensopiva Unityn kanssa, joka mahdollistaa työnteon mahdollisimman vähällä vaivalla. Jenkins mahdollistaa myös verkkosivujen rakentamisen ja sovellusten koodauksen. Se tukee myös kaikkia alustoja ja tukee mahdollisimman montaa kieltä, mukaan lukien C#, mitä käytämme. Jenkins näyttää koodien kirjoittamisen realiajassa myös ryhmissä joka mahdollistaa ryhmässä työskentelyn.
 
 Jenkins on yksinkertainen jatkuvan integraation sovellus mikä tukee myös melkein kaikkia kieliä. 
 
 Vuonna 2004 Kohsuke Kawaguchi oli Javan ohjelmoia Sunilla. Kawaguchi oli väsynyt purkamaan koodeja kehitystyössään ja halusi löytää tavan tietää ennen koodin lähettämistä, toimiiko koodi. Kawaguchi suunnitteli automaattisen palvelun Javalle jotta se olisi mahdollista. Ohjelman nimi oli Hudson. Hudsonista tuli suosittu Sunissa ja levisi muihin yrityksiin avoimena lähdekoodina nopeasti.
 
 Vuonna 2011 riita Oraclen kans (entinen Sun) johti tilanteeseen jossa avoimeen lähdekoodiin perustuva Hudson jakautui kahtia. Tällöin syntyi Jenkins. Jenkinsistä tuli nopeasti suositumpi kuin Hudsonista ja Hudsoniin ei ole tehty päivityksiä enää vuoden 2016 jälkeen.
 

 
 

 
