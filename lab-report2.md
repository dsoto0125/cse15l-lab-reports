![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/8e7dfb80-ab36-4716-8fc6-7e92654ee8ae)

![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/a2e054cf-0601-4a11-8122-68ae6f1d5880)

This first screenshot displays the ChatServer file getting the URL with the help of `URI` as an arguement in `handleRequest`.After getting the available URL using the `URI` command, the method does the next line of `if` and checks the URL for the string of `/add-message` towards the end in order to enact the code to also use `.split()` that splits the message after `/add-message` with whatever string you set, in this case it is `user=` and then assigns the split pieces to an array that can be connected to a statement such as `user = parameter[1]` allowing the code to print out the message in the browser. The code also checks all previously stored values and prints them out in the browser but for now the array containing the history is empty and does not print any history for now. It uses historybuilder, an array to build a string and print it out(I used to chatgpt to help me find a way to print it out in the website as I was stuck on printing it out on the website without having to use return)

![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/47872620-ae3a-400a-8e40-928941f7a921)

The second screenshot is showing just about the same commands as the first, however the history array was updated the last time `/add-message` was done. The history array now contains the previous message sent and will print the same message and the new message and it will continually do this until the history array is filled to it's maximum occupancy of 100. The way that it iterates through the array is using the value of index which is set to 0 originally but goess up everytime something is appended to the array.Then once again iterating through the history to append it to historybuilder array and returns the entire historybuilder in a string form.

![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/34ec50f6-4779-4892-9309-05c6d1b3410d)
![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/040ba2bf-3b5a-4fd4-a495-77dc577df052)



