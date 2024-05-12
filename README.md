<div align="center">
  <img height="60" src="./src/assets/logo.svg"  />
</div>

## 📄 Projeto

iWeather é um aplicativo de previsão do tempo por cidade. 
O aplicativo foi desenvolvido para praticar testes automatizados em React Native, deploy nas lojas de aplicativos (Play Store e Apple Store) e criação de workflows CI/CD para automação.

## 💻 Tecnologias

- **React Native**
- **TypeScript**
- **Jest**
- **React Native Testing Library**
- **Expo Application Services (EAS)**
- **AsyncStorage**
- **Axios**
- **DayJS**

## 🔖 Layout 

<div align="center" style="display: flex;">
  
<img src="https://github.com/luc-ribeiro/iweather-react-native/assets/69688077/e7abba30-d869-4e03-8426-4bdd292cc60e"
width="200px">
<img src="https://github.com/luc-ribeiro/iweather-react-native/assets/69688077/aedea009-e637-400a-9d0e-33a2b26c1640"
width="200px">
<img src="https://github.com/luc-ribeiro/iweather-react-native/assets/69688077/a071bb30-ca90-4ffa-8888-f6c8f6b77d09"
width="200px">

</div>

## :heavy_check_mark: Cobertura de Testes 

![image](https://github.com/luc-ribeiro/iweather-react-native/assets/69688077/357ee0f8-a085-4a43-ac42-7a0372b4d18a)

## 🚀 Executando o projeto

Para executar o projeto, é necessário [criar uma conta e gerar uma chave de API](https://openweathermap.org/api).

```bash
1. Clone este repositório em sua máquina
$ git clone https://github.com/luc-ribeiro/iweather-react-native.git

2. Instale as dependências
$ npm i

3. Crie um arquivo .env seguindo a estrutura do .env.example. Use a chave de API gerada anteriormente.

4. Rode o projeto através do comando:
$ npm start

- Com o Expo Go aberto em seu dispositivo, escaneie o QR code no terminal
OBS: É preciso ter o Expo Go instalado em seu dispositivo móvel

- Para executar os testes:
$ npm test

- Para gerar o relatório de testes:
$ npm run test:coverage
