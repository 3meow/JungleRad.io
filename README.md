# Ban_Band
Procedurally generated "music" or visuals which are created from various data pulled from the Banano ecosystem, such as; Banano Transactions, JungleTV, CoinEx Trading, Discord/Reddit Tipbots. 

Planned data sources:
- Banano Transactions 
- JungleTV
- CoinEx Trading
- Discord/Reddit Tipbots
- Faucet Claims

General Info and Rough Plan:
Generative sounds used will be produced using js, (such as tone.js). Users will be able to change sound settings with a small ban donation, which will persist until the following change.

Example 1: 
"Bass" 
Detect Banano tx of >69, play a note with the following settings:
Saw wave, pitch = 42.0 Hz @ 69 ban to 77.8 Hz @ 6900 ban, length fixed to 1/4 note

Bass Snapped to notes:

**Freq (Hz)**	  41.2	43.7	  46.3	  49.0  	51.9	  55	  58.3	  61.7	  65.4	  69.3	  73.4	  77.8

**Note**        E1	  F1	    F#1 	  G1	    G#1 	  A1	  A#1   	B1	    C2	    C#2 	  D2	    D#2


Example 2:
Tempo
BPM = Banano txps, 69 - 175 BPM 
percussion + bass snapped to nearest 1/16th note

Example 3:
events
detect txID of ban_1jung1e send (not refunds),
1st character of hash changes key- 
2nd character of hash changes mode (Major / minor) -

1st char    0	  1 	2 	3 	4 	5   6	  7 	8	  9	  a	  b	  c	    d	  e	  f
Key	        A	  A#	B	  C	  C#	D	  D#	E	  F	  F#	G	  G#	same	+5	+1	+3
Mode	      M 	m	  M	  m	  M	  m	  M	  m	  M	  m	  M	  m	  M	    m	  M	  m


Rough combo of examples:
prev JTV hash: B8A00E5EDBB3F241B4B8133A72703122D23EF1135A2F7D8F71F7A32CE6B2F1A2
tx of the following amounts:69, 1232, 7568, 120, 67900
mean txps (minute or hour): 3.14


based on jtv hash: b8 = Key of G# Major (Locked to notes: g# a# c c# d# f g 
bass will play (snapped to key based on closest Hz^): ~~E1~~ -> (d#2 or f1), G1, D#2, ~~F#1~~ -> (F1 or G1), G1
Tempo: 120 BPM (based on averages from past week)
