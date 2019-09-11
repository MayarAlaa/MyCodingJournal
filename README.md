# MyCodingJournal
A journal to keep track of what I learn/hear about everyday .

WARNING: My words may seem unrelated and unclear .

# 11/9/2019

Today, I learned the difference between authentication and authorization.
# 10/9/2019

Today,I revised the concept of normalization in SQL. I also read about null propagation operator in C#.


# 9/9/2019

Be aware of the conditions in the where clause in sql server.
# 8/9/2019

Today, I did a very little reading about setting up the timeout for MVC applications .The timeout is set up at two places .One at web.config file and the other through IIS recycle.

# 1/9/2019

This month may be the beginning of the end of a certain period in my life.
What I'm about to write is not exactly about coding. Over the last few days, 
I have been practicing answering some IQ questions. I felt the questions are reviving my mind. They made me revise things that I'd forgotten how to do manually because why when using the calculator is a lot easier.
These things include multiplication, long division ,turning a decimal to a fraction, simplifying fractions... etc


# 29/8/2019

Sometimes the tasks I'm assigned to during the sprint
help me learn more about the business of the product
on which we're working .This week's sprint taught me a bit 
technical,but I feel it was more about the business.
Talking about the technical side, today I learned how to call the try block more than one time
in case an exception is caught and you just want to go to the try block again.
Just use a while loop and flag to stop it once the try block is executed without any exceptions.


# 27/8/2019

I just want to say that I love Route 
Debugger <3. It really helps a lot with tracking your routes.


# 22/8/2019

Finallyyy back to work after a very long vacation.

**MSSQL**: select * from MyTable where MyColumn = null will always evaluate to null because null means unknown.So basically you're comparing something unknown to another unknown.
To do this check use MyColumn is null (resource: https://stackoverflow.com/questions/9581745/sql-is-null-and-null)

**Sharing Knowledge Sessions**: Amazon Lamda Function.

**Problem Solving at home**: I'm a total disappointment :( :(


# 7/8/2019

ConcurrentDictionary helps when using multiple threads.It ensures that there are no repeated keys. Tryadd will return false if the key was already added before.

# 6/8/2019

Dictionary vs Hashtable
The Dictionary is a generic type and that provides type safety and no need for boxing/unboxing.Its implementation is based on the Hashtable.
The Hashtable on the other hand is non-generic so boxing/unboxing is needed.
First time to hear about ConcurrentDictionary.Need to read about it.


# 5/8/2019

Wasn't a productive day. I've been working with c# and .Net for a couple of months now.
Dot net is an environment or a framework that provide some services for applications built on it. These services include cryptography, reading files,connecting to databases.... etc.
Dot net consists of CLR(Common Language Runtime)and FCL (Framework Class Libraries. 
CLR manages my app when it's running. It does things like memory management, garbage collection, Exception handling and it's independent of the operating system and the hardware used.
On the other hand, FCL provides **functionality** to my app.It represent the ready-made functions and libraries that are used in the app.


Side-note :The courses on LinkedIn learning are cool! 


# 4/8/2019

Today, I read **Software Entropy** and the story of **Stone Soup and Boiled Frogs** from the **Pragmatic Programmer book**. The thing I like the most is while reading, I can relate to some situations that I had encountered during work. For example,the story of the broken window reminded me of a stored procedure that was a bit difficult for me as a junior to understand and it was used multiple times. For me it was always complicated and hard to read until it was fixed .This stored procedure could have led to a disaster afterwards .Always remember not to live with the mind set of "I'll just follow what exists" . 

The story of the boiled stones is also brilliant .If I wait for inputs from people around me to do/start sth,I'll wait forever.  
