---
title: Automated Game Testing
date: 2024-08-24

tags:
  - Software Engineering
  - Game Development
  - Artificial Intelligence
---

This research project explores the validation, investigation, and improvement of the Xumes framework, which integrates Behavior-Driven Development (BDD) with Reinforcement Learning (RL) for video game testing. 

The study aims to advance game testing methodologies, particularly within the Godot Engine, by developing a comprehensive suite of tools and strategies that enhance the reliability and thoroughness of game quality assurance.

## Advisor
- [Fabio Petrillo, Ph.D.](https://fabiopetrillo.com)


## Key Contributions

### 1. **Xumes Framework Validation**
   - The framework was tested in a practical context by developing a new game, **Royal Knight**, using the Godot Engine. This "toy game" facilitated various testing scenarios that highlighted the strengths and limitations of Xumes.
   - Manual and automated testing were applied, with initial focus on validating test scripts manually before introducing RL agents for more advanced testing.

### 2. **Behavior-Driven Development (BDD)**
   - The study emphasizes the importance of BDD in creating clear and reusable test scenarios. Scenarios were written in Gherkin language, promoting better collaboration between developers, testers, and stakeholders.

### 3. **Reinforcement Learning Challenges**
   - While integrating RL into automated testing showed potential, several challenges were encountered, particularly in communication between the RL agents and the game engine. These challenges highlight the need for further improvements in the framework's core components.

### 4. **Testing Complex Games**
   - The project also explored testing more complex 3D games, like **Super Tux Party**, revealing the necessity for automation in setting up pre-game conditions to streamline testing processes.

### 5. **Comparison of Automated Game Testing Tools**
   - The paper provides a comparison of different automated game testing tools across various game engines (Unity, Unreal, Godot), highlighting their features, supported platforms, and limitations.

## Future Work
Future research will focus on enhancing Xumes' communication capabilities, simplifying scripting processes, and extending its application to more complex game genres. Additionally, a comprehensive study of existing automated game testing tools will be conducted to evaluate their effectiveness and identify potential innovations in game testing methodologies.

## Resources
- **Royal Knight Code**: [GitHub Repository](https://github.com/viniciusmioto/royal_knight)
- **Xumes Framework Documentation**: [Read the Docs](https://xumes.readthedocs.io/en/latest/)

--- 

This summary provides a concise overview of the paper's contents for the README file, focusing on key aspects and future directions.