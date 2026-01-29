# Natural ou Fake Natty? Como Vencer na Era das IAs Generativas

## 🚀 Introdução

Woooow. Olha isso 👀

Olá pessoal. Estou participando do Lab **Natty or Not**, da DIO. A ideia é brincar com o conceito do fisiculturismo. “Parece natural ou é claramente editado”. E trazer isso para o universo das **IAs Generativas**.

Aqui o desafio não é só “usar IA”. É usar IA com intenção, com critério, e entregar algo que fique o mais **natural, coerente e útil** possível. No fim, o que vale é o resultado. Serve para alguém? Facilita uma decisão? Ajuda a executar melhor?

---

## 🎯 Bora pro desafio. Você já venceu 💪🤓

### Objetivos

**Explorar IAs Generativas**
Usar IA para criar conteúdo com aparência realista e aplicável no mundo real. Pode ser texto, imagem, áudio, vídeo, ou uma mistura de tudo.

**Portfólio de Projetos**
Fazer o fork do repositório base do Lab. Atualizar o README seguindo o template. Submeter o link do repositório na plataforma da DIO.

**Efeito de rede**
Compartilhar o resultado nas redes com a hashtag **#LabDIONattyOrNot** e marcar a DIO.

---

# Meeting2Decisions. Transforme reuniões em execução

## 📒 Descrição

O **Meeting2Decisions** é um app criado no **AWS PartyRock** para transformar um resumo de reunião em um plano de execução.

Ele faz duas coisas muito bem. Extrai do texto o que realmente importa, decisões, ações, riscos e pendências. Converte tudo em **JSON estruturado**, pronto para ser reutilizado em checklists e acompanhamento.

Em vez de terminar com “ata”, a reunião termina com clareza de execução.

---

## 🤖 Tecnologias Utilizadas

* **AWS PartyRock** (criação do app e interface)
* **Amazon Bedrock** (modelo LLM usado nos widgets AI Output)
* Widgets PartyRock:

  * Text Input (Resumo da reunião, Contexto)
  * AI Output (ExtractJSON, TabelaAcoes, ChecklistFollowUp)

---

## 🧐 Processo de Criação

1. Criei dois campos de entrada: **Resumo da reunião** e **Contexto**
2. Modelei um bloco principal, **ExtractJSON**, para gerar uma saída estruturada e consistente
3. Defini regras rígidas para evitar invenção, incluindo a regra do **“A DEFINIR”** quando faltar dono, prazo, prioridade ou dependências
4. Reaproveitei o JSON em outros blocos para gerar:

   * Uma visão organizada por tipo (decisões, ações, riscos e pendências)
   * Um checklist de follow up, com foco em execução nas próximas 24 horas
5. Ajustei os prompts para manter linguagem profissional, direta e acionável. E para reduzir duplicidade de itens

---

## 🚀 Resultados

O app gera:

* **JSON válido**, com decisões, ações, riscos e pendências
* **Lista de acompanhamento**, organizada por tipo
* **Checklist de follow up**, pronto para usar no mesmo dia e nas próximas 24 horas

Exemplos de valor prático:

* Sair da reunião com dono, prazo e prioridade mais claros
* Reduzir retrabalho e desalinhamento
* Expor lacunas imediatamente, tudo que ficou “A DEFINIR”

---

## 💭 Reflexão (Natural ou Fake Natty?)

O mais difícil não foi “gerar texto bonito”. Foi gerar algo confiável.

Quando você usa IA para execução, qualquer detalhe inventado vira risco real. Por isso eu tratei o JSON como “fonte da verdade”, exigi evidência curta por item e forcei a regra do “A DEFINIR”. Isso deixa a saída mais honesta, mais útil e mais próxima do “natty” de verdade.

---

## 🔗 Link

* App no PartyRock: (https://partyrock.aws/u/gabrielsantarosa/Z0Mqknra-/Meeting2Decisions)
