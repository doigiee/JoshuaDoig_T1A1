# -Markdown JoshuaDoig_T1A1- 

## *Q1 Identify and explain common and important components and concepts of web development markup languages.*

There are many important components and concepts of web development markup languages. One concept is that all markup languages change over time, may merge together, break into separate models or evolve. To explain, different markup languages may merge into one if their semantics or syntax is similar enough dependant on such things as names of elements, attributes or content (Tennison, 2002).  

Through comparing different type of markup language such as XML, HTML, SGML it can be seen that they all implement tags, though the language, syntax or formatting used may be different, these tags help specify a function. The function lets the system reading the markup know how a piece of information or text is to be displayed or rendered (Gregersen, 2021).

From experience, markup languages can be useful to add elements such as color to show creativity and intuitiveness through design, can be used to let the coding software know what type of file is being created (i.e. .txt, .html). It’s important for developers to understand the proper syntax; indentation and formatting of mark-up languages to better enable readability and deployment. 





## *Q2 Define the features of the following technologies that are essential in terms of the development of the internet and explain how each technology has contributed to the development of the internet.*

Packets, IP addresses (IPv4 and IPv6), routers and routing and domains and DNS have all been essential in the development of the internet. The features and contribution to the development of the internet are as follows:

Packets can be defined in three main parts: the header, payload and trailer. The header contains instructions about the data being carried such as the length of the packet, synchronisation, packet number, protocol, address to be sent to, and address where the packet came from. The payload can be considered to be the main contents or data contained within the packet. Finally, the trailer is the part of the packet which tells the device receiving the packet that it’s reached the end (HowStuffWorks, 2021). Sending data through packets is a very efficient way to send data to other servers, even those with damaged networks (National Science and Media Museum, 2020).

Packets have been used at the beginning of the development of the internet in numerous ways. In 1965, Lawrence Robeters used packets to transfer digital data to talk between two computers. In 1969, Leonard Kleinrock used the first packet-switching network to send a message between computers. Following this, the ARPA Network was born and quickly expanded. Through the help of a method called transmission-control protocol, developed by Bob Kahn and Vint Cerf, the network expanded further and began to become a version of what we know today as the worldwide web (National Science and Media Museum, 2020). Thus Packets have been pivotal in the development and creation of the internet.

IP addresses are mathematically produced strings of numbers separated by periods, used to connect to a computer network through representing an address by numbers. Thus, the main features of IP addresses are to create network interface identification and location addressing through IPv4 (32 bit) or IPv6 (128 bit) addressing systems (Information Sciences Institute, 1981). IPv4 created around 4.3 unique IP addresses while IPv6 which was created at a later date, as the demand for more unique address grew, has 340 trillion, trillion, trillion IP addresses (Pawlik, 2013). Thus, IPv4 led to the development of IPv6. In addition, thanks, once again, to the work of Kahn and Cerf they created a method and standard to which data should be formatted, addressed, transmitted, routed and received between computers and networks (Pawlik, 2013). This in turn led to the direct result of the internet’s development and continued growth.

Routers and routing are used to send data as IP packets between networks; they receive, analyse and forward these data packets to both local and wide area networks (Moumita, 2020). Packets can also inspect the destination address and can decide the most optimal route to transfer data and then transfer via that route (Moumita, 2020). There are two main types of routers: hardware and software, hardware mainly serves to do routing while software is integrated into the computer or programs. Software might be portrayed as a window, NetWare or Linux server as they usually serve the purpose of being a gateway or firewall (All About Routers: Types Of Routers, Routing Table And IP Routing, 2022). Thus routers and routing serve as the gateway for packets and data to be sent in the most optimal way and for data to be checked for security purposes.

Finally, domains and DNS (domain name system) works as a foundation of the internet. Domains are used to match search queries, from a search engine, to content which is relevant. Rather than forcing users to recall the complex numbers representing an IP address (though they are still able to search this way) domains and DNS allow users of the internet an accessible and user-friendly way to search for desired content and navigate the internet (Fruhlinger, 2022).


## *Q3 Define the features of the following technologies that are essential in terms of the development of the internet: TCP, HTTP and HTTPS, web browsers and explain how each technology has contributed to the development of client and server communication over the internet.*

TCP (or transmitting control protocol) has many features including: ensuring data delivery to the application device or application and reliable service given through five functions; Segmentation, connection multiplexing, three-way handshake, sequencing and acknowledgment, and flow control through windowing (TCP Features and Functions Explained with Examples, 2022). TCP breaks down data from large packets into smaller then organizes data so that it can be transmitted between a server and a client. Before transmitting data, TCP establishes and maintains a secure connection between the source and its destination throughout the transferral (What is Transmission Control Protocol TCP/IP Model?, 2022). 
Thus, TCP guarantees secure, swift and reliable communication between client and servers over the internet (What is Transmission Control Protocol TCP/IP Model?, 2022).

