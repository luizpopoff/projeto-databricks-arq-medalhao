# Projeto: Arquitetura Medalhão com Databricks, SQL e PySpark

Este projeto demonstra a implementação da **Arquitetura Medalhão (Medallion Architecture)** utilizando **Databricks**, **PySpark** e **SQL** para criar um pipeline de dados robusto e escalável. A solução segue as melhores práticas de engenharia de dados, organizando os dados em três camadas: **Bronze**, **Silver** e **Gold**, garantindo maior qualidade, acessibilidade e eficiência.

---

## 🔍 Visão Geral do Projeto
- **Objetivo**: Transformar dados brutos em um modelo estruturado, pronto para análises e dashboards interativos.
- **Tecnologias Utilizadas**:  
  - Databricks para orquestração do pipeline.  
  - PySpark e SQL para manipulação e transformação dos dados.  
  - Armazenamento em camadas (Data Lake).  
- **Desafios Resolvidos**:  
  - Normalização de dados inconsistentes.  
  - Otimização de consultas através de particionamento e formatação adequada (Parquet/Delta).  
  - Construção de pipelines escaláveis.

---

## 🛠️ Estrutura do Projeto
1. **Camada Bronze**:  
   - Dados brutos, ingeridos no formato original.  

2. **Camada Silver**:  
   - Limpeza, padronização e transformação dos dados.  

3. **Camada Gold**:  
   - Dados prontos para análise, agregações e cálculos específicos.

## 📂 Estrutura do Repositório
```plaintext
├── Notebook/               # Scipts
│   ├── bronze/             # Scripts para ingestão de dados brutos
│   ├── silver/             # Scripts para limpeza e transformação
│   ├── gold/               # Scripts para análises e resultados
├── Dados/                  # Dados do projeto
└── README.md               # Documentação do projeto
```

## Agradecimento  
  EmpregaDados
