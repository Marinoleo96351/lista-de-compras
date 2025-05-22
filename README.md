# 🛒 Lista de Compras

Aplicação web simples e funcional para gerenciamento de uma lista de compras. Os usuários podem adicionar itens, marcá-los como comprados e visualizar a data e hora de inserção. O projeto é modularizado em arquivos JavaScript separados para facilitar manutenção e reutilização de código.

---

## ✨ Funcionalidades

- ✅ Adição de itens à lista
- 🚫 Validação para evitar itens em branco
- ⏰ Registro de data e hora ao adicionar um item
- ✔️ Marcação de itens como comprados (com efeito visual de riscado)
- 📭 Exibição de mensagem quando a lista estiver vazia
- 📁 Organização modular do código em arquivos separados

---

## 🧪 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
  - Módulos ES6 para separação de responsabilidades

---
## 🗂 Estrutura de Arquivos

```
📁 lista-de-compras/
├── 📁 scripts/
│   ├── criarItemDaLista.js         # Função para criar e configurar novos itens da lista
│   ├── gerarDiaDaSemana.js         # Função para gerar a data e hora formatada
│   └── verificarListaVazia.js      # Função para exibir ou ocultar a mensagem de lista vazia
├── index.html                      # Estrutura principal da interface
├── index.js                        # Script principal que integra os módulos
├── styles.css                      # Estilos da aplicação
└── README.md                       # Documentação do projeto
```

---

## 🧩 Possíveis melhorias

- [ ] Salvar itens usando `localStorage` para manter a lista entre sessões
- [ ] Adicionar botão para remover itens
- [ ] Filtros (todos, comprados, pendentes)
- [ ] Tema escuro/claro (modo noturno)

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

Desenvolvido por [Leonardo Marino Scarparo Silva](https://github.com/seu-usuario)(acompanhado por um curso da Alura)

