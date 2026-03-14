---
title: "Analog Electronics Fundamentals - Collaboration Guide"
description: "Contributing guide for Analog Electronics Fundamentals course content"
tableOfContents: true
sidebar:
  order: 999
---

# Analog Electronics Fundamentals

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Contributors Welcome](https://img.shields.io/badge/contributors-welcome-orange)

**Read this course at:** [https://siliconwit.com/education/analog-electronics/](https://siliconwit.com/education/analog-electronics/)

A practical course covering analog electronics from voltage dividers to sensor signal conditioning. Nine lessons connect every topic to embedded systems and PCB design. Not a prerequisite for other courses, but a reference that makes everything else easier.

## Lessons

| # | Title |
|---|-------|
| 1 | Voltage, Current, and Resistance |
| 2 | Capacitors, Inductors, and RC Circuits |
| 3 | Diodes, Rectifiers, and Protection |
| 4 | Transistors as Switches and Amplifiers |
| 5 | Operational Amplifiers |
| 6 | Power Supply Design |
| 7 | Filters and Frequency Response |
| 8 | Oscillators and Timing Circuits |
| 9 | Sensors and Signal Conditioning |

## File Structure

```
analog-electronics/
├── index.mdx
├── voltage-current-resistance.mdx
├── capacitors-inductors-rc-circuits.mdx
├── diodes-rectifiers-protection.mdx
├── transistors-switches-amplifiers.mdx
├── operational-amplifiers.mdx
├── power-supply-design.mdx
├── filters-frequency-response.mdx
├── oscillators-timing-circuits.mdx
├── sensors-signal-conditioning.mdx
└── README.md
```

## How to Contribute

1. Fork the repository: [SiliconWit/analog-electronics](https://github.com/SiliconWit/analog-electronics)
2. Create a feature branch: `git checkout -b feature/your-topic`
3. Make your changes and commit with a clear message
4. Push to your fork and open a Pull Request against `main`
5. Describe what you changed and why in the PR description

## Content Standards

- All lesson files use `.mdx` format
- Do not use `<BionicText>` in this course
- Code blocks should include a title attribute where applicable
- Use ASCII circuit diagrams in `text` code blocks where they aid understanding
- Use Starlight components (`<Tabs>`, `<TabItem>`, `<Steps>`, `<Card>`) where appropriate
- Every lesson should include a "How This Connects to Embedded Systems" section
- LaTeX math is fine for formulas (e.g., `$V = IR$`)

## Local Development

Clone the main site repository and initialize submodules:

```bash
git clone --recurse-submodules <main-repo-url>
cd siliconwit-com
npm install
npm run dev
```

To test a production build:

```bash
npm run build
```

## License

This course content is released under the [MIT License](LICENSE).
