•	(DevOps Screen) What command would you use to find resources used? Top, lsof, ps, vmstat
•	(DevOps Screen) Have you ever had to look at logs continuously? What commands did you use? Tail, lnav (install lnav first)
•	(DevOps Screen) (bonus) What would you use to check disk write/reads
dstat -d, iostat
•	(DevOps Screen) Explain what SSL is (either high level or go into depth).
Answer Question
•	(DevOps Screen) Explain how you handled a support request as a level 3 support.
Answer Question
•	(Group Interview) What is the difference between a relational and non-relational database?
Answer Question
•	(Group Interview) What is more/less in linux?
Less can be used to read the contents of a text file one page(one screen) at a time t has faster access because if file is large it doesn’t access the complete file, but accesses it page by page. 

More displaying one screen at a time in case the file is large. The more command also allows the user do scroll up and down through the page. 

•	(Group Interview) Where is the public and private RSA key stored in linux? How do you create it? .ssh folder, to provide access to user add it in authorizes_key file
Answer Question
•	(Group Interview) Give me the outline for a bash function to find all *.java files in the 
directory and use grep to find if the string "global relay" is inside it.
find . -type f -name "*.txt"
	grep -rnw '/path/to/somewhere/' -e 'pattern'

•	(Group Interview) What is SSL? Sometimes you might get a warning that the SSL certificate is expired in the browser, why could that be?
An SSL certificate is a digital certificate that authenticates a website's identity and enables an encrypted connection. SSL stands for Secure Sockets Layer, a security protocol that creates an encrypted link between a web server and a web browser.

After an SSL certificate expires, you will no longer be able to communicate over a secure, encrypted HTTPS connection. All the information will be transmitted in plaintext, leaving your (or your customer's) data exposed to any attacker listening in on the network.

The only solution to this problem is to get your host to update the root certificate on your server.

•	(Group Interview) What port does HTTP and HTTPS run on? What is the difference between the two?
•	HTTP lacks a security mechanism to encrypt the data, whereas HTTPS provides SSL or TLS Digital Certificate to secure the communication between server and client.
•	HTTP operates at the Application Layer, whereas HTTPS operates at Transport Layer.
•	HTTP by default operates on port 80, whereas HTTPS by default operates on port 443.
•	HTTP transfers data in plain text, while HTTPS transfers data in cipher text (encrypt text).
•	HTTP is fast as compared to HTTPS because HTTPS consumes computation power to encrypt the communication channel.
•	
Answer Question
•	(Group Interview) Write a function to print the first 30 terms in the fibonacci sequence.
Answer Question
•	(Group Interview) What is your favourite linux distrubition? What is package manager in ubuntu? Apt, yum , rpm, dpkg
Answer Question
•	(Group Interview) Tell me about a challenging script your wrote at your last workplace and what you overcame the challenges.
Answer Question
•	(Group Interview) How familiar are you with python, bash, ansible?
Answer Question
•	(Group Interview) Do you know SQL? What is the difference between inner and outer join?

![image](https://github.com/shreyasinha0711/DevOps_Interview_1/assets/22908535/ff66a6a8-87b7-4b97-971c-26f1f499b5fc)
