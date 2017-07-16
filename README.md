# CARRERA CHAMPS

A script to start a race for a given number of laps on a Carrera Digital 132/124 slot car set.

NOTE: This is intended as a simple prototype and therefore does not handle edge-cases or user error.

## Usage:

Ensure you've got the dependencies: ```pip install bluepy carreralib```.

You must supply the mac address of your Control Unit.

For options:
```
./champ --help
```

Example:
```
./champ -c D9:A4:83:22:C6:9B -b 5 -s 7 -l 3 -p Andrew -p Barry
```
