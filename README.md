# Immersive Questionnaire Tool for Unity VR (IQT)

**IQT** is a Unity-based tool designed to conduct Likert-scale questionnaires directly within virtual reality environments. This asset simplifies the process of collecting user feedback—such as on user experience or presence—by offering a flexible, immersive, and easy-to-use in-VR interface for questionnaire delivery and data collection.

> This project was developed as part of my Bachelor's thesis in Computer Science.

## Features

- **Built-in Questionnaires**  
  Comes pre-installed with two widely used instruments:  
  - **IPQ** – Igroup Presence Questionnaire  
  - **UEQ** – User Experience Questionnaire

- **Custom Questionnaire Support**  
  Easily import your own questionnaires in CSV format.

- **Highly Configurable**  
  Customize the visual presentation, layout, and data export format.

- **Export Results**  
  Collected questionnaire data can be exported for further analysis.

- **Research-Ready**  
  Designed for researchers and developers conducting user studies in VR.


## Getting Started


1.	Clone or download this repository.
2.	Add the folder to your Unity project.
3.	Place the Questionnaire object into your VR scene.
4.	Use the sliders and properties in the Unity Inspector to customize the component to your needs
(e.g., number of questions displayed simultaneously, scale size, layout).
5.	Import your own questionnaire in CSV format or use the included IPQ/UEQ.
6.	Enter Play Mode in VR and start collecting responses.
7.	Export the results for further analysis.

## Questionnaire Format

To use a custom questionnaire, provide a `.csv` file using semicolons (`;`) as separators, with the following structure:

```csv
Introduction text;
Closing text;
Question;LabelLeft;LabelRight;
...
