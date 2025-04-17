# Q-Faz Messenger

[![Chat](https://img.shields.io/matrix/q-faz:matrix.org?logo=matrix)](https://matrix.to/#/#q-faz:matrix.org)
![Tests](https://github.com/q-faz/q-faz/actions/workflows/tests.yaml/badge.svg)
![Static Analysis](https://github.com/q-faz/q-faz/actions/workflows/static_analysis.yaml/badge.svg)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=q-faz&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=q-faz)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=q-faz&metric=coverage)](https://sonarcloud.io/summary/new_code?id=q-faz)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=q-faz&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=q-faz)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=q-faz&metric=bugs)](https://sonarcloud.io/summary/new_code?id=q-faz)

## Sobre o Q-Faz Messenger

<<<<<<< HEAD
O **Q-Faz Messenger** é um cliente web para Matrix, derivado do Element, totalmente otimizado e modificado para uso empresarial. O sistema foi personalizado para atender às necessidades da **Promotora Q-Faz**, oferecendo uma solução de comunicação segura, privada e com suporte a integrações empresariais.

## Repositório Oficial

GitHub: [https://github.com/q-faz](https://github.com/q-faz)  
Website: [https://q-faz.com](https://q-faz.com)

## Funcionalidades Principais
- **Mensagens instantâneas seguras** via protocolo Matrix.
- **Suporte a chamadas de voz e vídeo**.
- **Integração com sistemas empresariais**.
- **Personalização de interface** com temas exclusivos.
- **Criptografia de ponta a ponta** para maior segurança.
- **Aplicativo para desktop e móvel**.
- **Servidor próprio** para comunicação interna.
=======
O **Q-Faz Messenger** é um cliente web para Matrix, desenvolvido a partir do código-fonte do Element. O sistema foi amplamente **refatorado, otimizado e adaptado** para uso privado e corporativo da **Promotora Q-Faz**, oferecendo uma solução de comunicação **segura, escalável e com identidade visual própria**. O projeto é mantido e aprimorado por **Nathan Martins**, dev full-stack e perito em cibersegurança.

## Repositório Oficial

- GitHub: [https://github.com/q-faz](https://github.com/q-faz)  
- Website: [https://q-faz.com](https://q-faz.com)

## Funcionalidades Principais
- 💬 **Mensagens instantâneas seguras** via protocolo Matrix
- 📞 **Chamadas de voz e vídeo integradas**
- 🔐 **Criptografia de ponta a ponta (E2EE)**
- 🖥️ **Interface personalizada** com temas corporativos
- 📱 **Compatível com desktop e mobile**
- 🧩 **Integração com sistemas internos (ERP, CRM etc.)**
- 🛡️ **Hospedagem em servidor próprio para comunicação interna**

## Linguagens e Tecnologias Utilizadas
- **JavaScript (React.js)**
- **TypeScript**
- **HTML5 + CSS3 (SASS/SCSS)**
- **Node.js**
- **Electron (para versão desktop)**
- **Matrix Protocol & SDK**
- **Webpack / Yarn**
>>>>>>> 272026b349217cfc182f570f98cc7497365e3458

## Instalação

### Requisitos:
<<<<<<< HEAD
- Node.js (versão LTS recomendada)
- Yarn (para gerenciar dependências)
- Servidor Matrix configurado
=======
- Node.js (LTS recomendado)
- Yarn
- Servidor Matrix configurado (ex: Synapse)
>>>>>>> 272026b349217cfc182f570f98cc7497365e3458

### Passos para compilar e rodar localmente:
```sh
# Clone o repositório
<<<<<<< HEAD
git clone https://github.com/q-faz/q-faz.git
cd q-faz
=======
git clone https://github.com/q-faz/q-faz-mensagens-web.git
cd q-faz-mensagens-web
>>>>>>> 272026b349217cfc182f570f98cc7497365e3458

# Instale as dependências
yarn install

<<<<<<< HEAD
# Configure o aplicativo copiando o arquivo de exemplo de configuração
cp config.sample.json config.json

# Compile o aplicativo
yarn build

# Inicie o servidor de desenvolvimento
=======
# Copie o arquivo de configuração de exemplo
tcp config.sample.json config.json

# Compile o projeto
yarn build

# Rode localmente em modo dev
>>>>>>> 272026b349217cfc182f570f98cc7497365e3458
yarn start
```

## Configuração
<<<<<<< HEAD
A configuração do sistema pode ser ajustada no arquivo `config.json`. Consulte a [documentação oficial](docs/config.md) para mais detalhes.

## Desenvolvimento

### Ambiente de Desenvolvimento
1. Certifique-se de ter as dependências instaladas com `yarn install`.
2. Para rodar o aplicativo em modo de desenvolvimento:
```sh
yarn start
```
3. O aplicativo será executado localmente em `http://localhost:8080`.

### Contribuições
Contribuições são bem-vindas! Consulte o guia de contribuição em `CONTRIBUTING.md` antes de enviar um PR.

## Suporte e Contato
Para suporte técnico e informações, entre em contato pelo nosso site: [https://q-faz.com](https://q-faz.com) ou pelo e-mail suporte@q-faz.com.
=======

Ajustes do sistema são feitos via `config.json`. Consulte a [documentação de configuração](docs/config.md) para entender cada parâmetro.

## Desenvolvimento

### Rodando ambiente local
```sh
yarn install
yarn start
```
O sistema estará disponível em `http://localhost:8080`

### Contribuindo
Contribuições são bem-vindas! Siga as orientações do arquivo [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Suporte

- Site: [https://q-faz.com](https://q-faz.com)  
- E-mail: suporte@q-faz.com
>>>>>>> 272026b349217cfc182f570f98cc7497365e3458

## Licença

Copyright (c) 2025 **Promotora Q-Faz**

<<<<<<< HEAD
O **Q-Faz Messenger** é um software **privado e comercial** da Promotora Q-Faz. Seu código pode ser utilizado **somente por licença adquirida** e mediante contrato.

Para adquirir uma licença comercial, entre em contato pelo e-mail **licensing@q-faz.com**.

Element e Matrix são marcas registradas de seus respectivos proprietários.
=======
Este software é **privado, proprietário e licenciado exclusivamente** para a Promotora Q-Faz.

Seu uso, redistribuição, modificação ou replicação **não são autorizados** sem contrato legal válido.

Para negociações comerciais e licenciamento, envie e-mail para: **licensing@q-faz.com**

> **Nota:** Este projeto é baseado no Element (https://element.io) e no protocolo Matrix (https://matrix.org), que são marcas registradas de seus respectivos detentores.
>>>>>>> 272026b349217cfc182f570f98cc7497365e3458

