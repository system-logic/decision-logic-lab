# Decision Logic Lab

Engineering robust decisions under uncertainty  

Constraints > Ideas · Robustness > Performance · Reasoning > Prediction  

A personal research log: decision-making under constraints, uncertainty, trade-offs and system degradation, recorded in specific situations. It is not a tutorial and not advice. Every example lives in its original context; applying it elsewhere is the reader's own decision and responsibility. Scope and tone: [MANIFESTO.md](MANIFESTO.md).

## Who writes this

Evgenii Zagorodskikh — power electronics and EMC engineer by specialisation, with a series of papers and patents on conducted emission from switching converters (2015–2019). The lab exists because the same way of working — constraints first, a written record of every decision, every correction and every mistake — applies far beyond electronics. Each experiment below is that method in a different domain. Contact: [LinkedIn](https://www.linkedin.com/in/evgenii-zagorodskikh-58671042a/).

## Experiments

| Experiment | Domain | What is under test | State |
|---|---|---|---|
| [motor-fault-diagnosis](https://github.com/system-logic/motor-fault-diagnosis) | Condition monitoring, signal processing | Physics-first fault diagnosis of a 2.2 kW induction motor on the public ZZU-MCC5 dataset: healthy baseline, broken rotor bar by motor current signature analysis, rotor unbalance by vibration. Every signature is predicted from the physics first, negative controls are run, and the wrong runs stay in the repository next to the right one. | Episodes 1–3 done; misalignment next |
| [conducted-emissions-lab](https://github.com/system-logic/conducted-emissions-lab) | EMC, power electronics | My own published results, re-tested on a home bench I built: a two-channel 5 µH LISN, a transient limiter, an electronic load. Every measurement, correction and mistake is public; the error log is a core part of the record. | Bench ready; converter prototypes next |
| [basement-model](https://github.com/system-logic/basement-model) | Electrical design, building automation | A 19.6 m² basement room, from a bare storage room to three levels of control — hardwired interlocks, a programmable relay, an AI that may only request. The hardware always has the last word. 16 drawing sheets, an [interactive 3D model](https://system-logic.github.io/basement-model/2026-10-03-design/3d-model.html), build photographed. | Design published; build in progress |
| [forex-bot-research](https://github.com/system-logic/forex-bot-research) | Adaptive systems in a non-stationary environment | A research prototype of a mid-term decision system: regime detection, constraint-aware filters, monitoring of model degradation. Not a trading strategy and not a profitable bot. | Video 1 published; paused |

What every experiment records, in this order: the constraints and the starting position; the decisions and why they were taken; what broke and what was corrected; what is still open. Results come last.

## YouTube  
Applied breakdowns of decision systems under real-world pressure.  
[Decision Logic Lab](https://www.youtube.com/channel/UCWOWanUk09jwCybs0VZSIqg)  

## Licence

Text of this repository: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (full text: [`LICENSE`](LICENSE)). Each experiment carries its own licence.

In the age of AI, building complex systems is easy.  
Making them robust remains hard.
