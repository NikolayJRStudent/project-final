CHECK COMIT!


List of tasks accomplished:
1Remove social networks: vk, yandex.


2.Put sensitive information in a separate property file:
login
database password
identifiers for OAuth registration/authorization
mail settings
The values of these properties should be read at server startup from the machine's environment variables.

3.Refactor the com.javarush.jira.bugtracking.attachment.FileUtil#upload method so that it uses a modern approach for working with the file system.

4.Redesign the tests so that during the tests the in memory database (H2) is used instead of PostgreSQL. To do this, we need to define 2 bins, and the selection of which one to use should be determined by the active Spring profile. H2 does not support all the features that PostgreSQL has, so you will have to simplify the scripts with test data a bit.
...
