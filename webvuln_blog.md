<![endif]-->

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3EncqL79tlne-eceqV5D6oOGoZ1FSyxjraQ&usqp=CAU" width="700" height="300">

Web Application Vulnerabilities

With an Increase in Web technology, the online risk is also increasing at the same pace.

Globally almost 30,000 websites are hacked daily which is a very alarming number. To solve this problem, the field of web application penetration testing should be explored more which would result in bringing talented minds onboard and overall reducing the potential of a site being hacked. To make you all interested in this field I would like to introduce to you some popular web vulnerabilities.

Types of Web Vulnerabilities

Basically, web vulnerabilities are divided into two parts :s

-   Client-side Vulnerabilities
-   Server-side Vulnerabilities

<img src="https://careerkarma.com/blog/wp-content/uploads/2019/08/client-side-vs-server-side.jpg" widht="600" height="500">

Client-side Vulnerabilities

In this category the client side application is exploited rather than the server itself hence these vulnerabilities are also dependent on client browser.

Some popular client-side vulnerabilities are :

-   XSS (Cross-site scripting)
-   Clickjacking
-   CSRF (Cross-site Request Forgery)
-   CORS (Cross-Origin Resource Sharing)

Just to make this short and interesting I would like to brief some of these vulnerabilities

<![if !vml]>![](https://1tskcg39n5iu1jl9xp2ze2ma-wpengine.netdna-ssl.com/wp-content/uploads/2019/05/cross-site-scripting-example.png)<![endif]>

<![if !supportLists]>Ø <![endif]>XSS or Cross-site Scripting is the most common vulnerability amongst all.

XSS vulnerabilities normally allow an attacker to disguise as a victim user, to carry out any actions that the user is able to perform, and to access any of the user's data. If the victim user has privileged access within the application(eg:- Victim is the admin of the webpage), then the attacker might be able to gain full control over all of the application's functionality and data. This is usually achieved by executing some javascript code on the victim's browser which could lead to cookie stealing, Executing commands from the victim's browser, etc.

This vulnerability has three types :

<![if !supportLists]>· <![endif]>Reflected XSS

<![if !supportLists]>· <![endif]>Stored XSS

<![if !supportLists]>· <![endif]>Dom based XSS

Although the types are different, the core exploit is almost the same.

<![if !vml]>![](https://upload.wikimedia.org/wikipedia/commons/0/0f/Clickjacking.png)<![endif]>

<![if !supportLists]>Ø <![endif]>Clickjacking is a type of web vulnerability in which the victim is tricked into clicking a web element which is invisible or hidden by some other element. For eg, Suppose you visit a malicious website and see some convincing content, let’s say a download button of your favorite Game or Movie. Clicking the button could lead to the execution of a specific code or just a simple form submission (maybe a payment form) or could simply send your sensitive data. This technique depends upon the incorporation of an invisible, actionable web page (or multiple pages) containing a button or hidden link, say, within an iframe.

Server-side Vulnerabilities

In this category, the web Server is compromised which results in the exploitation of all the users of that particular website.

Some popular Server-side vulnerabilities are :

-   SQL injection
-   Business logic vulnerabilities
-   Server-side request forgery(SSRF)
-   Command Injection
-   File upload vulnerability
-   Information disclosure

Briefing some of the vulnerabilities mentioned above :-

<![if !vml]>![](https://assets.website-files.com/5ff66329429d880392f6cba2/608958ea27293628afb3b58b_SQL%20injection%20work.jpg)<![endif]>

<![if !supportLists]>Ø <![endif]>Sql Injection is a vulnerability that allows an attacker to interfere/edit the queries that a webApp makes to its database.

It allows an attacker to view data that they normally cannot view.

For eg- User-Id and password , unlisted content, Or even allow editing in the database itself, like deleting a user. In many cases it can also lead to DOS(Denial-Of-Service).

<![if !vml]>![](https://www.cloudprotector.com/wp-content/uploads/2021/06/1-768x309.png)<![endif]>

<![if !supportLists]>Ø <![endif]>Command Injection is a very critical web vulnerability. It allows an attacker to execute arbitrary OS commands on the server that is running the application. This would compromise all other hosting on that server and typically giving full control of the server by allowing a reverse shell (reverse connection from the server to the attacker machine).

<![if !supportLists]>Ø <![endif]>Business logic vulnerabilities are the most exciting to test vulnerabilities in my opinion. Here, the attacker tries to break the application logic due to which the WebApp gives unexpected output.

Logic Flaws often are invisible to users who aren’t explicitly looking for it as they are not exposed by normal use of the WebApp. An attacker may be able to exploit the web logic by interacting with it in ways that developers never thought of. One basic example could be, imagine a login page with 2 Factor authentication, Now the developers expect the users to follow the process of first going through the login page and then verification page and finally move on to the home account page. But if this flow is not validated then the attacker can drop the verification request and directly move to the account page, thus bypassing the 2-Factor Authentication.

Excited already? Want to learn these topics in depth? Well, you are at the right place, There would be blogs dedicated to each of these topics with some in depth knowledge and exploitation demo along with the ways they can be fixed.

If you want to explore this on your own then you can also checkout the portswigger’s Web Security Academy and OWASP Top 10.

[https://portswigger.net/web-security/learning-path](https://portswigger.net/web-security/learning-path)

[https://owasp.org/www-project-top-ten/](https://owasp.org/www-project-top-ten/)

If you want to learn Linux and penetration testing then you can also checkout my youtube channel where I upload video related to cybersecurity with practical demonstration.

[https://www.youtube.com/channel/UC9aca51UZvIdxFbHH-Wyang/featured](https://www.youtube.com/channel/UC9aca51UZvIdxFbHH-Wyang/featured)