HTTP (Hypertext Transfer Protocol) and HTTPS (Hypertext Transfer Protocol Secure) have many features which are essential in terms of the development of the internet. First to establish the difference in simple terms: both serve the same purpose of sending and then receiving HTTP requests over the internet, however HTTPS is more secure than HTTP as it encrypts the communication protocol thought a SSL certificate and creates a secure connection between user’s internet browsers and the servers they connect to. Although, HTTP is less secure, accessible to anyone who intercepts the communication and primarily suitable for websites like blog, forums, educational sites, entertainment and articles it offers quicker download speeds from the internet (HTTP Vs HTTPS: An In-Depth Comparison Of Features And Performance, 2022). 
Other features of HTTP include: HTTP is media independent: and media can be sent via HTTP so long as both server and client can handle the contents sent. HTTP is connectionless, as a browser initiates the HTTP request and following the request being sent, the client disconnects from the server. HTTP is stateless: meaning client and server communicate only while requesting (javatpoint, 2021).
Other features of HTTPS include: encryption, data integrity and authentication. Encrypting the data exchange keeps the information away from potential threats who would wish to see personal data. Data integrity means that data cannot be manipulated or destroyed during transferal process without being detected. Finally, Authentication works as a way for businesses to build trust with their clients, as a HTTPS webpage can accept sensitive or personal client information without the risk of it being stolen or seen without permission (Sharief, 2022).
Web browsers have many features, some may include: a home button, address bar, refresh button, bookmarks and tabbed browsing, to name a few. These features enable users to: return to their default homepage, have a URL be seen or specified, reload a webpage, save a webpage’s URL in a collection and have multiple webpages open at the same time (Rana, 2022). Depending on the web browsers many more features maybe become available.  
Web browsers usually also offer some form of developer tools. These tools let users inspect a webpage for html, css and many other properties. Dev tools can also help programmers and developers understand the structure, syntax and formatting of a webpage and lead to a solution on how to fix problems. There may be many more capabilities of a default web browser though these are some baseline tools (Using the browser developer tools (article) | Khan Academy, 2022).
Ultimately, Web browsers enable the displaying of numerous kinds of information and media and they act as a mainframe to which various internet protocols and procedures come together. Web browsers contribute to the development of client and server communication over the internet as they enable clear and easy to digest information to be displayed and they also enable numerous great features to be accessed and gathering in one location.


## *Q4 Identify THREE data structures used in the Python programming language and explain the reasons for using each.*

Three basic data structures used in Python Programming include: lists, sets and tuples which are all array data structures. Each is unique with some similarities and each is used to organise and group data (Python Data Structures, 2022). Lists are used to store any data type which can be mutable and any data type can be stored within. Sets are an unordered collection of distinct immutable objects. Finally, Tuples are an immutable ‘collection of values separated by comma and enclosed in parentheses’ (Yıldırım, 2021).

Once developers understand these data structures they can use them to collect and store data, carry out advanced operations and design algorithms (Yıldırım, 2021). Example applications of each include, a developer using lists to: have a concise way to create a list representing objects or items and then carry out operations that satisfy certain conditions. Sets can be used can in the real world to: include quick membership testing and eliminating duplicate entries in a data system. Finally, an application of tuples is using them as keys (Data Structures — Python 3.10.6 documentation, 2022). Furthermore, lists; are used in JSON Format and array operations, tuples are used in parentheses checker and insert records into databases through SQL queries and sets are used to join operations and find unique elements (Kumar, 2022).


Additionally, another data structure is an integer. Simply put, integers are the whole numbers between negative-infinity (-∞) and infinity (∞), with no fractional values (i.e. 0.1). They are used to give a positive or negative value to a targeted attribute and then carry out simple to complex arithmetic operations, such as addition, subtraction, multiplication and division (Anupama, 2021). An application of integers in the real world would include but is not limited to: checking accounts for sufficient funds, represented by either positive or negative numbers; depending on funds being deposited or withdrawn (Anupama, 2021).


## *Q5 Describe the features of interpreters and compilers and how they are different.*

Compilers and interpreters are programs used to covert source code into codes which can be interpreted by computers. As discussed in our lectures and from this article, high level language (source code) is for humans to understand, so it’s necessary for compilers and interpreters to covert source code for computers to interpret the code (Difference between Compiler and Interpreter, 2019).

