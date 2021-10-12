# electRon
# What is it?
A chat bot that helps you in choosing your electives. You can ask about:
* various teachers
* list of courses in any domain(in CS)
* about any course
* supports (my) unversity lingo

# How to run?
Install Python AIML module:
### For python 3:
* pip install python-aiml
### For python 2:
* pip install aiml

Then create a python file with following code and run it:
```
import aiml

# Create the kernel and learn AIML files
kernel = aiml.Kernel()
kernel.learn("std-startup.xml")
kernel.respond("load aiml b")

# Press CTRL+C to break this loop
while True:
    print kernel.respond(raw_input("Enter your message >> "))
```

# Ongoing
- [ ] Android app interface
- [ ] Add more aiml files for general conversation.


