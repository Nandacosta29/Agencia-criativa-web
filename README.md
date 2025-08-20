# 🎨 Agência Criativa Web — Refatoração com SASS

## 📌 Objetivo
Refatorar o CSS do projeto **Agência Criativa Web**, aplicando os conceitos aprendidos no módulo de **SASS**.  
O foco é transformar o CSS tradicional em um projeto **organizado, modular e escalável**, utilizando:

- Partials  
- Variáveis  
- Mixins  
- Aninhamento  
- Operadores  
- Metodologia **BEM**

---

## 🛠 Requisitos da Atividade

### 1. Estrutura com Partials
Organizar o código em múltiplos arquivos dentro da pasta `scss/`:

- `_base.scss` → estilos base (body, tipografia, reset)  
- `_variaveis.scss` → cores, espaçamentos, fontes  
- `_mixins.scss` → estilos reutilizáveis  
- `_layout.scss` → estrutura geral da página  
- `_componentes.scss` → botões, cards, menus, etc.  
- `estilos.scss` → arquivo principal que importa os demais com `@use`

---

### 2. Uso de Variáveis e Mixins
- Criar variáveis para **cores, espaçamentos, fontes e tamanhos**.  
- Criar **pelo menos 2 mixins reutilizáveis** (ex.: espaçamentos padrão, botão básico).  
- Utilizar **operadores** para cálculos proporcionais:  
  ```scss
  margin-bottom: calc($espacamento / 2);
