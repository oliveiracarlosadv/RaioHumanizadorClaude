---
name: Humanizador de Escrita de IA
version: 1.0.0
description: "Skill para identificar e remover padrões de escrita gerados por IA, baseada no guia Signs of AI Writing da Wikipédia."
---

# Humanizador de Escrita de IA

## Descrição
Esta skill identifica e remove padrões típicos de textos gerados por modelos de linguagem, reescrevendo-os de forma mais natural, humana e com personalidade.  
Baseada no guia "Signs of AI Writing" da Wikipédia (WikiProject AI Cleanup).

## Objetivo
Transformar textos com aparência artificial em versões mais humanas, naturais e com ritmo orgânico, preservando o significado original.

## Funcionalidades
- Detecção de padrões de escrita de IA  
- Reescrita humanizada  
- Auditoria final anti-IA  
- Preservação de tom e intenção  
- Injeção de personalidade e variação rítmica  

## Padrões que a skill remove
- Exagero de importância e legado  
- Linguagem promocional  
- Atribuições vagas  
- Vocabulário típico de IA  
- Estruturas formulaicas  
- Emojis, negrito excessivo, travessões demais  
- Hedging e frases de enchimento  
- Tom servil ou de chatbot  

## Processo de uso
1. O usuário fornece um texto.  
2. A skill identifica padrões artificiais.  
3. Gera um rascunho humanizado.  
4. Lista os sinais restantes de IA.  
5. Gera a versão final revisada.  

## Estrutura do pacote
- `index.html` — Super Prompt interativo  
- `SKILL.md` — Este arquivo  
- `README.md` — Instruções gerais  

## Observação
Este pacote deve ser distribuído em um arquivo ZIP contendo obrigatoriamente o arquivo `SKILL.md`.
