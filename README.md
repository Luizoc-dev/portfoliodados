# 📊 Análise Salarial – Projeto em Excel

> 📘 **Nota do Autor:**  
> Este projeto faz parte do meu processo de **aprendizado e prática em análise de dados**.  
> Ele foi desenvolvido com base em dados fictícios e tem como objetivo exercitar conceitos de **tratamento de dados**, **estatística descritiva** e **visualização no Excel**.  
> O trabalho pode conter **erros ou simplificações**, pois está em constante aprimoramento.  
> Feedbacks e sugestões são sempre bem-vindos! 🚀  

---

## 🧭 Objetivo  
O objetivo deste projeto é realizar uma **análise exploratória sobre um conjunto de dados salariais de funcionários fictícios**.  
O foco é identificar **padrões de remuneração**, **distribuição de gêneros**, **relações entre escolaridade e salário**, além das **diferenças entre setores**.  

---

## 🛠️ Etapas do Desenvolvimento  

O projeto foi desenvolvido em quatro etapas principais:

### 1️⃣ Tratamento dos Dados  
- Remoção de registros duplicados e inconsistentes.  
- Padronização das colunas e organização geral.  
- Criação de uma nova variável de **setor**, agrupando cargos semelhantes.  
Essa etapa garantiu uma base limpa e estruturada para as análises seguintes.  

### 2️⃣ Estatísticas Descritivas  
- Cálculo de métricas como **média, mínimo e máximo de idade e salário**.  
- Contagem de funcionários por **gênero** e **nível de graduação**.  
- Análise geral do perfil da força de trabalho.  

### 3️⃣ Tabelas Dinâmicas  
- Cruzamento de informações para identificar padrões mais específicos.  
- Análise da **média salarial por setor**, da **distribuição de gênero por área** e da **relação entre escolaridade e remuneração**.  

### 4️⃣ Visualização de Dados  
- Construção de **gráficos** para representar as principais métricas e resultados.  
- Tornar a análise visualmente clara e intuitiva para interpretação.  

---

## 📈 Principais Resultados e Insights  

### 🧩 Distribuição por Setor  
A maior parte dos colaboradores atua nos setores de **Tecnologia e Engenharia de Software**, totalizando cerca de **887 funcionários**.  
Em seguida, aparecem os setores de **Gestão/Liderança** e **Dados/Analytics**.  

#### 💰 Médias Salariais por Setor  
| Setor | Média Salarial |
|-------|----------------|
| Dados/Analytics | R$ 143.000 |
| Tecnologia/Engenharia | R$ 126.000 |
| Gestão/Liderança | R$ 115.000 |

Esses resultados mostram que as áreas técnicas e de gestão concentram **maior número de profissionais e maiores remunerações**, refletindo o valor estratégico dessas funções.  

---

### 👥 Distribuição de Gênero  
- **Homens:** 967 (54,1%)  
- **Mulheres:** 813 (45,9%)  
A diferença é de aproximadamente **17,3%**, demonstrando uma composição relativamente equilibrada entre os gêneros.  

A idade média é também muito próxima:  
- **Homens:** 36 anos  
- **Mulheres:** 35 anos  

---

### 🎓 Nível de Escolaridade  
| Nível | Quantidade |
|-------|-------------|
| Ensino Médio | 110 |
| Bacharelado | 768 |
| Mestrado | 568 |
| PhD | 341 |

Observa-se uma predominância de profissionais com **ensino superior e pós-graduação**, indicando uma **força de trabalho altamente qualificada** e diversa em formação.  

---

## 🧾 Conclusão  

A análise evidencia uma organização com perfil **técnico, qualificado e moderno**, concentrando profissionais nas áreas de **Tecnologia**, **Dados** e **Gestão**.  
Os **salários mais altos** estão associados a funções **estratégicas e especializadas**, e há **equilíbrio de gênero** e **homogeneidade etária** entre os colaboradores.  

De forma geral, o conjunto analisado reflete uma empresa com **força de trabalho jovem, diversa e altamente capacitada**, alinhada a um ambiente corporativo **competitivo e inovador**.  

---

## ⚙️ Ferramentas e Recursos Utilizados  
- **Microsoft Excel**  
- **Fórmulas utilizadas:**  
  - `MÉDIA`  
  - `MÍNIMO`  
  - `MÁXIMO`  
  - `CONT.SE`  
  - `SOMASES`  
  - `PROCV`  
- **Tabelas Dinâmicas**  
- **Gráficos:** Colunas, Pizza e Barras  

---

## 🗂️ Estrutura do Projeto  

```
📁 analise-salarial-excel/
├── 📄 README.md
├── 📊 Salary_Data.xlsx
├── 📁 documentos/
│   └── Esqueleto_documentacao.docx
├── 📁 imagens/
│   ├── funcionarios-por-setor.png
│   ├── media-salarial-por-setor.png
│   ├── distribuicao-de-genero.png
│   └── escolaridade-por-genero.png
└── 📁 dados/
    └── Salary_Data.csv
```

---

## 📚 Fonte dos Dados  
Os dados utilizados são **fictícios**, baseados em modelos de datasets públicos disponíveis no **Kaggle**, com adaptações para fins educacionais.  

---

**Autor:** *Anônimo – em aprendizado contínuo de Análise de Dados*  
📅 *Ano: 2025*  
🔗 *Ferramenta: Microsoft Excel*
