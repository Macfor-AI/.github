## Olá, seja bem-vindo a este github 👋

Abaixo teremos algumas boas práticas para uso do time

### Templates de Projetos

Você sabia que temos alguns templates prontos para projetos? Isso vai ajudar os macfornianos a agilizarem o processo de inicialização dos projetos, com templates padrão. Sim, é só chegar e trabalhar ;)

#### Objetivo

Começar um projeto de forma rápida.

[1. Template para projeto de Data Science](https://github.com/Macfor-AI/cc-template-dsproject)

> Como usar:

```
pip install cookiecutter
```

```
cookiecutter https://github.com/Macfor-AI/cc-template-dsproject
```

[2. Template para projeto de Inteligência Artificial](https://github.com/Macfor-AI/cc-template-chatbot-ai)

```
pip install cookiecutter
```

```
cookiecutter https://github.com/Macfor-AI/cc-template-chatbot-ai
```

### Commits Padrões

Abaixo teremos alguns padrões de commit para tornar a comunicação mais fluida. Sugerimos utilizar para que possamos identificar pontos de mudanças mais rapidamente nos projetos.

Que ótimo que você gostou! No campo de MLOps, os engenheiros frequentemente utilizam o Conventional Commits em conjunto com outros padrões específicos da área para manter o repositório organizado e garantir uma rastreabilidade eficiente dos componentes de machine learning e DevOps. Aqui estão alguns padrões de commits comuns em MLOps, com base nos tipos de atividades e componentes característicos deste campo:

#### Padrões Específicos de Commits para o contexto de Ciência de Dados e Desenvolvimento de Soluções com Inteligência Artificial 

1. **feat**: Usado para novas funcionalidades, especialmente para adicionar componentes de pipeline ou modelos.
   - Exemplo: `feat(model): add XGBoost model for user classification`
   - Exemplo: `feat(data-ingestion): implement data ingestion pipeline`

2. **fix**: Para correções de bugs, especialmente em scripts de treinamento, preprocessamento de dados ou passos do pipeline.
   - Exemplo: `fix(preprocessing): handle null values in feature engineering`
   - Exemplo: `fix(model-serving): correct response format in API`

3. **chore**: Para tarefas de manutenção e ajustes que não afetam diretamente o pipeline ou o modelo, como mudanças em configurações de infraestrutura.
   - Exemplo: `chore: update Dockerfile to use latest Python version`
   - Exemplo: `chore: clean up unused notebooks`

4. **docs**: Para atualizações de documentação, especialmente importante em MLOps onde os pipelines e experimentos são complexos.
   - Exemplo: `docs: add readme for model training workflow`
   - Exemplo: `docs: update usage instructions for CI/CD pipeline`

5. **style**: Para ajustes de estilo de código que não alteram a lógica, mantendo a consistência em scripts e notebooks.
   - Exemplo: `style: format code using black`
   - Exemplo: `style: apply PEP8 guidelines to feature engineering script`

6. **refactor**: Para refatoração de código, como a melhoria de funções de preprocessamento ou organização de pipelines.
   - Exemplo: `refactor(data-pipeline): modularize feature engineering`
   - Exemplo: `refactor(model): optimize training loop for efficiency`

7. **test**: Para adicionar ou modificar testes, especialmente testes de validação do pipeline e unitários para scripts.
   - Exemplo: `test: add unit tests for data ingestion function`
   - Exemplo: `test(model-serving): add integration tests for prediction API`

8. **perf**: Usado para otimizações de performance, como melhorias em pipelines de dados ou aumento de eficiência em modelos.
   - Exemplo: `perf(data-processing): optimize data loading with Dask`
   - Exemplo: `perf(model): reduce inference time with batch predictions`

9. **ci**: Para mudanças no pipeline de CI/CD, comum em MLOps para automatizar testes e deployments de modelos.
   - Exemplo: `ci: add GitHub Actions workflow for model deployment`
   - Exemplo: `ci: integrate MLflow tracking with CI pipeline`

10. **build**: Para modificações na configuração de build, como ajustes no Docker ou dependências do ambiente.
    - Exemplo: `build: update Dockerfile for GPU support`
    - Exemplo: `build: add dependencies in requirements.txt for data processing`

11. **infra** (padrão adicional comumente usado em MLOps): Para mudanças de infraestrutura, como configurações em nuvem, permissões e recursos.
    - Exemplo: `infra: setup Cloud Storage bucket for raw data`
    - Exemplo: `infra: configure IAM roles for model deployment`

12. **data**: Para mudanças específicas relacionadas ao dataset, como atualizações, amostras de dados ou mudanças em dados de treinamento.
    - Exemplo: `data: update training dataset with recent records`
    - Exemplo: `data: add data augmentation for improved model performance`

13. **pipeline**: Para ajustes ou novas funcionalidades em pipelines de ETL, pipelines de treinamento ou pipelines de deploy.
    - Exemplo: `pipeline: update preprocessing steps in training pipeline`
    - Exemplo: `pipeline: add model validation step before deployment`

14. **exp** (experimento): Para marcar commits que estão relacionados a experimentos, como testes de hiperparâmetros ou novos algoritmos.
    - Exemplo: `exp: test new features in SVM model`
    - Exemplo: `exp: run hyperparameter tuning for Random Forest model`


Esses padrões ajudam a manter uma **visão clara do que cada commit representa**, permitindo uma organização e um entendimento mais fáceis das mudanças em um ambiente de desenvolvimento ou produção, onde há muitas partes interconectadas, como pipelines, dados, modelos e infraestrutura.
