# SMTP Test

A simple repo, containing :

- A smtp server, with webclient, 
- A python script, that sends a email, using the smtp server.

### Instuctions

Make sure you have docker and docker-compose installed.
Run 
```
docker-compose up -d
```
from the main directory, to start the server, as a service.

Then run the python script using 
```
python3 mail.py
```

log into the mail server using http://localhost:8025 and see the email, htat you just send.

To cleanup, simply run 
```
docker-compose down
```
to stop the container again.