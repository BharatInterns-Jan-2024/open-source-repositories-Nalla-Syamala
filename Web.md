## INTRODUCTION
The **World Wide Web**.
**Sir Tim Berners-Lee** is the name of the father of the Web. He worked on it while working at the CERN in Geneve. It was meant as an academic tool. He came up with the idea of **hyperlink**.
You had a window with the document. Clicking a link in the document showed another document in a separate window. You could go back to the original document.
**Web servers** serves **web pages** to web browsers. The communication happens through some rules set by a **protocol** called HTTP, which says how the browser should talk to the server, and vice versa.
A Web Page is a text file, encoded in a special format called **HTML**.
## THE HTTP PROTOCOL
HTTP (Hyper Text Transfer Protocol) is the most successful and popular protocol of TCP/IP. HTTP is what makes the World Wide Web work, giving browsers a language to communicate to remote servers that host web pages.
HTTP is the way web browsers like Chrome, Firefox and many others communicate with web servers.
The name Hyper Text Transfer Protocol derives from the need of transferring not just files, like in FTP - the “File Transfer Protocol”, but hypertexts, which would be written using HTML, and then represented graphically by the browser with a nice presentation and interactive links.
HTTP is what transfer those hypertext files over the network. An HTTP server will not just transfer HTML files, but typically it will also serve other files: CSS, JS, SVG, PNG, JPG, lots of different file types.
When an HTML page is retrieved by the browser, it’s interpreted and any other resource it needs to display property (CSS, JavaScript, images..) is retrieved through additional HTTP requests to the same server.
## HYPERLINKS 
Inside a web browser, a document can point to another document using links.
A link is composed by a first part that determines the protocol and the server address, either through a domain name or an IP. Anything appended to the address part represents the document path.
## WHAT IS A WEB SERVER
A Web Server is a program that listens for HTTP requests coming from clients over the network. A Server is the computer, which is running somewhere on the Internet. Whereas, Web Server is the program running on that computer whose job is to listen for HTTP requests.
We have many different programs that we can run and they do the Web Server job for us.[Apache](https://httpd.apache.org/) and Nginx are two traditionally popular solutions you would use to install a Web Server on your own Linux server on the Internet. What we call your VPS (Virtual Private Server).
