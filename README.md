
# 🗡️ Jogo de Combate em Turnos (Python)

Projeto simples de um jogo de combate em turnos feito em Python, com foco em praticar conceitos de Programação Orientada a Objetos (POO).

## 🚀 Funcionalidades

- Sistema de batalha em turnos  
- Ataque normal e ataque especial  
- Vida dinâmica dos personagens  
- Exibição de status (vida, nível, etc.)  
- Limpeza de tela a cada turno (melhora a visualização no terminal)  

## 🧠 Conceitos aplicados

- Classes e objetos  
- Herança (`Heroi` e `Inimigo` herdando de `Personagem`)  
- Encapsulamento (uso de atributos privados com `__`)  
- Métodos getters (`get_...`)  
- Polimorfismo (`exibir_detalhes` sobrescrito)  
- Uso de `random` para cálculo de dano  

## 🏗️ Estrutura do projeto

- `Personagem` → classe base com atributos comuns (nome, vida, nível)  
- `Heroi` → possui habilidade especial  
- `Inimigo` → possui tipo  
- `Jogo` → controla o fluxo da batalha  

## 🎮 Como jogar

* Pressione Enter para iniciar cada turno
* Escolha:

  * `1` → Ataque normal
  * `2` → Ataque especial
* A batalha continua até um dos personagens chegar a 0 de vida

## 💡 Melhorias futuras

* Barra de vida visual (ex: █████░░)
* Sistema de múltiplos inimigos
* Sistema de experiência e evolução de nível
* Interface gráfica (Tkinter ou Web)

## 👨‍💻 Autor

Gustavo Felipe
```
```

