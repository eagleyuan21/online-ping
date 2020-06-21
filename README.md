# online-ping

This is a program built using both jquery terminal plugin and ping.js. The link to the terminal plugin is https://terminal.jcubic.pl and the link to the ping.js is https://github.com/alfg/ping.js/.

Some of the features of this ping program include pinging addresses and reporting data responses. This data includes total pings, successful pings, percent loss, time in milliseconds reporting for each ping sequence, minimum value reporting after program ends, maximum value, average, and standard deviation.

In order to use the program, simply download everything in this repository. Then start by typing ping into the command and an argument of the address, and then hit enter. The program may be stopped at any time by hitting CTRL + C. 

The ping program is implemented so that it pings every second. If the response time is over 1500 ms, the ping is timed out. 

One important thing to note is that browsers do not support icmp protocol, so this ping implementation is not traditional to the original ping programs. The ping.js loads a favicon.ico image from the host and finds the time to response. If the image does not exit, there is an error returned. More information on ping.js may be found in the github link found above.
