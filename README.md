If you are using Catalina container for Authentication, there is the chances the group from your realm does not match to the security roles in your application. 
In such situation, usually you have to create the security roles that matches your realm groups or other way around. But some time time might not be fexible
as you may not have access of realm, like LDAP or databases. So, the best option is to have an adaptor that maps realm groups to security roles, so that developer just has to include this into classpath and add xml/json that maps the roles.
that's exactly I intend to do.
