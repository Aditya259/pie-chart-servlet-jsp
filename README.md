# JFreechart servlet sample

Prerequisites 
<hr/>
<ul>
<li>JDK 1.5 and above</li>
<li>Jfreechart jars</li>
<li>mysql connector jar</li>
</ul>
<hr/>
This sample contain related jar and database related scripts.

WEB-INF/lib - contains jar file.
<br/>
src/sql - contains sql statements

before deploying the war make sure db is ready and tomcat server is having mysql-connector jar in the lib.

URL : <a href="http://localhost:8080/jfreeChartServlet">http://localhost:8080/jfreeChartServlet</a>

chart will getting refreshed every 5 seconds.

This basic sample get the data from the database and using jfreechart <i>"JDBCPieDataset"</i> construct the piechart and return to jsp.

![demo](https://raw.githubusercontent.com/uttesh/servletSamples/master/jfreeChartServlet/sample.png)


