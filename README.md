## Technical challenge for the Business Data Analyst role at Phagos
Hi! Thank you for your interest in the Business Data Analyst role at Phagos.

This repository contains a technical challenge designed to assess your skills and suitability for the position. Please read this file carefully and complete the tasks as specified.

### Repository structure
- data/: Contains the datasets you will work with.
- analysis/: analysis files.
- README.md: This file with instructions for the challenge.

### Challenge
The challenge consists of two main tasks, described below. The total time expected to complete the challenge is approximately 1h and 15 minutes, divided as follows:

- 45 minutes for completing the two tasks;
- 30 minutes for discussing your approach and findings in a follow-up interview.

Please keep in mind that there are no strict rules on how to approach the tasks, nor correct or incorrect answers. Feel free to use any tools, libraries, or methods you deem appropriate. The goal is to demonstrate your analytical thinking, problem-solving skills, and ability to communicate your findings effectively.

### Setup
Phagos is a startup focused on developing phage therapy solutions for combating antibiotic-resistant bacterial infections in farm animals. The datasets provided contain information about how the bacterial infection for a specific pathogen are impacting the operations of several farms working with broiler chickens. In particular, the dataset has the following columns:

- Farm: Unique identifier for each farm.
- Lot: Unique identifier for each lot of broiler chickens within a farm.
- Total quantity: Total quantity of broiler chickens in the lot.
- Pathogen Presence: Whether the specific pathogen is present in the lot.
- Margin: The profit margin for the lot, in euros.
- Alphagos: Whether Alphagos treatment was applied to the lot.

### Task 1: Assessing the impact of bacterial infections on farm productivity
Analyze the dataset to determine how the presence of the pathogen affects the productivity of the farms.

### Task 2: Estimating a price for the Alphagos treatment
Estimate a reasonable price for the Alphagos treatment that would make it a viable option for farms to adopt. For this task, you can use the following additional information:

- Each lot where the pathogen is present and Alphagos is not applied has been treated with antibiotics.
- Each lot where the pathogen is not present has not been treated with antibiotics.
- Each lot where Alphagos has been applied has not been treated with antibiotics.
- The cost of antibiotic treatment is 0.05 euros per broiler chicken.
- Alphagos treatment needs to be used for each lot from day 1, without knowing if the pathogen will be present.
