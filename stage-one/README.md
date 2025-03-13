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

**Function 4:** I defined a function for time_to_80_percent_K that iterates through the population data and identifies the time point when the population reaches 80% of the carrying capacity.

**Function 5:** I defined a hamming_distance function that compares two strings(USERNAME). If the strings are of different lengths, I padded the shorter string with spaces to ensure accurate comparison.

**OUTPUT** 
Function 2 ouput should look like this C:/Users/Administrator/Hackbio_internship_oluwabusola/untitled3.py --wdir
Time: 0 Population: 10
Time: 1 Population: 10
Time: 2 Population: 10
Time: 3 Population: 10
Time: 4 Population: 10
Time: 5 Population: 10.0
Time: 6 Population: 16.487207161917993
Time: 7 Population: 27.1828
Time: 8 Population: 44.816845484098444
Time: 9 Population: 73.89046158400001
Time: 10 Population: 121.82473474251512
Time: 11 Population: 200.85496391455553
Time: 12 Population: 331.153739955884
Time: 13 Population: 545.980031309658
Time: 14 Population: 900.1685882472805
Time: 15 Population: 10.0
Time: 16 Population: 16.380940606695287
Time: 17 Population: 26.72361349405436
Time: 18 Population: 43.30896397722695
Time: 19 Population: 69.45307271012312
Time: 20 Population: 109.571887488839
Time: 21 Population: 168.66450575501565
Time: 22 Population: 250.654961599656
Time: 23 Population: 355.46037069513625
Time: 24 Population: 476.237195901129
Time: 25 Population: 599.858794535129
Time: 26 Population: 711.9505828755659
Time: 27 Population: 802.9565142190788
Time: 28 Population: 870.4423728633312
Time: 29 Population: 917.1983255452668
Time: 30 Population: 948.0869052687757
Time: 31 Population: 967.8565369934511
Time: 32 Population: 980.2542642041471
Time: 33 Population: 987.9298245451423
Time: 34 Population: 992.6441312591205
Time: 35 Population: 995.5254879663613
Time: 36 Population: 997.2812838277758
Time: 37 Population: 998.3492488723961
Time: 38 Population: 998.9981177506343
Time: 39 Population: 999.3920878490686
Time: 40 Population: 999.6311943016821
Time: 41 Population: 999.7762754957783
Time: 42 Population: 999.8642922370462
Time: 43 Population: 999.917684657947
Time: 44 Population: 999.9500715873796
Time: 45 Population: 999.9697162818376
Time: 46 Population: 999.9816317713962
Time: 47 Population: 999.9888590219207
Time: 48 Population: 999.9932426233212
Time: 49 Population: 999.9959014315893
Time: 50 Population: 999.9975140877528
