 LLM-агенты с использованием LangChain и LangGraph:

1. **Travel Assistant (LangChain ReAct Agent)**  
   Агент с conversational memory и tool calling, который использует инструменты `country_info_tool`, `currency_tool` и `final_answer`
   для получения информации о стране, конвертации валют и генерации итогового ответа.

2. **Weather Advisor (LangGraph Agent)**  
   Агент, реализованный как state graph: он извлекает параметры запроса пользователя, определяет координаты города через geocoding API,
   получает погодные данные через Open-Meteo API и формирует рекомендацию с помощью LLM.
