# Natural Language Processing To Query SQL

This work was development with goal to util the concepts of Natural Language Processing to convert an phrase from language natural more especificly in Portuguese to an query SQL. But, i made additions execution and answer too in language natural, forming an chain complete to interation between human and AI, conform image below:

![nl_to_sql](https://github.com/tiagosouzatfs/Natural_Language_Processing/blob/main/nl_to_sql.png)
Source: [Langchain](https://python.langchain.com/docs/tutorials/sql_qa/#%EF%B8%8F-security-note-%EF%B8%8F)

### For reproducte this work util next tecnologies:
- VSCode
- Python 3.10
- Ollama installed into your machine
- I used Ollama on version llama 3.1 (8B parameters), running localhost, on port 11434
- Optinally, Make your python virtual environment before install the libs

### Important!!!
#### Use resources of GPU to execute these work
#### If to need to util Colab, recommend change de environment to T4 GPU and follow the tutorial below:  
[Running Ollama in Google Colab](https://medium.com/@abonia/running-ollama-in-google-colab-free-tier-545609258453)

Was utilized the dataset with name [Estatisticas de transações Pix](https://github.com/tiagosouzatfs/Natural_Language_Processing/blob/main/estatisticas_transacoes_pix.xlsx) from open API from [Banco Central](https://olinda.bcb.gov.br/olinda/servico/Pix_DadosAbertos/versao/v1/aplicacao#!/recursos) which has the following description: Quantity and financial volume of Pix transactions settled monthly. Only for the month of November 2024.

Now, you is ready to execute the notebook: [pln](https://github.com/tiagosouzatfs/Natural_Language_Processing/blob/main/pln.ipynb)