Interpreters and Compilers are very similar in the fact that they are used to translate statements of a program into machine code. However, interpreters translate just one statement of the program at a time while compilers scan the entire program and translate the whole into machine code at once. An interpreter takes less time to analyse the source code though the overall time to execute the process is much slower (Difference between Compiler and Interpreter, 2019). 
Other mentionable features of interpreters and compilers include: interpreters translate till an error occurs, then pauses the translating and allows the programmer to work on the bug and fix it. Whilst compilers differ in the fact that they function by scanning the entire source code then only once completed does it show the errors and bugs to be fixed (Difference between Compiler and Interpreter, 2019). It’s also interesting to note that interpreters are used by the coding languages Ruby and Python whilst compliers are used with C and C++. These programming languages are quite commonly used so it’s interesting to see that both compliers and interpreters are adopted so vastly regardless of functionality. In conclusion, compilers and interpreters are very similar though differ slightly in terms of functionality and time required to operate.


## *Q6 Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.
Two commonly used programming languages are Python and JavaScript. Each has their expected benefits and negatives/drawbacks.*

Python, for instance, is considered to be versatile, flexible, extremely effective and easy to use and develop. Its syntax is similar to the English language, and compared to other programing language, Python allows users to get the tasks completed while using less lines of code. Python increases productivity as users don’t have to spend as much time learning the syntax and behaviour of the language so they can get stuck into their projects and code sooner rather than later. Python is also very flexible as it allows users to try new things and develop new applications, unlike other programming languages. Python also has a huge library of functions which can perform almost any function possibly needed which can still have meaningful and powerful functions. Python also has a massive community ranging from beginners and expert level engineers. Because of this following and continued growth, online Python guides, documents and resources keep expanding (Prasanna, 2022).

Some Drawbacks of Python include: a slower execution time when compared to other languages, very high memory consumption, lack of compatibility for use with mobile development (due to its consumption of power and memory to operate) and bad compatibility with databases (especially complex legacy databases). A final drawback results from Python being an over simplistic language as difficulty is said to occur when coders suddenly transition to other standardised complex programming languages, as they can’t handle the complexity (Prasanna, 2022). It could be likened to doing 5kg dumbbell training for 2-5 years continuously then suddenly transitioning to 40kg dumbbells, it would be extremely hard and uncomfortable to transition to a higher set pressure/skill).

JavaScript likewise also has many positive and negative features. Positive features include: speedy deployment as it can often be run within a browser, Simplistic syntax, akin to Python JavaScript is very popular and is seen everywhere on the internet, Interoperability as JavaScript can be inserted into any webpage, reduced server load, creative interfaces, extended functionality, versatility and useful annual updates which keep JavaScript alive (The Advantages and Disadvantages of JavaScript, 2019).

Some disadvantages of JavaScript include: bugs and oversights exploited for malicious purposes while executing on client-side and lack of browser supporting JavaScript as some browsers sometimes display JavaScript incorrectly though these issues are decreasing as time goes on (The Advantages and Disadvantages of JavaScript, 2019).


## *Q7 Identify TWO ethical issues from the areas below and discuss the extent to which an IT professional is ethically responsible in terms of the issue. User’s personal information and GPS tracking data // metadata, MAC addresses, hardware fingerprints were selected. Identify laws related and discuss a case study.*

IT professionals are responsible for implementing many different ethical practises to ensure they operate without breaking laws, protocol or infringing on others rights. With the skills IT workers gain, it’s important that they be mindful of data leaks and potential cyber threats which may steal user metadata or GPS location data. IT professionals must also keep a personal check as to not abuse their skills in a malicious or unethical way. Many laws have been developed and lawsuits filed in the aim of preventing such threats, though ultimately it’s the individuals, companies and governments responsibility to enforce a robust implementation of ethics, guidelines and laws.

Leaking personal information (PI) is vastly considered illegal and is often carried out in order to steal enough information to carry out identity theft for personal gain (Frankenfield, 2022). It’s an IT professional’s responsibility to do anything possible within their power to protect and prevent against any such threats, to PI, whether it be an internal or external threat. Steps and practices an IT professional can adopt are: hire security experts, get frequent training for all employees to consistently upgrade skills, encrypt data as a layer of protection (especially when using emails or data storage), frequently and securely update and change passwords, limit access to personal databases as necessary, delete old/unused data and have a data breach response plan (Omoth, 2022). IT professionals, depending on their location or position, might also be responsible to report a breach of Personal information being leaked as in most cases a failure to report a breach can also be a violation (Frankenfield, 2022). Thus it’s important for IT professionals to report these instances and always be vigilant in their code of conduct and ethics. It’s evident that there are various ethics and responsibilities an IT professional must adopt in order to protect themselves, others and their companies from theft of PI.

