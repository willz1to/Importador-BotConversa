# ⚡ Importador BotConversa

Ferramenta gratuita e open source para importar relatórios em planilha, tratar os dados e exportar no formato pronto para importação no **BotConversa** — tudo direto no navegador, sem instalar nada.

🔗 **[Acessar a ferramenta](https://willz1to.github.io/Importador-BotConversa/)**

---

## ✨ Funcionalidades

- 📂 Importa arquivos **.xlsx, .xls e .csv**
- 🗂 Mapeamento de colunas flexível — funciona com **qualquer formato de planilha**
- ✏ Edição de etiquetas antes de exportar — adicione, remova ou renomeie
- 🗑 Gerenciamento global de etiquetas — remova uma etiqueta específica ou limpe todas de uma vez
- 📤 Exporta em **.xlsx ou .csv** no formato BotConversa
- 🔒 **100% local** — nenhum dado é enviado para a internet
- 💻 Sem instalação — abre direto no navegador

---

## 🚀 Como usar

### 1. Importar arquivo
Arraste seu arquivo de relatório (.xlsx, .xls ou .csv) para a área de upload, ou clique para selecionar.

### 2. Mapear colunas
Indique qual coluna corresponde a **Nome** e **Telefone** (obrigatórios) e, opcionalmente, uma coluna para **Etiquetas**. Use o botão **Limpar Seleção** para reiniciar as escolhas.

### 3. Revisar & Editar etiquetas
- Clique no **+** para adicionar uma etiqueta — aplique só na linha ou em todas
- Clique no **×** para remover uma etiqueta
- **Duplo clique** em uma etiqueta para renomear
- Pressione **Delete** com a célula selecionada para limpar todas as etiquetas da linha
- Use **🗑 Gerenciar Etiquetas** na toolbar para remover uma etiqueta específica de todos os registros ou limpar tudo de uma vez

### 4. Exportar
Visualize a prévia dos dados e baixe o arquivo no formato BotConversa em **.xlsx** ou **.csv**. Telefones múltiplos separados por `/` são automaticamente divididos em linhas individuais.

---

## 📋 Formato de saída

O arquivo exportado segue o padrão de importação do BotConversa:

| Primeiro Nome | Sobrenome | Telefone | Etiquetas |
|---|---|---|---|
| João | Silva | 5511999999999 | Efetivo |
| Maria | Souza | 5511888888888 | Efetivo , Adimplente |

**Regras aplicadas automaticamente:**
- Nome dividido em Primeiro Nome + Sobrenome
- Telefone com apenas números (sem traços, parênteses ou espaços)
- Múltiplas etiquetas na mesma célula separadas por ` , `
- Um telefone por linha (múltiplos separados por `/` geram linhas individuais)

---

## 🛠 Tecnologias

- HTML5 + CSS3 + JavaScript puro
- [SheetJS (xlsx)](https://sheetjs.com/) para leitura e escrita de planilhas
- Sem frameworks, sem dependências externas além da biblioteca de planilhas
- Sem backend — tudo processado localmente no navegador

---

## 📁 Estrutura do projeto

```
importador-botconversa/
└── index.html   # Aplicação completa em arquivo único
```

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Se encontrar um bug ou tiver sugestão de melhoria:

1. Abra uma [Issue](../../issues) descrevendo o problema ou sugestão
2. Ou faça um fork, aplique suas alterações e abra um Pull Request

---

## 💬 Suporte

Dúvidas ou problemas? Entre em contato:

**William Luiz de Souza**
📧 [E-mail](mailto:william.26@hotmail.com)

---

## 📄 Licença

Este projeto é distribuído sob a licença [MIT](LICENSE) — livre para usar, modificar e distribuir.
