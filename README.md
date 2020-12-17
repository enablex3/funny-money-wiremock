# FUNNY MONEY WIREMOCK SERVER

## Summary

---
The purpose of the wiremock server is to provide a way for developers to mock their API. This assists with API design as well and cuts server costs in the early stages of development.
---

## Instructions
---
1. A jar file for the wiremock server is included in this repo, but if you'd like, you may download the wiremock standalone server from <a href="http://wiremock.org/docs/download-and-installation/">here</a>. Scroll to the end of the page to the <strong>Direct Download</strong> section.
2. Download java for your operating system. At least JRE8. Download can be found <a href="https://www.oracle.com/java/technologies/javase-jre8-downloads.html">here</a>.
3. To execute the server, in a terminal or command prompt, navigate to this repo's root directory and type `java -jar wiremock-jre8-standalone-2.27.2.jar`
4. Check to make sure mappings have loaded by going into your browser and entering `http://localhost:8080/__admin/`
---

## Configuration
---
There are two directories within the repo. One is calling <strong>mappings</strong>, the other is called <strong>__files</strong>. In our case, we have json files under mappings directory and the wiremock server will configure its mock API endpoints. Please refer to the documentation for further understanding of wiremock <a href="http://wiremock.org/docs/">here</a>.
