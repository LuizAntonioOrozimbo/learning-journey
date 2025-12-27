# journey-standard.md

Bem-vindo ao **Journey Standard** 👋
> **Padrão oficial para criação, organização e evolução de todos os Journeys**

Este documento faz parte central do ecossistema **Learning Journey** e representa o **padrão oficial** para criação, organização e evolução de todos os repositórios do tipo *journey*.

👉 AntesRecomenda-se a leitura do **[README principal do Learning Journey](./README.md)** antes de continuar.

Aqui não está apenas uma convenção de pastas ou nomes de arquivos.  
O **Journey Standard** define um **método de estudo**, uma identidade comum e uma forma consistente de transformar aprendizado em conhecimento organizado, rastreável e reaproveitável.

Este padrão nasceu da prática contínua, de decisões conscientes ao longo das Journeys e da necessidade real de manter clareza, progressão e controle em estudos de longo prazo.

Se você está iniciando uma nova journey, revisando uma existente ou buscando entender a lógica por trás do ecossistema, este é o **ponto de partida correto**.

---

## 🎯 Objetivo do Padrão

Garantir que todos os Journeys:

* Sigam uma **identidade comum**
* Tenham **progressão didática clara**
* Sejam fáceis de retomar no futuro
* Possam ser compreendidos por terceiros
* Evoluam sem perda de organização

---

## 🧠 Princípios Fundamentais

1. **Aprendizado progressivo**
   Nenhum conteúdo avançado antecede fundamentos sólidos.

2. **Organização faz parte do estudo**
   Estrutura, nomes e documentação também ensinam.

3. **Um método, múltiplas tecnologias**
   O que muda é o conteúdo, não o modelo.

4. **Pensado para o leitor futuro**
   Todo journey deve ser compreensível para quem chega do zero.

---

## 🗂 Estrutura Padrão de um Journey

```text
journey-name/
├── README.md
├── glossario.md
├── 00-templates/
├── 01-introducao/
├── 02-basico/
├── 03-intermediario/
├── 04-avancado/
├── 05-projetos/
├── 06-boas-praticas/
├── 07-testes/
└── 08-materiais/
```

> Nem todas as pastas precisam existir desde o início.
> A estrutura é **referência**, não obrigação imediata.

---

## 📁 Papel de Cada Pasta

### README.md

* Apresentação geral do journey
* Objetivos
* Estrutura
* Plano de estudo

### glossario.md

* Documento único e vivo
* Atualizado progressivamente
* Nunca apagado, apenas expandido
* Consulta rápida e revisão

### 00-templates/

* Templates reutilizáveis
* Estruturas-base
* Snippets recorrentes

### 01-introducao/

* Contexto da tecnologia
* Preparação de ambiente
* Conceitos iniciais

### 02-basico/

* Fundamentos essenciais
* Conceitos-chave

### 03-intermediario/

* Conexões entre conceitos
* Uso prático mais elaborado

### 04-avancado/

* Tópicos complexos
* Automação, otimização, padrões

### 05-projetos/

* Projetos aplicados
* Integração de conhecimentos

### 06-boas-praticas/

* Organização de código
* Tratamento de erros e logs
* Performance
* Padrões reutilizáveis
* Maturidade técnica

### 07-testes/

* Código experimental
* Provas de conceito
* Exploração livre

### 08-materiais/

* PDFs
* Links externos
* Artigos e guias oficiais
* Anotações de pesquisa

---

## 🧱 Estrutura Interna dos Módulos

Cada módulo principal deve conter um `README.md` explicando:

* O que será estudado
* O que se espera aprender ao final

### Exemplo de aulas

```text
02-basico/
├── README.md
├── aula-02.1/
│   ├── texto.md
│   └── exemplo-aula-02.1.ext
```

> A extensão do arquivo de exemplo depende da tecnologia do journey.

---

## ✍️ Padrão de Escrita das Aulas

* Linguagem clara e objetiva
* Markdown bem formatado
* Um conceito por vez
* Exemplos funcionais
* Evitar repetição de conteúdos já vistos

---

## 🧪 Testes e Projetos

### Testes (07-testes)

* Sem obrigação didática formal
* Espaço para errar e experimentar

### Projetos (05-projetos)

* Integram módulos anteriores
* Representam consolidação do aprendizado

---

## 🧭 Identidade Comum entre Journeys

Todos os journeys devem:

* Seguir este padrão
* Manter nomenclatura consistente
* Respeitar a progressão didática
* Utilizar templates quando aplicável

---

## 📋 Checklist — Criando um Novo Journey

Use esta lista ao iniciar qualquer journey:

* [ ] Criar repositório/pasta do journey
* [ ] Criar `README.md` com visão geral
* [ ] Criar `glossario.md`
* [ ] Criar `00-templates/` (se necessário)
* [ ] Criar `01-introducao/`
* [ ] Definir o escopo do `02-basico/`
* [ ] Respeitar progressão antes de avançar
* [ ] Atualizar glossário ao final das aulas
* [ ] Usar `07-testes/` sem medo
* [ ] Consolidar aprendizados em `05-projetos/`

---

## 🧠 Observação Final

Este padrão é um **documento vivo**.

Ele pode evoluir, desde que preserve:

* clareza
* organização
* progressão didática

Este padrão foi desenvolvido com o apoio do **ChatGPT** como ferramenta de estudo,
organização, revisão conceitual e documentação ao longo das journeys.

> "Método não limita — método sustenta."
