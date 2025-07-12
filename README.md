# HikingTripPlanner

A C++17 console application that helps users plan a hiking trip by recommending:

- Items to pack based on trail type and weather  
- Number of breaks based on duration and fitness level  
- An overall difficulty rating (Easy, Medium, Hard)  

---

## Features

1. **Trail Type Selection**: Choose from flat, hilly, forest, or desert.  
2. **Weather Selection**: Choose from hot, cold, sunny, or rainy.  
3. **Duration Input**: Enter planned hike time in hours (supports floats).  
4. **Fitness Level**: Select beginner, intermediate, or advanced.  
5. **Packing List**: Generates a `std::vector<std::string>` of recommended items.  
6. **Break Calculation**: Suggests breaks (1 per 2 h for beginners, 1 per 3 h for intermediates, 1 per 4 h for advanced).  
7. **Difficulty Rating**: Computes an overall difficulty score.  

---

## Requirements

- C++17 compatible compiler (e.g., `g++`, `clang++`, MSVC)  
- Standard C++ library  

---

## Build & Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/kristinaduh/HikingTripPlanner.git
   cd HikingTripPlanner
