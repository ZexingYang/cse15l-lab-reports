## CSE15L_Week2&3_lab_Zexing_Yang

## Part 1 Search Engine
#Wed 11:00 AM B260, Group 2, Serpentmarsh





## Part 2 One bug from Lab3
#Wed 11:00 AM B260, Group 2, Serpentmarsh

A Test induce failure
			@Test 
			public void testReverseInPlace() {
				int[] input1 = { 3 };
				ArrayExamples.reverseInPlace(input1);
				assertArrayEquals(new int[]{ 3 }, input1);
			}

  
Doesn't induce failure
			@Test 
			public void testReverseInPlace() {
				int[] input1 = { };
				ArrayExamples.reverseInPlace(input1);
				assertArrayEquals(new int[]{ }, input1);
			}




## Part 3 New Knowledge
#Wed 11:00 AM B260, Group 2, Serpentmarsh

![Image](report2_increment.png)
I didn't know Building and Running the Server before and it amazes me when I could build a server that perform simple calculations show on the screen.





![Image](report2_increase3.png)
I also noticed the difference between localhost and ieng6-203: localhost is a hostname that refers to the current device used to access it while ieng-203 is my ucsd remote computer.
