Nagios check for Nginx.
===========================

Small enhancements on "check_nginx" in https and NIC binding ... original script backs to [Mike Adolphs](https://github.com/fooforge).

Nagios plugin to check whether nginx is running. It also parses the nginx's status page to get requests and connections per second as well as requests per connection. You may have to alter your nginx configuration so that the plugin can access the server's status page.
