README.md — DataInsight SST Dashboard Online (Extintores & Inspeções)
# 🔥 DataInsight SST — Dashboard Online (Extintores & Inspeções)

Este é um dashboard **100% em HTML + JavaScript (Chart.js)** para controle de **extintores, validade, risco e inspeções de SST**, funcionando totalmente **offline**, sem servidor, sem backend, sem instalação.

Perfeito para:

✅ Segurança do Trabalho  
✅ Gestores de manutenção  
✅ Escolas, fábricas, comércios  
✅ Apresentações, portfólio e GitHub Pages  

---

## ✅ Funcionalidades

- **Simulação instantânea** de extintores (100 itens aleatórios)
- **Importação de CSV real** (via FileReader)
- KPIs automáticos:
  - Total de equipamentos
  - Vencidos
  - Vencem em 30 dias
  - OK / dentro da validade
- **Gráfico de barras por área** (status)
- **Gráfico de pizza por risco** (baixo / moderado / alto)
- **Tabela dos TOP 15 itens mais críticos**
- Interface moderna (tema escuro, estilo DataInsight SST)
- Não precisa instalar nada — **abre no navegador**

---

## ✅ Como usar

### 1️⃣ Abrir o dashboard
Basta abrir o arquivo:



SST_Dashboard_Online.html


Duplo clique → abre no navegador.

---

## ✅ 2️⃣ Simular dados (para demonstração)

Clique no botão:



Simular dados (100 itens)


O dashboard gera automaticamente:

- Áreas (Bloco A, B, Lab etc)
- Tipos de extintor
- Pressão
- Data de validade
- Status (OK, 30 dias, vencido)
- Risco (baixo/moderado/alto)

👉 Ótimo para teste ou apresentação.

---

## ✅ 3️⃣ Importar CSV real

Clique em:



Carregar CSV


Use um arquivo com as colunas:

| Campo     | Exemplo        | Observação                     |
|-----------|----------------|--------------------------------|
| id        | EXT-001        | Código do equipamento          |
| area      | Laboratório    | Local / setor                  |
| tipo      | CO2            | Tipo do extintor               |
| validade  | 2025-03-10     | Formato: AAAA-MM-DD            |
| pressao   | 80             | Número de 0 a 100              |
| risco     | alto           | baixo / moderado / alto        |

### ✅ Exemplo de CSV (pronto para usar)



id,area,tipo,validade,pressao,risco
EXT-001,Bloco A,Pó ABC,2025-03-10,85,moderado
EXT-002,Refeitório,CO2,2024-12-05,70,alto
EXT-003,Administração,Água,2025-01-18,95,baixo
EXT-004,Laboratório,Pó ABC,2024-11-02,60,alto
EXT-005,Bloco B,CO2,2025-02-12,88,moderado
EXT-006,Ginásio,Água,2024-10-08,75,alto


✅ Você pode baixá-lo pronto aqui no repositório.

---

## ✅ Estrutura do projeto



SST_Dashboard_Online.html
exemplo_extintores.csv
README.md


---

## ✅ Personalização

Posso adaptar este dashboard para:

✅ EPI vencendo  
✅ Checklists NR-17  
✅ APR / matriz de risco  
✅ Acidentes / CAT  
✅ Indicadores de ergonomia  
✅ Versão multi-dashboard com menu  
✅ Integração com Google Sheets  
✅ Versão Streamlit / Python  

É só pedir!

---

## ✅ Publicação online (opcional)

### ✅ GitHub Pages
- Envie este HTML para um repositório
- Vá em *Settings → Pages*
- Escolha:
  - Branch: `main`
  - Folder: `/root`
- Link será criado automaticamente

### ✅ Netlify (1 clique)
Acesse:  
https://app.netlify.com/drop

Arraste o arquivo `.html` → PRONTO.

---

## ✅ Licença

MIT — uso livre, inclusive comercial.

---

## 👤 Autor
**Edson Gomes Braz**  
DataInsight SST — Engenharia, Dados e Segurança do Trabalho
