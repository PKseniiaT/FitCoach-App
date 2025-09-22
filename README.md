# FitCoach-App
Пет-проект, посвященный автоматизации работы фитнес-тренеров. Мобильное приложение для персональных фитнес-тренеров, предназначенное для учета клиентов, планирования расписания, отслеживания платежей и создания тренировочных программ. Построено на многослойной архитектуре.Репозиторий содержит техническую спецификацию, UML-диаграммы и документацию по проектированию системы.
## Документация
С полной спецификацией требований к программному обеспечению и архитектурными схемами можно ознакомиться здесь:
https://docs.google.com/document/d/1j9GZxv2qhzgiUQxNeLdIXDK_n7eV89NtVoKQ0jgYnUg/edit?usp=sharing
## Архитектура
Проект следует принципам многослойной архитектуры 
Слой представления (UI) - мобильное приложение
Бизнес-слой- сервисы бизнес-логики (ClientService, ScheduleService, WorkoutService,PaymentService, ExercizeService)
Слой доступа к данным- репозитории (ClientRepository, ScheduleRepository, WorkoutRepository,PaymentRepository)
Слой хранения данных - локальная база данных SQLite
## Основные функции
**Управление клиентами** - база клиентов с поиском и детальной информацией

**Расписание тренировок** - календарь с созданием и переносом тренировок


**Финансовый учет** - фиксация платежей и отслеживание доходов

**Управление тренировочными программами** - создание и хранение библиотеки упражнений и тренировочных программ
## Диаграммы процессов
**Контекстная диаграмма** - https://drive.google.com/file/d/1jribtpiNiTz-Dmu8vNCGUE5OGUpk_ERo/view?usp=sharing

**Логическая модель данных** - https://drive.google.com/file/d/1kwmIkD601sCRSNS6dTL1g4AjrnY_sRux/view?usp=sharing

**Диаграмма компонентов** - https://drive.google.com/file/d/1n6VkIE-RIDDg56JzuMAf9tlfLRoYFdZN/view?usp=sharing

**Диаграмма последовательности - Управление клиентами** - https://drive.google.com/file/d/14YuEyxO3PODmHFGCHSbtdTEgfYqoZbnn/view?usp=sharing

**Диаграмма последовательности - Управление распсианием** - https://drive.google.com/file/d/1usSeNV9SiRqcHik7i-97H_7Df5SD0sA_/view?usp=sharing

**Диаграмма последовательности - Управление финансами** - https://drive.google.com/file/d/15DtxVzLalbHH0u02JHfocUIwW71igsDE/view?usp=sharing



