# Tuto 03 - Ai model sequences management module
> Version 2024.03.08.2, Author : Dominique Delaire


This module **is part of a series of 4 other modules which constitute the Shellbots OS and framework for creating innovative AI services.**

In this tutorial, we will detail the operation of **the first module and which concerns the management of the sequencing of shellbot AI models**.

## Here is a representative diagram of the first module in shellbots (click to expand) :
![shellbotsmodule1sur4](https://github.com/nuage365/Shellbots.ai/assets/102873102/0461ccc5-3b8b-415a-9a1f-85433464e0b3)


## Integration of market AI Engine
* The market AI engine integrated into the framework are available for all shellbot contexts, therefore for all AI projects and services.
* The advantage of shellbots for designing AI services or projects is that it does not use only 1 engine but all the AI ​​engines on the market from different fields and sectors. 
* When a new AI engine is available, we can quickly integrate it into the framework with basic functions from the shellbots environment.
* The objective is to be able to use the strength of each of them in areas where they are most efficient by managing the scoring of the results
* Functions also allow you to save different API keys for the same engine depending on your needs.
* We have integrated more than 70 AI engines including mistral, google gemini, openai, Microsoft Copilot, claude.ai, etc. and we add more regularly.

## Definition of AI models
* Shellbot AI models are defined by context. It is possible to import models between contexts.
* Here, we are not talking about models in machine learning (we have a specific module for that), but about AI models for each AI engine on the market.
* We can create a multitude of models per domain for one or more AI engines on the market based on customer needs and build a large library for creating AI services for our customers.
* The integration is done with the Python language to build a model inside shellbots :
   * For example, here is a type of hello world to create a simple model from the OpenAI market engine to generate sample datas for your applications or databases :
        * ![screenshot1](https://github.com/nuage365/Shellbots.ai/assets/102873102/aa415830-9ca2-4938-a7c4-156458e4eb54)
   * We have integrated shellbot constants and functions into the python code to interact with market AI engines and all shellbot modules.
   * Of course, there are very sophisticated models that allow generative AI to be mixed with machine learning and process automation.

## Models sequencer
* This module allows you to create sequences and nest several AI shellbot models. It is also in this sequencer that we can evaluate the result of each model and AI engine by giving it a score either by a human specialist in a particular field, or by our internal inference engine which uses our other module of machine learning.
* We can advance our AI models here as a data model.
* The score can also be evaluated by specific algorithms that can be modeled in the analysis tools module.

## Testing tools
* At any time to create an AI service for a client in a shellbots context, we can test the integration of an AI from the market, one or more models in parallel, and sequences linked to an AI model before linking it to our machine learning module and analysis and data tools if necessary.
* Another advantage of the testing engine is that it is capable of running Python at runtime to quickly test new models. So python of python :)

Here is an example here of 4 ai models created for a particular context with certain ai engines only :
![screenshot2](https://github.com/nuage365/Shellbots.ai/assets/102873102/f2041ad6-553a-406f-b9b8-6346a0cc620b)



**The next tutorial will talk about the data analysis module and the machine learning module.**

If you have any questions, feel free to send me a connection on Linkedin at https://www.linkedin.com/in/dominiquedelaire/
