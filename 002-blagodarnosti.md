- перевод: [KoppeKTop](http://habrahabr.ru/users/KoppeKTop/)
- @rb2 вычитка


1 января 2010 в 22:56

С небольшим опозданием от плана, продолжаю переводить книгу Чеда Фоулера
«Страсть к программированию».


[\< — Глава 1](http://koppektop.habrahabr.ru/blog/79254/) [Глава 3-\>](http://koppektop.habrahabr.ru/blog/79840/)

#### Благодарности

Я бы никогда не написал эту книгу, если бы не Дэйв Томас (Dave Thomas)
и Энди Хант (Andy Hunt). Их книга «Программист-прагматик» [1] послужила
для меня катализатором и со времени её прочтения я был вдохновлён их
работой. Если бы не поддержка и руководство Дэйва, я бы никогда не
посчитал себя достаточно квалифицированным для написания этой книги.

Сюзанна Файзер (Susannah Pfalzer) редактировала второе издание этой
книги. Под редактированием я подразумеваю подталкивание, воодушевление,
вдохновение, руководство и, конечно… редактирование. Её терпение и
умение сказать правильные слова, мотивируя меня, а не пугая — это как раз
то, что было так необходимо для завершения книги. Если бы не Сюзанна,
книга так и осталась бы набором беспорядочных полусформированных идей.

Дэвида Хэйнемера Хэнсона (David Heinemeier Hansson), написавшего
вступительное слово. Его карьера как партнёра проекта 37signals и
создателя Rails — это блестящий пример применения идей, лежащих в основе
этой книги. Также я рад, что свой вклад внесли и другие выдающиеся
люди, с которыми я сталкивался в ходе своей карьеры. Огромное спасибо
Стефену Акерсу (Stephen Akers), Джеймсу Дункану Дэвидсону (James Duncan
Davidson), Вику Чадха (Vik Chadha), Майку Кларку (Mike Clark), Патрику
Коллисону (Patrick Collison), и Тому Престену-Вернеру (Tom
Preston-Werner) за вдохновение меня самого и читателей моей книги.

Моим рецензентам, за ценные замечания к черновикам ко второму изданию.
Всегда удивительно, насколько же может быть неправильна первая версия
главы и насколько правильной её может сделать хороший рецензент. Спасибо
Сэмми Лэрби (Sammy Larbi), Брайну Дайку (Bryan Dyck), Бобу Мартину (Bob
Martin), Кенту Беку (Kent Beck), Алану Фрэнсису (Alan Francis), Джареду
Ричардсону (Jared Richardson), Ричу Доуни (Rich Downie), и Эрику
Костнеру (Erik Kastner).

Джульете Томас, редактировавшей первое издание книги. Её энтузиазм и
видение перспектив было неоценимы. Я получил огромное количество отзывов
от рецензентов первого издания книги: Кэри Боаз (Carey Boaz), Карла
Брофей (Karl Brophey), Брэндона Кэмбэла (Brandon Campbell), Вика Чандха,
Мауро Кисио (Mauro Cicio), Марка Донохью (Mark Donoghue), Пэта Эйлера
(Pat Eyler), Бэна Гудвина (Ben Goodwin), Якоба Харриса (Jacob Harris),
Адама Кейса (Adam Keys), Стива Морриса (Steve Morris), Билла Налла (Bill
Nall), Уэсли Рейза (Wesley Reiz), Авика Сенгупта (Avik Sengupta), Кента
Спиллнера (Kent Spillner), Сандеша Таттитали (Sandesh Tattitali), Крэйга
Утли (Craig Utley), Грега Вона (Greg Vaughn), и Питера У.А. Вуда (Peter
W. A. Wood). Они помогли сделать книгу значительно лучше и я не могу
с лихвой отблагодарить их за потраченное время, энергию и за проявленное
понимание.

Тем великим людям, с которыми я имел возможность работать как
официально, так и неофициально, за идеи, легшие в основу этой книги.
Спасибо за то, что выслушали, научили и просто общались Донни Уэббу
(Donnie Webb), Кену Смиту (Ken Smith), Уолтеру Хоэ (Walter Hoehn),
Джеймсу МакМюрри (James McMurry), Кэри Боаз, Дэвиду Алану Блэку (David
Alan Black), Майку Кларку, Николь Кларк (Nicole Clark), Вику Чадха, Ави
Брайнт (Avi Bryant), Ричу Килмеру (Rich Kilmer), Стиву Акерсу (Steve
Akers), Марку Гарднеру (Mark Gardener), Райну Оунересу (Ryan Ownens),
Тому Копелэнду (Tom Copeland), Дэйву Крэйну (Dave Craine), Джону Афайду
(John Athayde), Марселю Молина (Marcel Molina), Эрику Костнеру, Брюсу
Уильямсу (Bruce Williams), Дэвиду Хэйнемеру Хэнсону, Али Сареа (Ali
Sareea) и Джиму Уэричу (Jim Weirich).

Спасибо моим родителям за их постоянную поддержку. И, самое главное,
спасибо моей жене Келли за то, что ценит.



[1] The Pragmatic Programmer: From Journeyman to Master, Andrew Hunt
and David Thomas, 2000.

-  [Passionate Programmer](http://habrahabr.ru/search/?q=%5BPassionate%20Programmer%5D&target_type=posts)
