# 🐳 Caderno Temático - Docker para Iniciantes com NotebookLM

## 📖 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio prático da DIO, utilizando o NotebookLM como ferramenta de aprendizagem ativa para estudar e organizar conhecimentos sobre Docker.

O objetivo foi explorar conceitos fundamentais de conteinerização, praticar a curadoria de fontes confiáveis, experimentar técnicas de Engenharia de Prompts e consolidar o aprendizado em um material reutilizável para futuras consultas.

---

# 🎯 Objetivos de Estudo

Durante o desenvolvimento deste caderno temático, foram definidos os seguintes objetivos:

* Entender o que é Docker e quais problemas ele resolve.
* Compreender a diferença entre Containers e Máquinas Virtuais.
* Aprender os principais componentes do ecossistema Docker.
* Conhecer os comandos mais utilizados no dia a dia.
* Entender o uso de imagens, containers, volumes e redes.
* Criar um guia rápido para consultas futuras.
* Desenvolver habilidades de Engenharia de Prompts utilizando IA.

---

# 🛠️ Ferramentas Utilizadas

* NotebookLM
* GitHub
* Docker
* ChatGPT
* Markdown

---

# 📚 Curadoria de Fontes

As fontes abaixo foram selecionadas por serem materiais oficiais ou amplamente reconhecidos pela comunidade de tecnologia.

## 1. Documentação Oficial Docker

https://docs.docker.com/

Descrição:
Documentação oficial contendo conceitos, instalação, comandos e boas práticas.

---

## 2. Docker Overview

https://docs.docker.com/get-started/docker-overview/

Descrição:
Introdução ao Docker e seus principais conceitos.

---

## 3. Docker Hub

https://hub.docker.com/

Descrição:
Repositório oficial para busca e compartilhamento de imagens Docker.

---

## 4. Microsoft Learn - Introdução aos Containers Docker

https://learn.microsoft.com/pt-br/training/modules/intro-to-docker-containers/

Descrição:
Curso introdutório gratuito sobre Docker e containers.

---

## 5. Red Hat - O que é Docker?

https://www.redhat.com/pt-br/topics/containers/what-is-docker

Descrição:
Explicação conceitual sobre Docker e conteinerização.

---

# 🧪 Engenharia de Prompts

Durante os estudos foram realizados diversos testes de prompts para extrair conhecimento do NotebookLM.

## Prompt 1 - Conceitos Básicos

### Prompt

Explique o que é Docker para alguém que trabalha com suporte de TI e nunca utilizou containers.

### Resultado

O NotebookLM explicou os conceitos de forma acessível, utilizando exemplos de aplicações isoladas e ambientes padronizados.

### Aprendizado

Definir o perfil do usuário melhora significativamente a qualidade da resposta.

---

## Prompt 2 - Comparação

### Prompt

Compare Containers Docker e Máquinas Virtuais em formato de tabela.

### Resultado

Foi apresentada uma tabela clara demonstrando diferenças de desempenho, consumo de recursos e arquitetura.

### Aprendizado

Solicitar um formato específico torna a informação mais fácil de revisar.

---

## Prompt 3 - Aplicação Prática

### Prompt

Crie um ambiente simples utilizando Docker para hospedar uma aplicação web.

### Resultado

Foram apresentados exemplos utilizando Nginx e containers básicos.

### Aprendizado

Prompts voltados para cenários reais geram respostas mais úteis para aplicação profissional.

---

## Prompt 4 - Troubleshooting

### Prompt

Quais são os erros mais comuns encontrados por iniciantes ao utilizar Docker?

### Resultado

Foram identificados problemas relacionados a portas, volumes, permissões e gerenciamento de imagens.

### Aprendizado

Perguntas focadas em erros ajudam a antecipar dificuldades durante a implementação.

---

# ⚠️ Dificuldades Encontradas

Durante os testes, algumas dificuldades foram observadas:

* Respostas excessivamente genéricas.
* Explicações muito técnicas para iniciantes.
* Grande volume de informações em uma única resposta.
* Falta de exemplos práticos em alguns prompts.

