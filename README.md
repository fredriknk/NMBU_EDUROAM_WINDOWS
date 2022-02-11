# NMBU EDUROAM WINDOWS 10

For å få NMBU eduroam på egen personlig stasjonær over ethernet må man legge inn CA sertifikatet til NMBU, last ned CA.der sertifikatet og kjør installasjonen av sertifikatet til local machine

[CA.der](NMBU%20EDUROAM%20WINDOWS%2010/CA.der)

Deretter start  services og finn wired autoconfig

![Untitled](NMBU%20EDUROAM%20WINDOWS%2010/Untitled.png)

høyreklikk og velg properties og start tjenesten, deretter velg “Startup type: Automatic”

![Untitled](NMBU%20EDUROAM%20WINDOWS%2010/Untitled%201.png)

Gå inn på  “Control Panel\Network and Internet\Network Connections”

høyreklikk på ethernetkoblingen→ Properties → Authentication og sjekk at innstillingene er like som på bildet

![Untitled](NMBU%20EDUROAM%20WINDOWS%2010/Untitled%202.png)

velg settings og huk av “Verify servers identity” og bla ned til “USERtrust RSA certification authority” og huk av den og klikk OK

![Untitled](NMBU%20EDUROAM%20WINDOWS%2010/Untitled%203.png)

velg “Aditional settings” → huk av  “Specify authentication mode”, velg “User authentication” , og Replace Credentials

![Untitled](NMBU%20EDUROAM%20WINDOWS%2010/Untitled%204.png)

Skriv inn brukernavn i langform “ola.nordmann@nmbu.no” og passord og trykk OK, du skal da få internett veldig kjapt