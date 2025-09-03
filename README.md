# Koenigsmilch AI Coaching - Bestellformular

Dieses Projekt ist ein modernes, responsives Bestellformular für das Koenigsmilch AI Coaching.  
Es ermöglicht Kunden, verschiedene Coaching-Pakete auszuwählen, ihre Bitcoin-Zahlung zu bestätigen und die Bestellung über [Formspree](https://formspree.io) anonym und sicher abzuschicken.

---

## Features

- **Mehrere Pakete zur Auswahl**: 3 Tage Testphase, 1 Woche, 30 Tage, Quartal, 6 Monate, 1 Jahr, Unlimited  
- **Bitcoin Zahlung**: Kunden geben ihre TXID als Zahlungsbeleg an  
- **Automatisch generierte Kundennummer** für bessere Verwaltung  
- **AGB- und Datenschutzerklärungspflicht** vor Absenden  
- **Responsives, modernes Design** mit angenehmer UX  
- **Formspree Integration** für einfachen E-Mail Empfang ohne eigenes Backend  
- **Clientseitige Validierung** und Bestätigung nach Bestellung  

---

## Installation & Nutzung

1. **Formular-Datei speichern**  
   Speichere die Datei `bestellung.html` lokal oder lade sie auf deinen Webserver hoch.

2. **Formspree Account & Formular erstellen**  
   - Erstelle einen kostenlosen Account bei [Formspree](https://formspree.io).  
   - Erstelle ein neues Formular und notiere dir die Form-ID.

3. **Formular-Action anpassen**  
   Ersetze in `bestellung.html` die `action`-URL im `<form>`-Tag durch deine Formspree-Form-ID, z.B.:  
   ```html
   action="https://formspree.io/f/DEINE_FORM_ID"
