# Immersive Questionnaire Tool for Unity VR (IQT)

**IQT** is a Unity-based tool designed to conduct Likert-scale questionnaires directly within virtual reality environments. This asset simplifies the process of collecting user feedback—such as on user experience or presence—by offering a flexible, immersive, and easy-to-use in-VR interface for questionnaire delivery and data collection.

> This project was developed as part of my Bachelor's thesis in Computer Science.

---

## Features

- **Built-in Questionnaires**  
  Comes pre-installed with two widely used instruments:  
  - **IPQ** – Igroup Presence Questionnaire  
  - **UEQ** – User Experience Questionnaire

- **Custom Questionnaire Support**  
  Easily import your own questionnaires in **CSV format**.

- **Highly Configurable**  
  Customize the visual presentation, layout, and data export format.

- **Export Results**  
  Collected questionnaire data can be exported for further analysis.

- **Research-Ready**  
  Designed for researchers and developers conducting user studies in VR.

---

## Getting Started

1. Clone or download this repository.
2. Open the project in Unity (recommended version: [insert Unity version used]).
3. Import your own questionnaire (CSV format) or use the included IPQ/UEQ.
4. Enter Play Mode in VR and start collecting data.
5. Export your results for further analysis.

---

## Questionnaire Format

To use a custom questionnaire, provide a `.csv` file in the following structure:

```csv
Question,LabelLeft,LabelRight
"I felt present in the virtual environment",Strongly disagree,Strongly agree
...
