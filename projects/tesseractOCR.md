---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Alphanumeric Recognition"
date: 2023
published: true
labels:
  - Tesseract OCR
  - Python
summary: "I created an alphanumeric character recognition for my teams drone for the AUVSI SUAS 2023 compeition."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

The AUVSI SUAS competition is a competition where students design an unmanned aerial system (UAS) in order to meet certain goals. For the year of 2023, the rules of the competition were simple. You had to design an unmanned aerial system which could autonomously fly to waypoints provided by the competition and scan the area for any targets. If a target was located, the target would have to be classified and categorized, and then the UAS would drop a payload to that target. The payload that was used was a water bottle, and the targets were an image of a shape with a certain color and an alphanumeric character on it. Each payload would correspond to a target, and you had to drop the corresponding payload to its target.

For the competition, I was in charge of creating an optical character recognition (OCR) model in order properly identify what alphanumeric character was on the target. In order to do this, I used tesseract OCR, an open source OCR engine. I trained a tesseract model on several fonts and rotations of each alphanumeric character, capital A-Z, and 0-9. From there, I created scripts that could be used to evaluate the accuracy of the model. 

