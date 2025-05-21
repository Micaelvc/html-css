Perfeito! Abaixo está um único arquivo `README.md` em **Markdown** unificando a descrição dos **dois códigos que você enviou**. O conteúdo está dividido em dois desafios: um sobre posicionamento com formas e ícones, e outro com posicionamento de imagens (corpo + chapéu).

---

```markdown
# 🧩 Desafios CSS - Position

Este repositório contém dois desafios práticos desenvolvidos com HTML e CSS para demonstrar o funcionamento da propriedade `position`. O objetivo é ajudar no aprendizado visual dos comportamentos de `static`, `relative`, `absolute`, `fixed` e `sticky`.

---

## 📁 Estrutura do Projeto

```

/
├── desafio-1/
│   ├── index.html
│   └── estilo.css
├── desafio-2/
│   ├── index.html
│   ├── estilo.css
│   └── img/
│       ├── corpo.png
│       └── chapeu-encaixe.png
└── README.md

````

---

## 🎯 Desafio 1 — Posições no Layout com Formas e Ícones

### 📄 Arquivo: `desafio-1/index.html`  
### 🎨 Estilo: `desafio-1/estilo.css`

Este desafio apresenta blocos coloridos e ícones posicionados de diversas formas para demonstrar:

- `position: static`
- `position: relative`
- `position: absolute`
- `position: fixed`
- `position: sticky`
- Uso de `z-index`

### 💡 O que é mostrado:

| Bloco | Posição | Descrição |
|-------|---------|-----------|
| `.quadrado` | `relative` | Quadrado azul com leve deslocamento |
| `.static`, `.relative`, `.fixed`, `.parado` | diversas posições | Blocos que mostram sobreposição e comportamento na rolagem |
| `.estrela`, `.coracao`, `.like`, `.raio` | `absolute` | Ícones com posição absoluta dentro de um container relativo |
| `.container-4` | `sticky` | Bloco que fica "grudado" no topo ao rolar a página |

---

## 🎯 Desafio 2 — Posicionamento de Imagens com `absolute`

### 📄 Arquivo: `desafio-2/index.html`  
### 🎨 Estilo: `desafio-2/estilo.css`  
### 🖼️ Imagens: `desafio-2/img/corpo.png`, `desafio-2/img/chapeu-encaixe.png`

Este desafio consiste em **encaixar um chapéu sobre uma imagem de corpo** usando `position: absolute`. Ele demonstra como alinhar elementos visuais com precisão dentro de um `container` posicionado como `relative`.

### 💡 Conceitos aplicados:

- `.container` define o contexto com `position: relative`.
- `.corpo` e `.chapeu` são posicionados com `absolute` para sobreposição precisa.
- Ajustes finos com `left`, `top`, `right`, e `bottom` são feitos para o alinhamento correto.

---

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/desafios-css-position.git
   cd desafios-css-position
````

2. Acesse cada pasta (`desafio-1/` e `desafio-2/`) e abra o `index.html` no navegador para visualizar.

---

## 📘 Aprendizados

* Diferença entre todos os tipos de `position` no CSS.
* Como o `z-index` controla a ordem dos elementos.
* Como usar `position: absolute` para sobrepor imagens com precisão.
* Como `sticky` mantém elementos fixos durante a rolagem.

---

## 📝 Licença

Projeto livre para uso educacional. Sinta-se à vontade para modificar, explorar e praticar!

```

Se você quiser, posso montar isso já com os diretórios organizados num `.zip`, ou gerar uma versão com preview visual (imagens demonstrativas ou GIFs). É só pedir!
```
