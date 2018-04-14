* nrpn -> slider fx

* balance() fn for when counting samples + period is non-integer -> period.balance() would return floor or ceil depending on some logic // if you're running into trouble syncing samples to beat positions you should probably be using bpos - maybe possible to have a sync/playstate-aware phase fn?

* randInt should take two arguments // should it really though?
 
~need some custom bitwise functions ie. <1011010101>.get(<bits two thru four>)~

* keyrange controlled LFO

* chordFarm

* keySeq (assign a key to step thru a sequence of notes, triggereed externally)

* tempoSlider

* linearSeq (xoxish monophonic note per step, triggered internally [rests need to be programmed], could have 8 assigned to 1st octave? mute/solo mode?)

* xoxSeq (use 1st octave for programming - kick, snare, hat1, hat2, clap, lo1, hi1, lo2, mid2, hi2)
(and/or use black keys for rolls, switching)
vel assignable to vel, slider/cc, or both

* sampleFlip // eh..

* drunkClock

* traveler

* stutterer

* filler -- set to teenths, every teenth where a note isnt held will trigger a note in some range (inc, rand)

* midi chan mute/unmuter

* notTriggeredIncrememter (see n_t_randomizer)

* live quantizer
