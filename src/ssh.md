# Installation

## Ubuntu

Installation:

```bash
sudo apt-get install openssh-server
```

Aktivera SSH:

```bash
sudo systemctl enable ssh --now
```

Verifiera att SSH körs:

```bash
sudo systemctl status ssh
```

Starta SSH:

```bash
sudo systemctl start ssh
```

Logga in med användarnamn:

```bash
ssh userName@Your-server-name-IP
```

## Windows

1. Tryck på Windows-tangenten och sök efter ”Valfria funktioner”. (Optional features)

2. Öppna ”Inställningar” > ’Appar’ > ”Valfria funktioner” och kontrollera om OpenSSH-klienten är installerad - om det behövs installerar du den via ”Lägg till valfri funktion”

3. Öppna Powershell och anslut till önskad server med `ssh name@server`

4. Första anslutningen: Bekräfta Host Key Fingerprint med ”Yes” och ange lösenord.
