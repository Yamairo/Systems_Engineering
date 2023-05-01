# Inhoudsopgave
```toc
```

## SCL (Structured Control Language)
#voorbeeldcode
```pascal
IF "Button1" THEN
	// Statement section IF
	"Motor_B2" := TRUE;
END_If;
```
### Overview

- Vaak in FC/FB's maar kan ook in OB's
- "==" ipv =
- Let op de semicolon
### Assignments
In de code #voorbeeldcode kun je zien dat de "Motor_B 2" een waarde "True" meekrijgt
- Als er geen uitvoer is dan is er ook geen reactie
- Je moet dan een ELSE gebruiken voor gedrag bij een FBD assignment
- Let ook op de volgorde

### IF
- Alles tussen IF en THEN is een conditie
- ELSIF of ELSE kan ook gebruikt worden
- Je moet altijd eindigen met END_IF

### Case 
- Bij een CASE wordt een variabel getal meegegeven

### Loops
- FOR, WHILE, REPEAT loops kunnen allemaal gebruikt worden in SCL
- Bij loops kan je EXIT gebruiken om gelijk uit de loop te gaan, je kan CONTINUE gebruiken om verder te gaan

```pascal
WHILE "Button1" DO
	// Statement section WHILE
	"Motor_B1" := TRUE;
END_WHILE;
```