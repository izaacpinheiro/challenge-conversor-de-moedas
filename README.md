# Conversor de Moedas

Bem-vindo ao **Conversor de Moedas**, um projeto desenvolvido como parte da trilha *Backend Java G9 ONE (Alura)*.

Este desafio tem como objetivo reforçar conhecimentos fundamentais de Java, consumo de APIs, manipulação de JSON e interação via console. Constrói um aplicativo capaz de converter valores monetários em tempo real utilizando taxas atualizadas diretamente de uma API.


## 🧩 Sobre o Desafio
Neste projeto, criei o meu próprio **Conversor de Moedas** totalmente funcional.

A aplicação permite que o usuário escolha entre **6 opções de conversões** diferentes:
- Dólar → Peso Argentino
- Peso Argentino → Dólar
- Dólar → Real Brasileiro
- Real Brasileiro → Dólar
- Dólar → Peso Colombiano
- Peso Colombiano → Dólar

As taxas de conversão **não são fixas**, pois são obtidas dinamicamente através da API [ExchangeRate-API](https://www.exchangerate-api.com/), garantindo precisão e resultados atualizados.

Este projeto foi excelente para praticar:
- Requisições HTTP em Java
- Manipulação e leitura de JSON
- Estruturação de menus e interação com o usuário via console
- Organização de código em classes e métodos

## 🚀 Funcionalidades
- Menu interativo no console
- Conversão entre múltiplas moedas
- Consumo de API de câmbio em tempo real
- Tratamento e extração de dados JSON
- Exibição clara e formatada do valor convertido

## 📦 Como Executar
Este projeto pode ser executado **diretamente pelo IntelliJ IDEA**, de forma simples e prática.

1. Clone este repositório:
   ```bash
   git clone https://github.com/izaacpinheiro/challenge-conversor-de-moedas.git
   ```
> Caso esteja usando o IntelliJ, abra o projeto clonado nele e rode a aplicação. 

2. Compile o projeto:
   ```bash
   javac src/Main.java
   ```
   
3. Execute:
   ```bash
   java -cp src Main
   ```

4. Siga as instruções no menu e aproveite as conversões!

## 🛠️ Tecnologias Utilizadas
- Java 21+  
- Gson para JSON  
- [API ExchangeRate](https://www.exchangerate-api.com/)
- Scanner para entrada de dados

## ✨ Contribuição
Sinta-se livre para sugerir melhorias, enviar PRs ou adaptar o projeto para outras APIs e moedas.
