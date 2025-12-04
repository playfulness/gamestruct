# Полновесная модель

## Система координат

Проведем горизонтальную ось через игрока. Левую полуось интерпретируем как _геймлэнг_[^1]. Правую - как _геймплей_. Проведем вертикальную ось через игрока. Нижнюю полуось интерпретируем как _геймфил_[^2]. Верхнюю - как _геймлуп_. В итоге получим систему координат, где по оси X дихотомия геймлэнг-геймплей, а по оси Y дихотомия геймфил-геймлуп.
<p align="center">
    <img src="./fig/game-ffm/player-with-axes.svg">
</p>

Мы не будем давать строгих определений. Вместо этого соотнесем введенные термины с другими более знакомыми. При этом важно сохранить противоположность по значению, т.к. пытаемся раскрыть дихотомию.
<p align="center">
    <img src="./fig/game-ffm/axis-x-with-clarifications-ru.svg">
    <img src="./fig/game-ffm/axis-y-with-clarifications-ru.svg">
</p>

## Интерпретации

И вот мы добрались до понятий, знакомых практически каждому. Четверть геймлуп-геймлэнг интерпретируем как _арку_[^3], четверть геймлуп-геймплей - как _механику_ [^3], четверть геймфил-геймлэнг - как _тему_[^4] и четверть геймфил-геймплей - как _сеттинг_[^4].
<p align="center">
    <img src="./fig/game-ffm/matrix-with-axes.svg">
</p>

Представим игру, в которой все предопределено заранее. На стыке темы и арки автором закладывается _персонаж_, на стыке сеттинга и механики - _аватар_, на стыке арки и механики - _история_, на стыке темы и сеттинга - _нарратив_. В такой игре игрок выступает пассивным зрителем. А теперь представим игру, в которой, наоборот, все возникает в ходе игровой партии. На стыке темы и арки игроком генерируется _персонаж_, на стыке сеттинга и механики - _аватар_, на стыке арки и механики - _история_, на стыке темы и сеттинга - _нарратив_. В такой игре игрок выступает активным соавтором. Обе крайности в чистом виде встретить невозможно. Обычно что-то предопределено заранее, а что-то генерируется в процессе игры.
<p align="center">
    <img src="./fig/game-ffm/matrix-with-protocols-singular.svg">
</p>

До сих пор мы рассматривали простейший случай, когда все элементы игры представлены в единственном экземпляре. Это очередная крайность, которая не встречается в чистом виде. В общем случае игра масштабируется либо вширь, либо вглубь. Масштабирование в ширину (количественное) - это добавление новых отдельностоящих элементов, например, больше независимых игроков, больше независимых персонажей, больше альтернативных механик и т.п. Масштабирование в глубину (качественное) - это добавление новых составных элементов или, другими словами, расширение способов композиции элементов, например, объединение игроков в команды, объединение персонажей в группы, построение механических комбо и т.п.
<p align="center">
    <img src="./fig/game-ffm/matrix-with-protocols-plural.svg">
</p>

Осталось немного уточнить порядок взаимодействия игроков с мастером и движком. Мастер через персонажа принимает запросы по поводу намерений. Движок через аватара принимает команды по поводу действий. В свою очередь, игрок получает обратную связь через события в истории и/или нарративные эффекты[^5].
<p align="center">
    <img src="./fig/game-ffm/protocols-with-runtime-agents.svg">
</p>

## Резюме

Любую игру можно разложить на "спектральные" составляющие: геймлэнг, геймплей, геймфил и геймлуп. Все остальные элементы игры получаются "смешением" базовых. Арка является результатом "смешения" геймлупа и геймлэнга, механика - геймлупа и геймплея, тема - геймфила и геймлэнга, сеттинг - геймфила и геймплея. Персонаж является результатом "смешения" темы и арки, аватар - сеттинга и механики, история - арки и механики, нарратив - темы и сеттинга. Элементы игры могут предопределяться заранее, а могут генерироваться на лету. Игра масштабируется добавлением новых отдельностоящих элементов или расширением вариантов комбинирования существующих. Персонаж и аватар являются "проводниками" намерений и действий соответственно. История и нарратив являются "проводниками" событий и эффектов соответственно.

