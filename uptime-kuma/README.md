# Uptime Kuma Monitoring Project

Dieses Repository dient als Dokumentation und Erweiterungsprojekt für meine Uptime‑Kuma‑Installation.

## Inhalt
- Erste Schritte mit Uptime Kuma
- Beispielmonitor (Google)
- Screenshots
- Geplante Automatisierungen

## Beispielmonitor
Ich habe als ersten Test den Google‑Monitor eingerichtet, um die Funktionalität zu prüfen.

### Screenshot
![Uptime Kuma Screenshot](./Uptime%20Kuma%20Google.png)

## Roadmap
- [ ] Weitere Monitore hinzufügen
- [ ] Setup‑Dokumentation erstellen
- [ ] Backup‑Automatisierung integrieren
- [ ] GitHub Actions für regelmäßige Checks

## Ziel
Ein vollständiges, nachvollziehbares Monitoring‑Projekt, das sowohl Lernzwecken als auch praktischer Nutzung dient.

## 📊 Monitore

Ich überwache aktuell folgende Dienste:

- Google (HTTP)
- Cloudflare (HTTP)
- Wikipedia (HTTP)
- GitHub (HTTP)
- GitHub Port 443 (Port-Check)
- FritzBox (Ping)

## 📸 Screenshots

### Google Monitor
![Google Monitor](./Uptime%20Kuma%20Google.png)
*Zeigt die Erreichbarkeit und Antwortzeit von google.com.*

### Cloudflare Monitor
![Cloudflare Monitor](./cloudflare.png)
*HTTP-Check auf cloudflare.com.*

### Wikipedia Monitor
![Wikipedia Monitor](./wikipedia.png)
*Überwachung der Wikipedia-Startseite.*

### GitHub Monitor
![GitHub Monitor](./github.png)
*HTTP-Status von github.com.*

### GitHub Port 443
![GitHub Port 443](./githubport443.png)
*Port-Check auf HTTPS-Port 443.*

### FritzBox Ping
![FritzBox Monitor](./fritzbox.png)
*Ping-Monitor zur lokalen FritzBox.*
