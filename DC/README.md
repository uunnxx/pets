## Distributed Computing


```
Producer
--------------
| Bot Master |
--------------

- Distribute `tasks` which should be checked
- RabbitMQ for it's pull-based approach so clients could ask for
- Save sended `tasks` list to the client unless everything is OK
    - One could say "I found it, but I want more than `that`", so, in this case, we could check all `tasks` manually by ourselves or send it to other clients.





Consumer
------------ ------------ ------------ ------------ 
| Client 1 | | Client 2 | | Client 3 | | Client 4 |
------------ ------------ ------------ ------------

- Get API Keys for each of them to get 10RPS
    - OR: 1RPS without


```
