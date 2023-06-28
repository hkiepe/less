<!-- TABLE OF CONTENTS -->

#readme-top

<!-- <details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#use-docker">Use Docker</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details> -->

<!-- ABOUT THE PROJECT -->

## About The Project

Some commands and shortcuts for "less"

<!-- COMMAND COLLECTION -->

## Command collection

less -N Datei → Die Datei wird mit durchnummerierten Zeilen geöffnet (Zeilennummern werden mit kopiert)
less -X Datei → Der Bildschirminhalt bleibt nach dem Beenden in der Konsole stehen
g[n] → Springt zur n-ten Zeile (Nützlich in Verbindung mit -N) Beispiel: »g5«
/pattern → sucht vorwärts nach pattern und springt zum ersten Treffer
?pattern → sucht rückwärts nach pattern und springt zum ersten Treffer
n → springt zum nächsten Treffer
N → springt zurück zum letzten Treffer
g → Dadurch springt less zum Dateiende
G → Dadurch springt less zum Dateianfang
z → Eine Seite weiter springen (genauso wie SPACE)
w → Eine Seite zurück springen
h → Zeigt die Hilfe zum Befehl (q → springt zurück in die geöffnete Datei)
q → Schließt die Datei

<!-- ROADMAP -->

## Roadmap

- [x] Check if disk space on CIFS share is sufficient before running the backup command
- [ ] Logfile monitoring with grafana
  - [ ] Specify requirements

See the [open issues](https://github.com/hkiepe/docker/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the XXX. See `XXXLICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Henrik Kiepe - hkiepe@ssc-services.de

Project Link: [https://github.com/hkiepe/docker](https://github.com/hkiepe/docker)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
