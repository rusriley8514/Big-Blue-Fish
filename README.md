# Big-Blue-Fish
This is my final project for my C# class at University of the Cumberlands - I made a D&amp;D Character Randomizer that picks your class, rolls the dice for abilities, and gives two feats that are pertinent to the class that is picked.
Absolutely, Rusty! Here’s a polished and structured `README.md` for your D&D Character Creator project that blends professionalism with your learning journey and unique design choices:

---

# Dungeons & Dragons Character Creator  
**Console App Final Project – C# / OOP**

This project is an interactive console-based character creator that generates unique D&D characters by combining structured logic, randomness, and roleplay flavor. Built as a final project for the Object-Oriented Programming course at University of the Cumberlands, it exemplifies core OOP principles through immersive gameplay mechanics.

## Features  
- Race and class selection with user input validation  
- Ability score generation using 4d6 drop-the-lowest method  
- Class-prioritized assignment of ability scores  
- Randomized class-specific background generation  
- Feat selection with duplicate avoidance via dictionary-based logic  
- Clean character summary output using an overridden `ToString()` method

## Tech Stack  
- **Language**: C#  
- **Platform**: .NET Core Console App  
- **Paradigm**: Object-Oriented Programming  

## What I Learned  
Throughout this project, I deepened my understanding of:

- **Encapsulation and modular design**: Structuring reusable methods for character generation logic  
- **Inheritance and polymorphism**: Modeling customizable objects with flexible behavior  
- **Randomness control and validation**: Preventing duplicate selections in randomized feat allocation  
- **Algorithmic reasoning**: Applying a modified 4d6 method and sorting logic to stat balancing  
- **User experience in command-line interfaces**: Guiding players through coherent character creation flow with meaningful feedback

## Sample Output  
```text
Character Created Successfully!
Name: Thranduil
Race: Elf
Class: Wizard
Hit Points: 15
Magic User: True
Background: Arcane Researcher
Ability Scores:
  Strength: 8
  Dexterity: 14
  Constitution: 12
  Intelligence: 18
  Wisdom: 13
  Charisma: 10
Feats: Magic Initiate, Elemental Adept
```

## Future Improvements  
- Integrate equipment loadouts and starting gold  
- Expand race/class options and feat pools  
- Upgrade UI to a Windows Forms or WPF version  
- Save/load character profiles in JSON or text format  
- Optional multiclassing system for advanced players

## Repository Structure  
```
├── Program.cs
├── Character.cs
├── README.md
```

## Credits  
Created by Rusty — logical thinker, RPG enthusiast, and problem-solver-in-progress.