## Указатель

Указатель со ссылками на внешние источники.

### Понятия

#### Персонаж

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 18, метод непрямого контроля 5.
    - Глава 20.
- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Grouling использует термин _character_ на протяжении всей книги.
- Fullerton `Game Design Workshop`
    - Chapter 4, section `Character`.

#### Аватар

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 20, раздел `Аватар`.
- Sellers `Advanced Game Design: A Systems Approach`
    - Chapter 3, section `The Player as Part of a Larger System`. Sellers существенно расширяет понятие аватара.

#### Нарратив

- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Подробное исследование нарратива вообще и нарратива, генерируемого в реальном времени, в частности.
- Sellers `Advanced Game Design: A Systems Approach`
    - Chapter 3, section `Narrative`.
    - Chapter 4, section `Narrative and Interactive Engagement`.
- Sylvester `Designing Games: A Guide to Engineering Experiences`
    - Chapter 4.

#### История

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 17.
- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Grouling использует термин _story_ на протяжении всей книги.

#### Намерение

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 18, метод непрямого контроля 2. Шелл использует термин _цель_.
    - Глава 20, раздел `Создание привлекательных игровых персонажей`
        - Совет 1. Шелл использует термин _функция_.
        - Совет 2. Шелл использует термин _черта_.
- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Chapter 5, section `The Social Frame`. Grouling использует термин _narrative planning speech_.
    - Chapter 5, section `The Game Frame`. Grouling использует термин _statement of intention_.

#### Действие

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 12, механика 4.
- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Grouling использует термин _action_ на протяжении всей книги.

#### Эффект

- Sellers `Advanced Game Design: A Systems Approach`
    - Chapter 8, section `Providing Feedback`.

#### Событие

- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Chapter 1, section `Cybertext: A Model for Adventure Games`.

#### Тема

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 6.
- Sellers `Advanced Game Design: A Systems Approach`
    - Chapter 3, section `Architecture and Thematic Elements`.
    - Chapter 3, section `Theme, Experience, and Meaning`.
- Swink `Game Feel: A Game Designer's Guide to Virtual Sensation`
    - Chapter 5, section `Metaphor`.

#### Арка

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 20, раздел `Создание привлекательных игровых персонажей`
        - Совет 8. Шелл использует термин _трансформация_.
- Fullerton `Game Design Workshop`
    - Chapter 4, section `The Dramatic Arc`.
    - Chapter 11, section `Progress`.
