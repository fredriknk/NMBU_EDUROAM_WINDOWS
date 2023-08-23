# NMBU EDUROAM WINDOWS 10

For å få NMBU eduroam på egen personlig stasjonær over ethernet må man konfigurere autentikasjonsmetode, de har gått bort fra sertifikater (som gjør livet my enklere da man tidligere måtte holde serifikatet oppdatert) så her er oppskriften:

1. Gå til services og finn wired autoconfig

    ![Untitled](NMBU%20EDUROAM%20WINDOWS%2010/Untitled.png)

1. høyreklikk og velg properties og start tjenesten, deretter velg “Startup type: Automatic”

    ![Untitled](NMBU%20EDUROAM%20WINDOWS%2010/Untitled%201.png)

1. Gå inn på  “Control Panel\Network and Internet\Network Connections”

1. høyreklikk på ethernetkoblingen→ Properties → Authentication og sjekk at innstillingene er like som på bildet

    ![Untitled](NMBU%20EDUROAM%20WINDOWS%2010/Untitled%202.png)

1. velg “Aditional settings” → huk av  “Specify authentication mode”, velg “User authentication” , og Replace Credentials

    ![Untitled](NMBU%20EDUROAM%20WINDOWS%2010/Untitled%204.png)

1. Skriv inn brukernavn i langform “ola.nordmann@nmbu.no” og passord og trykk OK, du skal da få internett veldig kjapt