---

# 🔧 Soluções Aplicadas

Para melhorar os resultados foram adotadas as seguintes estratégias:

* Definir o nível de conhecimento esperado.
* Solicitar exemplos reais.
* Pedir respostas em tópicos.
* Solicitar tabelas comparativas.
* Dividir perguntas complexas em várias perguntas menores.

---

# 📘 Miniguia de Estudos Docker

## O que é Docker?

Docker é uma plataforma de conteinerização que permite empacotar aplicações e suas dependências em ambientes isolados chamados containers.

Seu principal objetivo é garantir que uma aplicação funcione da mesma forma em diferentes ambientes.

---

## O que é um Container?

Um container é uma unidade leve e isolada que executa uma aplicação juntamente com tudo o que ela precisa para funcionar.

Benefícios:

* Inicialização rápida
* Baixo consumo de recursos
* Facilidade de implantação
* Portabilidade

---

## O que é uma Imagem Docker?

Uma imagem é um modelo imutável utilizado para criar containers.

Exemplos:

* nginx
* ubuntu
* mysql
* postgres
* redis

---

## Container vs Máquina Virtual

| Característica      | Container     | Máquina Virtual |
| ------------------- | ------------- | --------------- |
| Inicialização       | Segundos      | Minutos         |
| Consumo de Recursos | Baixo         | Alto            |
| Sistema Operacional | Compartilhado | Próprio         |
| Desempenho          | Alto          | Moderado        |
| Portabilidade       | Alta          | Média           |

---

## Componentes Principais

### Docker Engine

Serviço responsável por executar containers.

### Docker Image

Modelo utilizado para criar containers.

### Docker Container

Instância em execução de uma imagem.

### Docker Hub

Repositório online de imagens Docker.

### Docker Volume

Permite persistir dados mesmo após a remoção do container.

### Docker Network

Responsável pela comunicação entre containers.

---

# 📝 Comandos Essenciais

## Verificar versão

```bash
docker --version
```

## Listar containers em execução

```bash
docker ps
```

## Listar todos os containers

```bash
docker ps -a
```

## Baixar imagem

```bash
docker pull nginx
```

## Executar container

```bash
docker run -d -p 80:80 nginx
```

## Parar container

```bash
docker stop <id>
```

## Remover container

```bash
docker rm <id>
```

## Remover imagem

```bash
docker rmi <imagem>
```

---

# 📖 Glossário

### Container

Ambiente isolado para execução de aplicações.

### Image

Modelo utilizado para criar containers.

### Volume

Mecanismo de persistência de dados.

### Dockerfile

Arquivo contendo instruções para construção de imagens.

### Registry

Repositório de imagens Docker.

### Docker Hub

Registry público mantido pela Docker.

### Port Mapping

Mapeamento entre portas do host e do container.

### Bind Mount

Mapeamento direto de diretórios do host para o container.

---

# 🔄 Prompts Reutilizáveis

## Resumo

Resuma os conceitos mais importantes deste conteúdo em tópicos.

---

## Comparação

Compare os conceitos X e Y em formato de tabela.

---

## Explicação para Iniciantes

Explique este conceito para alguém que está começando na área de TI.

---

## Exercícios

Crie 10 questões de revisão com respostas sobre este conteúdo.

---

## Aplicação Prática

Apresente um exemplo real de utilização deste conceito em ambiente corporativo.

---

## Troubleshooting

Liste os problemas mais comuns relacionados a este tema e como resolvê-los.

---

# 🚀 Conclusão

O NotebookLM demonstrou ser uma ferramenta eficiente para organizar estudos técnicos, permitindo consolidar informações de múltiplas fontes em um único ambiente de consulta.

O estudo sobre Docker proporcionou uma compreensão sólida dos conceitos de conteinerização, além de demonstrar como a Engenharia de Prompts pode melhorar significativamente a qualidade das respostas geradas por Inteligência Artificial.

Este material servirá como referência para futuras implementações utilizando Docker em ambientes de desenvolvimento e infraestrutura.
