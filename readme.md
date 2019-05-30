# IHMS - In House Management System

This project is the front end for fire alarm detection system. Various sensors (fire, humidity, temperature, etc) are connected to Arduino. `kron` app fetches data from Arduino's, writes to the Postgres database (wantedly named it as kron instead of cron). `server` is API for Angular app i.e `ngApp`. `ngApp` displays those current and historical sensors values by location.

Used technologies:
Angular, Express, Sockets, Mail, Google maps  API, d3, etc

This was originally developed as a demo to a client but later they aborted.
