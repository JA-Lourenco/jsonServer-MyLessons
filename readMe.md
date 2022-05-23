## Instruções para executar o JSON Server

Antes de iniciar o passo a passo, execute o comando abaixo para instalar as dependências do projeto React Native:

<code>npm install</code>

### React JS

1 - Verifique se existe a flag de host no arquivo package.json e exclua:

<code>
    "scripts": {
        "api": "json-server ./db.json --host 192.128.0.0 --port 3333 --delay 700"
    },
</code>

2 - Dentro da pasta services, arquivo api.ts do projeto React, coloque a seguinte URL:

http://localhost:3333

2 - Execute o comando no terminal do JSON Server:

<code>npm run api</code>

3 - Execute o projeto React:

[Repositório ReactJS](https://github.com/JA-Lourenco/myLessons-ReactJS)

### React Native

1 - Abra seu terminal e execute o seguinte comando para pegar o número de IP da sua máquina:

<code>ipconfig</code>

2 - Inclua o IP coletado na flag host no arquivo package.json:

<code>"api": "json-server ./db.json --host {seu_ip} --port 3333 --delay 700"</code>

3 - Dentro da pasta services, arquivo api.ts do projeto React Native, coloque a seguinte URL com o IP coletado:

http://192.128.0.0:3333

4 - Execute o comando no terminal do JSON Server:

<code>npm run api</code>


5 - Execute o projeto React Native:

[Repositório React Native](https://github.com/JA-Lourenco/myLessons-ReactNative)
