# Automação Cypress JavaScript Orange HRM com CI

![Texto alternativo](OrangeHRM.png)



Automação E2E com Cypress para o sistema OrangeHRM, utilizando a arquitetura Page Objects. Testes implementados para os módulos Login, Dashboard e My Info, com foco em escalabilidade e manutenção fácil. O projeto demonstra boas práticas em automação de testes e estruturas reutilizáveis, garantindo eficiência e qualidade.

## ⚙️ Installar

O comando npm install chance instala a biblioteca Chance.js, que é uma ferramenta simples e poderosa para gerar dados aleatórios em JavaScript. Ele foi utilizado neste projeto e será necessário.

```bash
npm install chance
```
## 📋 Pré-requisitos

> **💡 NOTA:**
> 
> È necessário ter o instalado
> 

Certifique-se de ter os seguintes componentes instalados para executar este projeto:

- [Node.js (v14 ou superior)](https://nodejs.org/)
- [Appium (última versão)](https://appium.io/docs/en/about-appium/intro/)
- [Java Development Kit (JDK) (v8 ou superior)](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Android Studio (com Android SDK configurado)](https://developer.android.com/studio)
- [Python (opcional para scripts adicionais)](https://www.python.org/downloads/)
- Dispositivo físico ou [Emulador Android](https://developer.android.com/studio/run/emulator) configurado para testes




## 📝 Passo a Passo para Instalação



**1.** **Clone o repositório na sua maquina 🖥️**

```bash
git clone https://github.com/ElizabethGomes-QAEngineer/mobile-appium-automacao.git
```

**2.** **Navegue até o diretório do projeto 📂**

```bash
cd appium-android-automation
````


**3.** **Instale as dependências do projeto 📦**

```bash
npm install -g appium
```

**4.** **Inicie o servidor Appium 🚀**

```bash
appium
```

> **💡 NOTA:**
> **5** **Conecte ao seu dispositivo Android ou apenas inicie um emulador**
> 


**6.** **Execute executa o WebdriverIO run 🚀**



```bash
npx wdio
````




> 
> **💡 NOTA:** **1. Configuração: abrir o android usar o emulator "Pixel 8 API 31" após dar run ,no vs code digite a porta do inspector***
> 
´´´bash
appium -p 4723
```
> após iniciar a porta no git bash execute o inspector e clique em "start session"
> quando o app abrir no emulator  
> usar o comando
´´´bash
npx wdio
´´´
