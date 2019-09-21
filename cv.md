# ELENA ITIN
**Phone:** 		058-400-5295  
**E-mail:**		elenakochegina@gmail.com  
**Location:**		Chernihiv  
**Languages:**		English ,Russian, Ukrainian, Hebrew  
**Year of birth:**	1989  

## JUNIOR DEVELOPER 

### EXPERIENCE SUMMARY:
- 	Working in QA (manual & automation) processes, approaches and methodologies:
Functional / Regression / Exploratory / Load / Compatibility / Usability testing, etc.
-	Developing STR (updating), executing test plans (STP), test design or test cases (STD).
-	Programming skills in Java, JS and C. Knowledge in WEB programming (HTML, CSS, Xpath). 
-	Understanding of front-end & back-end technologies.
-	Familiar with MySQL and PostgreSQL.
-	Web Testing & Automation Tools: TestStudio, IntelliJIdea, Eclipse, Selenium IDE, Postman, Firebug, Sublime.
-	Frameworks & Bug tracking: Selenium WebDriver, Protractor, Maven, TestNG, Junit, BugZilla, GIT/GitHub, Jira.
-	Experienced in Agile, Scrum development methodology.

### WORK EXPERIENCE
**2017 – Present: SAP Israel. PERFORMANCE AUTOMATED DEVELOPER. Raanana, Israel.**  
- **SAP BRAND IMPACT**– web application, that automatically analyzes videos to detect brand assets in moving images and measures their parameters.  
***Duties:***Performing automated Functional testing with “Protractor”. Manual testing: Exploratory/ Usability / Functional / Regression / Acceptance. Development STP / STD.  
***Code example:***  
```
var Login = require('./pageObject.js');
var Global = require('../lib/globalParams.js');
describe('Login. Blank login and password' , function(){
    var login = new Login();
    beforeAll(function () {
        browser.waitForAngularEnabled(false);
        browser.get(process.env.TESTSERVER);
        login.plainLogin('', '');
    })
    it('«Sorry, we could not authenticate you. Try again»  error appears' , function(){ 
        expect(login.error.getAttribute('innerText')).toEqual(Global.credentials.errorMessage);
    });
})
```
**2015-2017: Elpisor LTD. SOFTWARE QA TESTER. Rehovot, Israel.**  
- **LinkCare** - Web application for patient's administration at Israeli Clalit Health Services.  
***Duties:*** Performing automated Functional / Regression / Smoke testing with “IntelliJ IDEA” (Selenium Webdriver with TestNg framework). Manual testing with “Selenium IDE”.  
- [**Accelify **](http://accelify.com/) - app. for tracking student information in US special schools.  
***Duties:*** Automated tests with “Telerik Test Studio”: Functional / Performance / Load and Stress.
- **Eyecon**- Visual mobile Address Book & Dialer application.  
***Duties:*** Manual mobile testing Exploratory / Regression / Usability. Server side API tests with “Postman” - single endpoints and sets of request (according to user scenarios and existing requirements). Development STP / STD.
- [**Openweathermap API**](http://openweathermap.org/ ) - Weather information API.  
***Duties:*** Server side API tests with “Postman” – single endpoints and sets / Tests GEO cords.  

**2013-2015: Real View-UA (IT development). SOFTWARE QA TESTER. Chernigov,Ukraine.**  
- [**Prokitchensoftware**](http://www.prokitchensoftware.com/) - Prokitchen professional kitchen design software.  
***Duties:***Manual testing. Usability / Functional / Regression / Smoke / Compatibility tests. Exploratory  testing  according user’s scenarios on different devices.

