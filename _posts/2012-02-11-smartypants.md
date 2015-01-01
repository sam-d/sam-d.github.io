---
title: Deutscher Schlaumeier/ SmartyPants auf deutsch
summary: Ich habe ein Python Paket auf deutsche Typographie umgestellt
date: 2012-02-11
tags: code
permalink: /2012/02/11/de/deutscher-schlaumeier-smartypants-auf-deutsch/
---

Um diesen Blog zu schreiben benutze ich ein Markdown Plugin sowie das
smartypants Plugin um die korrekten Anführungszeichen zu setzen. Allerdings
musste ich zu meinem Erstaunen feststellen, das man hier nur die englischen
Anführungszeichen setzten kann ohne Möglichkeit diese Einstellung zu ändern.

Ich habe nun erstmal, wie viele Andere auch (z.B. [Peter Unruh][1] mit dem
Wordpress Typogrify Plugin) meine eigene Not gelindert und die
Python-Implementierung des smartypants Modul an die deutschen Gegebenheiten
angepasst. Den Kode findet Ihr auf meinem [GitHub][2]. Das Ziel wäre es eine
Version zu schreiben, die basierend auf der Eingabesprache ('locale') die
richtigen Voreinstellung vornimmt. Für mich die einzige elegante Lösung.

Ich hoffe der Kode ist auch Anderen nützlich!

[1]: http://www.peterunruh.de/blog/webtypografie-richtige-zeichensetzung/ "Peter Unruh's Blog"
[2]: https://github.com/sam-d/smartypants-german "Mein GitHub"
