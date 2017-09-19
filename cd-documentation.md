# Continuous CI and CD Documentation

MVP Application: [http://165.227.136.184](http://165.227.136.184)

---

Because we are going to use the language PHP with the Laravel 5 framework, it was obvious to use  **Laravel Forge** tool for Continuous Deployment, and **Travis CI** for Continuous Integration.

**Laravel Forge:** The reason why we are using forge, is because forge is especially build for Laravel continuous deployment.


**Travis CI:** With the help of Travis, we do continuous test for our application and trig our deployment service.    


**The CD chain steps:**

 - Push to master branch on Github.
 - Travis CI trigs the push and runs the tests.
 - Then Forge is trigged by Travis CI and deploy the changes to the remote server.

