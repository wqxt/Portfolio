## 1. **Snow Runner**  
- **Статус:** Релиз на Yandex Games.  
- **Ссылка на проект:** [Runner на GitHub](https://github.com/wqxt/Runner)  
- **Ссылка на билд:** [Runner Build](https://drive.google.com/file/d/17BGX3_P3Efvt2NVtsOAbKTgDZHGiSYum/view?usp=sharing)
- **Ссылка на видео:** [Gameplay Video](https://drive.google.com/file/d/1rp_8TMYkErcxjfzLutUXc8OrLHv48Idz/view?usp=drive_link)
- **Платформа:** PC/WebGL
  
![SnowRunner](https://github.com/user-attachments/assets/6f4279ac-68cd-45b3-b0e9-17c4e5422f61)

**Ключевые задачи:** 
- Интеграция текстур, моделей и анимаций.
- Настройка анимаций через Mixamo. 
- Спавн окружения с помощью паттерна **Factory**.  
- Настройка LOD для оптимизации производительности на WebGL.  
- Разработка UI-анимаций без сторонних инструментов.  

**Комментарий:**  
Этот проект - первый опыт в разработке игр. Совместная работа с 3D-дизайнером позволила набраться опыта работы с моделями, материалами, шейдерами, текстурами. В процессе разработки я изучил базовые аспекты работы с Unity, включая работу с физикой, реализацию паттернов и базовые принципы построения приложений. 

---

## 2. **Platformer**
- **Статус:** Пет-проект.
- **Цель:** Изучение фреймворков для дальнейшей работы с ними.  
- **Ссылка на проект:** [Platformer на GitHub](https://github.com/wqxt/PlatformerExample)  
- **Ссылка на билд:** [Platformer Build](https://drive.google.com/file/d/1RnP-WAldqp_fahwNEoUs2ZIfiRpEYAZi/view?usp=sharing)
- **Ссылка на видео:** [Gameplay Video](https://drive.google.com/file/d/1FGZLzzkW6guRFSE2u24gU6QWxFCajuko/view?usp=drive_link)
- **Платформа:** PC
  
![Platformer](https://github.com/user-attachments/assets/72430cfc-11ef-4fbf-b3b1-aa0bb1fb75d9)

**Ключевые задачи:**  
- Реализация движения - **FSM** и **Character Controller**.  
- Настройка анимаций через Mixamo.  
- Спавн объектов - **Zenject**.  
- Пользовательский ввод - **Unity Input System**.  
- Анимация UI - **DOTween**.  
- Интеграция **LeoECS**.

**Комментарий:**  
Этот проект разрабатывался для изучения и применения разных подходов в разработке на Unity. Работа над **Platformer** позволила базово понять такие технологии, как **ECS** с помошью **LeoECS**, **DI** с помощью **Zenject** и реактивное программирование с помощью **UniRx**.

---

## 3. **Tic-Tac Toe: Классика**
- **Статус:** Релиз на Yandex Games.  
- **Ссылка на проект:** [Tic-Tac Toe на GitHub](https://github.com/wqxt/TicTacToe)  
- **Ссылка на билд:** [Tic-Tac Build](https://drive.google.com/file/d/1cFYTQ-DKNi6miQMLiQ52gmkTRLsd8_EB/view?usp=sharing)
- **Ссылка на видео:** [Gameplay Video](https://drive.google.com/file/d/1bTtPCOHEOe1M_Q081Z8IgQt_luzGuxgt/view?usp=sharing)
- **Платформа:** PC/Mobile/WebGL
  
![TicTacToe](https://github.com/user-attachments/assets/a2ff88e8-9721-4514-9295-cbf8771bd7b4)

**Ключевые задачи:** 
- Реализация игровой логики и передачи хода.  
- Реализация AI - алгоритм **MiniMax** с отсечением.  
- Разработка UI. 
- Пользовательский ввод - **Unity Input System**.  
- Интеграция **Yandex SDK** для монетизации.

**Комментарий:**  
Работа над проектом помогла углубить знания в области алгоритмов и структурирования кода для игр с простыми правилами. Изучение особенностей разработки мультиплатформенных приложений расширило мое понимание работы с различными платформами. Интеграция с **Yandex Games** предоставила ценный опыт адаптации проекта под требования определенной платформы, включая оптимизацию и монетизацию.

---

## 4. **VR**
- **Статус:** Тестовое задание.
- **Цель:** Изучение разработки виртуальной реальности.
- **Ссылка на проект:** [VR на GitHub](https://github.com/wqxt/ZongTestTask.git)
- **Ссылка на билд:** [VR Build](https://drive.google.com/file/d/1bd5aAvH2iIQyv3MI5d1OxqZFOqSscXId/view?usp=drive_link)
- **Ссылка на видео:** [Gameplay Video](https://drive.google.com/file/d/1_myCLD0tEnkN-cmrdE-X9AT6OPlBRqDN/view?usp=drive_link)
- **Платформа:** PC
  
![VR](https://github.com/user-attachments/assets/86eb11b3-0c94-4704-a104-7423d82a4a68)

**Ключевые задачи:** 
- Взаимодействие с объектами (перетаскивание, вращение).  
- Эмуляция VR-контроллеров и настройка управления.  
- Разработка UI.  
- Система инвентаря и управление объектами.  
- Использование **Zenject** для создания объектов и внедрения зависимостей.

**Комментарий:**  
Этот проект позволил мне освоить технологии VR. Углублённая работа с фреймворком **Zenject** помогла внедрять зависимости, делая архитектуру проекта более чистой и поддерживаемой. В процессе работы я приобрёл полезные навыки, которые будут актуальны при создании более сложных VR-приложений, особенно в области проектирования взаимодействий и построения архитектуры с использованием **Zenject**.

---

## 5. **IdleRPG**
- **Статус:** Пет-проект, в разработке.
- **Цель:** Разработка игрового приложения с архитектурными решениями.
- **Ссылка на проект:** [IdleRPG на GitHub](https://github.com/wqxt/IdleRpg)
- **Ссылка на билд:** [IdleRPG Build](https://drive.google.com/file/d/15DoSuD34lwCoqt4uGYcqpVAgm2VTMUHN/view?usp=sharing)
- **Ссылка на видео:** [Gameplay Video](https://drive.google.com/file/d/1y726BH3jiRfIC8mODeLw91BsSzkAQdrt/view?usp=drive_link)
- **Платформа:** PC/Mobile
  
![IdleRPG](https://github.com/user-attachments/assets/87ae45ad-83b9-4d3a-94a5-24f2444ad777)

**Ключевые задачи:** 
- Работа с **Zenject** для создания объектов и внедрения зависимостей.  
- Использование **Zenject Factory** и **Object Pool** для спавна сущностей.  
- Реализация UI через паттерн **Observer**.  
- Логика персонажей на основе **FSM**.  
- Написание тестов.  

**Комментарий:**  
В процессе работы над проектом, я получил ценный опыт оптимизации кода и построение архитектуры на основе **Zenject**. Реализация таких паттернов, как **Observer** для работы с UI,  **Factory** и **Object Pool** для правильной работы с сущностями и покрытие некоторых системи тестами, помогли мне укрепить навыки в обеспечении стабильной работы приложения.
