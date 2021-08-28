# Star Wars Star Destroyer Attack
#### System Programmimg course assignment.
#### Simulates a comunication of Threads that send messages to a global MessageBus in RoundRobin way.
#### The user chooses the number of attacks, attacks duration and the setups for the Threads.
#### Threads names are: Leia, HanSolo, C3PO, R2D2, Lando (As the characters who appear in the Star Wars Movies).

### USAGE:
```mvn exec:java -Dexec.mainClass="bgu.spl.mics.application.Main" -Dexec.args="input.json output.json"```

### INPUT:
##### The input should be a JSON file containing:
- The attacks configurations the Thread Leia is sendings to the Threads: HanSolo and C3PO in RoundRobin.
- The attack durating of the Thread R2D2.
- The attack durating of the Thread Lando.
- The number of Ewoks used for the attacks of the Threads: HanSolo and C3PO.

##### Input JSON file is available in the Example folder.
