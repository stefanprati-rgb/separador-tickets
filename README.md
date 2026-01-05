# Separador de Tickets LDB 🎫

Ferramenta web para automação e normalização de planilhas de tickets (LDB). Processa arquivos Excel, separa dados por marca ("Brand"), corrige formatações e gera relatórios individuais e consolidados.

🔗 **Acesse a ferramenta online:** [Coloque aqui o link do seu GitHub Pages]

## 🚀 Funcionalidades (V14.1)

- **Processamento Local:** Tudo roda no navegador, garantindo segurança dos dados.
- **Normalização de EANs:**
  - Separa múltiplos EANs na mesma célula em novas linhas ("explosão de linhas").
  - Remove caracteres inválidos e corrige zeros à esquerda.
  - Converte EANs para formato numérico (evita notação científica `1E+13`).
- **Organização por Marca:** Gera um arquivo `.xlsx` separado para cada marca encontrada.
- **Base Geral:** Gera um arquivo mestre consolidado com todas as marcas tratadas.
- **Formatação Automática:**
  - Aplica cores condicionais baseadas no Status (Open, Closed, Handover, etc.).
  - Adiciona filtros no cabeçalho.
  - Fixa painel superior.
- **Dashboard Rápido:** Coluna com contagem automática (`CONT.SE`) de status.
- **Download Flexível:** Interface para baixar arquivos individuais ou um ZIP completo.

## 🛠️ Como Usar

1. Exporte a planilha LDB (Excel).
2. Acesse o link da ferramenta.
3. Clique em **"Carregar LDB"**.
4. Aguarde o processamento.
5. Escolha baixar os arquivos individuais ou o pacote ZIP.

## 📦 Tecnologias

- HTML5 / CSS3
- JavaScript (ES6+)
- [SheetJS](https://sheetjs.com/) (Manipulação de Excel)
- [JSZip](https://stuk.github.io/jszip/) (Compactação)
- [FileSaver.js](https://github.com/eligrey/FileSaver.js) (Download)

---
Desenvolvido para otimização de fluxo de tickets.
