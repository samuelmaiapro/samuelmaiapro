# 👨‍💻 Samuel Maia | Analista de Dados & Especialista Cloud AWS

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Sobre Mim

Analista de Dados com formação em **Ciência de Dados** e especialização em **Cloud Computing AWS**. Tenho experiência em análise de dados, ETL, desenvolvimento de dashboards Power BI, queries SQL, automação com Python e implementação de soluções AWS. Sou apaixonado por transformar dados complexos em insights estratégicos para tomada de decisão.

**📍 Localização:** Fortaleza, CE  
**📧 E-mail:** smaia2@gmail.com  
**📱 Telefone:** (85) 98409-6353  
**🔗 LinkedIn:** [linkedin.com/in/samuelmaiapro](https://linkedin.com/in/samuelmaiapro)  
**🎯 PcD:** Hemiparesia direita - sem impacto em funções técnicas, total independência, laudo disponível (CID T90.5)

## 🚀 Projetos em Destaque

### 📈 [Análise de Vendas com Python](https://github.com/samuelmaiapro/analise-vendas-python)

**Objetivo:** Sistema completo de análise de dados de vendas para identificar tendências, métricas de performance e insights estratégicos.

**Tecnologias:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

**Principais Funcionalidades:**
- 📊 Análise exploratória de dados (EDA)
- 📈 Visualização de tendências de vendas
- 🔍 Identificação de produtos mais lucrativos
- 📅 Análise temporal e sazonalidade
- 🎯 Cálculo de KPIs de performance

**Exemplo de Código:**

```python
import pandas as pd
import matplotlib.pyplot as plt

class AnalisadorVendas:
    def __init__(self, caminho_dados):
        self.df = pd.read_csv(caminho_dados)
        self.df['data'] = pd.to_datetime(self.df['data'])

    def analise_mensal(self):
        """Analisa vendas por mês"""
        df_mensal = self.df.groupby(self.df['data'].dt.to_period('M')).agg({
            'valor': 'sum',
            'quantidade': 'sum',
            'cliente_id': 'nunique'
        })
        return df_mensal

    def gerar_relatorio(self):
        """Gera relatório completo de vendas"""
        relatorio = {
            'total_vendas': self.df['valor'].sum(),
            'media_diaria': self.df.groupby('data')['valor'].mean().mean(),
            'produto_mais_vendido': self.df['produto'].mode()[0],
            'crescimento_mensal': self.calcular_crescimento()
        }
        return relatorio

    def calcular_crescimento(self):
        pass
```

📁 **Estrutura do Projeto:**
```
analise-vendas-python/
├── data/              # Arquivos de dados
├── notebooks/         # Jupyter notebooks
├── src/               # Código fonte Python
├── outputs/           # Resultados e gráficos
└── README.md          # Documentação
```

🔗 **[Acesse o projeto completo aqui](https://github.com/samuelmaiapro/analise-vendas-python)**

## 🛠️ Habilidades Técnicas

### ☁️ Cloud Computing & Infraestrutura
- **AWS**: EC2, S3, Lambda, RDS, CloudFormation
- **Linux**: Administração de servidores, shell scripting
- **Segurança**: OPNsense, Pfsense, Zabbix, configuração de firewalls
- **Controle de Versão**: Git, Subversion

### 📊 Análise de Dados & BI
- **Power BI**: Dashboards interativos, DAX, Power Query
- **Excel Avançado**: VBA, Power Pivot, fórmulas complexas
- **Visualização**: Matplotlib, Seaborn, Plotly
- **Estatística**: Estatística descritiva e preditiva

### 💻 Programação & Automação
- **Python**: Pandas, NumPy, Scikit-learn, automação
- **SQL**: Consultas avançadas, otimização, stored procedures
- **Web**: PHP, Ruby, Apache configuration
- **ETL/ELT**: Pipeline de dados, transformações

### 🗄️ Bancos de Dados
- **Relacionais**: MySQL, MariaDB, Informix
- **Conceitos**: Normalização, indexação, transações

### 📋 Metodologias
- **Ágil**: Scrum, Kanban, sprints
- **Design Thinking**: Solução criativa de problemas
- **RPA**: Automação de processos repetitivos

## 💼 Experiência Profissional

### 📊 Analista de Dados | ¡9 Life (Jun 2015 - Jan 2019)
- Liderança de equipe com 100+ consultores comerciais
- Implementação de sistema de metas baseado em análise de dados
- Aumento de 15-20% na produtividade através de dashboards
- Expansão da base de clientes com análise de mercado

### 🔧 Supervisor de TI | Instituto de Tecnologia José Rocha (Mai 2007 - Mai 2009)
- Administração de infraestrutura Linux com Apache
- Gerenciamento de bancos de dados MySQL/Informix
- Automação de 70% das rotinas com scripts PHP/Ruby
- Implementação de soluções de segurança e monitoramento

### 🏦 Assistente de Atendimento | Banco Santander (Set 2009 - Abr 2013)
- Análise de perfil de clientes pessoa física e jurídica
- Cruzamento de dados para propostas personalizadas
- Reconhecimento por excelência no atendimento ao cliente

## 🎓 Formação & Certificações

### 🏫 Formação Acadêmica
- **Ciência de Dados** | Gran Faculdade (Cursando - 2026)
- **AWS Cloud Practitioner/Solutions Architect** | Escola da Nuvem (Cursando - 2026)
- **Inovação e Transformação Digital** | Gran Faculdade (Cursando - 2026)
- **Administração de Empresas** | FACULDADE FAEL (Concluído - 2024)

### 📜 Certificações
- **AWS Certified Cloud Practitioner** (Em processo - 2026)
- **Power BI – Do Básico ao Profissional** | Udemy (2025)
- **Python para Análise de Dados** | Udemy (2025)
- **SQL para Data Science** | Coursera (2025)

## 📈 Estatísticas do GitHub

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=samuelmaiapro&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="Samuel's GitHub stats" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=samuelmaiapro&layout=compact&theme=dark&hide_border=true&langs_count=6" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=samuelmaiapro&theme=dark&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=samuelmaiapro&color=blueviolet&style=flat-square" alt="Visualizações do perfil" />
  <a href="https://github.com/samuelmaiapro?tab=followers">
    <img src="https://img.shields.io/github/followers/samuelmaiapro?label=Seguidores&style=flat-square&color=green" alt="GitHub followers" />
  </a>
  <img src="https://img.shields.io/github/stars/samuelmaiapro?label=Estrelas&style=flat-square&color=yellow" alt="Total Stars" />
</div>

## 🌐 Idiomas
- **Português**: Nativo
- **Inglês**: B2 (Intermediário) - Técnico e comunicação
- **Espanhol**: B1 (Pré-Intermediário)

## 💪 Competências & Habilidades Profissionais

### 🔍 Pensamento Analítico & Técnico
- **Análise de Dados Estratégica**: Transformação de dados complexos em insights acionáveis
- **Diagnóstico de Problemas**: Identificação de padrões e oportunidades com abordagem analítica
- **Raciocínio Quantitativo**: Aplicação de estatística em cenários empresariais
- **Storytelling com Dados**: Comunicação técnica para públicos não-técnicos

### 🤝 Colaboração & Trabalho em Equipe
- **Sinergia Multidisciplinar**: Integração com equipes de negócio, TI e stakeholders
- **Metodologias Ágeis**: Experiência em Scrum e Kanban
- **Compartilhamento de Conhecimento**: Mentoria e documentação de processos
- **Resolução de Conflitos**: Mediação construtiva com foco em soluções

### 🎯 Resolução de Problemas Complexos
- **Abordagem Estruturada**: Aplicação de frameworks como 5 Porquês e PDCA
- **Pensamento Crítico**: Avaliação de múltiplas perspectivas
- **Criatividade Aplicada**: Soluções inovadoras para desafios técnicos
- **Gestão de Riscos**: Identificação proativa de obstáculos

### 💬 Comunicação & Influência
- **Comunicação Técnica**: Tradução de conceitos complexos para linguagem acessível
- **Apresentação Executiva**: Dashboards e relatórios para decisores estratégicos
- **Documentação Clara**: Manuais e tutoriais compreensíveis
- **Escrita Profissional**: Emails, propostas e relatórios com precisão

### 👨‍💼 Liderança & Gestão
- **Gestão de Equipes Multidisciplinares**: Coordenação de diferentes backgrounds
- **Delegação Efetiva**: Distribuição de tarefas conforme competências
- **Mentoria & Desenvolvimento**: Capacitação de talentos
- **Gestão de Projetos**: Planejamento e monitoramento de iniciativas

### 🔄 Adaptabilidade & Aprendizado Contínuo
- **Agilidade Tecnológica**: Rápida assimilação de novas ferramentas
- **Mindset de Crescimento**: Busca constante por atualização
- **Resiliência a Mudanças**: Adaptação a novos contextos
- **Autoaprendizagem**: Proatividade no estudo de tecnologias

### 🏆 Diferenciais Competitivos

| Competência | Nível | Aplicação Prática |
|------------|-------|-------------------|
| **Análise de Dados** | ⭐⭐⭐⭐⭐ | Aumento de 15-20% em produtividade |
| **Liderança** | ⭐⭐⭐⭐ | Gestão de equipe com 100+ consultores |
| **Resolução de Problemas** | ⭐⭐⭐⭐⭐ | Automação de 70% das rotinas |
| **Comunicação** | ⭐⭐⭐⭐ | Interface entre áreas técnicas e de negócio |
| **Adaptabilidade** | ⭐⭐⭐⭐⭐ | Transição para Cloud Computing AWS |

> "Competências são como músculos: desenvolvem-se com prática consistente e desafios progressivos."

## 📫 Vamos Conectar?

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/samuelmaiapro)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/samuelmaiapro)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:smaia2@gmail.com)

---

> ⭐ "Dados não são apenas números; são histórias esperando para serem contadas e problemas esperando para serem resolvidos."
> 
> 🔗 **Visite meus projetos para ver essas histórias em ação!** 
```