The 1988 Privacy Act, created by the Australian government, is legislation which helps establishes obligations that governmental and private entities must uphold (History of the Privacy Act, 2022). This legislation is helpful in assisting a developer to act in an ethical way as it creates laws which govern standards in regards to: the collection, use and disclosure of personal information, accountability, integrity and correction of personal information and protects the rights of individuals to access their personal information (History of the Privacy Act, 2022). Objects 2A of the Privacy Act clearly show how this document help guide IT professionals to ethically handle PI as shown in section 2A (a) promote the privacy of individuals while (b) while carrying out activities or functions which are interests of the individuals (Privacy Act 1988). Through enforcing this Act, with the potential of penalty, it helps guide IT professionals ethics to act and be responsible when handling and using PI. This Act maybe not setup or develop the technology or systems to prevent a cyber-security hack or data leak but it does help IT professionals by giving them a foundation on which they can build their morals and ethics.

IT professionals are also ethically responsible in regards to safeguard and protect GPS tracking data and other types of metadata, MAC addresses, hardware fingerprints. Even though metadata isn’t explicit information like PI it can still give others insights into a person’s lifestyle, associations and behaviour (Nellis, 2015). After all, who would willingly want to give their current location away to a stranger, especially a stranger who may have ill intent?  Considering such dangers, it becomes apparent that this information’s should be protected. Thus, once again it falls upon the IT developer and company to carefully handle and protect such information through creating digital security systems and adopting positive workforce morals based within properly monitoring and protecting this critical information. 

An interesting piece of legislation is that of the Australian Data Retention Law which basically requires telecommunication companies to store customer metadata for two years (Gal, 2017). This includes; phone calls, text messages, emails and internet activity. This is done in case government intelligence and law enforcement agencies need to withdraw stored information to in order to take legal actions (i.e. prove innocence through alibi, identify suspects, support warrants and be used as evidence to support prosecutions). This legislation does not promote a good practice of ethics for IT professionals as it promotes invasion and collection of personal metadata without proper consent. Although the ethics of the Australia government may seem sound, IT professionals should be careful when following similar models of collecting hyper sensitive and personal data, for extended periods of time, without consent as this is an invasion of privacy. Though, as it is necessary for IT professionals to collect and store some form of metadata of their customers, it could be recommended that this metadata collection be as little as possible, not stored for extend periods and only be collected through proper consent of individuals.

The case study chosen is that between Facebook and Cambrdge Analytica in regards to the masses amounts of PI being leaked and the ethics IT professionals can learn to mitigate or prevent ethical breaches in their own practise. Looking back to the incident of 2018 the outside company called Cambridge Analytica built and used a Facebook app questionnaire which, through using a loophole, was able to collect the data from friends and family who used the app. It resulted in over 50 million Facebook users having their PI and data exposed. Cambridge Analytica profited by selling this PI and data whilst Facebook occurred $3 billion in legal fees, damage to company image which lead to annual profit decreases of around 50% (Frankenfield, 2022). 

Following this incident, the security and legal team working at Facebook had to re-prioritise user protection decision making, redesign processes and technical mechanisms that embed privacy into all aspects of the company. This involved investing into following global privacy and data protection laws,  showing transparency to all users in regards to how their PI is being used/stored, funding experts to improve privacy and security within the company, increasing training and awareness and opening various privacy relation committees (Privacy Progress | Meta, 2022). 

For this case, it’s obvious that any company or IT professional should take data breaches and protection of user data seriously. Companies and IT professionals will be able to then avoid suffered incredible losses of money, company image and annual profit. Of course, the monetary investment into similar protections, defences, research and training will cost a company and IT professional a lot of time, money and recourses. However the benefits will likely outweigh the impacts of suffering a similar breach and lawsuit which Facebook suffered. IT professionals could thus likewise consider upgrading their systems, train staff, hire qualified professionals to upgrade systems/processes, follow the global laws and always have a clear communication stream open to all users/customers.



## *Q8 Explain control flow, using examples from the Python programming language.*

Control flow refers to the order which a program executes code. In the case of Python, it is determined by conditional statements, loops and functional calls. These statements are represented by the clauses ‘if’, ‘elif’, ‘else’ and ‘while’ (Python in a Nutshell, 2022). When there are multiple statements it’s the clauses which determine when the block of statements terminates or loops infinitely which is why these clauses are important. Examples of these clauses can be represented as follows (Python in a Nutshell, 2022): 

if expression:
    statement(s)
elif expression:
    statement(s)
elif expression:
    statement(s)
...
else:
    statement(s)

and the following for a while expression: 

while expression:
    statement(s)

To explain further, an ‘if’ statement checks the value of a Boolean statement to see if it’s true or false, if true the line will print, if false python will keep checking until a true statement is found but will also read the rest of the code without executing. Using ‘elif’, following the first ‘if’, and replacing the rest of the ‘if’s’ will check statements and stop checking once a true statement is found and skip reading the rest of the code, thus saving processing time. Alternatively, ‘else’ statements are used in combination with ‘if’ and ‘elif’ statements when no ‘if’ or ‘elif’ statements were executed, or in other words if both the ‘if’ and ‘elif’ statements were false the else statement gets executed (Ed — Digital Learning Platform, 2022).


