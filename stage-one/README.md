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

Function 3 ouput should look like this

{'Time': 0, 'Curve_1': 7, 'Curve_2': 9, 'Curve_3': 11, 'Curve_4': 13, 'Curve_5': 15, 'Curve_6': 17, 'Curve_7': 19, 'Curve_8': 21, 'Curve_9': 23, 'Curve_10': 25, 'Curve_11': 27, 'Curve_12': 29, 'Curve_13': 31, 'Curve_14': 33, 'Curve_15': 35, 'Curve_16': 37, 'Curve_17': 39, 'Curve_18': 41, 'Curve_19': 43, 'Curve_20': 5, 'Curve_21': 7, 'Curve_22': 9, 'Curve_23': 11, 'Curve_24': 13, 'Curve_25': 15, 'Curve_26': 17, 'Curve_27': 19, 'Curve_28': 21, 'Curve_29': 23, 'Curve_30': 25, 'Curve_31': 27, 'Curve_32': 29, 'Curve_33': 31, 'Curve_34': 33, 'Curve_35': 35, 'Curve_36': 37, 'Curve_37': 39, 'Curve_38': 41, 'Curve_39': 43, 'Curve_40': 5, 'Curve_41': 7, 'Curve_42': 9, 'Curve_43': 11, 'Curve_44': 13, 'Curve_45': 15, 'Curve_46': 17, 'Curve_47': 19, 'Curve_48': 21, 'Curve_49': 23, 'Curve_50': 25, 'Curve_51': 27, 'Curve_52': 29, 'Curve_53': 31, 'Curve_54': 33, 'Curve_55': 35, 'Curve_56': 37, 'Curve_57': 39, 'Curve_58': 41, 'Curve_59': 43, 'Curve_60': 5, 'Curve_61': 7, 'Curve_62': 9, 'Curve_63': 11, 'Curve_64': 13, 'Curve_65': 15, 'Curve_66': 17, 'Curve_67': 19, 'Curve_68': 21, 'Curve_69': 23, 'Curve_70': 25, 'Curve_71': 27, 'Curve_72': 29, 'Curve_73': 31, 'Curve_74': 33, 'Curve_75': 35, 'Curve_76': 37, 'Curve_77': 39, 'Curve_78': 41, 'Curve_79': 43, 'Curve_80': 5, 'Curve_81': 7, 'Curve_82': 9, 'Curve_83': 11, 'Curve_84': 13, 'Curve_85': 15, 'Curve_86': 17, 'Curve_87': 19, 'Curve_88': 21, 'Curve_89': 23, 'Curve_90': 25, 'Curve_91': 27, 'Curve_92': 29, 'Curve_93': 31, 'Curve_94': 33, 'Curve_95': 35, 'Curve_96': 37, 'Curve_97': 39, 'Curve_98': 41, 'Curve_99': 43, 'Curve_100': 5}
{'Time': 1, 'Curve_1': 7, 'Curve_2': 9, 'Curve_3': 11, 'Curve_4': 13, 'Curve_5': 15.0, 'Curve_6': 17, 'Curve_7': 19, 'Curve_8': 21, 'Curve_9': 23, 'Curve_10': 25.0, 'Curve_11': 27, 'Curve_12': 29, 'Curve_13': 31, 'Curve_14': 33, 'Curve_15': 35.0, 'Curve_16': 37, 'Curve_17': 39, 'Curve_18': 41, 'Curve_19': 43, 'Curve_20': 5.0, 'Curve_21': 7, 'Curve_22': 9, 'Curve_23': 11, 'Curve_24': 13, 'Curve_25': 15.0, 'Curve_26': 17, 'Curve_27': 19, 'Curve_28': 21, 'Curve_29': 23, 'Curve_30': 25.0, 'Curve_31': 27, 'Curve_32': 29, 'Curve_33': 31, 'Curve_34': 33, 'Curve_35': 35.0, 'Curve_36': 37, 'Curve_37': 39, 'Curve_38': 41, 'Curve_39': 43, 'Curve_40': 5.0, 'Curve_41': 7, 'Curve_42': 9, 'Curve_43': 11, 'Curve_44': 13, 'Curve_45': 15.0, 'Curve_46': 17, 'Curve_47': 19, 'Curve_48': 21, 'Curve_49': 23, 'Curve_50': 25.0, 'Curve_51': 27, 'Curve_52': 29, 'Curve_53': 31, 'Curve_54': 33, 'Curve_55': 35.0, 'Curve_56': 37, 'Curve_57': 39, 'Curve_58': 41, 'Curve_59': 43, 'Curve_60': 5.0, 'Curve_61': 7, 'Curve_62': 9, 'Curve_63': 11, 'Curve_64': 13, 'Curve_65': 15.0, 'Curve_66': 17, 'Curve_67': 19, 'Curve_68': 21, 'Curve_69': 23, 'Curve_70': 25.0, 'Curve_71': 27, 'Curve_72': 29, 'Curve_73': 31, 'Curve_74': 33, 'Curve_75': 35.0, 'Curve_76': 37, 'Curve_77': 39, 'Curve_78': 41, 'Curve_79': 43, 'Curve_80': 5.0, 'Curve_81': 7, 'Curve_82': 9, 'Curve_83': 11, 'Curve_84': 13, 'Curve_85': 15.0, 'Curve_86': 17, 'Curve_87': 19, 'Curve_88': 21, 'Curve_89': 23, 'Curve_90': 25.0, 'Curve_91': 27, 'Curve_92': 29, 'Curve_93': 31, 'Curve_94': 33, 'Curve_95': 35.0, 'Curve_96': 37, 'Curve_97': 39, 'Curve_98': 41, 'Curve_99': 43, 'Curve_100': 5.0}
{'Time': 2, 'Curve_1': 7.0, 'Curve_2': 9, 'Curve_3': 11, 'Curve_4': 13, 'Curve_5': 24.73081074287699, 'Curve_6': 17.0, 'Curve_7': 19, 'Curve_8': 21, 'Curve_9': 23, 'Curve_10': 27.629271093400696, 'Curve_11': 27.0, 'Curve_12': 29, 'Curve_13': 31, 'Curve_14': 33, 'Curve_15': 57.70522506671298, 'Curve_16': 37.0, 'Curve_17': 39, 'Curve_18': 41, 'Curve_19': 43, 'Curve_20': 5.52585421868014, 'Curve_21': 7.0, 'Curve_22': 9, 'Curve_23': 11, 'Curve_24': 13, 'Curve_25': 24.73081074287699, 'Curve_26': 17.0, 'Curve_27': 19, 'Curve_28': 21, 'Curve_29': 23, 'Curve_30': 27.629271093400696, 'Curve_31': 27.0, 'Curve_32': 29, 'Curve_33': 31, 'Curve_34': 33, 'Curve_35': 57.70522506671298, 'Curve_36': 37.0, 'Curve_37': 39, 'Curve_38': 41, 'Curve_39': 43, 'Curve_40': 5.52585421868014, 'Curve_41': 7.0, 'Curve_42': 9, 'Curve_43': 11, 'Curve_44': 13, 'Curve_45': 24.73081074287699, 'Curve_46': 17.0, 'Curve_47': 19, 'Curve_48': 21, 'Curve_49': 23, 'Curve_50': 27.629271093400696, 'Curve_51': 27.0, 'Curve_52': 29, 'Curve_53': 31, 'Curve_54': 33, 'Curve_55': 57.70522506671298, 'Curve_56': 37.0, 'Curve_57': 39, 'Curve_58': 41, 'Curve_59': 43, 'Curve_60': 5.52585421868014, 'Curve_61': 7.0, 'Curve_62': 9, 'Curve_63': 11, 'Curve_64': 13, 'Curve_65': 24.73081074287699, 'Curve_66': 17.0, 'Curve_67': 19, 'Curve_68': 21, 'Curve_69': 23, 'Curve_70': 27.629271093400696, 'Curve_71': 27.0, 'Curve_72': 29, 'Curve_73': 31, 'Curve_74': 33, 'Curve_75': 57.70522506671298, 'Curve_76': 37.0, 'Curve_77': 39, 'Curve_78': 41, 'Curve_79': 43, 'Curve_80': 5.52585421868014, 'Curve_81': 7.0, 'Curve_82': 9, 'Curve_83': 11, 'Curve_84': 13, 'Curve_85': 24.73081074287699, 'Curve_86': 17.0, 'Curve_87': 19, 'Curve_88': 21, 'Curve_89': 23, 'Curve_90': 27.629271093400696, 'Curve_91': 27.0, 'Curve_92': 29, 'Curve_93': 31, 'Curve_94': 33, 'Curve_95': 57.70522506671298, 'Curve_96': 37.0, 'Curve_97': 39, 'Curve_98': 41, 'Curve_99': 43, 'Curve_100': 5.52585421868014}
{'Time': 3, 'Curve_1': 8.380520527160225, 'Curve_2': 9.0, 'Curve_3': 11, 'Curve_4': 13, 'Curve_5': 40.7742, 'Curve_6': 30.362641477111215, 'Curve_7': 19.0, 'Curve_8': 21, 'Curve_9': 23, 'Curve_10': 30.535064846105097, 'Curve_11': 32.324864890475155, 'Curve_12': 29.0, 'Curve_13': 31, 'Curve_14': 33, 'Curve_15': 95.13980000000001, 'Curve_16': 66.08339615606559, 'Curve_17': 39.0, 'Curve_18': 41, 'Curve_19': 43, 'Curve_20': 6.107012969221019, 'Curve_21': 8.380520527160225, 'Curve_22': 9.0, 'Curve_23': 11, 'Curve_24': 13, 'Curve_25': 40.7742, 'Curve_26': 30.362641477111215, 'Curve_27': 19.0, 'Curve_28': 21, 'Curve_29': 23, 'Curve_30': 30.535064846105097, 'Curve_31': 32.324864890475155, 'Curve_32': 29.0, 'Curve_33': 31, 'Curve_34': 33, 'Curve_35': 95.13980000000001, 'Curve_36': 66.08339615606559, 'Curve_37': 39.0, 'Curve_38': 41, 'Curve_39': 43, 'Curve_40': 6.107012969221019, 'Curve_41': 8.380520527160225, 'Curve_42': 9.0, 'Curve_43': 11, 'Curve_44': 13, 'Curve_45': 40.7742, 'Curve_46': 30.362641477111215, 'Curve_47': 19.0, 'Curve_48': 21, 'Curve_49': 23, 'Curve_50': 30.535064846105097, 'Curve_51': 32.324864890475155, 'Curve_52': 29.0, 'Curve_53': 31, 'Curve_54': 33, 'Curve_55': 95.13980000000001, 'Curve_56': 66.08339615606559, 'Curve_57': 39.0, 'Curve_58': 41, 'Curve_59': 43, 'Curve_60': 6.107012969221019, 'Curve_61': 8.380520527160225, 'Curve_62': 9.0, 'Curve_63': 11, 'Curve_64': 13, 'Curve_65': 40.7742, 'Curve_66': 30.362641477111215, 'Curve_67': 19.0, 'Curve_68': 21, 'Curve_69': 23, 'Curve_70': 30.535064846105097, 'Curve_71': 32.324864890475155, 'Curve_72': 29.0, 'Curve_73': 31, 'Curve_74': 33, 'Curve_75': 95.13980000000001, 'Curve_76': 66.08339615606559, 'Curve_77': 39.0, 'Curve_78': 41, 'Curve_79': 43, 'Curve_80': 6.107012969221019, 'Curve_81': 8.380520527160225, 'Curve_82': 9.0, 'Curve_83': 11, 'Curve_84': 13, 'Curve_85': 40.7742, 'Curve_86': 30.362641477111215, 'Curve_87': 19.0, 'Curve_88': 21, 'Curve_89': 23, 'Curve_90': 30.535064846105097, 'Curve_91': 32.324864890475155, 'Curve_92': 29.0, 'Curve_93': 31, 'Curve_94': 33, 'Curve_95': 95.13980000000001, 'Curve_96': 66.08339615606559, 'Curve_97': 39.0, 'Curve_98': 41, 'Curve_99': 43, 'Curve_100': 6.107012969221019}
{'Time': 4, 'Curve_1': 10.0333034723077, 'Curve_2': 11.672368738614622, 'Curve_3': 11.0, 'Curve_4': 13, 'Curve_5': 67.22526822614766, 'Curve_6': 54.22882338044672, 'Curve_7': 36.76103803354296, 'Curve_8': 21.0, 'Curve_9': 23, 'Curve_10': 33.7464633795043, 'Curve_11': 38.699884821758275, 'Curve_12': 37.61096593553601, 'Curve_13': 31.0, 'Curve_14': 33, 'Curve_15': 156.85895919434455, 'Curve_16': 118.02743912214873, 'Curve_17': 75.45686754253555, 'Curve_18': 41.0, 'Curve_19': 43, 'Curve_20': 6.749292675900859, 'Curve_21': 10.0333034723077, 'Curve_22': 11.672368738614622, 'Curve_23': 11.0, 'Curve_24': 13, 'Curve_25': 67.22526822614766, 'Curve_26': 54.22882338044672, 'Curve_27': 36.76103803354296, 'Curve_28': 21.0, 'Curve_29': 23, 'Curve_30': 33.7464633795043, 'Curve_31': 38.699884821758275, 'Curve_32': 37.61096593553601, 'Curve_33': 31.0, 'Curve_34': 33, 'Curve_35': 156.85895919434455, 'Curve_36': 118.02743912214873, 'Curve_37': 75.45686754253555, 'Curve_38': 41.0, 'Curve_39': 43, 'Curve_40': 6.749292675900859, 'Curve_41': 10.0333034723077, 'Curve_42': 11.672368738614622, 'Curve_43': 11.0, 'Curve_44': 13, 'Curve_45': 67.22526822614766, 'Curve_46': 54.22882338044672, 'Curve_47': 36.76103803354296, 'Curve_48': 21.0, 'Curve_49': 23, 'Curve_50': 33.7464633795043, 'Curve_51': 38.699884821758275, 'Curve_52': 37.61096593553601, 'Curve_53': 31.0, 'Curve_54': 33, 'Curve_55': 156.85895919434455, 'Curve_56': 118.02743912214873, 'Curve_57': 75.45686754253555, 'Curve_58': 41.0, 'Curve_59': 43, 'Curve_60': 6.749292675900859, 'Curve_61': 10.0333034723077, 'Curve_62': 11.672368738614622, 'Curve_63': 11.0, 'Curve_64': 13, 'Curve_65': 67.22526822614766, 'Curve_66': 54.22882338044672, 'Curve_67': 36.76103803354296, 'Curve_68': 21.0, 'Curve_69': 23, 'Curve_70': 33.7464633795043, 'Curve_71': 38.699884821758275, 'Curve_72': 37.61096593553601, 'Curve_73': 31.0, 'Curve_74': 33, 'Curve_75': 156.85895919434455, 'Curve_76': 118.02743912214873, 'Curve_77': 75.45686754253555, 'Curve_78': 41.0, 'Curve_79': 43, 'Curve_80': 6.749292675900859, 'Curve_81': 10.0333034723077, 'Curve_82': 11.672368738614622, 'Curve_83': 11.0, 'Curve_84': 13, 'Curve_85': 67.22526822614766, 'Curve_86': 54.22882338044672, 'Curve_87': 36.76103803354296, 'Curve_88': 21.0, 'Curve_89': 23, 'Curve_90': 33.7464633795043, 'Curve_91': 38.699884821758275, 'Curve_92': 37.61096593553601, 'Curve_93': 31.0, 'Curve_94': 33, 'Curve_95': 156.85895919434455, 'Curve_96': 118.02743912214873, 'Curve_97': 75.45686754253555, 'Curve_98': 41.0, 'Curve_99': 43, 'Curve_100': 6.749292675900859}

Function 5 output should look like this.

Hamming Distance: 13
