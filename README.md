# Q-Faz Messenger

[![Chat](https://img.shields.io/matrix/q-faz:matrix.org?logo=matrix)](https://matrix.to/#/#q-faz:matrix.org)
![Tests](https://github.com/q-faz/q-faz/actions/workflows/tests.yaml/badge.svg)
![Static Analysis](https://github.com/q-faz/q-faz/actions/workflows/static_analysis.yaml/badge.svg)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=q-faz&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=q-faz)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=q-faz&metric=coverage)](https://sonarcloud.io/summary/new_code?id=q-faz)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=q-faz&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=q-faz)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=q-faz&metric=bugs)](https://sonarcloud.io/summary/new_code?id=q-faz)

## Sobre o Q-Faz Messenger

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

## Instalação

### Requisitos:
- Node.js (LTS recomendado)
- Yarn
- Servidor Matrix configurado (ex: Synapse)

### Passos para compilar e rodar localmente:
```sh
# Clone o repositório
git clone https://github.com/q-faz/q-faz-mensagens-web.git
cd q-faz-mensagens-web

# Instale as dependências
yarn install

# Copie o arquivo de configuração de exemplo
tcp config.sample.json config.json

# Compile o projeto
yarn build

# Rode localmente em modo dev
yarn start
```

## Configuração

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

## Licença

Copyright (c) 2025 **Promotora Q-Faz**

Este software é **privado, proprietário e licenciado exclusivamente** para a Promotora Q-Faz.

Seu uso, redistribuição, modificação ou replicação **não são autorizados** sem contrato legal válido.

Para negociações comerciais e licenciamento, envie e-mail para: **licensing@q-faz.com**

> **Nota:** Este projeto é baseado no Element (https://element.io) e no protocolo Matrix (https://matrix.org), que são marcas registradas de seus respectivos detentores.

