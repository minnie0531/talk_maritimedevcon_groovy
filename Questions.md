
### Questions from *Covert Ops: Transform Your Java Team (From The Inside!) With Groovy* (slides [here](http://codetojoy.github.io/talk_maritimedevcon_groovy/assets/player/KeynoteDHTMLPlayer.html#0)) at [Maritime Dev Con 2016](http://maritimedevcon.ca/) 

* **Q:** If the Acme-Dao jar uses Java 8 features, can we still use it with Groovy?
    * Yes, with Groovy 2.3 or higher. In [Example_C_Acme_Dao](http://bit.ly/25FKJoO), there is a new method, `getAccountUsernamesByStatus()` in [AccountDao](http://bit.ly/1ZphhzN). It uses Java 8 extensively and is illustrated [here](http://bit.ly/1PxmGV4).

* **Q:** Can we use Java 8 streams in Groovy?
    * Yes, with some changes in syntax. Check out [this implementation](http://bit.ly/1O9nsr1) of `AccountDao.getAccountUsernamesByStatus()` 

* **Q:** Aside from Java 8 lambdas and method references, are there other syntax differences between Groovy and Java?
    * Yes [here is a list](http://groovy-lang.org/differences.html). e.g. Groovy redefines `==`. In practice, there are rarely any problems.

* **Q:** Can we use [Grapes] with a repository that is not Maven Central?
    * Yes, see [Section 1.2](http://docs.groovy-lang.org/latest/html/documentation/grape.html)
    * I hope to illustrate this with an example using the Acme-Dao jar, but that will take some time.

* **Q:** *after session* In [Nothing is Something](https://www.youtube.com/watch?v=OMPfEXIlTVE), Sandi Metz illustrates the power of object composition using `House`, `RandomHouse`, and `EchoHouse`. Can this be achieved in Groovy?
    * Sure. Coming soon

* **Q:** Can you illustrate using a Groovlet from Jenkins?
    * Coming soon.
