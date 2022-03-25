----
# Bem-vindo ao SBR! #

----
## O que é SBR? ##
SBR é uma criptomoeda para tornar o mundo um lugar melhor.

----
## Get it! ##

  - *dependencies*:
    - *general* - Java 8
    - *Ubuntu* - `http://www.webupd8.org/2012/09/install-oracle-java-8-in-ubuntu-via-ppa.html`
    - *Debian* - `http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html`
    - *FreeBSD* - `pkg install openjdk8`

----
## Run it! ##

  - clique no ícone SBR ou inicie na linha de comando:
  - Unix: `./start.sh`
  - Window: `run.bat`

  - aguarde a janela da carteira JavaFX abrir
  - on platforms without JavaFX, open http://localhost:36876/ in a browser

----
## Compile it! ##

  - se necessário compile: `./compile.sh`
  - você precisa do jdk-8 também

----
## Troubleshooting the NRS (SBR Reference Software) ##

  - How to Stop the NRS Server?
    - click on SBR Stop icon, or run `./stop.sh`
    - or if started from command line, ctrl+c or close the console window

  - UI Errors or Stacktraces?
    - report on BitBucket

  - Permissions Denied?
    - no spaces and only latin characters in the path to the NRS installation directory
    - known jetty issue

----
## Further Reading ##

  - in this repository:
    - USERS-GUIDE.md
    - DEVELOPERS-GUIDE.md
    - OPERATORS-GUIDE.md
    -Na pasta doc

