# 🧾 Validador Automático de Notas Fiscais (NF-e)

Este projeto é um **sistema em Python (feito pelo Google Colab) para validação e análise automática de Notas Fiscais eletrônicas (NF-e)** a partir de arquivos XML. Ele foi desenvolvido com foco em **automação, organização de dados fiscais e apoio à análise operacional**, reduzindo tarefas manuais e aumentando a confiabilidade das informações.

---

## 🚀 Funcionalidades

* 📂 Leitura automática de arquivos **XML de NF-e**
* 🔍 Extração dos principais dados fiscais:

  * Número da NF
  * Data de emissão
  * Valor total
  * Emitente
  * Destinatário
  * Chave de acesso
    
* 📊 Geração de **gráfico** para visualização dos valores das NFs
* 📄 Exportação automática dos dados para:

  * Arquivo **CSV**
  * Arquivo **Excel (.xlsx)**

---

## 🛠️ Tecnologias Utilizadas

* **Python**
* `xml.etree.ElementTree` – leitura e parsing do XML
* `pandas` – estruturação e exportação dos dados
* `matplotlib` – visualização gráfica
* `openpyxl` – geração do arquivo Excel

---

## 📈 Exemplo de Saídas Geradas

* 📊 Gráfico com o valor total das Notas Fiscais
* 📁 `notas_fiscais.csv`
* 📁 `notas_fiscais.xlsx`

Esses arquivos permitem análise rápida, auditoria e integração com outros processos de dados.

---

## ▶️ Como Utilizar

1. Clone o repositório:

```bash
git clone https://github.com/joaodddev/validador-nfe-python.git
```

2. Acesse a pasta do projeto:

```bash
cd validador-automatico-nfs-python
```

3. Instale as dependências (se necessário):

```bash
pip install pandas matplotlib openpyxl
```

4. Insira os arquivos XML de NF-e no diretório configurado no código

5. Execute o script:

```bash
python validador_automatico_de_notas_fiscais_(csv).py
```

---

## 🎯 Objetivo do Projeto

Este projeto foi criado com o objetivo de:

* Automatizar a validação de documentos fiscais
* Facilitar a análise de dados de NF-e
* Reduzir erros manuais no tratamento de informações fiscais
* Servir como **projeto de portfólio** voltado a dados, automação e processos fiscais

---

## 📌 Próximos Passos (Melhorias Futuras)

* Validação de layout da NF-e (schema)
* Consolidação de múltiplos XMLs automaticamente
* Dashboard interativo
* Integração com banco de dados

---

## 👤 Autor

Desenvolvido por **João Victor**

🔗 [LinkedIn](https://www.linkedin.com/in/joao-victor-macedo-neves/)
💻 Projetos focados em **dados, automação, processos fiscais e eficiência operacional**

---

Se este projeto te ajudou ou gerou algum insight, fique à vontade para ⭐ o repositório!

---

## 📄 Licença

Este projeto está sob licença MIT. Sinta-se à vontade para usar, estudar e evoluir.

---

⭐ Se este repositório foi útil, considere deixar uma estrela!