## *Q9 Explain the difference between type coercion and type conversion. Are either of these used in Python?*

Type coercion and type conversion are similar in that they both convert data types from one data type into another; such as strings to numbers or integer to string. Though the key difference between the two is that type coercion is automatic and implicit whilst type conversion differs in that it can be implicit or explicit (Difference between Compiler and Interpreter, 2019). 

Python uses a few types of implicit coercions to concatenate such as: mathematical operations, when adding integers and floats the answer will automatically be represented as a float thus changing the integer into a float as to not lose the decimal value, and also after using ‘print ( )’ when combining strings and non-strings as Python will automatically convert the non-string it to a string (Flury, 2015).Thus, when using python, engineers will most frequently have to explicitly convert one data type into another manually through executing commands. The command to change a data type into another most often requires the newly desired data type to be followed by the data type wishing to be transformed into contained within parenthesis. Some of these commands may include: ‘int (a, base)’- converts any data type to an integer, ‘float()’- to convert any data type into a floating point number, ‘ord()’ - .. a character into an integer, ‘hex()’ ... any integer into a hexadecimal string, ‘oct()’ – integer to octal string, ‘tuple()’- to a tuple, ‘set()’- returns the type after converting to set, ‘list()’- any data type into a list, ‘str()’- to convert an integer into a string and as so on (Type Conversion in Python - GeeksforGeeks, 2022). Though it’s notable to mention that there is the possibility to lose some data when manually forcing the transferal of one data type to another (Type Conversion in Python - GeeksforGeeks, 2022).


## *Q10 Explain data types, using examples.*

There are many data types, some of which have been mentioned in previous answers, though this answer will attempt to delve deeper into their meaning and functions as well as provide some examples of data types used in Python. 

Five commonly used data types, used across most programming languages, include: integer (this includes whole numbers e.g. -10, 54, 324), Floating point numbers or decimal numbers (which could be represented by -100.5, 0.0, 71.234567), strings (a sequence of characters e.g. “Hi my name is Bob”), Booleans (logical true or false statements) and finally, nothing (represented by null - meaning no data) (Busbee and Braunschweig, 2022). These data types function relatively similar when compared between programming languages and through expert application these data types can, when formatted correctly, allow programmers to accomplish great achievements.

In the case of Python, used data types are similar, if not identical in some instances. The main data types of Python include: integers, floats, complex numbers, strings, concatenation, slicing, repetition, tuples, sets and dictionary (Sharma, 2021). 

An example of each are as follows:

1. Integer-
```py
45, -100, 0.
```

2. Float-
```py
1.6.
```

3. Complex number-
```py
7+4t.
```

4. Strings-
```py
“Hello World”.
```

5. Concatenation-
```py
string1= bob, string2 = bill, print(string1=string2), output : bob bill.
```

6. Slicing-
```py
string1 = ‘apple’, print(string1[2:4]), output: ple.
```

7. Repition-
```py
print(string1*3), output: appleappleapple.
```

8.Tuples-
```py
games = ("Monopoly", "UNO", "Chess"), Sets, Set = {72, 45, 21, “Bye”}, print(set), output: {45,21,”Bye”, 72}.
```

9. Dictionary-
```py
Dict1= {1: ‘silly’, 2: ‘42’, 3: ‘billy’}, Print(Dict[3]), Output: ‘billy’.
```

The function of each is as follows: floats are true numbers with floating-point representations, complex numbers are represented by complex classes, strings are a sequence of Unicode characters which can be put in single/double/triple quotations, concatenation involves joining two or more strings together, slicing is used for extracting certain parts of a string, repetition is used to repeat a sequence of instruction a specified number of times, tuples are an ordered collection of objects identical to a list though tuples can’t be modified once created, sets are an unordered collection of items and finally dictionary is an unordered collection of data values used to store data to be pulled out at a later point as specified (Sharma, 2021).


## *Q11 Here’s the problem: “There is a restaurant serving a variety of food. The customers want to be able to buy food of their choice. All the staff just quit, how can you build an app to replace them?” Identify the classes you would use to solve the problem and write a short explanation of why you would use the classes you have identified.*

I would need to build an app which:
1. Greets the customers 
2. Lists the menu items
3. Asks which menu items they desire followed by asking how many servings 
4. I’d need to combine the overall cost of their items and ask for payment
5. Finally, thank the customers and let them know that their food will be prepared shortly, assuming there are still staff/robots working in the restaurant kitchen.

