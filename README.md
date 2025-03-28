# 🚀 Pipeline de Machine Learning com foco em DevOps

Este repositório demonstra a construção de uma pipeline simples, modular e pronta para automação de Machine Learning utilizando o dataset Titanic. O projeto aplica boas práticas de DevOps (MLOps), incluindo versionamento, automação e preparação para deploy como API ou microserviço.

---

## 📊 Visão Geral do Projeto

A pipeline realiza:

1. **Importação e tratamento dos dados**
2. **Pré-processamento automático**
   - Escalonamento de variáveis numéricas
   - Codificação One-Hot de variáveis categóricas
3. **Treinamento de modelo com RandomForestClassifier**
4. **Avaliação com acurácia**
5. **Salvamento do modelo com `joblib`**

---

## 📁 Estrutura do Projeto

```
.
├── ml_pipeline.ipynb             # Jupyter notebook com a pipeline completa
├── requirements.txt              # Dependências do projeto
├── modelo/
│   └── modelo_titanic.pkl        # Modelo treinado salvo com joblib
├── README.md
```

---

## ⚙️ Tecnologias Utilizadas

- Python **3.11.11**
- pandas
- scikit-learn
- joblib
- Jupyter Notebook

---

## 💻 Como Executar o Projeto Localmente

### 🔁 1. Clone o repositório

```bash
git clone https://github.com/ede1000son/ml-pipeline-devops.git
cd ml-pipeline-devops
```

### 📦 2. Crie um ambiente virtual (recomendado)

```bash
python3.11 -m venv .venv
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate     # Windows
```

### 📥 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### ▶️ 4. Execute o notebook

```bash
jupyter notebook ml_pipeline.ipynb
```

---

## 🧪 Avaliação do Modelo

A acurácia será exibida ao final da execução do notebook. O modelo treinado é salvo como `modelo/modelo_titanic.pkl` usando `joblib`.

---

## 🧰 Pronto para DevOps

Este projeto pode ser facilmente integrado com:

- ✅ CI/CD com GitHub Actions ou GitLab CI
- 🐳 Docker para padronizar o ambiente
- 🌐 FastAPI ou Flask para servir o modelo como API
- 📈 Monitoramento e versionamento com MLflow e DVC (futuro)

---

## ✨ Possíveis melhorias

- [ ] Adicionar `Dockerfile`
- [ ] Criar API com FastAPI
- [ ] Adicionar pipeline CI/CD
- [ ] Versionamento de dados com DVC

---

## 👩‍💻 Autor

**Edemilson Fernandes Vieira**  
Analista de Dados com foco em soluções escaláveis e práticas de MLOps.

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
