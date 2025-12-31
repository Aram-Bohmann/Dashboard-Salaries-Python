# 📊 Dashboard Interativo - Salários em Ciência de Dados

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/)
[![Live Demo](https://img.shields.io/badge/Live_Demo-Online-success?style=for-the-badge)](https://dashboard-salaries-python-2025-aram.streamlit.app)

> **Dashboard analítico interativo para exploração do mercado de trabalho em Ciência de Dados**  
> Desenvolvido na Imersão Dados com Python - Alura (2025)

Análise exploratória completa de salários globais na área de dados, com filtros dinâmicos, KPIs automatizados e visualizações interativas. Ferramenta web para profissionais de dados entenderem tendências salariais por país, cargo, senioridade e modalidade de trabalho.

---

## 📖 Sobre o Projeto

Dashboard interativo desenvolvido em **Python** com **Streamlit** para análise exploratória do mercado de trabalho em Ciência de Dados. A aplicação permite que profissionais, recrutadores e estudantes da área explorem:

- 💰 **Tendências salariais** por cargo e região
- 🌍 **Comparações internacionais** de remuneração
- 📈 **Evolução temporal** do mercado
- 🏢 **Diferenças por porte** de empresa
- 🏠 **Impacto do trabalho remoto** nos salários

### 🎯 Objetivo

Democratizar o acesso a insights sobre remuneração em dados através de uma interface visual, intuitiva e gratuita.

---

## ✨ Principais Funcionalidades

### 🔍 Filtros Interativos

<details>
<summary><b>4 Dimensões de Análise</b></summary>

1. **📅 Ano** - Evolução temporal (2020-2024)
2. **🎓 Nível de Senioridade** - Entry-level, Mid-level, Senior, Executive
3. **💼 Tipo de Contrato** - Full-time, Part-time, Freelance, Contract
4. **🏢 Tamanho da Empresa** - Small, Medium, Large

</details>

### 📊 KPIs Automáticos

Dashboard com **4 indicadores-chave** calculados dinamicamente:

| KPI | Descrição | Atualização |
|-----|-----------|-------------|
| 💵 **Salário Médio** | Média aritmética dos salários filtrados | Em tempo real |
| 🔝 **Salário Máximo** | Maior remuneração identificada | Em tempo real |
| 📈 **Total de Registros** | Quantidade de observações no filtro | Em tempo real |
| 👔 **Cargo Mais Frequente** | Posição com mais ocorrências | Em tempo real |

### 📊 Visualizações Interativas (Plotly)

#### 1️⃣ Top 10 Cargos por Salário Médio
- Gráfico de barras horizontal
- Ordenado por remuneração decrescente
- Hover com detalhes de cada cargo

#### 2️⃣ Distribuição Salarial
- Histograma de frequências
- Identificação de concentração de salários
- Visualização de outliers

#### 3️⃣ Modalidades de Trabalho
- Gráfico de pizza/donut
- Proporção: Remoto vs Híbrido vs Presencial
- Percentuais dinâmicos

#### 4️⃣ Mapa Mundial - Salário de Data Scientists
- Choropleth interativo
- Salário médio por país
- Zoom e exploração geográfica
- Gradiente de cores por faixa salarial

### 📋 Tabela de Dados Detalhada

- Visualização completa dos dados filtrados
- Ordenação por colunas
- Busca e navegação
- Download em CSV

---

## 🖼️ Demonstração Visual

### Interface Principal

<p align="center">
  <img width="900" alt="Dashboard Principal" src="https://github.com/user-attachments/assets/bbb68563-8dee-43b4-bec9-58d4dbe8ed3e" />
</p>

**Funcionalidades visíveis:**
- ✅ Barra lateral com filtros
- ✅ KPIs em destaque
- ✅ Gráficos interativos lado a lado
- ✅ Design responsivo e profissional

### Visualizações Detalhadas

<p align="center">
  <img width="900" alt="Gráficos e Mapa" src="https://github.com/user-attachments/assets/66414f61-96b7-4c87-adcc-644db52233f5" />
</p>

**Destaques:**
- ✅ Mapa mundial interativo
- ✅ Distribuição salarial clara
- ✅ Gráficos com hover tooltips
- ✅ Cores e layout profissionais

---

## 🚀 Acesso ao Dashboard

### 🌐 Versão Online (Streamlit Cloud)

**Acesse agora:** [dashboard-salaries-python-2025-aram.streamlit.app](https://dashboard-salaries-python-2025-aram.streamlit.app)

✅ **Sem instalação necessária**  
✅ **Gratuito e sempre disponível**  
✅ **Atualizado automaticamente**  
✅ **Responsivo (mobile-friendly)**  

---

## 🛠️ Stack Tecnológica

### Core
![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

### Análise de Dados
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

### Visualização
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square)

### Desenvolvimento
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📊 Dataset

### Fonte de Dados

**Dataset:** Salários em Ciência de Dados (2020-2024)  
**Origem:** Kaggle / AI Jobs  
**Registros:** ~10.000 observações  
**Período:** 2020-2024  

### Variáveis do Dataset

| Coluna | Tipo | Descrição |
|--------|------|-----------|
| `work_year` | Integer | Ano da observação |
| `job_title` | String | Cargo/Posição |
| `salary_in_usd` | Float | Salário anual em USD |
| `experience_level` | String | Nível de experiência (EN/MI/SE/EX) |
| `employment_type` | String | Tipo de contrato (FT/PT/FL/CT) |
| `company_size` | String | Porte da empresa (S/M/L) |
| `company_location` | String | País da empresa (ISO code) |
| `remote_ratio` | Integer | % trabalho remoto (0/50/100) |

### Pré-processamento

✅ Remoção de valores ausentes  
✅ Conversão de moedas para USD  
✅ Normalização de nomes de cargos  
✅ Categorização de níveis de senioridade  
✅ Mapeamento de códigos ISO de países  

---

## 💡 Insights Principais

### 📈 Tendências Identificadas

#### Salários Globais
- 💰 **Média global:** $120.000/ano
- 🔝 **Cargos mais bem pagos:** ML Engineer, Data Architect
- 🌍 **Top 3 países:** USA, Suíça, Israel

#### Senioridade
- 🎓 **Entry-level:** $60k-80k
- 👔 **Mid-level:** $90k-120k
- 🏆 **Senior:** $130k-170k
- 💼 **Executive:** $180k-250k+

#### Trabalho Remoto
- 🏠 **100% remoto:** +15% no salário médio
- 🏢 **Presencial:** Salários 10% menores
- 🔄 **Híbrido:** Equilibrado

#### Porte da Empresa
- 🏢 **Large:** Salários 20% maiores
- 🏭 **Medium:** Competitivos
- 🏪 **Small:** Menor média, mas maior variação

---

## 🎓 Contexto Acadêmico

### Imersão Dados com Python - Alura

**Programa:** Imersão Dados  
**Plataforma:** Alura  
**Ano:** 2025  
**Duração:** 4 horas  

### Competências Desenvolvidas

1. **📊 Análise Exploratória** - EDA com Pandas
2. **📈 Visualização Interativa** - Plotly avançado
3. **🎨 UI/UX** - Design de dashboards
4. **🚀 Deploy** - Streamlit Cloud
5. **📝 Storytelling** - Narrativa com dados
6. **💻 Python Aplicado** - Código limpo e modular

---

## 🚀 Melhorias Futuras

### Roadmap

#### Curto Prazo (1-2 meses)
- [ ] **Comparador de salários** - "Quanto eu deveria ganhar?"
- [ ] **Filtro por tecnologias** - Python, R, SQL, etc.
- [ ] **Previsão salarial** - Modelo ML integrado
- [ ] **Download de relatórios** - PDF customizado

#### Médio Prazo (3-6 meses)
- [ ] **Autenticação** - Perfis de usuário
- [ ] **Salvar análises** - Histórico personalizado
- [ ] **API REST** - Dados programáticos
- [ ] **Multi-idioma** - PT, EN, ES

#### Longo Prazo (6-12 meses)
- [ ] **Dados em tempo real** - Scraping automatizado
- [ ] **Comparação com inflação** - Poder de compra
- [ ] **Análise preditiva** - Tendências futuras
- [ ] **Versão mobile** - App nativo

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Este é um projeto open-source.

### Como Contribuir

1. Fork o projeto
2. Crie uma branch (`git checkout -b feature/melhoria`)
3. Commit suas mudanças (`git commit -m 'Adiciona feature X'`)
4. Push para a branch (`git push origin feature/melhoria`)
5. Abra um Pull Request

### Áreas de Contribuição

- 📊 **Novas visualizações** - Gráficos adicionais
- 🔍 **Filtros extras** - Mais dimensões de análise
- 🤖 **Machine Learning** - Modelos preditivos
- 📝 **Documentação** - Melhorias no README
- 🐛 **Bugs** - Correções e otimizações

---

## 📝 Licença

Este projeto foi desenvolvido para fins **educacionais** e está disponível para:

✅ Uso pessoal e profissional  
✅ Modificação e adaptação  
✅ Distribuição com créditos  
✅ Uso em portfolio  

---

## 📞 Contato

**Desenvolvedor:** Aram Bohmann Leite da Luz

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arambohmannleitedaluz@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aram-luz-1b0ab1321)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Aram-Bohmann)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://aram-bohmann.github.io/Site-Portfolio/)

---

## 🙏 Agradecimentos

- **Alura** - Pela Imersão Dados com Python
- **Streamlit** - Framework incrível para dashboards
- **Plotly** - Visualizações interativas profissionais
- **Kaggle** - Dataset de qualidade
- **Comunidade Python** - Ferramentas open-source

---

## 📚 Referências

- [Streamlit Documentation](https://docs.streamlit.io/)
- [Plotly Python](https://plotly.com/python/)
- [Pandas User Guide](https://pandas.pydata.org/docs/)
- [Data Visualization Best Practices](https://www.storytellingwithdata.com/)

---

<div align="center">

### ⭐ Se este projeto foi útil para você, considere dar uma estrela!

**Desenvolvido com 💙 e 📊 na Imersão Alura 2025**

*"Dados visualizados são insights democratizados"*

[🚀 **Acesse o Dashboard Agora**](https://dashboard-salaries-python-2025-aram.streamlit.app)

</div>
