# How to install code styles tools

## Table of content
* [Configuration Checkstyle for IntelliJ IDEA](Configuration_Checkstyle_for_IntelliJ_IDEA)
* [Configuration Code Style for IntelliJ IDEA](Configuration_Code_Style_for_IntelliJ_IDEA)

## Configuration Checkstyle for IntelliJ IDEA
We will use the following config: https://raw.githubusercontent.com/DmitryKhodakovsky/epam-training-center-code-checkers-configurations/main/checkstyle/checkstyle.xml. 
Settings for pom.xml can be taken from this repo pom.xml

In IntelliJ IDEA I use the following plugin: https://plugins.jetbrains.com/plugin/1065-checkstyle-idea

![image](docs/images/idea_checkstyle_plugin_installation.png)

![image](docs/images/idea_checkstyle_plugin_configuration.png)

paste mentioned URL: https://raw.githubusercontent.com/DmitryKhodakovsky/epam-training-center-code-checkers-configurations/main/checkstyle/checkstyle.xml

![image](docs/images/add_checkstyle_configuration.png)

![image](docs/images/add_checkstyle_configuration_2.png)

Check imported Configuration file

![image](docs/images/checkstyle_imported_configuration.png)

Sometimes run checks

![image](docs/images/checkstyle_run_check.png)

## Configuration Code Style for IntelliJ IDEA

Copy content of the file https://raw.githubusercontent.com/DmitryKhodakovsky/epam-training-center-code-checkers-configurations/main/formatter/code_style.xml to your project and set up path to it in the settings 

![image](docs/images/idea_code_style_import.png)
