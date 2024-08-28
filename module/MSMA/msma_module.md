# About MicroSoft SQLServer Migration Assessment(MSMA) Module
"The MS2PG module provides a Rough order of magnitude (ROM) of the auto conversion and the manual efforts required to migrate an MS SQL Server database to PostgreSQL. It discovers the objects, accesses them and estimates conversion rate of your MS SQL Server db to Postgres Sql db.
When given an MS SQL Server export in the form of a ZIP archive, the module parses and subsequently assesses its SQL files. The entire process takes place solely in the browser, without using any external resources."
# Steps to build the project
1. Open the `package.json` file of `atroposs-msma-module` project and increase the version number based on release type i.e. minor or major to publish a new version of same NPM package.
2. Run `ng build atroposs-msma-module` to build the project. The build artifacts will be stored in the `dist/` directory.
# Publishing
After building your library with `ng build atroposs-msma-module`, go to the `dist` folder `cd dist/atroposs-msma-module` and run `npm publish`.
