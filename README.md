# Railway Logistics Simulation System

## **Overview**
A comprehensive simulation and management system for railway logistics, developed using Java as part of an academic Object-Oriented Programming (OOP) course. The application models and manages railway infrastructure, including stations, trainsets, connections, and various types of railroad cars.

## **Key Features**
- **Dynamic Trainset Management**: Create locomotives and various railroad cars (e.g., passenger, refrigerated, hazardous materials) with specific attributes and constraints.
- **Route Optimization**: Automatically calculate routes between railway stations using graph algorithms.
- **Real-Time Simulation**: Multithreaded train movement with speed adjustments, station stops, and collision prevention.
- **Hazard Detection and Exception Handling**: Custom exception handling for hazards like exceeding speed limits.
- **Report Generation**: Generate detailed reports on trainsets, including cargo summaries and journey progress.
- **Data Persistence**: Periodically save system state to a file (`AppState.txt`) with sorted trainset and car details.

## **Technologies Used**
- **Programming Language**: Java
- **Core Concepts**: OOP (inheritance, interfaces, generics), multithreading, file I/O, graph algorithms.
- **Custom Features**: Train collision prevention, custom exception handling.**
