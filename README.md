# 1Finance - Dell

Este repositório contém a automação de testes do projeto **1Finance** da Dell, utilizando o **Robot Framework** com **Python**. O objetivo do projeto é criar e manter testes automatizados eficientes e reutilizáveis, garantindo a qualidade contínua do sistema financeiro **1Finance**.

## 🛠 Tecnologias Utilizadas

- **Robot Framework**: Framework de automação para testes aceitos e funcionais.
- **Python**: Linguagem usada para desenvolver e customizar as bibliotecas de teste.

## 🚀 Funcionalidades

- Automação de testes de **UI** e **API**.

## ⚙️ Instalação

### Python
Baixe e instale o Python a partir do site oficial:  
[Download Python](https://www.python.org/downloads/windows/)

### Robot Framework
Siga as instruções para instalar o Robot Framework:  
[Guia de Introdução ao Robot Framework](https://robotframework.org/?tab=1#getting-started)

### Bibliotecas do Robot Framework

Instale as bibliotecas necessárias para o projeto usando `pip`:

- **SeleniumLibrary**: Para automação de navegadores  
  ```bash
  pip install --upgrade robotframework-seleniumlibrary
  ```
  Documentação: [SeleniumLibrary Documentation](https://robotframework.org/SeleniumLibrary/SeleniumLibrary.html)

- **RequestsLibrary**: Para automação de testes de APIs  
  ```bash
  pip install robotframework-requests
  ```
  Documentação: [RequestsLibrary Documentation](https://marketsquare.github.io/robotframework-requests/doc/RequestsLibrary.html)

- **DatabaseLibrary**: Para testes envolvendo banco de dados  
  ```bash
  pip install robotframework-databaselibrary
  ```
  Documentação: [DatabaseLibrary Documentation](https://marketsquare.github.io/Robotframework-Database-Library/)

- **FakerLibrary**: Para gerar dados de teste falsos  
  ```bash
  pip install robotframework-faker
  ```
  Documentação: [FakerLibrary Documentation](https://marketsquare.github.io/robotframework-faker/)

### Web Drivers

Baixe os drivers necessários para automação de navegadores:

- **Chromedriver**:  
  [Download Chromedriver](https://googlechromelabs.github.io/chrome-for-testing/)
  
- **Geckodriver (Firefox)**:  
  [Download Geckodriver](https://github.com/mozilla/geckodriver/releases/tag/v0.35.0)

> **Observação**: Atualize os navegadores e coloque ambos os drivers na pasta do Python (mesmo caminho configurado no Path).

## 📚 Documentação Útil

- **Robot Framework User Guide**: [Link](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html)
- **BuiltIn Library**: [Link](https://robotframework.org/robotframework/latest/libraries/BuiltIn.html)
- **Collections Library**: [Link](https://robotframework.org/robotframework/latest/libraries/Collections.html)
- **DateTime Library**: [Link](https://robotframework.org/robotframework/latest/libraries/DateTime.html)
- **Dialogs Library**: [Link](https://robotframework.org/robotframework/latest/libraries/Dialogs.html)
- **OperatingSystem Library**: [Link](https://robotframework.org/robotframework/latest/libraries/OperatingSystem.html)
- **Process Library**: [Link](https://robotframework.org/robotframework/latest/libraries/Process.html)
- **String Library**: [Link](https://robotframework.org/robotframework/latest/libraries/String.html)