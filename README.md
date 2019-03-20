# Här har småhuspriserna ökat mest

Dagens Samhälle publicerade den 14 mars 2019 en artikel om hur mycket småhuspriserna stigit runt om landet. Övrig info och länkar finns i notebooken.

Vid eventuella frågor är det bara att höra av sig till min mejl: johan.ekman@dagenssamhalle.se

Ansvarig utgivare: Olov Carlsson




## Usage

Dagens Samhälles beräkningar utförs i python och oftast med hjälp av biblioteket pandas. Du behöver python (minst v 3.6) samt pipenv installerat. Här kommer en kort förklaring ifall du är nybörjare och vill ha lite stöd:

### 1. Installera pipenv

Först se till att du har python installerat och att pip fungerar (minst v 3.6). I terminal (eller motsvarande) skriver du sedan:

`pip install pipenv`

pipenv är en variant av virtual miljö som isolerar ditt arbete i repot från övriga installationer i python. Om du är intresserad [kan du läsa mer här!](https://realpython.com/pipenv-guide/)


### 2. Klona repot

Tanka hem hela repots innehåll till din dator. Detta görs lättast (tycker jag själv) genom terminal. Gå till den mapp du vill ladda ned repot i. Däri skriver du:

`git clone <repo-url>`

Du hittar repo-url:n i repot under den gröna knappen "Clone or download" uppe till höger.


Om du önskar en mer utförlig beskrivning på hur man klonar och hur det egentligen fungerar [kan du läsa det här!](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone)

### 3. pipenv install

När du sedan befinner dig den klonade mappen ser du att det finns två filer som heter Pipfile och Pipfile.lock. Det är dessa som måste användas för att du ska få rätt pythonbibliotek installerade och sedan kan köra notebooken. När du befinner dig i den klonade mappen som innehåller Pipfile skriver du i terminal (eller motsvarande):

`pipenv install`

Detta kommer installera en lokal virtual environment (läs i länken under punkt 1 om du unrar vad det är) på din dator med alla de pythonbibliotek som krävs för notebooken. 

### 4. Shell och Jupyter

Nu när allt är installerat och klart så kan du köra notebooken. Du skriver följande i terminal (eller motsvarande):

`pipenv shell`

Nu har du aktiverat din lokala venv genom pipenv med alla nöfvändiga installationer. Därefter så startar du notebooken. Antingen med Jupyter Notebook:

`jupyter notebook`

Eller med Jupyter Lab:

`jupyter lab`

Sedan är det bara att kolla igenom notebooken!


Notera att alla repos är anpassade efter python <= 3.6. I flertalet finns variabelnamn med å, ä och ö vilket kommer crasha ifall du prövar på python 2.



