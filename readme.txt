This sample project is cloned from https://github.com/spring-guides/gs-securing-web.git

The only change I made to this project is as follows,

In WebSecurityConfig.java, I have added on line 15, the below code,
http.sessionManagement().sessionCreationPolicy(SessionCreationPolicy.STATELESS);

After adding this code,and after successfully authenticating I still am challenged with
the login page from every page I accessin the app.

This is the issue I am facing.

Since I do not want to use sessions and want my services to be stateless I am looking for
a better way to authenticate the users of my service.

