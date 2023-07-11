### Spring Boot Demo 2 JUnit Example

**Steps:**
<ol>
<li>Install IDE for Spring Project  
<br/><kbd><img src="Pic1.PNG" width="500" /></kbd>
<ul>
<li>Go to https://spring.io/tools - Download standalone jar (I downloaded Spring Tools 4 for Eclipse - Windows x86_64 )</li>
<li>Double click to run, and you will have generated folder 'sts-4.19.0.RELEASE'<br/>
*Try to avoid downloading from https://www.eclipse.org/downloads/, cause you may need additional steps to install Spring extensions for Eclipse to detect Spring library imports.  
</li>
</ul>

</li>

<br/>

<li>Run IDE  
<ul>
<li>$ cd sts-4.19.0.RELEASE</li>
<li>$ SpringToolSuite4.exe</li>
</ul>
</li>


<br/>

<li>Git clone this project  
<ul>
<li>$ git clone https://github.com/worldpeacez0991/SpringBoot_demo2_JUnit.git  
</li>
</ul>
</li>
<br/>

<li>Once IDE is loaded;  
<br/>
<kbd><img src="Pic2.PNG" width="500" /></kbd>
<ul>
<li>Select 'Import Projects...' >  </li>
<li>Select 'Existing Gradle Projects >   </li>
<li>Next  </li>
<li>Copy and paste directory for this Spring project  </li>
</ul>
</li>
<br/>

<li>Once project is loaded, run the project as 'Spring Boot App'  </li>
<kbd><img src="Pic3.PNG" width="500" /></kbd>
<br/>

<br/>
<li>Open your browser and type 'http://localhost:8080/hello'</li>
<ul>
<li>If you see this text 'Hello World!', means your Spring project is success!  </li>
</ul>
<kbd><img src="Pic4.PNG" width="500" /></kbd>

<br/>
<li>Using command prompt, you could run curl to test your app</li>
<ul>
<li>$ curl localhost:8080</li>
<li>$ curl localhost:8080/hello</li>
</ul>
<kbd><img src="Pic5.PNG" width="500" /></kbd>

<br/>
<li>For running JUnit Tests</li>
<ul>
<li>Error 1: Import cannot be found<br/>
<kbd><img src="1A_Error1_import_cannot_be_found.PNG" width="500" /></kbd><br/>
Solution 1 applied in this project: Place your JUnit Test class file in the correct test folder 'SpringBoot_demo1\src\test\java\com\example\demo'<br/>
<kbd><img src="1B_Solution1_import_cannot_be_found.PNG" width="500" /></kbd>
</li>
<li>Error 2: See file '2A_Error2_spring_test_cannot_detect_default_configuration.txt'<br/>
Solution 2 applied in this project: Edit the annotation to detect the files for Spring Test to work correctly<br/>
<kbd><img src="2B_Solution2_cannot_detect_configuration.PNG" width="500" /></kbd>
</li>
</ul>

</ol>

Credits: https://spring.io/team<br/>
Source: [https://spring.io/quickstart](https://spring.io/guides/gs/spring-boot/)https://spring.io/guides/gs/spring-boot/



