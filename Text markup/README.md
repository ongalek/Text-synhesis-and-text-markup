# Алгоритм автоматического распознавания речи и сбора данных в датасет

Этот код использует библиотеки Pydub и SpeechRecognition для автоматического распознавания большого набора аудиоданных при помощи ASR моделей. Затем полученные образцы собираются в единый датасет, который сохраняется по указанному пути.

## Установка

Для запуска этого кода необходимо установить следующие библиотеки:

- SpeechRecognition
- pydub
- pandas
- glob
- transliterate

Вы можете установить эти библиотеки, используя pip, запустив следующую команду:

```bash
pip install SpeechRecognition pydub pandas glob transliterate
```

## Использование

Для использования этого кода выполните следующие шаги:

0. Изменить пути сохранения и загрузки на пользовательские

1. Импортируйте необходимые библиотеки:

```python
import speech_recognition as sr 
import os 
from pydub import AudioSegment
from pydub.silence import split_on_silence
import glob
import pandas as pd
import transliterate
from transliterate import translit
```

2. Запустите файл 'ASR dataset collecting algorithm' в среде VS code для автономной работы или в Google Colab (необходимо использовать относительные пути вместо абсолютных)

## контакты

[iksmolenchuk@miem.hse.ru](https://cabinet.miem.hse.ru/#/project/371/team) - researcher

[manizhegorodov@miem.hse.ru](https://cabinet.miem.hse.ru/#/project/371/team) - researcher

