# IntelliJ IDE Settings
[Shared settings for IntelliJ IDE](https://www.jetbrains.com/help/idea/sharing-your-ide-settings.html)
with repository ```https://github.com/lorenzo-m/intellij-settings.git```.

Authentication uses an [access token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/).

In case of authentication issues, the [settings repository](https://intellij-support.jetbrains.com/hc/en-us/articles/206544519-Directories-used-by-the-IDE-to-store-settings-caches-plugins-and-logs)
can be [reset](https://stackoverflow.com/questions/48618774/phpstorm-settings-repository-commit-on-repo-without-head-not-supported).

Project settings present in the .idea folder [should not all be stored in the project repository](https://intellij-support.jetbrains.com/hc/en-us/articles/206544839).
In particular the following contain user-specific settings:
* .idea/workspace.xml
* .idea/usage.statistics.xml
* .idea/tasks.xml
