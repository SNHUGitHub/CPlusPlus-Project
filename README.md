# C-Program

# Summarize the project and what problem it was solving.
I developed an object-oriented programming application to create two clocks (one in 12-hour and the other in 24-hour format) that display simultaneously and allow the user to increase an hour, a minute, or a second by selecting the option from a user menu.

# What did you do particularly well?
Writing the code to convert the clock to the 12-hour format.

# Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
I could enhance my code by adding more user buffer, such as the condition to print an error message and take the user back to the user menu if they enter a character or string. This would make my code more efficient by ensuring that the program doesn't break if the user accidentally enters a non-integer. 

# Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
Writing the code to change the 12-hour format from AM to PM and vice versa when the user added another second or minute was the most challenging, especially when the minute and second were both "59". This was challenging, because I had to solve for multiple parts of the logic. For example, if user increases the second by 1 from a second of "59", then I had to ensure that the second changes to "00", triggers the minute to increase by 1 and change to "00", then increase the hour by 1, and then updating the AM/PM correctly. I overcame this challenge by breaking down the logic and solving one part of it at a time, beginning with the second, and then running my code periodically to check that the logic works correctly before moving on to solving the next chunk of the problem. The tool that I'm adding to my support network is the debugging feature in the coding system. 

# What skills from this project will be particularly transferable to other projects or course work?
Creating loops and condition statements. For example, creating the user menu loop and all of the conditions that it's padded with to ensure that the correct actions are taken based on the user selection from the menu. This includes the condition to print an error message and request for the correct input when the user selects a menu option that is not listed.

# How did you make this program maintainable, readable, and adaptable?
By including detailed in-line comments so that it is easy to follow along. I also ensured that the codes were written with precision in mind, separated into their own functions with function names that clearly described their action, and main() had as minimal code as possible. 
