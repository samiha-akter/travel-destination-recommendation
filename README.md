# Rule-Based System for Travel Destination Recommendation  

A **Rule-Based System for Travel Destination Recommendation** aims to assist travelers in finding destinations quickly and efficiently by leveraging logical rules based on user preferences such as weather, budget, activity, and duration of stay. This project simplifies the decision-making process by narrowing down travel options based on user input.  

## Features  

- User-friendly interaction to gather preferences.  
- Recommendations based on weather, budget, activities, and seasons.  
- Calculates total cost for the duration of stay.  
- Outputs destination details such as cost per day and total cost.  
- Interactive and rule-driven decision-making system.  

## Tech Used  

- **Turbo Prolog**: Used for implementing the rule-based logic.  
- **DOSBox**: Emulator for running Turbo Prolog on modern systems.  

## How It Works  

1. The system asks the user about their preferences:  
   - Weather type (e.g., beach, cold, moderate).  
   - Budget (economy, mid-range, luxury).  
   - Activities (e.g., adventure, relaxation, sightseeing).  
   - Duration of stay (in days).  
2. Matches the input with predefined facts about destinations.  
3. Calculates and displays:  
   - Recommended destinations.  
   - Cost per day and total cost for the stay.  

## Setup  

1. Download and install [DOSBox](https://www.dosbox.com/).  
2. Install Turbo Prolog and set it up in DOSBox.  
3. Copy the `.pro` source code file to your Turbo Prolog working directory.  

## Running the Project  

1. Start DOSBox and navigate to your Turbo Prolog directory.  
2. Load the project file in Turbo Prolog.  
3. Compile and run the program using the `goal` directive:  

   ```prolog  
   goal  
       go.  
