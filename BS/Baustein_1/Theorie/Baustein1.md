## RODC
- ein RODC dient dazu vor diebstahl der hardware zu schützen.

- ein RODC macht KEIN credential cashing (speichert in keiner weißer passwörter ab)

## Dhcp in einer Child domain
- Enterprise admin is notwendig.

# Anwendungen / services in einem AD
- LOB anwendung (datenbank)
- BMD


# Testen
- ## AD-TEST-Commands
    - ## [dcdiag](https://learn.microsoft.com/de-de/windows-server/administration/windows-commands/dcdiag)

        - ```dcdiag /test:DNS```

    - ## [repadmin](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/cc770963(v=ws.11))
        - ```repadmin /showrepl```
            
            Zeigt die Letzten Replikationen an und ob diese Succesfull waren.


        - ```repadmin /replsummary```

            Zeigt eine Zusammenfassung der Replikation.
            *(standardmässig Forest weit. mit der option -d kann man eine domain angeben)*

    - ``` ```