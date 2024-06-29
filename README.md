# WPF Register Student

This application is meant to allow students to easily register for courses. It was developed using C#.
## Summary
The requirements for this application was to register students for courses with error handling, such as registering for a course that doesn't exist, registering for the same course twice, and registering for more than 9 credit hours. The program also shows the user what courses they are currently registered for as well as how many credit hours they are registered for.
## Strengths
As C# used to be my favorite language (C++ has recently topped it), I had a fairly easy time with the syntax. I also have made a basic WPF application in the past, so connecting the XAML to the CS file wasn't too difficult.
## WPF vs Console application
The WPF application was much more user friendly. The console application was difficult to read, as it did not clear the previous output each time something new was printed, so it became pretty messy really quickly. It was also a bit of a pain to type "y" each time you wanted to continue, and would probably have been better to use "q" to quit as an additional option.
## Coding and Debugging
I approached this task using iterative design, meaning I programmed a few lines and then tested the program each time. This allowed me to verify my code worked and helped me to avoid future difficulties. In the future, I will use these strategies to help me write functional code and avoid bugs.
## Challenges and Innovations
I didn't do much innovating for this application, but I had a bit of a challenge remembering how to do a foreach loop and had to try a few times, but I actually learned I didn't need to cast an `object` type to a `Course` type to use it's `ToString` method, so I was able to avoid a few inefficiencies. 