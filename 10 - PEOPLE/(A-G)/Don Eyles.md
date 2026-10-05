---
aliases:
- Don Eyles
- Donald Eyles
- Donald E. Eyles
category: "Technologists"
tags:
  - Person
  - Apollo
  - ApolloGuidanceComputer
  - Software
  - MITInstrumentationLaboratory
summary: "Don Eyles wrote lunar landing software for the Apollo Lunar Module's guidance computer at the MIT Instrumentation Laboratory and devised the keystroke workaround for the Apollo 14 abort-switch fault."
born: 1943
updated: 2026-10-05
relations:
  - type: employed_by
    with: "[[MIT Instrumentation Laboratory]]"
    role: "programmer of the Lunar Module guidance computer software (SUNBURST, then LUMINARY)"
    fn: 1
  - type: participant_in
    with: "[[Apollo 14]]"
    start: 1971-02
    role: "wrote the abort-monitor code and the workaround procedure the crew entered before powered descent"
    fn: 3
  - type: participant_in
    with: "[[Apollo Program]]"
    role: "author of Lunar Module landing guidance code, including the throttle-control routine flown on Apollo 11 and Apollo 12"
    fn: 1
---
Don Eyles (born 1943) was a programmer of the Apollo Guidance Computer at the [[MIT Instrumentation Laboratory]] in Cambridge, Massachusetts, the laboratory under [[Charles Stark Draper]] that held the first [[Apollo Program]] contract, for the Primary Guidance, Navigation and Control System. In 1970 the laboratory was renamed the Charles Stark Draper Laboratory, and in 1973 it became independent of [[MIT]].[^1]

### Lunar Module software

The Lunar Module computer program for the unmanned [[Apollo 5]] flight (LM-1) was called SUNBURST. It was followed by SUNDANCE, which flew the Earth-orbital [[Apollo 9]] mission, and by LUMINARY, the program for [[Apollo 10]] and the lunar landing missions. LUMINARY revision 99 flew [[Apollo 11]] in July 1969, and revision 116 flew [[Apollo 12]] in December 1969. The computer was programmed in two languages, an assembly language ("Basic" or "Yul") by [[Hugh Blair-Smith]] and the list-processing "Interpretive" language written by [[Charles Muntz]].[^1]

Eyles wrote descent and landing code, including the Lunar Module's throttle-control routine, and tested it against a simulation of the descent engine. He observed an oscillation in thrust when a large throttle change was commanded without compensation for the engine's throttle lag. Compensating 0.2 seconds for a lag of 0.3 seconds nearly eliminated it, and Apollo 11 and Apollo 12 both flew with that value. Eyles later wrote that if he had coded the "correct" compensation number, Apollo 11 would not have landed, and he invited someone with a grasp of the mathematics and no personal stake to reexamine the theory.[^1]

For LUMINARY 1B he filed a program change request (PCR 848, July 23, 1969) to prevent the rendezvous radar's coupling units from taking memory cycles from the guidance computer, after the radar-mode switch settings associated with the Apollo 11 landing alarms. He also developed a "variable SERVICER" in which the guidance period could stretch under heavy computer load, described in Luminary Memo 139 (March 3, 1970), and in May 1971 wrote the Draper Laboratory report E-2581, "Apollo LM Guidance and Pilot-Assistance During the Final Stage of Lunar Descent."[^1]

### Apollo 14 abort switch

During [[Apollo 14]] the Lunar Module Antares carried [[Alan Shepard]] and [[Edgar Mitchell]]. After undocking, flight controllers in Houston saw that the abort bit in the Lunar Module computer was set, indicating that the ABORT pushbutton circuit was closed. At 104:31 ground elapsed time [[Fred Haise]], the capsule communicator, asked Mitchell to cycle the pushbutton. At 105:46 Haise asked Mitchell to tap the panel around the ABORT pushbutton, and Mitchell reported that the display changed while he was tapping. The bit returned at 106:23 and again at 106:30. At 106:25 Mitchell asked [[Thomas Stafford]] whether the cause was "something like a solder ball." Haise told Mitchell that Houston supposed there was contamination in the ABORT switch, and that with the bit set, program 63 (the braking phase of the descent) would convert to program 70, the descent abort.[^2]

