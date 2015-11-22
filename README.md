# jsta-soapui-maven-runner
En pom-fil som kör valfritt SoapUI projekt

För att köra tester utan SoapUI installerat med maven:

1. Lägg pom-filen i mappen där SoapUI-projektet är sparat

2. Kör testerna genom att exekvera: mvn com.smartbear.soapui:soapui-maven-plugin:5.1.3:test "-Dfiletorun=\<SoapUI-projektets filnamn\>"


Hur man kör med SoapUI runner utan maven:

\<SoapUI Home\>/java/app/bin/testrunner.sh -r -a -j -J \<SoapUI-projekt-filsökväg\>

Gå till http://jsta.se för kurser i SoapUI och testautomatisering

---------------------------------------------------------------------------------------

A pom file that runs any SoapUI project

To run tests without SoapUI installed with maven:

1. Put the pom file in the directory where the soapui project is saved

2. Run the tests by executing: mvn com.smartbear.soapui:soapui-maven-plugin:5.1.3:test "-Dfiletorun=\<The SoapUI project filename\>"
 
How to run with SoapUI runner without maven:

\<SoapUI Home\>/java/app/bin/testrunner.sh -r -a -j -J \<SoapUI-projekt-filsökväg\>

Visit http://jsta.se for cources in SoapUI and test automation
