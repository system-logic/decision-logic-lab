# Decision Logic Lab

Engineering robust decisions under uncertainty  

Constraints > Ideas · Robustness > Performance · Reasoning > Prediction  

This is a personal research log. Not a product. Not a framework. Not a library. Not a tutorial. Not advice.  

Here I document decision-making under constraints, uncertainty, trade-offs, and system degradation.  

No recipes. No best practices. No templates.  

If after reading you think:  
“Now I know how to build this”  
— the format has failed.  

## Who writes this

Evgenii Zagorodskikh — power electronics and EMC engineer by specialisation, with a series of papers and patents on conducted emission from switching converters (2015–2019). The lab exists because the same way of working — constraints first, a written record of every decision, every correction and every mistake — applies far beyond electronics. Each experiment below is that method in a different domain. Contact: [LinkedIn](https://www.linkedin.com/in/evgenii-zagorodskikh-58671042a/). Scope and tone: [MANIFESTO.md](MANIFESTO.md).

## Experiments

| Experiment | Domain | What is under test | State |
|---|---|---|---|
| [conducted-emissions-lab](https://github.com/system-logic/conducted-emissions-lab) | EMC, power electronics | My own published results, re-tested on a home bench I built: a two-channel 5 µH LISN, a transient limiter, an electronic load. Every measurement, correction and mistake is public; the error log is a core part of the record. | Bench ready; converter prototypes next |
| [basement-model](https://github.com/system-logic/basement-model) | Electrical design, building automation | A 19.6 m² basement room, from a bare storage room to three levels of control — hardwired interlocks, a programmable relay, an AI that may only request. The hardware always has the last word. 16 drawing sheets, an [interactive 3D model](https://system-logic.github.io/basement-model/2026-10-03-design/3d-model.html), build photographed. | Design published; build in progress |
| [forex-bot-research](https://github.com/system-logic/forex-bot-research) | Adaptive systems in a non-stationary environment | A research prototype of a mid-term decision system: regime detection, constraint-aware filters, monitoring of model degradation. Not a trading strategy and not a profitable bot. | Video 1 published; video 2 planned |

What every experiment records, in this order: the constraints and the starting position; the decisions and why they were taken; what broke and what was corrected; what is still open. Results come last.

## YouTube  
Applied breakdowns of decision systems under real-world pressure.  
Decision Logic Lab  

## Responsibility  
Understanding the structure does not grant permission to apply it.  
Every example lives in its original context.  
Using anything here transfers full responsibility to you.  

In the age of AI, building complex systems is easy.  
Making them robust remains hard.
