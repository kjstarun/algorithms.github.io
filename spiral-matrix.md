Algorithm:
Step- 1:
	Create an empty array - "final".
Step - 2:
	Create a counter variable c starting with 1.
Step- 3:
	Run a while loop of:
        - sc <= ec and sr <= er
Step- 4:
	Run a for loop of:
        - sc to ec:
        - place final[sr][i] as counter variable c.
        - Increment the counter with 1.
Step- 5:
    Increment the sr by 1.
Step- 6:
	Run a for loop of:
        - sr to er:
        - place final[i][ec] as counter variable c.
        - Increment the counter with 1.
Step- 7:
    Increment the er by 1.
Step- 8:
    Repeat from step 4 again in a reverse manner.
Step- 9:
    Print the final