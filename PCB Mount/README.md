# BIQU KFB 2.0 replacement board

Went with this board hence it was fairly cheap, decent set of IO, JST connectors so I can plug existing cables without modifications (no need to re-crimp connectors and board has perfect USB port location so it can be fitted nicely without adding cable extensions or so).

Under consideration also had these boards but chose not to go with them:

MKS Gen board - has slightly different layout so cable extensions or case modifications will be required.

MKS S Gen - 32bit board is not necessary for cartesian machine.

RAMPS - too thick for lid to come back on + requires connector re-crimping.


If you have suggestion of quality board with similar form factor and JST connectors - happy to reconsider.


Motion wiring is pretty buch straight forward apart from typical UP machine X and Y axis mixup (X = Y and Y is X, looks like they come from CNC background...)

Hotend, Extruder and Bed wiring (ribbon connector ones) info you can find in their folders.


PCB Mount also includes place for additional mosfet if you desire to run chamber heaters.

DC jack is generic DC jack, like the one you can find on Arduino Mega boards. Haven't checked AMP rating but UP machine has quite low power rated components so I've assumed it's good enough - please correct me if I'm wrong.