To start, we’d need to identify the proper nouns and key words found in the problem and would be then be able to see the key words needed to figure out the app. The nouns and key words used would include food items: e.g. spaghetti, pizza, pasta, chips and garlic bread written as variables which have float values representing the price (e.g. spaghetti = 13.50). I’d enter these in as key word arguments or classes at the top of the python script. We’d also need another variable with a float value titled ‘total price’ which represents the bill needing to payed (e.g. total price = 0.00). The ‘total price’ would have a default starting value of 0.00 and would increase in value as food items are added (‘+’). I’d use a float value (0.00) over an integer (0) value as my prices use decimals, besides if my total price starts as a zero it will be changed into a float through python’s automated processes. Also, we’d use strings as a ‘print ( )’ statement, requesting how many of each item the customer desires and would use multiplication in parenthesis to multiply the food item times the number of servings (e.g. (13.50 * 3) + 0.00) or ((food item * number of desired servings) + total_price). Strings would also be used for the greeting, farewell, statements and questions. The last class used would be Boolean, if and elif control flow statements implemented to cycle through the options of food (e.g. would you like pizza? If - yes, add pizza to total and keep asking about other foods and elif – no, continue onto next food item without adding any prices to ‘total_price’). So far the class of food has mainly been represented though perhaps more classes would be needed.

Other classes which could be included and be important for my app are: restaurant table number (so that robots can deliver to the correct table), time till food is prepared (to let customers know how long their food will take to arrive), customer name and age - attribute (to greet the customers by name to make it more personal/display a birthday animation on their birthday), payment screen- method (to allow customers to pay at the end of their evening), customer rewards (which rewards customers after a set number of visits presented on their app with a stamp animation), robot chef (to cook food), robot runner (to send food out), food items (to maintain stock and for robot chef to interact with), stock items- like cups, plates, cooking utensils (to maintain appropriate levels and create a stock list), a shelf class could contain attributes (such as column or row and shelf number/aisle). Numerous more classes could be defined but for now these classes are the main ones that would be needed. 

Finally I’d like my app to be full of sprites, animations, visual effects and colour. I’d likely incorporate anime –like characters and put a mascot character on the rewards page and logo. The main intro page which showcases my restaurant would implement more formal colours and design with hints of interactive elements.



## *Q12 Identify and explain the error in the code snippet below that is preventing correct execution of the program.*

The first problem I’m seeing is that python is unable to combine a string and a integer “TypeError: unsupported operand type(s) for /: 'str' and 'int'”. 
The way I fixed this was through manually converting my string into an integer. 
Code snippet below:

```python
celsius = int(input())

fahrenheit = (celsius*9/5)+32

print(f"The result is: {fahrenheit}.")
```

After applying this small change the code snippet works perfectly. Although, another thing I noticed, whether it was intentionally or not, is there is no statement asking the user ‘what is the current Celsius ?’. So I would also consider putting in a print () statement asking what the current temperature is in Celsius.


## *Q13 The code snippet below looks for the first two elements that are out of order and swaps them; however, it is not producing the correct results. Rewrite the code so that it works correctly.*

```python
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
i = 0
while (i < len(arr) -1) :
    if(arr[i] > arr[i+1]):
        arr[i], arr[i+1] = arr[i+1], arr[i]
        break
    i += 1
    
print(arr)
```


## *Q14 Demonstrate your algorithmic thinking through completing the following two tasks, in order: Create a flowchart to outline the steps for listing all prime numbers between 1 and 100 (inclusive) and write pseudocode for the process outlined in your flowchart.*

Pseudocode:
-	Print operable potential prime numbers between 1 and 100 to use as a reference.
-	Create a range beginning at 1 which increments by +1 each time we loop (which stops looping once 100 has been reached).
-	If the number is bigger than 1 continue (exception 1)
-	Check if the current number is divisible by every number up till itself, 
1.	If the division takes place before reaching its own number do not include in the final print.
2.	If the number is able to reach itself, without being divisible by other numbers, print and include it in the list of prime numbers
-	Return to the beginning of loop 