The software abort monitor checked the abort discretes every quarter second; if the LETABORT flag permitted aborts, it selected P70 (descent engine abort) or P71 (ascent engine abort) at the first sign of a closed switch. Eyles had written the code that monitored this discrete. His first idea, resetting LETABORT through the bit-manipulation noun, failed because the ignition routine set LETABORT again 0.2 seconds after engine start. The workaround used the mode register (MODEREG): the crew loaded P71 into it before ignition so that the abort monitor would treat an abort as already in progress, set the zoom flag after the 26-second throttle-trimming interval, reset LETABORT to disable aborts, and then restored P63 so that the state-vector routine would weight landing-radar altitude data correctly. If an abort were needed, Mitchell was to set LETABORT again with a Verb 25, Noun 7 sequence. The fix was tested at [[Grumman]] and in Houston before powered descent; the commentary by Paul Fjeld in the [[Apollo Lunar Surface Journal]] gives the available time as three to four hours.[^3]

Eyles described the episode in his 2004 paper: "The abort switch on the instrument panel was sending a spurious signal that could have spoiled Alan Shepard and Ed Mitchell's landing. I had written the code that monitored this discrete. The workaround simply changed a few registers, first to fool the abort monitor into thinking that an abort was already in progress, and then to clean up afterward so that the landing could continue unaffected. The procedure radioed up and flawlessly executed by the astronauts involved 61 DSKY keystrokes." He added that "the number of differing versions that have been offered to history" was the most interesting part of the incident.[^1]

Mitchell began entering the sequence on the display keyboard at 108:02:58, with Shepard handling the throttle. At 108:03:23 Mitchell announced "I'm Disabling (aborts)," and he then restored the P63 code and enabled the landing radar. Mitchell later said, "We disabled that circuit so that the system would not recognize the single point of the abort button."[^3]

[[Annie Jacobsen]] wrote that Eyles, then twenty-seven, was at the Instrumentation Laboratory when [[NASA]] called him, that he had less than two hours to create a solution, that the Antares guidance system malfunctioned and flashed an abort signal, and that Eyles recalled, "We deceived the program by telling it an abort was already in progress," in a sixty-one-keystroke sequence that Mitchell copied down and entered.[^4] The Lunar Surface Journal transcript places the fault in the ABORT pushbutton circuit and the available time at three to four hours.[^3]

### Edgar Mitchell and the Apollo 14 ESP tests

Mitchell, who after the mission founded the [[Institute of Noetic Sciences]], conducted a private test of extrasensory perception during Apollo 14. In a later interview he said it was arranged about three weeks before launch with two physicists and two receivers on Earth, including [[Olof Jonsson]], a Chicago psychic. He said he used tables of random numbers keyed to the five [[Zener cards]] symbols, transmitting each symbol for fifteen seconds, and that the launch delay upset the timing with the receivers. He said Jonsson told the press before the data had been reviewed.[^5] Mitchell published a report in the Journal of Parapsychology in 1971.[^6]

### Footnotes
[^1]: Eyles, Don. "Tales from the Lunar Module Guidance Computer." AAS 04-064, American Astronautical Society, 2004. https://www.doneyles.com/LM/Tales.html. His memoir is *Sunburst and Luminary: An Apollo Memoir* (Fort Point Press, 2018).
[^2]: Jones, Eric M., ed. "Landing at Fra Mauro," Apollo 14 Lunar Surface Journal, NASA, transcript at 104:30 to 106:33 GET. https://web.archive.org/web/2023/https://www.hq.nasa.gov/alsj/a14/a14.landing.html
[^3]: Fjeld, Paul. "Masking the Abort Discrete," Apollo Lunar Surface Journal, NASA, 2009, and the transcript at 108:02 to 108:03 GET. https://web.archive.org/web/2023/https://www.hq.nasa.gov/alsj/a14/a14AbortDiscrete.html
[^4]: Jacobsen, Annie. *Phenomena: The Secret History of the U.S. Government's Investigations into Extrasensory Perception and Psychokinesis*. Little, Brown and Company, 2017. Sole source for the passages so cited.
[^5]: "Private Lunar ESP: An Interview with Edgar Mitchell." Cabinet, issue 5. https://cabinetmagazine.org/issues/5/backstrom_mitchell.php
[^6]: Mitchell, Edgar D. "An ESP Test from Apollo 14." *Journal of Parapsychology*, 1971.
