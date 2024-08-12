# Hard Skill Test - LRGE Systems

Este repositório contém o teste dividido em duas partes: a extração de informações de um arquivo zipado usando Python 3 e a criação de uma aplicação fullstack em Node.js/JavaScript para listar e exibir essas informações.

## Parte 1: Extração de Arquivo Zipado

Desenvolva um script em Python 3 para abrir um arquivo zipado e extrair suas informações.

### Requisitos

- Python 3

### Instruções

1. Crie um script em Python 3 que:
   - Abra um arquivo zipado.
   - Extraia todas as informações do arquivo zipado.
   - Salve os arquivos extraídos em um diretório temporário ou específico.
   - A extração deve ser integrada ao frontend, isto é, extrair para um local que o frontend consiga acessar e operar

## Parte 2: Aplicação Fullstack em Node.js/JavaScript

Crie uma aplicação fullstack em Node.js/JavaScript para listar e exibir as informações extraídas na Parte 1.

### Requisitos

- Node.js
- Framework de sua escolha (Express, Nest, Next, React, etc.)
- É importante a criação de um design limpo e bonito para podermos avaliar o frontend

### Funcionalidades

1. *Página 1:* Listar de maneira organizada os arquivos extraídos do arquivo zipado.
2. *Página 2:* Exibir o conteúdo do setor "Device Info" do arquivo report.xml dentro do zipado.

```xml
<metadata section="Device Info">
</metadata>