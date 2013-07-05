.. raw:: html

    <img src="https://enekenbat.cc/file/download/227885" title="- -   ---- -  -  - - -  -  -- -" />


.. code:: python

    from datetime import datetime

    def topahack(dashes):
        binary = ''.join([ '1' if char == '-' else '0' for char in dashes ])
        timestamp = int(binary, 2)
        time = datetime.fromtimestamp(timestamp)
        return time.isoformat()


TOPAHACK?
=========

Kurtso guztian zehar hacklab eta gainontzeko ikastaroetan ikasi degun guztia elkartrukatzeko hacklaben eta inguruko sateliteen arteko topaketatxo bat antolatzea otu zaigu, petit komite. Proiektu ezberdinak daude proposatuta eta bakoitza bere interes berdinak dituen pertsonekin elkartzea da ideia.


NOIZ?
=====

Ostiralean bazkari batekin hasiko gera eta igandean beste bazkari batekin bukatuko dugu. **2013-07-19 14:00:13** -- **2013-07-21 14:00:13**. Ea aurkitzen duzun goiko pythoneko funtzioak hasiera data bueltatzeko jaso behar duen parametroa!


NON?
====

`Lakaxita Gaztetxean <http://www.lakaxita.org/>`_ `(43.34077477455139, -1.8035200238227844) <http://osm.org/go/b~nOL9yzq-->`_, Irunen.


ZER?
====

Dagoeneko proiektu ezberdinak planteatu diren arren, zerrenda guztiz irekia dago, beraz proposamenik baduzu, bota lasai!


Dagoeneko aurkeztutako proiektuak:
    - pankarten inprimagailua
    - jaialdien prestaketa (audioa, bideoa, argiak, etab.)
    - bideo edizioa blenderrekin
    - guifi.net-eko supernodoen konfiguraketa
    - enekenbat.cc webgunearen euskararatzea


Modu orientatiboan erabiliko dugun parrila ondorengoa da:

+----------------------+---------------------+--------------------------------+
| ostirala             | larunbata           | igandea                        |
+======================+=====================+================================+
|                      | gosaria             | gosaria                        | 
+----------------------+---------------------+--------------------------------+
|                      | **proiektuak**      | **proiektuak**                 | 
+----------------------+---------------------+--------------------------------+
| bazkaria             | bazkaria            | bazkaria                       | 
+----------------------+---------------------+--------------------------------+
| aurkezpena + subiraut| **proiektuak**      | kolonbiarekin elkarrizketa?    | 
| za teknologikoa      |                     |                                | 
+----------------------+---------------------+--------------------------------+
| afaria               | afaria              |                                | 
+----------------------+---------------------+--------------------------------+
|                      | jaitxoa             |                                | 
+----------------------+---------------------+--------------------------------+


NOLA?
=====


Lo egiteko
----------

Gaztetxean bertan lo egiteko aukera izango dugu. Nahi duenak ere kanpoan jarri daiteke kanpin dendarekin. Beharrezkoa izanez gero, hacklabeko kideen etxeetan geratzea ere posible da.


Dutxatzeko
----------

Gaztetxean bertan ez dago dutxarik beraz dutxatzea nahi bada, Irunen bizi den norbaiten etxera joatea beharrezkoa izango da.


Jateko
------

Egunero gosaria, bazkaria eta afaria egongo da Lakaxita Gaztetxean elkartzen diren barazki koperatiben eskutik (Aldatsa, Xixare eta Barealaia).

+----------------------------+----------------------------+--------------------------------+
| ostirala                   | larunbata                  | igandea                        |
+============================+============================+================================+
|                            | **gosaria**                | **gosaria**                    | 
+                            +                            +                                +
|                            | - Zukuak                   | - Zukuak                       |
+                            + - Kafea                    + - Kafea                        + 
|                            | - Beizamako ogia           | - Beizamako ogia               |
+                            + - Untatzeko gauzak         + - Untatzeko gauzak             + 
|----------------------------|----------------------------|--------------------------------|
+ **bazkaria**               + **bazkaria**               + **bazkaria**                   + 
|                            |                            |                                |
+ - Entsalada buffeta        + - Entsalada buffeta        + - Entsalada buffeta            +
| - Arroza berdurakin        | - Cous-cous                | - Tortila patata               | 
+ - Fruta (era desberdinetan)+ - Fruta (era desberdinetan)+ - Fruta (era desberdinetan)    +
|----------------------------|----------------------------|--------------------------------|
+ **afaria**                 + **afaria**                 +                                +
|                            |                            |                                |
+ - Entsalada buffeta        + - Entsalada buffeta        +                                +
| - Falafel tomate saltsan   | - Patatak saltsa-berdean   |                                | 
+ - Fruta (era desberdinetan)+ - Fruta (era desberdinetan)+                                +
|----------------------------|----------------------------|--------------------------------|


Elkartrukatzeko
---------------

Lakaxitan barne sarea egongo da. Bertan Owncloud eta Ampache exekutatzen duen RaspberryPy bat egongo da 1TBeko disko gogorrarekin. Interneterako konexioa lotzen ere saiatuko gera.


ETORRIKO ZEA?
=============

.. raw:: html

    <script type="text/javascript">
        function sendMail() {
            var subject = "topahack";
            var body = "Ondorengo otorduetan egongo naiz:\r\n\r\n";
            var form = document.getElementsByTagName('form')[0];
            for (var i = 0; i < form.length; i++) {
                if (form[i].type == 'checkbox') {
                    body += form[i].name + ': ' + form[i].checked + '\r\n';
                };
            }
            var uri = "mailto:lakaxita@gaztetxea.org";
            uri += "?subject=" + encodeURIComponent(subject);
            uri += "&body=" + encodeURIComponent(body);
            window.open(uri, '_self');
            alert("Bidali gaitzazu sortu zaizun eposta, idatzi lasai bururatzen zaizun beste edozer gauza.");
        };
    </script>

    <form method="post" enctype="txt/plain" onSubmit="sendMail();">
        <ul>
            <li><input type="checkbox" name="ostirala-bazkaria"/>ostiraleko bazkarira</li>
            <li><input type="checkbox" name="ostirala-afaria"/>ostiraleko afarira</li>
            <li><input type="checkbox" name="ostirala-lo"/>ostiralean lotara</li>
            <li><input type="checkbox" name="larunbata-bazkaria"/>larunbateko bazkarira</li>
            <li><input type="checkbox" name="larunbata-afaria"/>larunbateko afarira</li>
            <li><input type="checkbox" name="larunbata-lo"/>larunbatean lotara</li>
            <li><input type="checkbox" name="igandea-bazkaria"/>igandeko bazkarira</li>
        </ul>
        <input type="submit" name="submit" value="Bidali!"/>
    </form>


.. note:: Goiko JS kodetxoak buruausteak bakarrik ematen badizkizu, bidali eposta bat `lakaxita@gaztetxea.org` helbidera hurrengoa betez

    Ondorengo otorduetan egongo naiz:
        - ostirala-bazkaria: false/true
        - ostirala-afaria: false/true
        - ostirala-lo: false/true
        - larunbata-bazkaria: false/true
        - larunbata-afaria: false/true
        - larunbata-lo: false/true
        - igandea-bazkaria: false/true


------------------------------------------------------------------------------------

ANTOLATZEA LORTUKO DUTE?
========================

.. image:: https://enekenbat.cc/file/download/227887
    :alt: Lakaxita Gaztetxea
    :target: http://www.lakaxita.org/

.. image:: https://enekenbat.cc/file/download/227886
    :alt: Labkaxita Hacklaba
