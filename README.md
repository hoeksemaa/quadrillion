# Quadrillion demo (unofficial)

An autoresearch-style demo for Quadrillion's Qualia research editor.

An agent improves a model one experiment at a time, in the style of Karpathy's [autoresearch](https://github.com/karpathy/autoresearch). It changes the model code, runs one experiment, scores it, and keeps or discards the change. Then it repeats. The page will replay a recorded run.

Data: [CMI – Detect Behavior with Sensor Data](https://www.kaggle.com/competitions/cmi-detect-behavior-with-sensor-data) on Kaggle. A wrist device records motion, heat, and distance while people do 18 gestures. The task is to detect body-focused repetitive behaviors, such as hair pulling and skin picking. The raw data is not in this repo (license: CC BY-NC-SA 4.0). Get it from Kaggle.

Stack: TypeScript + React frontend, Python backend.

Unofficial demo by [John Hoeksema](https://johnhoeksema.com). Not affiliated with Quadrillion.
