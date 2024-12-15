## Initiate Connection

```
ncat --ssl mumbo-dumbo.chals.nitectf2024.live 1337
```
![InitiateConnection.png](./images/InitiateConnection.png)

## Solve the P-O-W Challenge as Prompted

```
python3 pow.py solve s.ACcQ.AABqsIvWSrjfFqo1wV9UZHKW
```
![SolvePOW.png](./images/SolvePOW.png)

## Use Command Execution to Poke at the Bot

```
$(whoami)
$(id)
$(cat flag.txt)
$(ifconfig)
$(ls)
```
![CommandExecution.png](./images/CommandExecution.png)

## Annoy it with 'ls -al'

```
$(ls -al)
```
![ShowMe.png](./images/ShowMe.png)

## Relay the Password
"Elephant in the room" seems a bit of an odd thing to say; additionally, it stated that the end was near. I'm thinking this phrase may be the password that'll make the bot give me the flag, and end this interaction (as hinted).

```
Elephant in the room
```
![GetFlag.png](./images/GetFlag.png)
