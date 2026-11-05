---
layout: default
title: "Olá, mundo!"
date: 2026-11-05
tags: [geral, pessoal]
---

Primeiro post só pra testar.

<!--more-->

---

## 🧭 TESTE

# Títulos

# Título 1 
## Título 2 
### Título 3 
#### Título 4
##### Título 5
###### Título 6

# Estilização de Texto

**Texto em negrito**
*Texto em itálico* ou _assim_
***Texto em negrito e itálico***
~~Texto tachado / riscado~~
Texto normal com `código inline` no meio da frase.

# Blocos de Códigos

```bash
# Comandos de terminal
nmap -p- -T4 10.10.10.X
whoami
```

# Lista não ordenada (Marcadores):

- Item 1
- Item 2
  - Subitem 2.1 (dê 2 espaços antes do hífen)
  - Subitem 2.2
* Também dá pra usar asterisco
+ Ou sinal de mais

# Lista ordenada (Numerada):

1. Primeiro passo
2. Segundo passo
3. Terceiro passo

# Lista de tarefas (Checklist):

- [x] Tarefa concluída
- [ ] Tarefa pendente
- [ ] Outra tarefa pendente

# Links e Imagens

<!-- Link normal -->
[Nome que aparece no link](https://google.com)

<!-- Link que abre em nova aba (se o blog suportar) ou link com título -->
[Meu GitHub](https://github.com "Acessar GitHub")

<!-- Imagem -->
![Texto alternativo da imagem](https://site.com/caminho-da-imagem.png)

<!-- Imagem com caminho local (como no Jekyll/Hugo) -->
![Scan do Nmap](/assets/img/nmap-scan.png)

# Citações

> Isso é uma citação ou uma nota de destaque.
> Dá pra fazer em várias linhas.
>> TESTE.

# Divisores Horizontais

---
teste1
***
teste2
___

# Tabelas

| Porta | Serviço | Vulnerabilidade |
| :--- | :---: | ---: |
| 80/tcp | HTTP | SQLi (Alinhado à esquerda) |
| 22/tcp | SSH | Nenhuma (Centralizado) |
| 445/tcp| SMB | EternalBlue (Alinhado à direita) |

# HTML TESTE

<!-- Quebra de linha forçada -->
Primeira linha<br>Segunda linha

<!-- Texto sublinhado -->
<u>Texto sublinhado</u>

<!-- Texto pequeno ou nota de rodapé -->
<small>* Nota: Testado no Linux Debian 12.</small>

<!-- Detalhes retráteis (Accordion) -->
<details>
  <summary>Clique para ver a resposta / payload</summary>
  <code>' OR 1=1 -- -</code>
</details>