**TASK** 

The task was to evaluate my undertanding on functions in Python. The instructions were to:

1. Write a function for translating DNA to protein
2. Write a function that simulates and generates a logistic population growth curve. Your function should include 2 extra parameters that randomize the length of the lag phase and the exponential phase [See population curve here] . Most living populations follow a logistic population growth. Therefore, your growth curve can be: Population Size vs Time, Cell density vs Time, OD vs Time, CFU vs Time, etc
3. Using your function, generate a dataframe with 100 different growth curves
4. Write a function for determining the time to reach 80% of the maximum growth; usually the carrying capacity
5. Finally, write a function for calculating the hamming distance between your Slack username and twitter/X handle (synthesize if you don’t have one). Feel free to pad it with extra words if they are not of the same length.

**SOLUTION** 

**Function_1:** I created a dictionary (codon_table) that maps out the dna sequence to the corresponding amino acids. 
                I then defined a function that translates a dna sequence into a protein sequence.

**Function_2:** I defined a logistic_growth function that simulates the population growth curve. 
                I added two extra parameters (lag_phase and exp_phase) to introduce randomness in the lag and exponential phases. The function calculates population size over time based on the logistic growth model.

**Function 3:** I used a loop to create 100 different growth curves with varying parameters for growth rate, initial population, lag phase, and exponential phase. 
                I stored the results in a dictionary and converted it to a dataframe-like structure.

**Function 4:** I created a time_to_80_percent_K function that iterates through the population data and identifies the time point when the population reaches 80% of the carrying capacity.
                

**OUTPUT** 


The ouput should look like this Hackbio_internship_oluwabusola/untitled9.py --wdir {'team_member1': {'name': 'Oluwabusola Asenuga', 'slack_username': 'Oluwabusola', 'email': 'asenugaoluwabusola@gmail.com', 'hobbies': 'watching vlogs, reading novels, dressing up', 'country': 'nigeria', 'discipline': 'zoology', 'preferred_language': 'python'}, 'team_member2': {'name': 'Kaosara Olabode', 'slack_username': 'TheResearchNerd', 'email': 'olabodeomowunmi5@gmail.com', 'hobbies': 'research, travelling, fashion', 'country': 'nigeria', 'discipline': 'natural product chemistry', 'preferred_language': 'R'}, 'team_member3': {'name': 'Himabindu Kumdam', 'slack_username': 'Himabindu', 'email': 'khbiitm@gmail.com', 'hobbies': 'music', 'country': 'india', 'discipline': 'biotechnology', 'preferred_language': 'R'}, 'team_member4': {'name': 'Aisha Mehmood', 'slack_username': 'Aisha', 'email': 'aishamehmood23@gmail.com', 'hobbies': 'reading, shopping', 'country': 'pakistan', 'discipline': 'biotechnology', 'preferred_language': 'R'}}