- Sellers `Advanced Game Design: A Systems Approach`
    - Chapter 4, section `Narrative and Interactive Engagement`. Sellers ссылается на [работу](https://lostgarden.com/2012/04/30/loops-and-arcs) Даниэля Кука.
- Sylvester `Designing Games: A Guide to Engineering Experiences`
    - Chapter 1, section `Emotion Through Character Arcs`.

#### Сеттинг

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 19. Шелл использует термин _трансмедийный мир_.
- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Chapter 4, section `Campaign Settings in D&D`.

#### Механика

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 12.
- Sellers `Advanced Game Design: A Systems Approach`
    - Chapter 3, section `Structural Elements and Game Mechanics`.
    - Chapter 7, section `Game Mechanics`.
- Swink `Game Feel: A Game Designer's Guide to Virtual Sensation`
    - Chapter 4, section `Mechanics: Game Feel Atoms`.

#### Мастер

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 18, метод непрямого контроля 5. Шелл предлагает контролировать персонажа игрока через других персонажей.
- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Grouling использует термин _dungeon master_ (DM) на протяжении всей книги.

#### Движок

- Sellers `Advanced Game Design: A Systems Approach`
    - Chapter 7, section `Engines`.

#### Игрок

- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Grouling использует термин _player_ на протяжении всей книги.

#### Геймлэнг

- Wehrle [Game Design Workshops](https://www.youtube.com/playlist?list=PLNOeNKnzorF5BsM8Rwm3WouPvChzBh2-h)
    - Видео `Game Design as Process`, минута 20. Wehrle использует термин _грамматика_.
- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Chapter 5, section `The Creation of Possible Worlds in Fiction`. Grouling использует термин _possible world_.
- Sellers `Advanced Game Design: A Systems Approach`
    - Chapter 3, section `The Player’s Mental Model`.
    - Chapter 12, section `Goals for Your Playtests`.

#### Геймплей

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 15.

#### Геймфил

- Swink `Game Feel: A Game Designer's Guide to Virtual Sensation`.
- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 22. Шелл использует термин _эстетика_.

#### Геймлуп

- Sellers `Advanced Game Design: A Systems Approach`
    - Chapter 7.

### Дуальности

Ссылки на разделы, в которых указанные понятия противопоставляются, связываются или просто упоминаются как синонимы.

#### Персонаж и аватар

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 17, раздел `Проблемы`
        - Проблема 4. Шелл противопоставляет персонажей фильмов и персонажей игр.
- Fullerton `Game Design Workshop`
    - Chapter 4, figure `Characters versus avatars`. Fullerton противопоставляет персонажей, предопределенных автором, и персонажей, конструируемых игроком.
- Sylvester `Designing Games: A Guide to Engineering Experiences`
    - Chapter 4, section `Player–Character Motivation Alignment`.
    - Chapter 4, section `The Human Interaction Problem`.

#### Намерение и действие

- Шелл `Геймдизайн. Как создать игру, в которую будут играть все`
    - Глава 12, механика 4. Шелл противопоставляет стратегические действия и базовые.
- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Chapter 5, section `The Game Frame`. Grouling противопоставляет narrative planning speech и narrative suggestion.
- Sellers `Advanced Game Design: A Systems Approach`
    - Chapter 4, section `Player Behaviors and Cognitive Load`. Sellers указывает на _semantic distance_ между намерением и действием.
    - Chapter 4, section `Core Loops`. Sellers указывает на взаимообусловленность намерения и действия.

#### Нарратив и история

- Grouling `The Creation of Narrative in Tabletop Role-Playing Games`
    - Chapter 3, section `Stories Across Media`.
    - Chapter 4, section `Games Versus Narratives`.
    - Chapter 5, section `The Creation of Possible Worlds in Fiction`. Grouling указывает на то, что _textual actual world_ (TAW) является частичным представлением _text reference world_ (TRW).
- Sellers `Advanced Game Design: A Systems Approach`
    - Chapter 3, section `Narrative`. Sellers использует термины _narrative_ и _story_ как синонимы.

#### Эффект и событие

- TBD

[^1]: К сожалению, пока не удалось подобрать более подходящий общепринятый термин. Почему такой выбор? Во-первых, термин должен иметь значение противоположное геймплею. Во-вторых, Коул Верле неоднократно [утверждал](https://www.youtube.com/watch?v=hNdAbZQsqrc&t=1257s), что в фундаменте любого дизайна лежит построение синтаксиса, грамматических правил, которые позволяют выражать различные игровые ситуации.
[^2]: Термин из одноименной книги Стивена Свинка "Game Feel: A Game Designer's Guide to Virtual Sensation".
[^3]: Термины механики и арки взяты из [статьи](https://lostgarden.com/2012/04/30/loops-and-arcs) и [доклада](https://www.youtube.com/watch?v=qwPe3OHR04c) Даниэля Кука. Или на русском из [доклада](https://www.youtube.com/watch?v=RDZdxjzFKzI&t=968s) Андрея Столярова. В оригинале Кук использует термин loop, но в качестве примеров приводит различные механики. Столяров подтверждает, что "петли это просто понятие, которое используется для описания игровых механик".
[^4]: Подразумевается тема и сеттинг в литературном смысле, т.к. в сообществе настольщиков часто сеттинг называют темой. Но существуют и обратные примеры (например, [раз](https://louardongames.blogspot.com/2014/08/theme-setting.html), [два](https://bumblingthroughdungeons.com/theme-setting-and-mechanics-in-games) и [три](https://www.youtube.com/watch?v=tAHnu4PIyG0)).
[^5]: Почему эффект? Во-первых, эффект приводит к необратимым изменениям. Во-вторых, один и тот же контент, невзирая на количество повторов, может произвести не более одного эффекта (at most once).