![image](https://user-images.githubusercontent.com/105025162/189479463-634c5f46-9fe0-4c0b-813b-cede17667a16.png)

Additionally I’ve included the code used to run the operation,

```python
print("Prime numbers between 1 and 100 are:")

#code to represent all prime numbers between 1 and 100
for num in range(1, 100 + 1):
    if num > 1:
        for i in range(2, num):
            if (num % i) == 0:
               break
        else:
           print(num)
```



## *Q15 Write pseudocode OR Python code for the following problem: You have access to two variables: raining (boolean) and temperature (integer). If it’s raining and the temperature is less than 15 degrees, print to the screen “It’s wet and cold”, if it is less than 15 but not raining print “It’s not raining but cold”. If it’s greater than or equal to 15 but not raining print “It’s warm but not raining”, and otherwise tell them “It’s warm and raining”.*

```python
#The below python code allows users to assign values to variables and get an output in regards to the weather.

raining = True
temperature = 15

if raining and temperature < 15 :
    print("It's wet and cold")
elif not raining and temperature < 15 :
    print("It's not raining but cold")
elif not raining and temperature >= 15 :
    print ("It's warm but not raining")
else:
    print ("It's warm and raining")
```

This is another version which is similar (I believe this code works with strings and not Booleans, for the variable raining), this version is more interactive and asks users for inputs rather than the variable value needing to be altered before running:

```python
print ("What is your temperature in degrees?")
temperature = float(input ())

print ("Is it raining, please print either 'yes' or 'no'?")
raining = (input ())

if temperature < 15 and raining == "yes" :
    print ("It's wet and cold")
elif temperature < 15 and raining == "no" :
    print ("It's not raining but cold")
elif temperature >= 15 and raining == "no" :
    print ("It's warm but not raining")
else :
    print ("It's warm and raining")
```


## *Q16 ACME Corporation are hiring a new junior developer evaluate them by assessing their skills. Write and program to asess, grade and give feedback to user.*




## References
About.facebook.com. 2022. Privacy Progress | Meta. [online] Available at: <https://about.facebook.com/privacy-progress#learn-more> [Accessed 2 September 2022].

All About Routers: Types Of Routers, Routing Table And IP Routing. [online] Available at: <https://www.softwaretestinghelp.com/types-of-routers-routing-table/> [Accessed 26 August 2022].

Anupama, M., 2021. What are integers and why it is important?. [online] Cuemath. Available at: <https://www.cuemath.com/learn/maths-olympiad-integers/> [Accessed 22 August 2022].

Busbee, K. and Braunschweig, D., 2022. Data Types. [online] Press.rebus.community. Available at: <https://press.rebus.community/programmingfundamentals/chapter/data-types/> [Accessed 30 August 2022].

Business Insider. 2019. Difference between Compiler and Interpreter. [online] Available at: <https://www.businessinsider.in/difference-between-compiler-and-interpreter/articleshow/69523408.cms> [Accessed 29 August 2022].

Business Insider. 2019. Difference between Compiler and Interpreter. [online] Available at: <https://www.businessinsider.in/difference-between-compiler-and-interpreter/articleshow/69523408.cms> [Accessed 29 August 2022].

Computernetworkingnotes.com. 2022. TCP Features and Functions Explained with Examples. [online] Available at: <https://www.computernetworkingnotes.com/ccna-study-guide/tcp-features-and-functions-explained-with-examples.amp.html> [Accessed 28 August 2022].

Corporate Finance Institute. 2022. Python Data Structures. [online] Available at: <https://corporatefinanceinstitute.com/resources/knowledge/other/python-data-structures/#:~:text=The%20basic%20Python%20data%20structures,based%20on%20mutability%20and%20order.> [Accessed 22 August 2022].

Docs.python.org. 2022. Data Structures — Python 3.10.6 documentation. [online] Available at: <https://docs.python.org/3/tutorial/datastructures.html> [Accessed 22 August 2022].

Edstem.org. 2022. Ed — Digital Learning Platform. [online] Available at: <https://edstem.org/au/courses/9040/lessons/24186/slides/171134> [Accessed 30 August 2022].

Flury, T., 2015. [Blog] What is the definition of type coercion in Python?, Available at: <https://www.quora.com/What-is-the-definition-of-type-coercion-in-Python> [Accessed 30 August 2022].

Fortinet. 2022. What is Transmission Control Protocol TCP/IP Model?. [online] Available at: <https://www.fortinet.com/resources/cyberglossary/tcp-ip> [Accessed 28 August 2022].

Frankenfield, J., 2022. Personally Identifiable Information (PII). [online] Investopedia. Available at: <https://www.investopedia.com/terms/p/personally-identifiable-information-pii.asp> [Accessed 2 September 2022].

Fruhlinger, K., 2022. What is DNS and how does it work?. [online] Network World. Available at: <https://www.networkworld.com/article/3268449/what-is-dns-and-how-does-it-work.html> [Accessed 26 August 2022].

Gal, U., 2017. The new data retention law seriously invades our privacy – and it's time we took action. [online] The Conversation. Available at: <https://theconversation.com/the-new-data-retention-law-seriously-invades-our-privacy-and-its-time-we-took-action-78991> [Accessed 2 September 2022].

GeeksforGeeks. 2022. Type Conversion in Python - GeeksforGeeks. [online] Available at: <https://www.geeksforgeeks.org/type-conversion-in-python/> [Accessed 30 August 2022].

Gregersen, E., 2021. XML | Definition & Facts. [online] Encyclopedia Britannica. Available at: <https://www.britannica.com/technology/XML> [Accessed 26 August 2022].

HowStuffWorks, 2021. What is a packet?. [online] HowStuffWorks. Available at: <https://computer.howstuffworks.com/question525.htm> [Accessed 23 August 2022].

Information Sciences Institute, 1981. RFC 791 - Internet Protocol. [online] Datatracker.ietf.org. Available at: <https://datatracker.ietf.org/doc/html/rfc791> [Accessed 23 August 2022].

Khan Academy. 2022. Using the browser developer tools (article) | Khan Academy. [online] Available at: <https://www.khanacademy.org/computing/computer-programming/html-css/web-development-tools/a/using-the-browser-developer-tools> [Accessed 28 August 2022].

Kumar, G., 2022. Differences and Applications of List, Tuple, Set and Dictionary in Python - GeeksforGeeks. [online] GeeksforGeeks. Available at: <https://www.geeksforgeeks.org/differences-and-applications-of-list-tuple-set-and-dictionary-in-python/> [Accessed 22 August 2022].

Moumita, 2020. What are Routers in Computer Network?. [online] Tutorialspoint.com. Available at: <https://www.tutorialspoint.com/what-are-routers-in-computer-network> [Accessed 25 August 2022].

National Science and Media Museum. 2020. A short history of the internet | National Science and Media Museum. [online] Available at: <https://www.scienceandmediamuseum.org.uk/objects-and-stories/short-history-internet#:~:text=The%20packet%20switching%20method%20is,network%20was%20produced%20in%201969.> [Accessed 23 August 2022].

Nellis, M., 2015. Standards and ethics in electronic monitoring. Strasbourg: Council of Europe, p.39.

O’Reilly Online Learning. 2022. Python in a Nutshell. [online] Available at: <https://www.oreilly.com/library/view/python-in-a/0596001886/ch04s09.html> [Accessed 29 August 2022].

OAIC. 2022. History of the Privacy Act. [online] Available at: <https://www.oaic.gov.au/privacy/the-privacy-act/history-of-the-privacy-act> [Accessed 2 September 2022].

Omoth, T., 2022. Ten ways to protect your company from the next big data breach. [online] Itpro.com. Available at: <https://www.itpro.com/security/data-breaches/358455/10-ways-to-protect-your-company-from-the-next-big-data-breach> [Accessed 2 September 2022].

Pawlik, A., 2013. IP Addresses: How they shaped the past of the Internet and what they will influence in its future. [online] ITProPortal. Available at: <https://www.itproportal.com/2013/07/02/ip-addresses-how-they-shaped-the-past-of-the-internet-and-what-they-will-influence-its-future/> [Accessed 23 August 2022].

Prasanna, 2022. Advantages and Disadvantages of Python | Python Language Advantages, Disadvantages and Its Applications. [online] A Plus Topper. Available at: <https://www.aplustopper.com/advantages-and-disadvantages-of-python/> [Accessed 29 August 2022].

Privacy Act 1988. 2A (a) (b).

Rana, K., 2022. What is a Web Browser? Definition, Features, and Examples. [online] ArtOfTesting. Available at: <https://artoftesting.com/what-is-a-web-browser> [Accessed 28 August 2022].

Sharief, K., 2022. What is HTTPS? - Definition, Features, And Why Switch to HTTPS. [online] Computer Tech Reviews. Available at: <https://www.computertechreviews.com/definition/https/> [Accessed 28 August 2022].

Sharma, P., 2021. Data Types in Python | 6 Standard Data Types in Python. [online] Analytics Vidhya. Available at: <https://www.analyticsvidhya.com/blog/2021/08/data-types-in-python-you-need-to-know-at-the-beginning-of-your-data-science-journey/#:~:text=Data%20types%20are%20the%20classification,(object)%20of%20those%20classes.> [Accessed 30 August 2022].

Software Testing Help. 2022. HTTP Vs HTTPS: An In-Depth Comparison Of Features And Performance. [online] Available at: <https://www.softwaretestinghelp.com/http-vs-https/#The_Exact_Differences_8211_HTTP_vs_HTTPS> [Accessed 28 August 2022].

Tennison, J., 2002. Comparing Markup Languages. [ebook] Mulberry Technologies, Inc, pp.4, 5. Available at: <https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.103.4958&rep=rep1&type=pdf> [Accessed 26 August 2022].

The Advantages and Disadvantages of JavaScript. 2019. The Advantages and Disadvantages of JavaScript. [online] Available at: <https://www.freecodecamp.org/news/the-advantages-and-disadvantages-of-javascript/> [Accessed 29 August 2022].
Javatpoint. 2021. HTTP - javatpoint. [online] Available at: <https://www.javatpoint.com/http> [Accessed 28 August 2022].

Yıldırım, S., 2021. 15 Examples to Master Python Lists vs Sets vs Tuples. [online] Medium. Available at: <https://towardsdatascience.com/15-examples-to-master-python-lists-vs-sets-vs-tuples-d4ffb291cf07> [Accessed 22 August 2022].
