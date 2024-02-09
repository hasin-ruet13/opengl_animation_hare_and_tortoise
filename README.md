# Hare and Tortoise OpenGL Animation
## Project Description
This project is an OpenGL animation that tells the classic story of the Hare and the Tortoise. It demonstrates basic animation techniques in OpenGL, including movement, texture mapping, and basic physics. The story is visualized through animated characters (a hare and a tortoise) in a race scenario, where the hare, confident in its speed, ends up losing to the slow and steady tortoise.

## Features
* Animation of two characters: a hare and a tortoise.
* Dynamic background that simulates the race environment.
* Interaction based on the storyline (e.g., the hare sleeps, and the tortoise wins).
* Display of moral at the end of the story.

## Installation
## Prerequisites
* C++ compiler (GCC recommended)
* OpenGL library
* GLUT library

For Windows, you might need to install MinGW (for GCC) and freeglut (for the GLUT library).

For macOS, you can use Homebrew to install the required libraries:
```bash
brew install gcc
brew install freeglut
```
For Linux (Ubuntu/Debian), you can install the dependencies using apt-get:
```bash
sudo apt-get update
sudo apt-get install g++ freeglut3-dev
```
## Compiling the Project
After installing the prerequisites, you can compile the project using the following command in the terminal (Linux/macOS) or command prompt (Windows):
```bash
g++ main_d.cpp -o hare_tortoise -lGL -lGLU -lglut
```
## Usage
To run the animation, execute the compiled program:
```bash
./hare_tortoise
```
Controls and interactions are predefined as part of the animation script based on the Hare and Tortoise story.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.


