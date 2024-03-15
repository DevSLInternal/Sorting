# Sorting Visualizer

Welcome to Sorting Visualizer! I built this application because I was fascinated by sorting algorithms, and I wanted to visualize them in action. I hope that you enjoy playing around with this visualization tool just as much as I enjoyed building it. You can access it here (use Google Chrome!): https://clementmihailescu.github.io/Sorting-Visualizer/
Here's a simple flow chart:
```mermaid
sequenceDiagram
    participant Anshul
    participant Arpit
    participant Satwik
    participant Raj
    participant Shruti

    Anshul->>Arpit:First validated the idea by doing a low level implementation (Proof of concept) of the components involved in the project.
    activate Arpit
    
    Arpit->>Satwik:Created the website's UI
    activate Satwik
    deactivate Arpit
    
    Satwik->>Raj:Improved UI using CSS
    activate Raj
    deactivate Satwik
    
    Raj->>Shruti:Created Bars Using JavaScript
    activate Shruti
    deactivate Raj
    
    Shruti->>Anshul:Implemented Bubble Sort Algorithm
    activate Anshul
    deactivate Shruti
    
    Anshul->>Arpit:Implementation of remaining Sorting function
    activate Arpit
    deactivate Anshul
    
    Arpit->>Satwik:Changing the number of bars and speed
    activate Satwik
    deactivate Arpit
    
    Satwik->>Raj: Host your website live
    deactivate Satwik
    activate Raj
    
    Raj->>Shruti: Created a navigation bar for changing various sort
    deactivate Raj 
    activate Shruti
    
    Shruti->>Anshul:Collected the data for fetching our output
    deactivate Shruti
```
