# Summer-Project

Joern setup and startup should be as simple as

```
bash setup_joern.sh
bash run_joern.sh [ABSOLUTE PATH OF FOLDER CONTAINING CODE YOU WANT TO IMPORT]
```

`run_joern.sh` will import the code into Joern if necessary (so you'll need to clone whichever repository you want to analyze with Joern and provide the path), and also launch the Neo4j database on `0.0.0.0:7474`. 

Since `setup_joern.sh` installs python libraries I recommend you start up a virtual environnment, but the script will run regardless.
