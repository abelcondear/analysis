## How to audit our Software System

**The connections our system is making use**

We should compare the package that is going through the net, versus, the package that our system is expecting. We can rely completely on multinational large companies like Oracle, Amazon. However, it is a good initiative to do this extra step to audit and make more secure our system functionality.

**Database transactions**

We should audit delete, update, insert onto database tables, registering the database user who is performing those operations. Besides, we should audit when the table structure changes, using some kind of service that make control of it.

**Data source provider**

We should compare the data structure that the system receives from the provider, versus, data structure that our system is expecting. If the comparison is true then we could rely on that data source. If not, then you should warn the provider and our support or technical team that we need either to update our data structure or we should ask the provider why they changed the data structure. Because, it may happen that accidentally they changed it so.

**System login**

We should review all attempts connections and on the other hand we should have a list of programmed possible weird user behaviors in order to use it and compare it with the current user behaviors. In case it matches then we could save the date and time, user accounts the user is using to login, the frequency between every moment that user is making login.

**User interface application** 

We should review the interaction between the user and the controls (corresponding to the user interface). So, we could see if it is human being that is interacting with the user interface, or it is a remote controlling that is interacting with it. In case, that we notice that a remote robot or automatic controlling is interacting with the user interface, then we could stop immediately the application execution.

