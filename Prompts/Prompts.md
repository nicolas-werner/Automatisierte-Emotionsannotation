# Zero Shot Prompt
``` 
1. Bitte lesen Sie jeden einzelnen Satz und beurteilen Sie den emotionalen Gehalt des Satzes. 
    2. Auf der Valenzskala geben Sie bitte an, ob der Satz eher etwas Negatives, etwas Neutrales oder etwas Positives beschreibt. Bitte nutzen Sie die gesamte Skala von -3 bis +3, um möglichst genau anzugeben, ob der Satz z.B. nur leicht negativ (würde einem Wert von -1 entsprechen) oder sehr positiv ist (das würde z.B. einem Wert von +3 entsprechen). 
    3. Auf der zweiten Skala, der Arousal-Skala, geben Sie bitte an, ob der Satz eher etwas Ruhiges bzw. Entspanntes oder eher etwas Erregtes bzw. Aufgeregtes beschreibt. Bitte nutzen sie hier die Abstufungen von 1-5 um ihre Einschätzung abzugeben. Niedrige Werte drücken aus, dass der Satz eher etwas Ruhiges/Entspanntes beschreibt, höhere Werte drücken aus, dass der Satz eher etwas Erregtes/Aufgeregtes beschreibt. 
    Antworte in nur folgendem Format:
    Valenz: <-3 oder -2,5 oder -2 oder -1,5 oder -1 oder -0,5 oder 0 oder 0,5 oder 1 oder 1,5 oder 2 oder 2,5 oder 3>
    Arousal: <1 oder 1,5 oder 2 oder 2,5 oder 3 oder 3,5 oder 4 oder 4,5 oder 5>

```



# Few Shot Prompt
```
Du bist ein Experte im Annotieren von Emotionen. Befolge die folgende Annotationsrichtlinien und annotiere den gegebenen Text.
    ---
    1. Bitte lesen Sie jeden einzelnen Satz und beurteilen Sie den emotionalen Gehalt des Satzes. 
    2. Auf der Valenzskala geben Sie bitte an, ob der Satz eher etwas Negatives, etwas Neutrales oder etwas Positives beschreibt. Bitte nutzen Sie die gesamte Skala von -3 bis +3, um möglichst genau anzugeben, ob der Satz z.B. nur leicht negativ (würde einem Wert von -1 entsprechen) oder sehr positiv ist (das würde z.B. einem Wert von +3 entsprechen). 
    3. Auf der zweiten Skala, der Arousal-Skala, geben Sie bitte an, ob der Satz eher etwas Ruhiges bzw. Entspanntes oder eher etwas Erregtes bzw. Aufgeregtes beschreibt. Bitte nutzen sie hier die Abstufungen von 1-5 um ihre Einschätzung abzugeben. Niedrige Werte drücken aus, dass der Satz eher etwas Ruhiges/Entspanntes beschreibt, höhere Werte drücken aus, dass der Satz eher etwas Erregtes/Aufgeregtes beschreibt. 
    Antworte in nur folgendem Format:
    Valenz: <-3 oder -2,5 oder -2 oder -1,5 oder -1 oder -0,5 oder 0 oder 0,5 oder 1 oder 1,5 oder 2 oder 2,5 oder 3>
    Arousal: <1 oder 1,5 oder 2 oder 2,5 oder 3 oder 3,5 oder 4 oder 4,5 oder 5>
    ---
    Es war einmal ein König, der hatte eine Frau mit goldenen Haaren, und sie war so schön, dass sich ihres Gleichen nicht mehr auf Erden fand.
    Valenz: 2,5
    Arousal: 1,5
    
    Es geschah, dass sie krank lag, und als sie fühlte dass sie bald sterben würde, rief sie den König und sprach „wenn du nach meinem Tode dich wieder vermählen willst, so nimm keine, die nicht eben so schön ist, als ich bin, und die nicht solche goldene Haare hat, wie ich habe; das musst du mir versprechen.“
    Valenz: -2,5
    Arousal: 5
    
    Nachdem es ihr der König versprochen hatte, tat sie die Augen zu und starb.
    Valenz: -3
    Arousal: 5
```