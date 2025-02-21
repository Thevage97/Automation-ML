# Automatización para Mercado Libre

Este proyecto es una automatización para la página de Mercado Libre, utilizando herramientas y librerías populares en el ámbito de pruebas automatizadas. El objetivo es facilitar la ejecución de pruebas funcionales y de regresión en la plataforma de Mercado Libre.

## Tecnologías Utilizadas

- **Java**: Versión 17
- **Gradle**: Versión 8.4
- **Selenium**: Para la automatización de navegadores.
- **Cucumber**: Para la escritura de pruebas en un formato legible.
- **JUnit**: Para la ejecución de pruebas.
- **TestNG**: Para la gestión de pruebas.
- **ExtentReports**: Para la generación de informes de pruebas.

## Dependencias

Este proyecto utiliza las siguientes librerías:

```groovy
// Dependencias de prueba
testImplementation group: 'junit', name: 'junit', version: '4.12'
testImplementation group: 'io.cucumber', name: 'cucumber-junit-platform-engine', version: '7.14.0'
testImplementation 'io.cucumber:cucumber-junit:7.12.1'
testImplementation group: 'org.testng', name: 'testng', version: '7.10.1'

// Dependencias de implementación
implementation group: 'org.seleniumhq.selenium', name: 'selenium-java', version: '4.13.0'
implementation group: 'io.cucumber', name: 'cucumber-java', version: '7.14.0'
implementation group: 'info.cukes', name: 'cucumber-java', version: '1.2.6', ext: 'pom'
implementation group: 'io.github.bonigarcia', name: 'webdrivermanager', version: '5.5.3'
implementation group: 'tech.grasshopper', name: 'extentreports-cucumber6-adapter', version: '2.17.0'
implementation 'tech.grasshopper:extentreports-cucumber7-adapter:1.7.0'
implementation 'com.aventstack:extentreports:5.0.9'
implementation group: 'io.appium', name: 'java-client', version: '9.2.2'

## Comando de ejecucion en consola

- gradle clean test