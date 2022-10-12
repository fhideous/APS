> LAST UPDATE:
>
> Обновлены все лабораторные
>
> [RV32I](Other/RV32I.md) - Стандартный набор целочисленных инструкций RISC-V
>
> [Индивидуальные задания](Tests/Problems%20RISC-V.md) для программирования на языке ассемблера RISC-V
>
> В настоящей статье появился раздел [#Контроль знаний](#контроль-знаний) и [#Оглавление](#)

# Путеводитель АПС для РТ

![](../technical/Pic/gus_gr.svg)

## Оглавление
- [#Лекции](#лекции)
- [#Лабораторные работы](#лабораторные-работы)
- [#Дополнительные материалы](#дополнительные-материалы)
- [`ОБЛАКО`](https://1drv.ms/u/s!AlYsTGjsjfIfhP4GhdRLPQzK60vqGw?e=qKQz3L)
- [#Контроль знаний](#контроль-знаний)
- [#Обратная связь и преподаватели](#обратная-связь-и-преподаватели)
- [#Место АПС в Computer Science](#место-апс-в-computer-science)
- [#Обзор тематической литературы](#обзор-тематической-литературы)

Привет, студент!

Это путеводитель по дисциплине «Архитектуры процессорных систем». Здесь ты найдёшь ссылки на всю информацию генерируемую в данном курсе: конспекты лекций, методички по лабораторным работам, дополнительные материалы и литература, популярные материалы, ссылка на облако, способы связи с преподавателями (включая анонимный) и тому подобное. Имея доступ к этой страницы ты имеешь доступ ко всему курсу АПС.


## Лекции

Весь цикл лекций можно условно разделить на 5 основных модулей. На  **основах** вводятся основные понятия дисциплины и рассматриваются используемые инструменты. Модуль **цифровой схемотехники** посвящен видам и способам построения различных функциональных блоков и узлов процессора. В модуле **архитектура и микроархитектура** процессора, на примере архитектуры RISC-V реализуется три способа построения микроархитектуры, после чего классифицируются существующие архитектуры процессоров. Блок **процессорные системы** рассматривает основные элементы процессорных систем: память, коммуникация, ввод/вывод. На **современных архитектур процессорных систем** разбираются примеры коммерческих компьютеров различных классов применения. Каждый конспект сопровождается ссылками на подробные материалы, запись лекции, популярные и дополнительные материалы.

**[Основы]**

1. [Вводная](Lectures/01.%20Introduce.md)
2. [Основные концепции и инструменты](Lectures/02.%20Instruments.md)

**[Цифровая схемотехника]**

3. Цифровая арифметика. Арифметико-логическое устройство
4. Последовательностная логика. Память

**[Архитектура и микроархитектура]**

5. Архитектура RISC-V
6. Программирование RISC-V
7. Однотактный процессор
8. Многотактный процессор. Устройство с микропрограммным управлением
9. Конвейерный процессор и методы повышения производительности
10. Виды и классификация архитектур

**[Процессорные системы]**

11. Подсистема прерываний
12. Память
13. Кэш. Виртуальная память
14. Шины
15. Ввод\вывод

**[Современные архитектуры процессорных систем]**

16. Микроконтроллеры (на примере PIC и ARM). Системы общего назначения


## Лабораторные работы

Курс *Архитектур процессорных систем* включает в себя цикл из 4 лабораторных работ, в течение которых используя язык описания аппаратуры **Verilog HDL** на основе **FPGA** (ПЛИС, программируемая логическая интегральная схема), с нуля, последовательно, создается программируемое устройство – процессор. [Подробнее](Labs/README.md) о лабораторных работах.

Список работ направления подготовки КТ [в квадратных скобках указаны номера лекций, в которых поднимаются соответствующие темы]:
1. [Verilog](Labs/1.%20Verilog.%20FPGA/README.md) (Язык Verilog HDL) – [Лекция 2]
2. [Adder](Labs/2.%20Adder/README.md) (Сумматор) – [Лекция 3]
3. [ALU](Labs/3.%20Arithmetic-logic%20unit/README.md) (Арифметико-логическое устройство) – [Лекция 3]
4. [TB](Labs/4.%20Testbenches/README.md) (Тестовое окружение)
5. [RF](Labs/5.%20Register%20file%20and%20memory/README.md) (Регистровый файл и память) – [Лекция 4]
6. [PPD](Labs/6.%20Primitive%20programmable%20device/README.md) (Простейшее программируемое устройство) – [Лекция 4]
7. [PU](Labs/7.%20Peripheral%20units/README.md) (Периферийные устройства) – [Лекция 15]
8. [Programming](Labs/8.%20Programming/README.md) (Программирование)

Полезное дополнение к лабораторным:
- [Как установить Vivado](Other/Install%20Vivado.md)
- [Создание базового проекта с прошивкой ПЛИС в Vivado](Other/Vivado-trainer.md)
- [Что такое язык описания аппаратуры HDL](Other/What%20is%20HDL.md)
- [Конструкции языка Verilog](Other/Verilog%20syntax.md)
- [Тестовое окружение](Other/Testbench.md)
- [Как добавить файл с содержимым памяти в проект](Other/How%20to%20add%20a%20mem-file.md)


## Дополнительные материалы

- [Список основных определений](Other/Basic%20definitions.md)
- [Хочу под ПЛИС](Other/About%20FPGA.md)
- [RV32I](Other/rv32i.md)


## Облако ☁️

Основным хранилищем "габаритных" учебных и методических материалов является  [ОБЛАКО](https://1drv.ms/u/s!AlYsTGjsjfIfhP4GhdRLPQzK60vqGw?e=qKQz3L) . На данный момент в облаке находятся:

1. Презентации лекций (отдельные папки для каждого потока)
2. Методические материалы и презентации лабораторных работ (также находятся в этом репозитории)
3. Вся используемая литература 


## Контроль знаний

- [Индивидуальные задания](Tests/Problems%20RISC-V.md) для программирования на языке ассемблера RISC-V, выполняемые после лекций 5–6, посвященных этой теме
- [Примеры вопросов](Tests/Questions%202020.md) к экзамену, проводимого в 2020 году


## Обратная связь и преподаватели

[Преподаватели АПС](Other/Teachers.md) - в этой статье ты найдешь информацию о всех людях задействованных в организации проведения этой дисциплины, их контакты и расписание консультаций. 

Любые комментарии, критика, жалобы, замечания, да все что угодно, что может как-то улучшить курс, или что не нравится в текущем положении вещей, обратная связь, в любой момент времени, **анонимно** —  [сюда](https://forms.gle/Y1Dtn6EWydFxxzYXA) !


## Место АПС в Computer Science

В оригинальном видео [Map of Computer Science](https://www.youtube.com/watch?v=SzJ46YA_RaA) Доминик Уоллиман предлагает, безусловно неполную, но удобную для представления обширной области знаний, карту компьютерных наук. Ниже, на этой карте, отмечена зона, которую покрывает предлагаемый курс лекций и лабораторных работ.

Эта `COMPUTER ENGINEERING` дисциплина главным образом уделяет внимание компьютерным архитектурам, и всем взаимосвязанным вопросам в этом контексте: компиляторы, операционные системы, виртуальные машины, ПЛИС. Такая дисциплина является важным связующим звеном между теоретическими компьютерными науками и ее приложениями, представленными в нижней части карты. Компьютерная инженерия – неотъемлемая часть в реализации современных приложений. АПС закладывает необходимую инженерную базу, наборы понятий и концепций в отношении цифровых технологий и устройств.

![](../technical/Pic/cs2.png)

---


## Обзор тематической литературы

В приведенном ниже списке будут даны описания книг, а так же способы их получения: покупка/чтение в электронной библиотеке/получение экземпляра книги в универитетской библиотеке. <!--Руководство по работе с электронной библиотекой вы можете найти [здесь](<placeholder>)-->.

**Митио Сибуя и Такаси Тонаги**  

*Центральный процессор. Образовательная манга*

Самый лайтовый вариант усвоения основных концепций изучаемой дисциплины. Про архитектуру процессора в виде манги. По сюжету девушка Каиураги Дюми, чемпион по японским шахматам сёги, встречает незнакомца, который предлагает ей сыграть с компьютером. Конечно же она сливает партию. И понеслось. Слово за слово и вот он уже рассказывает ей, как работает обыгравший ее компьютер. Не понять просто невозможно. А прочитав эту мангу любая книга ниже станет понятна абсолютно любому читателю. Манга [продается](https://dmkpress.com/catalog/manga/978-5-97060-507-3/) как в электронном, так и в печатном виде. В обозримом будущем будет доступна студентам МИЭТ в [электронной библотеке](https://e.lanbook.com/book/93581).

![](../technical/Pic/manga.jpg)

---

**Чарльз Петцольд**  

*Код. Тайный язык информатики*

Книга для тех, кому плохо пошел материал. Очень, очень классно рассказывается что такое цифровые устройства, как это работает и зачем это все нужно. На примере фонариков, азбуки Морзе, шрифта Брайля и штрих-кодов автор знакомит нас с основами кодирования информации. Из лампочек и батареек сначала собираются разные вроде бы пустяковые устройства, которые позже превращаются в полноценный компьютер. Отличная популярная литература. Если ты знаешь человека, которому с трудом дается понимание цифровой техники, то ты просто обязан порекомендовать ему эту книгу. В образовательных целях можно ознакомиться с ней в облаке. Почитать восхищенный отзыв о книге и ее содержании можно [тут](https://habr.com/ru/post/68365/). А дождаться, когда она начнет снова продаваться можно [тут](https://www.ozon.ru/context/detail/id/125884/). Либо поискать в магазинах.

![](../technical/Pic/code.jpg)

---

**Дэвид М. Харрис и Сара Л. Харрис**

*Цифровая схемотехника и архитектура компьютера: RISC-V*

Потрясающая книга, являющаяся более доступным вариантом изложения и иллюстрации книги "Архитектура компьютера и проектирование компьютерных систем", Паттерсона и Хеннесси. На примере архитектуры **RISC-V** рассказывается как построить процессор начиная с вопросов работы транзистора. Рассматриваются базовые конструкции языков описания аппаратуры **SystemVerilog** и **VHDL**. Эту книгу на чистом энтузиазме перевели на русский язык группа ученых и инженеров из стран бывшего СССР с подачи [Юрия Панчула](http://panchul.com/about_ru/). Электронный вариант для архитектуры **MIPS** распространяется бесплатно и абсолютно легально. Обязательна к ознакомлению каждому! Гораздо удобнее использовать печатный вариант, на этот случай ее можно приобрести  [тут](https://dmkpress.com/catalog/electronics/circuit_design/978-5-97060-961-3/). Электронный вариант с архитектурой **MIPS** доступен в облаке и [электронной библотеке](https://e.lanbook.com/book/241166).

![](../technical/Pic/harris.png)

---

**Дэвид М. Харрис и Сара Л. Харрис**  

*Цифровая схемотехника и архитектура компьютера.  
Дополнение по архитектуре ARM*

Как и следует из названия, эта книга дополняет предыдущие описанием отличий архитектуры **ARM** от **MIPS** и **RISC-V**. Книга состоит из глав, посвященных архитектуре процессоров **ARM**, их микроархитектуре, описанию подсистемы памяти и системы ввода-вывода. Также в приложении приведена система команд **ARM**. Почему такое пристальное внимание этой архитектуре? Потому что это одна из самых массово используемых архитектур в мире. Например, 98% всех мобильных телефонов работают на процессорах с архитектурой **ARM**. Книгу можно приобрести [тут](https://dmkpress.com/catalog/electronics/circuit_design/978-5-97060-650-6/), а так же прочесть в [электронной библиотеке](https://e.lanbook.com/book/111431).

![](../technical/Pic/arm.jpg)

---

**под редакцией Романова А.Ю. и Панчула Ю.В.**

*Цифровой синтез: практический курс*

В дополнение к Харрисам отлично идет практический курс цифрового дизайна, в том числе, как раз, от того самого Юрия Панчула. Книга ориентирована в первую очередь на практику создания цифровой аппаратуры на ПЛИС с помощью **Verilog HDL**. Затрагиваются вопросы процесса создания **ASIC**. Очень хорошо написана, грамотно структурирована и имеет много полезной информации, требующейся на практике дизайнеру цифровой аппаратуры. Купить можно [тут](https://dmkpress.com/catalog/electronics/circuit_design/978-5-97060-850-0/), так же доступна в [электронной библиотеке](https://e.lanbook.com/book/179492).

![](../technical/Pic/digitaldesign.png)

---

**Д. Паттерсон и Дж. Хеннесси**  

*Архитектура компьютера и проектирование компьютерных систем*

Отцы архитектуры **RISC** делятся накопленным опытом. Не только рассказывают, как процессоры работают, но и как их построить, прививают принципы проектирования, красиво указывают на заблуждения, дают хитрые задания, да и вообще книга богата полезной информацией. Нетленка. Не зря на лицевой стороне книги написано _классика computer science_. Заканчивается книга разбором многоядерных, многопроцессорных параллельных систем. Если решишь поставить к себе на полку, то придется подождать когда она  [вновь поступит в продажу](https://www.ozon.ru/context/detail/id/7425447/) или поискать на полках магазинов.

![](../technical/Pic/patterson1.jpg)

---

**Д. Паттерсон и Дж. Хеннесси**

*Архитектура компьютера. Количественный подход*

Дополнение к предыдущей книге, вся суть которой передана в названии. Рассматривается эффективность современных вычислительных машин в численном эквиваленте. Что и как влияет на производительность вычислительных систем и какие существуют зависимости. Уделяется большое внимание построению иерархии памяти и анализу результатов, исследуется параллелизм исполнения команд. В некотором смысле это библия анализа вычислительных систем. Авторы получили за нее премию Тьюринга. Рекомендуется к прочтению после прослушивания курса Архитектуры процессорных систем. В облаке лежит часть книги для ознакомления, а ее  [физическая копия](https://www.ozon.ru/context/detail/id/35204637/) хорошо дополнит домашнюю библиотеку computer science.

![](../technical/Pic/patterson2.jpg)

---

**С.А. Орлов и Б.Я. Цилькер**

*Организация ЭВМ и систем*

Фундаментальный курс по архитектуре и структуре современных компьютерных систем, написанный двумя опытными профессорами из питерских вузов. Книга написана излишне сухо, в советской манере, порой с излишним формализмом даже там, где этого можно было избежать. Однако, книга изобилует большим объемом полезной информации, богатым списком источников, в основном зарубежных. Рекомендуется использовать ее как дополнительное справочное пособие. В ней можно найти много оригинальной информации, не содержащейся в другой отечественной печатной продукции. Купить книжку можно, например, [здесь](https://www.ozon.ru/context/detail/id/147603179/).

![](../technical/Pic/orlov.jpg)

---

**Д.Н. Беклемишев, А.Н. Орлов, А.Л. Переверзев, М.Г. Попов, А.В. Горячев, А.И.Кононова**  

*Микропроцессорные средства и системы. Курс лекций*

Курс лекций, читавшийся несколько лет назад. На данный момент книга является актуальной, но дисциплина организована несколько иначе. Из достоинств можно выделить хорошую организацию написанного материала, представленного в виде одинаковых порций разбитых на тематические лекции. Книга доступна в облаке и в университетской библиотеке. Отдельно стоит отметить, что часть читаемого на лекциях материала представлена только в этом издании.

![](../technical/Pic/vt.jpg)

---

**Э. Таненбаум и Т. Остин**  

*Архитектура компьютера*

Книга для изучения компьютерной архитектуры от всемирно известного специалиста в области информационных технологий, писателя и преподавателя, выходящая уже в шестом издании и посвящена структурной организации компьютера. В качестве примеров архитектур рассматриваются **Intel Core i7**, **Texas Instrument OMAP4430** и **Atmel ATmega168**. Книга рассчитана на широкий круг читателей, так что можешь читать ее без опасения что что-то не поймешь, хотя не все с этим согласятся, некоторым (включая автора этих строк) книга [не нравится](https://habr.com/ru/post/589091/). Чувствуется влияние того, что Таненбаум чаще взаимодействует с цифровой аппаратурой в роли программиста, а не разработчика. Вероятно это поможет в освоении материала обучающимся на соответствующих специальностях. Купить книгу можно [тут](https://www.piter.com/collection/all/product/arhitektura-kompyutera-6-e-izd-2).

![](../technical/Pic/tanenbaum.jpg)

---

**Дональд Томас**

*Логическое проектирование и верификация систем на SystemVerilog*

Тем, кто не только пытается разобраться в принципах работы компьютера, но и сам хочет разрабатывать цифровые устройства потребуется более серьезно изучить какой-нибудь современный язык описания аппаратуры. Сходу, многие посоветуют SystemVerilog – наиболее популярный вариант в индустрии. Он является более современной версией Verilog, лишенной некоторых его недостатков.

![](../technical/Pic/svbook.png)

---

`Дорогу осилит идущий`
