<h1>Example how to integrate apache shiro with struts2 and sitemesh3 (flat file)</h1>

In this project I built an example how to configure an application that uses <a href='http://shiro.apache.org/'>Apache Shiro</a> with struts2 and sitemesh3.

In this example I will use a flat file to configure <a href='http://shiro.apache.org/'>Apache Shiro</a>. In a next project I will use a database.

```


<?xml . . .

<display-name>Apache shiro with Struts2 and Sitemesh3

Unknown end tag for &lt;/display-name&gt;




<listener>

<listener-class>org.apache.shiro.web.env.EnvironmentLoaderListener

Unknown end tag for &lt;/listener-class&gt;





Unknown end tag for &lt;/listener&gt;





<filter>

<filter-name>ShiroFilter

Unknown end tag for &lt;/filter-name&gt;



<filter-class>org.apache.shiro.web.servlet.ShiroFilter

Unknown end tag for &lt;/filter-class&gt;





Unknown end tag for &lt;/filter&gt;





<filter>

<filter-name>struts-prepare

Unknown end tag for &lt;/filter-name&gt;


<filter-class>org.apache.struts2.dispatcher.ng.filter.StrutsPrepareFilter

Unknown end tag for &lt;/filter-class&gt;





Unknown end tag for &lt;/filter&gt;




<filter>

<filter-name>sitemesh

Unknown end tag for &lt;/filter-name&gt;



<filter-class>org.sitemesh.config.ConfigurableSiteMeshFilter

Unknown end tag for &lt;/filter-class&gt;





Unknown end tag for &lt;/filter&gt;




<filter>

<filter-name>struts-execute

Unknown end tag for &lt;/filter-name&gt;



<filter-class>org.apache.struts2.dispatcher.ng.filter.StrutsExecuteFilter

Unknown end tag for &lt;/filter-class&gt;





Unknown end tag for &lt;/filter&gt;




<filter-mapping>

<filter-name>ShiroFilter

Unknown end tag for &lt;/filter-name&gt;



<url-pattern>/*

Unknown end tag for &lt;/url-pattern&gt;



<dispatcher>REQUEST

Unknown end tag for &lt;/dispatcher&gt;



<dispatcher>FORWARD

Unknown end tag for &lt;/dispatcher&gt;



<dispatcher>INCLUDE

Unknown end tag for &lt;/dispatcher&gt;



<dispatcher>ERROR

Unknown end tag for &lt;/dispatcher&gt;





Unknown end tag for &lt;/filter-mapping&gt;




<filter-mapping>

<filter-name>struts-prepare

Unknown end tag for &lt;/filter-name&gt;



<url-pattern>/*

Unknown end tag for &lt;/url-pattern&gt;





Unknown end tag for &lt;/filter-mapping&gt;




<filter-mapping>

<filter-name>sitemesh

Unknown end tag for &lt;/filter-name&gt;



<url-pattern>/*

Unknown end tag for &lt;/url-pattern&gt;



<dispatcher>REQUEST

Unknown end tag for &lt;/dispatcher&gt;



<dispatcher>FORWARD

Unknown end tag for &lt;/dispatcher&gt;



<dispatcher>INCLUDE

Unknown end tag for &lt;/dispatcher&gt;





Unknown end tag for &lt;/filter-mapping&gt;




<filter-mapping>

<filter-name>struts-execute

Unknown end tag for &lt;/filter-name&gt;



<url-pattern>/*

Unknown end tag for &lt;/url-pattern&gt;





Unknown end tag for &lt;/filter-mapping&gt;






Unknown end tag for &lt;/web-app&gt;



```


<br><br>
You can see a living example here:<br>
<br><br>
<a href='http://www.goodvibras.com'>Brainwave entrainment free mp3 downloads</a>