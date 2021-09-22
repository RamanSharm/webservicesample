# Create Web Server

GoTo IBM Web Administration for i: http https.

Click on "http" .

Click on "Create a New HTTP Server" link.

Provide configuration to server.

Once the server is created then add the "ScriptAliasMatch" into the edit configuration file.

Now server is created.

# Create a Program to Handle GET Request

Create a RPGLE program on Handle GET Request.

In this, we need to use the binding directory(includes service program QCBHCGI/QHTTPSVR)

This program will send the data from physical file to browser.

Create a Physical File to store the data.

Send Get request through URL.

Data will be displayed on browser.

# Create a Program to Handle POST Request

Create a RPGLE program on Handle POST Request.

In this, we need to use the binding directory(includes service program QCBHCGI/QHTTPSVR)

Send Post request through URL.

Give plain text / JSON  in the body of the URL.
