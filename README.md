# Exercise - Spring Boot - Environment Variables 2
* create a `Spring Boot` application using `Spring Initializr` that has the following dependencies:
    * `Lombok`
    * `Spring Boot DevTools`
    * `Spring Web`
* define an `application.yaml` config file where you set 3 environments:
  * an environment called `test` that runs on the port `4000` and that has the property `welcomeMsg` set to `Hello from Test`
  * an environment called `prod` that runs on the port `5000` and that has the property `welcomeMsg` set to `Hello form Prod`
* run both the environments, observing the change of the return value by a controller
* remember to add the VM option: `-Dspring.profiles.active=[enter_here_the_profile_name]`
