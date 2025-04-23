# DataWrangling_Cleaning

### Projeto de limpeza de dados para modelagem e estatisticas 

# Projeto de Data Wrangling and Cleaning 🧹📊

Este projeto foi desenvolvido com o objetivo de aplicar técnicas de limpeza, transformação e análise exploratória de dados usando a linguagem Python e a biblioteca Pandas. A base de dados utilizada contém informações sobre atletas, incluindo altura, peso, data de nascimento, gênero, país de origem e informações relacionadas a medalhas olímpicas.

---

## 📁 Estrutura do Projeto

O projeto segue as etapas clássicas de um processo de data wrangling e análise:

1. **Importação e Exploração Inicial**
   - Leitura de arquivos CSV e JSON
   - Inspeção dos dados (`.head()`, `.info()`, `.dtypes`)

2. **Limpeza e Conversão de Tipos**
   - Conversão de colunas como `birth_date` e `code`
   - Tratamento de valores nulos
   - Detecção e remoção de duplicatas

3. **Filtragem e Seleção de Dados**
   - Uso de filtros com `isin`, `&`, `|`, `~`
   - Seleção por condições específicas (ex: altura mínima)

4. **Análise Estatística e Agrupamentos**
   - Frequência de valores (`value_counts`, `mode`)
   - Agrupamentos por `country_full` e `gender` com média, mediana etc.

5. **Criação de Novas Colunas**
   - Conversão de altura para metros
   - Cálculo de IMC (Índice de Massa Corporal)
   - Cálculo de idade e identificação de maiores de idade

6. **Discretização de Variáveis**
   - Usando `pd.cut`, `pd.qcut` e intervalos personalizados

7. **Junção de Tabelas**
   - Merge de datasets com medalhas por código

8. **Análise de Strings**
   - Filtros por palavras-chave e prefixos em colunas textuais

9. **Tratamento de Dados Faltantes**
   - Remoção e preenchimento (`dropna`, `fillna`)
   - Análise percentual de colunas com muitos nulos

10. **Detecção de Outliers**
    - Visualização com boxplot e histograma
    - Cálculo de IQR e limites para identificação de outliers

---

## 📦 Bibliotecas Utilizadas

- `pandas`
- `datetime`
- `matplotlib`
- `chardet`

---

## 📈 Exemplos de Insights

- Distribuição de gênero entre atletas brasileiros.
- Países com maior média de altura e peso.
- Categorização de idade em faixas etárias.
- Relação entre atletas e medalhas conquistadas.
- Detecção de inconsistências e outliers nos dados de altura.

---

## 💡 Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git

2. Instale as bibliotecas necessárias:
   ```bash
   pip install -r requirements.txt

3. Execute o notebook em um ambiente como Jupyter, VS Code ou Google Colab.

## Observações
O projeto utiliza dados fictícios/anonimizados para fins de estudo.

Alguns arquivos exigem detecção de encoding para serem carregados corretamente.

Para gráficos e visualizações, recomenda-se usar Matplotlib.



🧑‍💻 Autor
Desenvolvido por Marcio Luiz - Conecte-se comigo no LinkedIn<https://www.linkedin.com/in/marcioluiz-multicloud/>