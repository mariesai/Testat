# Datensatz Testat Reichsbürger Razzia #
Codebuch Stand 2022-12
erstellt von Marie Sailer (ms594u@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

Das Netzwerk ist ein *gerichtetes two-mode Netzwerk*. 

# EDGE-Attribute

**id**  
(eindeutige Codierung des Knoten)   

**from**
initiierender Knoten

**to**
erhaltender Knoten

**relation**  
1 = Leiter    
2 = Mitglied    
3 = Freunde
4 = Kollegen

# NODE-Attribute  

**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten. 

**name**
numerische ID

**sector**  
1 = Militär
2 = Adel 
3 = Politik
4 = Polizei
5 = Wirtschaft
6 = Jura
7 = Medizin
8 = Astrologie
9 = Kunst

**type**  
1 = Akteur
2 = Organisation

