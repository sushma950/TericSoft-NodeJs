# TericSoft-NodeJs Task1
### How to run these  tasks.

### first clone the repository using the below address
repo:https://github.com/sushma950/TericSoft-NodeJs.git


## NodeJs Backend Task API
Step1: Go to Task1(cd Task1)<br/>
Step2:Open Terminal<br/>
Step3:node index.js<br/>
Step4:Open Postman<br/>
Step5:Select POST request in url paste http://localhost:5000/account/register and in body pass parameters<br/>
{<br/>
"phonenumber":1231231230,<br/>
"password":"qwertyu"<br/>
}<br/>
Click Send button in response you will get token<br/>
Step6:Select POST request in url paste http://localhost:5000/account/login and in body pass parameters<br/>
{<br/>
"phonenumber":1231231230,<br/>
"password":"qwertyu"<br/>
}<br/>
Click Send button in response you will get token<br/>
Step7:Select POST request in url paste http://localhost:5000/movie and in body pass parameters<br/>
{<br/>
"movieName":1231231230,<br/>
"year":"qwertyu"<br/>
"genre":"Fiction"<br/>
}<br/>
Click Send button after that details will be stored in DB<br/>
Step7:Select GET request in url paste http://localhost:5000/movie <br/>
Click Send button in response you will get all movies list<br/>
Step8:Select PUT request in url paste http://localhost:5000/movie/movieID 
and in body you can edit details <br/>
Click Send button in response you will get updated movie data<br/>
Step9:Select DELETE request in url paste http://localhost:5000/movie/movieID 
 <br/>
Click Send button after that the selected movie will be deleted from DB<br/>
Step10:Select GET request in url paste http://localhost:5000/movie/movieID <br/>
Click Send button in response you will get particular moviedata<br/>

