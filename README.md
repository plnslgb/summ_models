# Дообученные модели для суммаризации академических текстов

Репозиторий содержит дообученные модели для автоматической суммаризации научных текстов на русском языке. Разработано в рамках дипломной работы по теме:  
**"Автоматическая суммаризация академических текстов для поиска научной информации"**.

## Доступные модели

1. **SCI_rut5_base_sum_gazeta**  
   - Исходная модель: [IlyaGusev/rut5_base_sum_gazeta](https://huggingface.co/IlyaGusev/rut5_base_sum_gazeta)
   - Архитектура: T5 (Text-to-Text Transfer Transformer)
   - [Доступна на Hugging Face(https://huggingface.co/plnchk/SCI_rut5_base_sum_gazeta)]

2. **SCI_rugpt3medium_sum_gazeta`**  
   - Исходная модель: [IlyaGusev/rugpt3medium_sum_gazeta](https://huggingface.co/IlyaGusev/rugpt3medium_sum_gazeta)
   - Архитектура: GPT-3 (Generative Pre-trained Transformer)

3. **SCI_ru-mbart-large-summ`**  
   - Исходная модель: [d0rj/ru-mbart-large-summ](https://huggingface.co/d0rj/ru-mbart-large-summ)
   - Архитектура: mBART (Multilingual Bidirectional Auto-Regressive Transformer)

## Данные для дообучения
- **Корпус ТКиКЛ** Корпус текстов по компьютерной и корпусной лингвистике ([https://github.com/CompLinguists-22M28/Topic-Modeling-Project-22M28](url))
