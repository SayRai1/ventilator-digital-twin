# Ventilator Digital Twin

Interactive digital twin of a mechanical ventilator, built for the medical track
of a hackathon. It replays **real ventilator recordings** (pressure, flow and
volume) and lets a clinician try new settings on a virtual patient before
changing the real machine.

![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF)

## Features

- Three patient profiles (ARDS, severe pneumonia, post-op respiratory failure),
  each with its own lung compliance and airway resistance
- Live pressure / flow / volume waveforms from recorded patient data
- Adjustable settings: tidal volume, PEEP, FiO₂, respiratory rate, I:E ratio
- Lung-mechanics model that predicts the waveform for the new settings
- Risk level and alarm estimate for each setting change
- AI assistant panel that summarises the patient state for the doctor

## Run

`ventilator-digital-twin.jsx` is a single React component. Drop it into any
React + Recharts project (for example Vite) and render `<VentilatorDigitalTwin />`.

## Author

Sirapop Poonkaew, Control Systems & Instrumentation Engineering, KMUTT
