# Inhoudsopgave
```toc
```

## PLC Cyclus
![[Pasted image 20230418091742.png]]


![[Pasted image 20230418091817.png]]

--- 

## Input Outputs
### Normally open / closed
**Normally open** in de huidige stand loopt hier geen stroom door
**Normally closed** in de huidige staat loopt hier stroom door

### Bi- / Mono-stabliliteit

**Mono-stabiel**
Bij **mono-stabiel**, reset de sensor of actuator automatisch naar normaal na het wegvallen van de actie: Drukknop, simpel DC-motor, LED ect.
**Bi-stabiliteit**
Bij **bi-stabiel** is na het wegvallen van de actie, een andere actie nodig om te resetten naar normaal: Brug met open/dicht motoren, draaiknop of pushers met aparte intakes ect. (soms als A+ en A- genoteerd).

### Distributed IO
- Door de buslijn zijn er minder kabels nodig 
- Soms lokale CPU
- IO is transparant voor hoofd CPU
- Kan draaien naast lokaal IO
- Kan goedkoper zijn

---

## Geheugen
- Bit - 1 of 0
- Byte is 8 bits
- "Word" is 2 bytes
- **Double** word is 2 x word
- Een '.' tussen 2 cijfers geeft aan welke bit van een byte geadresseerd is: 2.1 is dus 1 bit van byte 2
- 'I' is input 
- 'Q' is output
- 'M' staat voor Merker (Ofwel geheugen, **Memory**)

Voor een **word** en een **double word** gebruiken we even adressen

<br>

### Voorbeelden
- I 4.5 is input bit op byte adres 4 en bit adres 5,
- Q 6.2 is output bit op byte adres 6 en bit adres 2,
- IB3 is input byte, op byte adres 3 (groep van 8 ingangen: I3.0 – I3.7), 
- MW6 is merker word, op woord adres 6 (groep van 16 merkers M6.0 – M7.7), 
- ID0 is input dubble word, op dubble word adres 0 (groep van 32 merkers M0.0 – M3.7).

