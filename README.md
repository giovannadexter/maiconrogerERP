O repositório de gerência de configuração para o projeto ERP está estruturado da seguinte forma:


- **README.md**
- **baseline/**
  - **v1.0/**
    - arquivo1.txt
    - arquivo2.txt
    - ...
  - **v2.0/**
    - arquivo1.txt
    - arquivo2.txt
    - ...
- **mainline/**
  - arquivo1.txt
  - arquivo2.txt
  - ...
- **funcionalidades/**
  - **manufatura/**
    - arquivo1.txt
    - arquivo2.txt
    - ...
  - **saude/**
    - arquivo1.txt
    - arquivo2.txt
    - ...
  - **educacao/**
    - arquivo1.txt
    - arquivo2.txt
    - ...
- **relatorio/**
  - relatorio.pdf

- **.gitignore**: Este arquivo lista os arquivos e pastas que devem ser ignorados pelo controle de versões Git.

- **baseline/**: Nesta pasta, são armazenadas as versões baselines do projeto. Cada subpasta representa uma versão específica do ERP, e os arquivos dentro delas refletem o estado do projeto naquela versão.

- **mainline/**: Esta pasta contém a linha principal de desenvolvimento do projeto. Os arquivos aqui representam a versão mais recente e estável do ERP.

- **funcionalidades/**: Aqui estão as pastas que contêm os nichos diferenciados do ERP. Cada nicho possui sua própria subpasta e arquivos associados.

- **relatorio/**: Uma pasta para armazenar documentos relacionados ao projeto, como relatórios de status, documentação técnica e outros documentos importantes.

## ERP

Para gerenciar o projeto de ERP altamente especializado, foram escolhidos três nichos que se destacam:

1. **Nicho de Manufatura**:
   - Arquivo de configuração: `funcionalidades/nicho_manufatura/configuracao.txt`
   - Código-fonte: `funcionalidades/nicho_manufatura/`
   - Documentação: `funcionalidades/nicho_manufatura/documentacao.txt`

2. **Nicho de Saúde**:
   - Arquivo de configuração: `funcionalidades/nicho_saude/configuracao.txt`
   - Código-fonte: `funcionalidades/nicho_saude/`
   - Documentação: `funcionalidades/nicho_saude/documentacao.txt`

3. **Nicho de Educação**:
   - Arquivo de configuração: `funcionalidades/nicho_educacao/configuracao.txt`
   - Código-fonte: `funcionalidades/nicho_educacao/`
   - Documentação: `funcionalidades/nicho_educacao/documentacao.txt`

## Relatório

O relatório completo sobre o projeto de gerência de configuração, incluindo detalhes sobre a estratégia de controle de versões, fluxo de desenvolvimento colaborativo e os diferenciais dos nichos do ERP, pode ser acessado [aqui](./relatorio/relatorio.pdf).
