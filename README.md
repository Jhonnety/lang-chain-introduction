
<div align="center">

# 🦜️🔗 Introduction to LangChain

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-0.1.0+-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Educational-orange?style=for-the-badge)

</div>

<br>

Este repositorio contiene un cuaderno introductorio (`langchain_introduction.ipynb`) diseñado para explorar y entender los conceptos fundamentales de **LangChain**. A través de ejemplos prácticos, se abordan los componentes esenciales para construir aplicaciones impulsadas por modelos de lenguaje (LLMs).

> [!NOTE]
> **Nota Educativa**: Este material sirve como una guía técnica y práctica para desarrolladores que inician en el ecosistema de LangChain. Se requiere una API Key de OpenAI activa para ejecutar los ejemplos.

<br>

## ✨ Características Principales

El cuaderno cubre los siguientes tópicos clave:

- ⛓️ **Cadenas (Chains)**: Creación de flujos de trabajo secuenciales conectando prompts y modelos LLM.
- 🧠 **Memoria (Memory)**: Implementación de `RunnableWithMessageHistory` para que el asistente recuerde el contexto de la conversación.
- 🛠️ **Herramientas (Tools)**: Integración de capacidades externas como **Wikipedia** y **Tavily Search** para enriquecer las respuestas.
- 🤖 **Agentes (Agents)**: Construcción de agentes autónomos capaces de decidir qué herramientas utilizar para responder a las consultas del usuario.
- 📦 **Gestión de Dependencias**: Configuración del entorno con librerías esenciales como `langchain-openai`, `python-dotenv` y `langchain-community`.

<br>

## 🏗️ Arquitectura del Contenido

El flujo de aprendizaje del notebook se estructura de la siguiente manera:

1.  **Configuración del Entorno**: Instalación de paquetes y carga de variables de entorno.
2.  **Interacción Básica**: Consultas directas al modelo `ChatOpenAI`.
3.  **Prompt Templates**: Uso de plantillas para estructurar las instrucciones al modelo.
4.  **Sistemas con Memoria**: Creación de un chat interactivo que mantiene el historial.
5.  **Uso de Herramientas**: Ejemplos prácticos de búsqueda web y consulta de documentación.
6.  **Orquestación con Agentes**: Unificación de herramientas y modelos en un agente inteligente.

<br>

## 🚀 Cómo Empezar

1.  Clona este repositorio.
2.  Asegúrate de tener un archivo `.env` con tu `OPENAI_API_KEY`.
3.  Instala las dependencias listadas en el notebook:
    ```bash
    pip install langchain langchain-openai openai python-dotenv langchain-community wikipedia langchainhub
    ```
4.  Ejecuta el servidor de Jupyter y abre `langchain_introduction.ipynb`.

<br>

<div align="center">
    <sub>Desarrollado con ❤️ para el aprendizaje de IA Generativa.</sub>
</div>
