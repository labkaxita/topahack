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

Kurtso guztian zehar hacklab eta gainontzeko ikastaroetan ikasi degun guztia elkartrukatzeko hacklaben eta sateliteen arteko topaketatxo bat antolatzea otu zaigu, petit komite.


NOIZ?
=====

.. role:: spoiler
.. role:: spoiler-data

Parametro egokia emanez, goiko pythoneko funtzioak topahackaren hasiera bueltatuko du emaitza gisa (:spoiler:`spoiler` :spoiler-data:`topahack('- -   ---- -  -  - - -  -  -- -') 2013-07-19 14:00:13`). ~48h irauten ditu.


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

Lo egiteko gaztetxean.
Dutxatzeko jendearen etxeetan.
Egunero gosari, bazkari eta afariak Lakaxitan elkartzen diren barazki koperatiben eskutik (aldatsa, xixare, barealaia).


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


Goiko JS kodetxoak buruausteak bakarrik ematen badizkizu, bidali eposta bat `lakaxita@gaztetxea.org` helbidera hurrengoa betez::

    Ondorengo otorduetan egongo naiz:

    ostirala-bazkaria: false/true
    ostirala-afaria: false/true
    ostirala-lo: false/true
    larunbata-bazkaria: false/true
    larunbata-afaria: false/true
    larunbata-lo: false/true
    igandea-bazkaria: false/true


------------------------------------------------------------------------------------

ANTOLATZEA LORTUKO DUTE?
========================

.. image:: https://enekenbat.cc/file/download/227887
    :alt: Lakaxita Gaztetxea
    :target: http://www.lakaxita.org/

.. image:: https://enekenbat.cc/file/download/227886
    :alt: Labkaxita Hacklaba
