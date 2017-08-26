# Google Sync Reminder

A reminder web application engineered with technologies like HTML, Bootstrap, JSP, Servlets and Presto database.What makes it different is that it uses the user's google account(mandatory to register as a user) to sync the added events and tasks to the user's google calender using google calender API and send reminder emails using Gmail.

### Installation

The application runs on tomcat server with Java 7. You need to setup an instance of Presto database on your local and update the connection details in the database config file before you run tha application for the first time.
Tested with Google Chrome and it should work with other popular browsers as well.

### Usage

```
<servlet> 
    <servlet-name>Hello</servlet-name> 
    <servlet-class>HelloWorld</servlet-class> 
</servlet> 
<servlet-mapping> 
    <servlet-name>Hello</servlet-name>
    <url-pattern>/HelloServlet</url-pattern> 
</servlet-mapping>
```    

### Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

License
----

**Free Software, Hell Yeah!**