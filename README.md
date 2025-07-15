* **`data/`**: Contém os conjuntos de dados brutos e originais fornecidos. **Estes arquivos não devem ser modificados.**
    * `base_case_analista_pesquisa_pleno_1.xlsx - base completa.csv`: O dataset principal com os dados do NPS.
    * `base_case_analista_pesquisa_pleno_1.xlsx - Descritivo das colunas.csv`: Um arquivo que descreve as colunas presentes na base de dados principal.
* **`data/processed/`**:Dados que foram processador ou gerados como resultado das etapas de ETL.
* **`notebooks/`**: Contém os notebooks Jupyter que documentam a análise de dados e a visualização.
    * `case_sicredi_v0.ipynb`: O notebook principal contendo o código para a análise de sentimentos e o desenvolvimento da base completa.
* **`README.md`**: Este arquivo, fornecendo uma visão geral do projeto.

## Como Usar

Para replicar ou estender esta análise, siga os passos abaixo:

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/SEU_USUARIO/analise-nps-sicredi.git](https://github.com/SEU_USUARIO/analise-nps-sicredi.git) # Substitua SEU_USUARIO e analise-nps-sicredi
    cd analise-nps-sicredi
    ```

2.  **Instale as Dependências (Python):**
    É altamente recomendável usar um ambiente virtual.
    ```bash
    # Crie um ambiente virtual (se ainda não tiver um)
    python -m venv venv
    # Ative o ambiente virtual
    # No Windows:
    # venv\Scripts\activate
    # No macOS/Linux:
    # source venv/bin/activate
    # Instale as bibliotecas necessárias 
    pip install pandas numpy matplotlib seaborn jupyter
    ```

3.  **Execute o Notebook:**
    Abra o notebook `case_sicredi_v0.ipynb` usando Jupyter Lab ou Jupyter Notebook:
    ```bash
    jupyter notebook notebooks/case_sicredi_v0.ipynb
    # ou
    jupyter lab notebooks/case_sicredi_v0.ipynb
    ```
    Execute as células sequencialmente para replicar a análise.

## Tecnologias Utilizadas

* Python 3.x
* Jupyter Notebook
* Bibliotecas Python Pandas, NumPy, Matplotlib, Seaborn

---

**Autor:** Matheus Fay Soares
**E-mail:** mfaysoares@gmail.com
**Data:** Julho de 2025
