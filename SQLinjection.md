# Online Graduate Tracer System for College of ICT Alumni has SQLInjection vulnerability

First, goto the admin page and try to login, use username as SQLinjection parma![](img/5.png)

Look at the code, username has been inserted to the SQL without any  handle

Try SQLmap![](img/6.png)

Time-based payload can be used

Code Link

https://www.sourcecodester.com/php/15904/online-graduate-tracer-system-college-ict-alumni.html