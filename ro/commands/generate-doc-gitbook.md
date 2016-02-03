# generate:doc:gitbook
**generate:doc:gitbook** comanda Generează documentațiile pentru Comenzi

**Folosire:**
```
$ drupal generate:doc:gitbook [arguments] [options] 
$ gdg  
```

## Opțiuni disponibile
Opțiune | Detalii
-------|-------------
--path | Calea de randare a documentației
--learning | Generarea unui cod verbal.
--help | Afișează acest mesaj de ajutor
--quiet | Nu afișa nici un mesaj
--verbose | Crește nivelul de detaliere a mesajelor: 1 pentru o detaliere normală, 2 pentru o detaliere mai amănunțită si 3 pentru depanare
--version | Afișează versiunea aplicației
--ansi | Forțează standardul ANSI
--no-ansi | Dezactivați standardul ANSI
--no-interaction | Nu adresa nici o întrebare interactivă
--env | Numele mediului de lucru.
--root | Definiți rădăcina Drupal care va fi folosită la executarea comenzilor
--no-debug | Oprește modul de depanare.
--generate-chain | Printează opțiunile și argumentele de execuție în format yaml pentru a fi folosit în comandă înlănțuită
--generate-inline | Printează opțiunile și argumentele de execuție în apel inline pentru a fi folosit pe viitor
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI-ul sitului Drupal care va fi folosit (pentru medii multi-sit sau când rulează pe un port alternativ)
--yes | Skip confirmation and proceed

## Argumente disponibile
Argument | Detalii
---------|-------------
command | Comanda ce urmează a fi executată
