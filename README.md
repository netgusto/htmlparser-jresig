# HTML Parser By John Resig (ejohn.org)

HTML Parser By John Resig (ejohn.org) wrapped as a Node.js module.

Original code by Erik Arvidsson, Mozilla Public License
<http://erik.eae.net/simplehtmlparser/simplehtmlparser.js>

    // Use like so:
    HTMLParser(htmlString, {
        start: function(tag, attrs, unary) {},
        end: function(tag) {},
        chars: function(text) {},
        comment: function(text) {}
    });

    // or to get an XML string:
    HTMLtoXML(htmlString);

    // or to get an XML DOM Document
    HTMLtoDOM(htmlString);

    // or to inject into an existing document/DOM node
    HTMLtoDOM(htmlString, document);
    HTMLtoDOM(htmlString, document.body);
