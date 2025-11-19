---
layout: single
title: "Hallo Welt - oder mein Weg zu Jekyll"
---

## Meine Portfolio Website

Ich habe in den letzten Jahren sehr viel mit eigenen Websites experimentiert. Immer aus dem Antrieb heraus, dass ich eine Anlaufstelle im Netz haben möchte, auf der ich Gedanken und Ideen teilen kann (mit allen Menschen, die das lesen wollen). Und ich wollte eine Website haben, auf der ich etwas über mich erzählen kann; als Alternative zu LinkedIn oder Xing und allen anderen sozialen Netzwerken. Eine Seite also, auf der ich mich kreativ und technisch austoben kann.

## Meine Gehversuche mit Wordpress

Irgendwie haben alle Lösungen, die ich getestet habe, nicht meinen Wünschen entsprochen. Ich habe Seiten mit Wordpress gebaut, da ich bislang immer ein großer Wordpress-Fan war. Aber gerade nach dem Gutenberg-Update war mir das alles irgendwie zu verspielt. Zu viel Fokus auf Design, Pagebuilder und eine endlose Zahl von Plugins. Ja klar, kann man auch alles weglassen und es gibt auch minimale Versionen, aber gerade hier hatte ich auch keine große Lust viel Geld für aufwändigere Themes auszugeben.

## Tests mit Pagebuildern

Ich habe dann Squarespace getestet, also einen der führenden Pagebuilder, die es da draußen gibt. Aber auch hier: ewiges Geklicke in Themes, Design-Einstellungen. Am Ende für eine Website, die ja kein Business aufbauen soll, sondern nur eine Spielwiese für mich sein sollte. Und vor allem fühlte ich mich so eingesperrt in einem Ökosystem. Was, wenn ich mal wechseln möchte? Sind dann die Inhalte "weg", bzw. nur wieder über Umwege zu extrahieren. 

## Der Umweg über Ghost

Meine nächste Anlaufstelle war Ghost. Ein Open-Source-System (Pluspunkt) und wesentlich (!) schneller und simpler installiert als jedes selbstgehostete Wordpress. Das schien zunächst die Lösung. Was mir hier allerdings nicht gefiel, war die Auswahl an Themes (Premium-Themes sind überdurchschnittlich teuer, zumindest für meinen Zweck). Und natürlich ist Ghost sehr auf das Thema Newsletter, Paid-Content und Abonnements ausgelegt. Also passte auch das letzten Endes nicht. 

## Exkurs: Tracking-Tools

Zu einer Website gehört immer auch Datenerfassung. Ich will ja wissen, woher die User kommen, wie lange sie auf welcher Seite sind, was sie dort anschauen und auf welcher Seite sie abspringen. Also gehörte für mich zu jedem Seiten-Setup auch das Setup von Tracking-Tools dazu. Zunächst Google Analytics, nach einem DSGVO-Rappel dann der Umstieg auf eine selbstgehostete Matomo-Instanz.
Allerdings: Wenn ich ganz ehrlich zu mir bin, brauche ich das alles gar nicht. Ganz im Gegenteil: Mir geht diese ganze tiefe Datenerfassung im Netz ziemlich gegen den Strich, vor allem auf Seiten, die Daten "einfach nur so" erfassen ohne sie zu verwerten. Ich bin auch einer von denen, die ganz akribisch alle Cookie-Banner nutzen und alles deaktivieren, was nur geht. Warum sollte ich also selbst zu einer "Datenkrake" werden?

## Die Lösung? Static Page Builder

Jetzt bin ich bei Jekyll gelandet - ein Static Page Builder, also Website ohne Datenbanken und dem ganzen Aufwand drumherum. Installation und Setup über die Kommandozeile, Upload bei Github und Deployment über IONOS Deploy Now. Das befriedigt einerseits den Nerd in mir, andererseits ist das so minimalistisch, wie es nur geht. Eine Seite oder ein Beitrag, das sind einfach html-Seitenm, die ich bequem im Code-Editor mit Markup schreiben kann. Mehr braucht es für Text und ein paar Bilder auch nicht. Jekyll setzt auch keine Tracking-Cookies, die ich dann wieder nur über Umwege aus dem System bekomme. Es gibt kein Online-Interface, sondern ich mach alles lokal auf meiner Maschine. Damit ist auch jede Code-Zeile gesichert. Da die Texte alle *.md-Files sind, kann ich sie auch einfach in anderen Apps (wie Obsidian) erstellen und in den Code-Editor einfügen. Herrlich! Ja, das Setup (vor allem über IONOS Deploy Now) war anfangs etwas fummelig und man bekommt auch keine schnelle Out-of-the-Box Lösung wie mit einem Squarespace-Theme mit tausend optischen Spielereien. Dafür sind die verfügbaren Jekyll-Themes super minimalistisch und sehr schön, extrem übersichtlich und sehr anpassbar, die Ladezeit der Seite ist überragend. Und vor allem: Es ist genau die Lösung, die ich schon lange gesucht habe. Einfach, schnell, minimal. So muss es sein.