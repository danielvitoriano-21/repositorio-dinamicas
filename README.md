# 🔎 Guia de Busca no Repositório

Este repositório armazena dinâmicas organizadas como ativos reutilizáveis, estruturadas em:

* `habilidades técnicas`
* `habilidades interpessoais`

Cada dinâmica possui:

* `dinamica.md` (descrição detalhada)
* `metadata.yaml` (metadados estruturados)

A busca pode ser feita de duas formas:

1. 🔎 Busca Manual (GitHub Search)
2. 🤖 Busca Assistida por IA (Copilot)

---

# 🔎 Guia de Pesquisa Manual (Busca Textual)

A busca do GitHub é baseada em correspondência textual literal. Para melhores resultados, utilize os seguintes padrões:

---

## 🔹 Buscar por Tema

Exemplo:

```
requisitos
```

---

## 🔹 Restringir por Pasta

Buscar apenas em habilidades técnicas:

```
requisitos path:"habilidades técnicas"
```

Buscar apenas em habilidades interpessoais:

```
requisitos path:"habilidades interpessoais"
```

---

## 🔹 Buscar Apenas nos Metadados

```
requisitos path:**/metadata.yaml
```

---

## 🔹 Buscar por Nível de Complexidade

⚠ Deve ser feito como texto literal:

```
"nivel_complexidade: Medio" path:**/metadata.yaml
```

---

## 🔹 Buscar por Frase Exata

```
"Engenharia de Requisitos"
```

---

## 🔹 Estratégia Recomendada

Combinar termo + pasta + tipo de arquivo:

```
requisitos path:"habilidades técnicas" path:*.yaml
```

---

# 🤖 Guia para Fazer Perguntas ao Copilot

O Copilot permite recuperação semântica (conceitual), superando limitações da busca textual.

## 📌 Exemplos de Perguntas Eficientes

### 🔹 Perguntas Temáticas

* Liste todas as dinâmicas relacionadas a requisitos.
* Quais dinâmicas trabalham modelagem de processos?
* Quais dinâmicas são Soft Skills?

---

### 🔹 Perguntas com Filtro Implícito

* Liste dinâmicas de nível médio.
* Quais dinâmicas são aplicadas em Engenharia de Software?
* Liste dinâmicas com foco em análise.

---

### 🔹 Perguntas Estruturais

* Quais dinâmicas possuem licença CC-BY-4.0?
* Liste dinâmicas classificadas como Hard Skill.
* Existe alguma dinâmica de requisitos fora da pasta habilidades técnicas?

---

## 🎯 Boas Práticas ao Perguntar para a IA

✔ Seja específico
✔ Use termos do metadata (nível, categoria, tipo)
✔ Peça para listar ID e caminho do arquivo
✔ Solicite consolidação em tabela,  se necessário

---

# 📊 Diferença Entre Busca Manual e IA

| Busca Manual          | Copilot                      |
| --------------------- | ---------------------------- |
| Literal               | Semântica                    |
| Baseada em palavras   | Baseada em conceitos         |
| Exige sintaxe correta | Interpreta linguagem natural |
| Limitada              | Mais flexível                |

---

# 🧠 Recomendação Geral

Use:

* 🔎 Busca manual → quando souber o termo exato.
* 🤖 Copilot → quando precisar de interpretação conceitual ou análise.

## 📘 Documentação Complementar

- [Guia Completo de Busca](./GUIA-BUSCA.md)
- [Manual de Uso do Copilot](./MANUAL-COPILOT.md)
- [Documentação Técnica da POC](./DOCUMENTACAO-BUSCA.md)
