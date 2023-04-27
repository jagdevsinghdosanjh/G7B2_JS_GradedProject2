# G7B2_JS_GradedProject2
This Repository is being submitted to GreatLearning for Full Stack Software Development Certification on behalf of Buddy Group G7B2. Project is Resume Template for an Organization

Resume Template
You are working as a front end developer in an organization and the organization has job openings in various departments. The organization has also received various applications for these positions and the data is available in JSON format. Use the data shared along with this problem statement. You, as a front end engineer, should develop a single User interface where you can see the details shared by the candidates or the applicants. Below are the detailed requirements which you have to achieve as a first version of the web page design.

In Login Page: 
1.	Store the username and password in local storage
2.	Create a simple login page
3.	Validate the username and password. If successful, direct the user to Resume Page
4.	Once the user is in the Resume page restrict the user from going back to the login page. (When clicked on the back button in the browser, restrict the user from going back to the login page).
5.	If the user has entered invalid credentials, print invalid username/password.

![image](https://user-images.githubusercontent.com/33898246/234891396-c6765454-55e3-4178-b55b-6e78424a0c49.png)

In Resume Page:
1.	Each applicant's details should be fetched from the JSON file and displayed in the web page.
2.	When clicked on Next or Previous Buttons in the web page, the next or previous applicant details should be displayed irrespective of the job they applied for.
3.	The web application should also have filtering capability where when searched for a particular job, only applications of that job openings should be displayed.
4.	In case if there is one application when searched for a job opening, the left and right buttons should not be seen. If the shown application is the first application, then previous buttons should be hidden and vice-versa.
5.	If there are no job openings for the searched value, then print “Invalid search or No applications for this job”.

Sample Outputs:
1.	Error Image where there are no related applications.

![image](https://user-images.githubusercontent.com/33898246/234891569-9aab7ec3-34d1-4d6f-a935-249cd96b922d.png)

2.	Sample output of the page when Loaded

![image](https://user-images.githubusercontent.com/33898246/234891742-45265d33-f11b-4ec8-8e02-50b10c5ada95.png)

