# Peliohjelmointiyrityksen työkalut

 ### Suunnittelu ja ohjelmointi
 Ohjelmointikieleksi valitsimme C#. Se on helppokäyttöinen ja helposti luettava kieli ja sillä pystyy ohjelmoimaan mitä vain, mutta on erittäin hyvä ja kykenevä eri sovellusten ja pelien ohjelmointiin. C#:lla voi myös tehdä verkkosivuja ja puhelinsovelluksia ja on laajuutensa ansioista nykyään erittäin suosittu kieli. C# tukee myös melkein kaikkia alustoja.
 
 C# käytetään paljon pelien valmistamineen Unity pelimoottorilla, joka on kaikista suosituin pelimoottori nykyään. Noin joka kolmas peli toimii ja on valmistettu Unityllä. Unity on kehittäyt myös paljon VR (Virtual Reality) pelejä.

 Unity on monialustainen pelimoottori, jolla voidaan ohjelmoida 2d peleistä - VR peleihin. Unity käyttää Nvidian PhysX fysiikkamoottoria. Unityssä voidaan käyttää kolmea eriä ohjelmointikieltä. Javascript (Unityscript), Boo ja C#. UnityScriptiä luullaan monesti JavaScriptiksi, vaikka ne ovatkin eri kieliä. Boo taas muistuttaa Pythonia ja C# taas Javaa. C-kieli on kuitenkin käytetyin kieli Unityssa. C# pärjää paremmin tehokkuudessa kuin UnityScript suorituskykynsä 
 ansioista. 
 
 ### Tektinkäsitely
 
 Monodevelop-unity valittiin tekstinkäsittelyohjelmaksi, kun se kuuluu Unityyn mitä käytetään pelien rakentamisessa. Monodevelop mahdollistaa myös verkkosivujen rakentamisen ja sovellusten koodaksen. Monodevelop tukee myös kaikkia alustoja ja tukee mahdollisimman montaa kieltä, mukaan lukien C#, mitä käytämme. Monodevelop näyttää koodien kirjoittamisen realiajassa myös ryhmissä.


 
 ### Jatkuva integraatio
 
 CI (continuous integration) on prosessi jonka tarkoituksena on helopottaa ja korjata koodien eri osien integroimista yhteen ohjelmistokehityksessä niin, että ohjelmisto toimii kokoajan vakaasti. CI-palvelinohjelmistot ovat tärkeitä vaikka jatkuva integraatio ei vaadi itseltään mitään työkaluja.
 
 CI:ksi valitsimme Jenkins. Jenkins on avoimeen lähdekoodiin perustuva CI. Jenkins mahdollistaa sen että vaikka koodia kirjoitetaan jatkuvasti, se tarkistaa että, koodi toimii silti eikä kaada ohjemia. Jenkins on yteensopiva Unityn kans joka mahdollistaaa työnteon mahdollisimman vähällä vaivalla. Jos ohjelmoinnissa ilmenee virhe, CI osaa kertoa mikä on väärin ja jättää kyseisen koodin pois ja kertoo työryhmälle että missä vika on. Tämän jälkeen koodi korjataa ja se laitetaan uudelleen eteenpäin . CI testaa kaikki koodit ennenkuin laittaa ne juoksemaan muitten koodien sekaan. Tämä kaikki mahdollistaa usean koodin yhtenäisen kirjoittamisen yhtä aikaa, jolloin tulosta tulee enemmän.
 
**Kehitys** --> Uusiversio --> **Versionhallinta** --> CI-prosessin käynnistys --> **Koontiversion muodostaminen** -->Testausten aloitus --> **Testaus** --> Raportointi --> **Kehitys** --> ...
 
 CIn käyttöönotto  varmistaa, etä ohjelmistotiimi voi tehä isoja ja monimutkaisia järjestelmiä, jotka ovat helposti hallittavia. Kuitenkaan yksinään CI ei riitä pelkästään täydellinen koodin jatkuvaan ja ketterään juoksuun.
 
 Jatkuva integraatio koostuu pääasiallisesti versiohallinnasta, automatisoidusta koostamisesta sekä testauksesta.

 
