# Open Journal Systems (OJS) para Cadernos de Saúde Pública (CSP)
 Este repositório visa documentar a configuração do sistema OJS para hospedar o Cadernos de Saúde Pública da Fiocruz.


## Instalação

Instale o sistema OJS conforme [documentação](https://docs.pkp.sfu.ca/dev/documentation/en/getting-started) na versão 3.4.0

## Configuração

1) Para o Cadernos de Saúde de Pública, é necessário instalar e habilitar os seguintes plugins do projeto OJS, encontrados na galeria de plugins do sistema:

   - Bootstrap
   - QuickSubmit
   - Custom Locale Plugin
   - ORCiD Profile
   - Control Public Files

2) Os seguintes plugins desenvolvidos para customizar o OJS, com regras de negócio do CSP, foram desenvolvidos e são necessários ser instalados, conforme documentação em seus repositórios:

   - [CspTheme ](https://github.com/FiocruzLivre/ojs-csp-theme)
   - [CspUser](https://github.com/FiocruzLivre/ojs-csp-user)
   - [CspSubmission](https://github.com/FiocruzLivre/ojs-csp-user  )
   - [CspWorkflow](https://github.com/FiocruzLivre/ojs-csp-workflow)
   - [CspMail](https://github.com/FiocruzLivre/ojs-csp-mail)

3) Restaure um dump do banco de produção do CSP na nova instalação e faça a cópia das pastas ``files/journals/1/`` e ``public/journals/1/`` de produção para a nova instalação.