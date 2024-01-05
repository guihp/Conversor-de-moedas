# Conversor de Moedas em React Native

  Este é um aplicativo simples de conversão de moedas desenvolvido em React Native.

## Estrutura do Código

  O código está organizado em componentes e utiliza o React Hooks para gerenciar o estado do aplicativo.

### App Component

#### State

  - `loading`: Indica se as moedas estão sendo carregadas.
  - `moedas`: Armazena a lista de moedas disponíveis.
  - `moedaSelecionada`: Moeda selecionada pelo usuário.
  - `moedaBValor`: Valor inserido pelo usuário para conversão.
  - `valorMoeda`: Valor na moeda de origem.
  - `valorConvertido`: Valor convertido para reais.

#### Métodos

  - `loadMoedas`: Função assíncrona que carrega a lista de moedas disponíveis ao iniciar o aplicativo.
  - `converter`: Função que realiza a conversão com base na moeda selecionada e no valor inserido.

#### Renderização

  Mostra um indicador de carregamento enquanto as moedas estão sendo carregadas. Exibe a interface do aplicativo após o carregamento, permitindo que o usuário selecione a moeda, insira o valor e execute a conversão.

### Styles

  Utiliza o StyleSheet do React Native para estilizar os componentes.

## Como Usar

### 1. Instalação das Dependências

  Certifique-se de ter todas as dependências necessárias instaladas usando o npm ou yarn.

```bash
npm install
# ou
yarn install
```

### 2. Execução do Aplicativo
  Execute o aplicativo em um emulador ou dispositivo físico.
```bash
npx react-native run-android
# ou
npx react-native run-ios
```
### 3. Teste o Aplicativo
  Abra o aplicativo no emulador ou dispositivo e siga as instruções para selecionar uma moeda, inserir um valor e converter.

### Observações
  O código utiliza a API api para obter informações sobre as moedas.
  A conversão é realizada considerando a taxa de câmbio entre a moeda selecionada e o real (BRL).

### Fotos
![image](https://github.com/guihp/Conversor-de-moedas/assets/119879832/fbea72dc-8d6a-4910-abd4-aca88cbf138b)
![image](https://github.com/guihp/Conversor-de-moedas/assets/119879832/a6668c97-92ca-44ba-8133-37f5fe6d1def)
![image](https://github.com/guihp/Conversor-de-moedas/assets/119879832/d6650f65-8d3f-415f-988b-f770072420ab)
![image](https://github.com/guihp/Conversor-de-moedas/assets/119879832/8f7fa25b-4059-43de-9915-7fb68dc3ed55)




