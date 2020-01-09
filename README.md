# Bin Collection for Home Assistant

![Imgur](https://i.imgur.com/w9zJRDT.png)
---

### Table of Contents
-   [Description](#Description)
-   [Installation and Usage](#Installation-and-Usage)
-   [Learning Outcomes](#Learning-Outcomes)
-   [References](#References)

---

### Description
A series of Python functions to determine what the next rubbish collection date will be, and
which bin (in addition to the landfill bin) will be emptied.

This code is modified for my own personal use. Your waste collection cycle may differ resulting
in inaccurate outputs. The original code was written by @Rookeh and can be found 
[at this Home Assistant thread](https://community.home-assistant.io/t/bin-waste-collection/55451/56).

---

### Installation and Usage
1. `cd` into your Home Assistant config directory
2. Create a new directory called `scripts`
3. Create a project level directory with in your `scripts` directory called `bin-day`
4. Clone this Github repo into your new `bin-day` directory
5. Create 2 new sensors in Home Assistant using the code from `bin-day.yaml`
6. Restart Home Assistant and add the sensors to any card you wish
7. Enjoy not having to figure out which bin needs to go out... Ever again!
---

### Learning Outcomes
This project is a demonstration of my ability to use:
-   Functions
-   Flow control using `if` and `else` statements
-   Integration of python scripts into Home Assistant
-   Readme creation and markdown

---

### References
-   [The Home Assistant Forums](https://community.home-assistant.io/t/bin-waste-collection/55451/56)

---

### Author Information
-   [LinkedIn](https://www.linkedin.com/in/tim-lawrence/)
-   [Github](https://github.com/a5pire)

---

[Back to the top](#Bin Collection for Home Assistant)
