Proposta de projecte a desenvolupar  
Cognom i nom:  **Josep Gregori Bertomeu**
Cicle formatiu:  2on DAW
Any: Curs 2023-2024
TÌTOL:  Videogame Oliva's Shop (VOS)
**1. Objectius del projecte  
Explicar clarament que és el projecte i que és el que va a realitzar.**  
La funció del projecte principalment consistira en dues parts, la de generar un api amb symfony per a gestionar tots els elements d'una tenda de videojocs usuaris, plataformes que serà un crud, plataformes, usuaris i videojocs totes aquestes parts només podran ser gestionades per un usuari administrador. Després els usuaris compradors podran llegir les dades, comprar u votar jocs. La part de comprar utilitzaré possiblement Paypal o qualsevol sistema gratuït de pagament amb unes crides a l'api de Paypal. L'api de la tenda la generaré jo usant symfony com ha framework. Necessitaré un api per a tindre informació dinàmica per al projecte. Perquè no siga una pàgina estàtica.  
La següent part del projecte la realitzaré usant bootstrap e react. Perquè els usuaris administradors i clients podent interactuar en la pàgina web.  
He decidit que sega una mescla de les 3 assignatures perquè volia desenvolupar una pàgina amb tot l'ho apres durant el curs.
**2. Característiques del projecte.  
Quines característiques tècniques te el projecte, quin és el seu funcionament,etc.**
Les crides de l'api seran un crud per a usuaris que només serà accessible per usuaris de rol administrador de la tenda en aquest cas si l'usuari comprador fa un ús no adequat dels servicis podrà ser vanejat, deixar reviews bomba.  
Un crud per als videojocs, els generes i plataformes on els administradors tindran total control per a crear, actualitzar informació o borrar. Els usuaris normals nomes podran fer ressenyes per a videojocs, votacions o compres són l'únic moment en què interactuaran.
**3. Motivació a realitzar aquest projecte.  Perquè has escollit este projecte.**
**Motivació a l'hora de desssarrollar el projecte:**
Lo que m'ha motivat a realitzar el projecte es principalment ampliar els meus coneixements de com funciona una tenda online i per a facilitar l'enfoc a l'hora de treballar en el projecte  he decidit que siga de videojocs ja que es un tema que m'agrada.
**4. Abast del projecte  
Quines tecnologies i en quins mòdul està basat el projecte**
Com ja he dit en l'apartat anterior utilitzaré symfony per a generar l'api, React per a generar tota l'interfaz i realitzar totes les consultes de l'API amb l'ajuda de bootstrap i Css per a donar-li un caràcter més personal als estils de la web.
**5. Funcionalitats del projecte:**
Gestionar videojocs, plataformes, generes, resenyes, compres i clients de un pàgina de videojocs.
**6. Cridaes a l'API.**
|Nom de l'enllaç|Tipus de petició| Enllaç que tidrà la cridada|Funcionalitat|
|---|---|---|---|
|api_llistar_usuaris|GET| /api/v1/usuaris|Llistar usuaris|
|api_conseguir_usuari|GET|/api/v1/usuari/{id}|Conseguir usuari amb unid|
|api_insertar_usuari|POST|/api/v1/usuari/nou|Afegir un usuari|
|api_modificar_plataforma|PUT|/api/v1/plataforma/{id}/editar|Editar un usuari|
|api_llistar_generes|GET|/api/v1/generes|Llistar generes|
|api_borrar_genere|DELETE|/api/v1/genere/{id}|Borrar genere amb un id|
|api_conseguir_genere|GET| /api/v1/genere/{id}|Conseguir un genere|
|api_insertar_genere|POST|/api/v1/genere/nou|Insertar un genere|
|api_actualizar_genere|PUT|/api/v1/genere/{id}/editar|Editar un genere|
|api_llistar_plataformes|GET|/api/v1/plataformes|Llistar plataformes|
|api_conseguir_plataforma|GET|/api/v1/plataforma/{id}|Conseguir una plataforma|
|api_insertar_plataforma|POST|/api/v1/plataforma/nou|Insertar una plataforma|
|api_borrar_plataforma|DELETE|/api/v1/plataforma/{id}/borrar|Borrar plataforma|
|api_modificar_plataforma|PUT|/api/v1/plataforma/{id}/editar|Editar una plataforma|
|api_llistar_videojocs|GET|/api/v1/videojocs|Conseguir un videojoc|
|api_conseguir_videojoc|GET|/api/v1/videojoc/{id}|Conseguir un videojoc|
|api_insertar_videojoc|POST|/api/v1/videojoc/nou|Insertar un videojoc|
|api_borrar_videojoc|DELETE|/api/v1/videojoc/{id}/borrar|Borrar un videojoc|
|api_modificar_videojoc|PUT|/api/v1/videojoc/{id}/editar|Editar un videojoc|
La part d'enllaçament entre els usuaris i els videojocs per a comprar, votar i resenyar videojoc encara no han sigut decidides.

 
 
**7. Valor afegit **

El valor afegit de la meva pàgina va en generar contingut multimèdia de manera habitual en plataformes com Instagram, Tiktok o YouTube realitzant tops de videojocs, curiositats, etc. A través del qual puc generar publicitat només invertint temps.

**8. Respostes als comentaris.**
Javi: He tractat de passar el corrector aquesta vegada. Respecte a valor afegit jo el que habia pensat ara sobre el projecte que aportes tu que no aporten els demés he esta pensant en alguna cose i es aquest la que me s'habia ocurrit se que esta fora del tema en questio per esta relacionat en el posicionament parlat en la teva assignatura i facilitat la visibilitat. Tindra un carret de compra i el pagament s'utilitzara paypal si puc fer probes com ha desarrollador després justificare quina plataforma utilitzare i per que.  
Vicent: Espere que haja quedat ara clar el contingut. Trobe que te mes coses.  
Joan: l'api sera exclusivament per a us intern del projecte i la dissenye jo amb symfony.  
David: la part de l'api la requerisc per a tindre informació dinamica i volia reforçar els coneiximents adquirits durant el curs. La diferencia respecte a tendes con games es per exemple els ve videojocs de segona mà i jo em dedicare a vendre videojocs digitals per a les distintes plataformes seria mes paregut a tendes com steam que a game. Però no me s'ha ocurrit algo en lo que inovar.
Logotip:
![[icon256x256.webp]]
Colors corportatius:
![[palette.png]]
Paleta de colors en orden d'esquerra a dreta:
1. 2b2d42
2. 8d99ae
3. edf2f4
4. ef233c
5. d90429

Data: 26/09/2022
Signat:  Josep Gregori Bertomeu
