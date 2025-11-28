# Musical Instrument Inventory (freeCodeCamp Project)

This project is part of the freeCodeCamp “Object-Oriented Programming” curriculum.  
It introduces the basics of Python classes, object creation, and instance methods through a simple musical instrument inventory system.

## 📌 Features

- Defines a `MusicalInstrument` class with:
  - `name` — the instrument’s name  
  - `instrument_type` — category of the instrument (woodwind, brass, string, etc.)

- Includes two methods:
  - **play()** → prints a message about playing the instrument  
  - **get_fact()** → returns a short fact about the instrument family

- Demonstrates how to create instances and call class methods.

## 📁 Example Usage

```python
instrument_1 = MusicalInstrument('Oboe', 'woodwind')
instrument_2 = MusicalInstrument('Trumpet', 'brass')

instrument_2.play()
instrument_1.play()

print(instrument_1.get_fact())
print(instrument_2.get_fact())
