# CGI Python

I made a simple CGI program with Python, by using Get method to passing information. 
GET method is the default way to pass information from browser to web server, which produces a string and appears in the browser’s Location: box. The GET method should not be use to carry sensitive information or password to the server, instead use the POST method. The GET method sends information using QUERY_STRING header and will be accessible in CGI Program through QUERY_STRING environment variable. The information can be passed by simply concatenating key and value pairs along with any URL or HTML <FORM> tags can be used to pass information using GET method.
The is main.py script to handle input given by the browser. By using cgi module, the information is easily access passed.
