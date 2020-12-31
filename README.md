<h1 align="center">
  <br>
  <br>
  Minesweeper-Client
  <br>
</h1>
<h4 align="center">Client for game mineswipeer.</h4>
<p align="center">
  <a href="#list-of-items-completed">List of items completed</a> •
  <a href="#dependencies">Dependencies</a> •
  <a href="#technologies">Technologies</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#contributing">Contributing</a>
</p>

# [Click me to play Minesweeper Game](https://minesweeper-client-ob.herokuapp.com/)  

##  List of items completed

* Design and implement a documented RESTful API for the game (think of a mobile app for your API)
* Implement an API client library for the API designed above. Ideally, in a different language, of your preference, to the one used for the API
* When a cell with no adjacent mines is revealed, all adjacent squares will be revealed (and repeat)
* Ability to 'flag' a cell with a question mark or red flag
* Detect when game is over



## Technologies 
* [JDK 11](https://www.oracle.com/index.html)
* [Spring Boot](https://projects.spring.io/spring-boot/)
* [Thymeleaf](https://www.thymeleaf.org/)
* [Gradle](https://gradle.org/)
* [jUnit 5](http://junit.org/junit5/)
* [Mockito](http://site.mockito.org/)
* [Heroku](https://www.sonarqube.org/)


## Dependencies
* [Minesweeper-Service](https://app.swaggerhub.com/apis/obarra-dev/MinesweeperApiRest/1.0.0)
* [Java 11](https://www.oracle.com/index.html)

## How To Use

### Running the project

Before running the project please ensure that all the dependencies are installed in your system. Then follow the next:


1. Run the project itself 

    ```
    gradlew bootRun 
    ```
### Running the tests

In order to run the project tests you need to execute the following command:

```
gradlew test 
```


## Contributing
1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Make your changes
4. Run the tests, adding new ones for your own code if necessary (`junit5`)
5. Commit your changes (`git commit -am 'Added some feature'`)
6. Push to the branch (`git push origin my-new-feature`)
7. Create new Pull Request

* Questions?, <a href="mailto:barraomar12@gmail.com?Subject=Question about Game Mineswipeer" target="_blank">write here</a>
