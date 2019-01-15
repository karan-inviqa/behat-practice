# behat-practice
Learn and practice Behat.

### Installation
- create project directory
- run command composer install behat/behat (You must have installed composer)
- check installed behat version using vendor/bin/behat -v

### Start with a demo
- create a features directory
- put a demo feature file i.e. basket.feature in features directory
- run command vendor/bin/behat --init form project root dir
- The --init command tells Behat to provide you with things missing to start testing your feature. In our case, it’s just a **FeatureContext** class under the **features/bootstrap/FeatureContext.php** file.