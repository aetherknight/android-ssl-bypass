These are the JDIPlugin classes which are loaded at runtime and used to 
request VirtualMachine events and register themselves as handlers for 
them. These plugins must implement the JDIPlugin interface. 

* SSLBypassJDIPlugin

 * Bypass SSL checks for certain methods of SSL certificate pinning
	
  * javax.net.HttpsURLConnection
		
  * org.apache.http.* 
	
 * JythonConsoleDebuggerPlugin
