# 🚀 Fine-tune LLMs (README gerado com auxilio de LLM - Gemini 2.5 Pro)

Bem-vindo ao repositório `finetune_llms`! Este projeto é uma coleção de scripts, ferramentas e guias práticos para facilitar o processo de fine-tuning (ajuste fino) de Modelos de Linguagem Grandes (LLMs).

O objetivo é fornecer um ponto de partida claro e funcional para treinar modelos como Llama, Mistral, e outros, em seus próprios datasets.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/downloads/)

---

## 📚 Índice

- [Visão Geral](#-visão-geral)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [Como Começar](#-como-começar)
  - [Pré-requisitos](#pré-requisitos)
  - [Instalação](#instalação)
- [Licença](#-licença)

---

## 🎯 Visão Geral

O fine-tuning de LLMs pode ser um processo complexo, envolvendo preparação de dados, configuração de ambiente, gerenciamento de memória de GPU e escolha de hiperparâmetros. Este repositório visa simplificar essas etapas, oferecendo scripts reutilizáveis e bem documentados para diversas tarefas de ajuste fino.

## ✨ Funcionalidades Principais

- **Scripts Modulares**: Scripts separados para preparação de dados, treinamento e inferência.
- **Suporte a Técnicas Eficientes**: Implementações prontas para uso de técnicas como **LoRA** e **QLoRA** (usando a biblioteca PEFT da Hugging Face).
- **Fácil de Adaptar**: Os scripts são parametrizados para que você possa facilmente trocar o modelo base, o dataset e os hiperparâmetros de treinamento.
- **Exemplos Práticos**: Inclui exemplos de como formatar seu dataset e executar o treinamento do início ao fim.

## 📂 Estrutura do Repositório

```
finetune_llms/
│
├── notebooks/                  # notebooks com documentação
├── requirements.txt            # Dependências do projeto
└── README.md                   # Este arquivo
```

---

## 🛠️ Como Começar

Siga os passos abaixo para configurar seu ambiente e começar a usar os scripts.

### Pré-requisitos

- **Python 3.9+**
- **Git**
- **NVIDIA GPU** com **CUDA 11.8+** (fortemente recomendado para performance)

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/finetune_llms.git
    cd finetune_llms
    ```

2.  **Crie e ative um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```
---

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
