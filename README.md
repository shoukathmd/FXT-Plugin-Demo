# FXT-Plugin-Demo



Requirements to run this project
1. Java8
2. Maven

Clone the project and go to pom.xml file and change the username, password and jobid of yours from https://clouds.fxlabs.io 


          <configuration>
						<username>tenant//shoukathmd@gmail.com</username>
						<password>{pwd}</password>
						<jobId>{jobid}</jobId>
					</configuration>




run below command in project directory which will trigger the job in fxlabs.

mvn clean fxlabs:job

to see the results on fxlabs go to 

https://cloud.fxlabs.io/#/app/projects/{projectid}/jobs/{jobid}/runs

