# Prova de conceito para sistemas sistemas de Gerenciamento de Identidade e Acesso (IAM)

Este repositório contém uma Prova de Conceito (POC) para a implementação de sistemas de Gerenciamento de Identidade e Acesso (IAM), focada em autenticação e autorização para aplicações web e APIs. Serão realizados testes com as seguintes soluções de IAM:

- **Keycloak**
- **Authelia**
- **Casdoor**
- **Authentik**

## Objetivos da POC

A POC visa validar a viabilidade e a integração dos sistemas de IAM para os seguintes cenários:

- **OpenID Connect**: Testar a implementação do protocolo OpenID para autenticação e autorização.
- **Passwordless Authentication**: Avaliar a capacidade dos sistemas de oferecer autenticação sem senha.
- **LDAP Integration**: Testar a integração com LDAP para gerenciamento de usuários e autenticação.
- **Integração com API Gateways (Krakend e outros)**: Validar a integração dos sistemas de IAM com o Krakend e outros gateways de API.
- **Acesso via API**: Verificar a possibilidade de realizar autenticações e autorizações diretamente via API.

## Requisitos

- A solução deve ser **leve** e preferencialmente **cloud native**, facilitando a escalabilidade e o uso em ambientes em nuvem.
- Todas as ferramentas utilizadas são **open source** e com **utilização livre**, permitindo adaptação e personalização conforme as necessidades.

## Ferramentas Utilizadas

As seguintes ferramentas de IAM serão testadas:

- **Keycloak**: Sistema de IAM de código aberto que oferece suporte a SSO, MFA e protocolos como OpenID, OAuth2 e SAML.
- **Authelia**: Plataforma de autenticação multifator e autorização projetada para proteger aplicações web com forte foco em segurança.
- **Casdoor**: Sistema unificado de IAM que oferece suporte a vários métodos de autenticação, incluindo OpenID e LDAP.
- **Authentik**: Sistema de IAM cloud native focado em facilidade de uso e integração com outras ferramentas de autenticação.

## Estrutura do Projeto

- **docs/**: Documentação e guias de instalação e configuração.
- **configs/**: Arquivos de configuração de cada sistema de IAM.
- **tests/**: Scripts e exemplos de testes para cada um dos cenários mencionados.

## Como Executar

1. Clone o repositório:

    ```bash
    git clone https://github.com/seuusuario/poc-iam-systems.git
    cd poc-iam-systems
    ```

2. Instale as dependências e siga as instruções de cada solução de IAM dentro da pasta `docs/`.

3. Execute os testes em cada sistema:

    - OpenID
    - Passwordless
    - LDAP
    - Integração com Krakend e outros gateways
    - Acesso via API

## Contribuições

Este projeto é open source e contribuições são bem-vindas. Se desejar adicionar novos cenários ou corrigir bugs, fique à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](./LICENSE) para mais informações.
