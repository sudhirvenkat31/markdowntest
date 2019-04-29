# Description #

This add-on is a **Groovy** based **integration test** framework. Tests are Groovy scripts with testcase definitions. The framework is targeted at integration level testing of software supporting a command line interface (CLI) or accessible via groovy scripts. The framework can also be used for unit and integration testing of Java, Groovy, and Gant code. A declarative style simplifies many test scenarios and the full power of Groovy scripting makes more complex test scenarios possible as well. Parallel execution of testcases significantly reduces run time, enabling more frequent use and more timely feedback for continuous integration (CI) environments.

# Key Attributes #

The following summarizes the key attributes that are fundamental to GINT.

1.  **Groovy** - powerful capabilities, concise syntax, easy adoption for JAVA programmers. Simple where that is sufficient. Fully extendable to cover more difficult and complex cases often encountered in integration level testing.
1.  **Integration testing** - testing complete programs from the outside. Unit testing is not sufficient and unit test based tools and frameworks are overly complex and lack specific features for productive integration level testing.
1.  **Agile methodology** - supporting the practices of **Test Driven Development**, **Acceptance Testing**, and **Continuous Integration**.

![GINT Building Blocks](https://bobswift.atlassian.net/wiki/download/attachments/5767199/gint-groovy-base.png?version=1&modificationDate=1371576781764&api=v2)

# Links #

* [Documentation Site](https://bobswift.atlassian.net/wiki/display/GINT) - extensive user documentation
* [JIRA Issues](https://bobswift.atlassian.net/browse/GINT) - support and improvement requests
* [Groovy Tasks for Bamboo](https://bobswift.atlassian.net/wiki/display/BGTP) - Bamboo tasks for GINT, Groovy, and Gradle (commercial)
* [GINT on Atlassian Marketplace](https://marketplace.atlassian.com/plugins/org.swift.tools.gint)

# Features #
*   [Feature - Atlassian Application Testing](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+Atlassian+application+testing) â€” an extension for testing add-ons for Atlassian products like JIRA, Service Desk, Confluence, Bamboo, Bitbucket, and HipChat
*   [Feature - Automatic Comparisons](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+automatic+comparisons) â€” validating data produced matches expected results
*   [Feature - Automatic Retry Support](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+automatic+retry+support) â€” Support for automatic retry of failed testcases and conditional retries
*   [Feature - Command Logging](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+command+logging)
*   [Feature - CSV Defined Testcases](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+CSV+defined+testcases) â€” testcase definitions can come from CSV files
*   [Feature - Database Defined Testcases](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+database+defined+testcases) â€” testcase definitions can come from database tables
*   [Feature - Database Output](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+Database+Output) â€” for getting test results data directly into a reporting database
*   [Feature - GINT Properties](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+GINT+properties) â€” Automatic loading of properties from gint.properties found in standard locations
*   [Feature - Interactive Testing](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+interactive+testing) â€” Support for manual and semi-automated tests using instant messaging
*   [Feature - JUnit-style XML Output](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+JUnit-style+XML+output) â€” for integrating test results with Continuous Integration (CI) tools
*   [Feature - Parallel](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+parallel) â€” automatic running of testcases in parallel
*   [Feature - Profiles](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+profiles) â€” automatic and more advanced than simple property files
*   [Feature - Reports](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+reports) â€” supports output logging, JUnit-style XML, mail, and IM reports
*   [Feature - Selenium Support](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+selenium+support) â€” enables quick and maintainable Selenium testing
*   [Feature - Subsets](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+subsets) â€” ability to control which testcases should be included in a specific run
*   [Feature - Command Generators](https://bobswift.atlassian.net/wiki/display/GINT/Feature+-+command+generators) â€” ease testcase definition and maintenance by defining testcase parameters used to generate commands
    *   [Command Generator for Atlassian](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+Atlassian)
    *   [Command Generator for Bamboo](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+Bamboo)
    *   [Command Generator for Bitbucket](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+Bitbucket)
    *   [Command Generator for Confluence](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+Confluence)
    *   [Command Generator for Confluence Macro](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+Confluence+Macro)
    *   [Command Generator for CURL](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+CURL)
    *   [Command Generator for FindReplace](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+FindReplace)
    *   [Command Generator for FTP](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+FTP)
    *   [Command Generator for GANT](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+GANT)
    *   [Command Generator for GROOVY](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+GROOVY)
    *   [Command Generator for JAVA](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+JAVA)
    *   [Command Generator for JIRA](https://bobswift.atlassian.net/wiki/display/GINT/Command+generator+for+JIRA)
