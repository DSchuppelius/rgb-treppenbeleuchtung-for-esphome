# RGB Treppenbeleuchtung mit ESPHome (Auch ohne Home Assistant nutzbar!)

## Livestream über den Umbau zur Standalone Variante mit Offline-Automatisierungen

[![RGB-Treppenbeleuchtung Standalone](http://img.youtube.com/vi/RzkHVJpzZmQ/0.jpg)](https://www.youtube.com/watch?v=RzkHVJpzZmQ "RGB Treppenbeleuchtung Standalone")

## Anleitung

Dieses Skript besteht aus 2 Varianten. Jede Treppe benötigt ihren eigenen Namen unter dem Punkt esphome.

* treppe-demo-package.yaml (Package-Variante)
  * Benötigt alle Dateien aus dem Verzeichnis ./common. Jede weitere Treppe benötigt nur die Angaben aus der treppe-demo-package.yaml, welche ihr dann in euer neues File einfügen müsst.
* treppe-demo.yaml (One File Variante)
  * Benötigt nur die eine Datei. Jede weitere Treppe muss den "kompletten" Code der Datei enthalten. Natürlich angepasst auf euer neues Gerät, wie in der folgenden Anleitung beschrieben.

Eine ausführliche Anleitung des Projektes findet Ihr unter:
<https://smarthomeyourself.de/rgb-treppenbeleuchtung-standalone-jetzt-auch-ohne-home-assistant/>

### Anmerkung

Dieser Fork ist entstanden, weil mir der urspüngliche Code immer abgeschmiert ist. Hauptursache ist meines Erachtens die Verwendung der Delay-Funktion gewesen, welche bei einem entsprechend langen LED-Streifen dafür sorgte, dass das Programm vorzeitig beendet wurde bzw. der Controller jedes mal neustartete.

## Verwendete Bauteile

**NodeMCU:** <https://amzn.to/3xMmppB>*  
**Bewegungsmelder:** <https://amzn.to/2PTrbAI>*  
**Photoresistor:** <https://amzn.to/3ukm0J0>*  
**RGB-LED-Stripes:** <https://amzn.to/3ei12ol>*  
**LEDs:** <https://amzn.to/33bRViM>*  
**Widerstände:** <https://amzn.to/3eQghUJ>*  
**Netzteil:** <https://amzn.to/3xJilq5>*  
**Netzteil-Buchse:** <https://amzn.to/33biVPo>*  

\* Affiliate-Links von/für Daniel Scheidler

**Die Platine findet Ihr wie immer bei PCBWay.com unter folgendem Link:**
<https://www.pcbway.com/project/shareproject/RGB_LED_Stairlight.html>

## Weitere Videos zum Projekt

**Video zur ursprünglichen Variante der RGB-Treppenbeleuchtung**  
[![RGB-Treppenbeleuchtung](http://img.youtube.com/vi/jhAS_OhYyys/0.jpg)](https://www.youtube.com/watch?v=jhAS_OhYyys "RGB Treppenbeleuchtung Ursprung")

**Video zum Update: Stufenweise Animationen**  
[![RGB-Treppenbeleuchtung UPDATE](http://img.youtube.com/vi/29ch0v86I_o/0.jpg)](https://www.youtube.com/watch?v=29ch0v86I_o "RGB Treppenbeleuchtung jetzt auch mit Stufenweiser Animation")
