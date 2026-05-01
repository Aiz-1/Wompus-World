# Wumpus World Agent

An intelligent agent that explores a Wumpus World grid using logical reasoning.  
It uses percepts like breeze and stench to infer safe paths and avoid danger.

## Features

- Grid-based Wumpus World simulation
- Knowledge Base with percept tracking
- CNF conversion for logical reasoning
- Resolution-based inference engine
- Safe and dangerous cell detection
- Step-by-step and automatic gameplay

## Project Structure

- `index.html` — Main UI
- `styles.css` — Styling
- `app.js` — Game logic and inference engine

## How It Works

### Knowledge Base
The agent stores percepts from visited cells such as:
- Breeze
- Stench

### Logical Reasoning
Rules are converted into CNF clauses and solved using resolution inference.

### Decision Making
- Move to safe cells first
- Avoid dangerous cells
- Take calculated risks when necessary

## How to Run

1. Open `index.html` in a browser
2. Click **New Game**
3. Use **Step** or **Auto** mode

## Technologies Used

- HTML
- CSS
- JavaScript
- Artificial Intelligence Concepts
- CNF Conversion
- Resolution Algorithm

## Author

**Aiz Ali**  
BS Computer Science