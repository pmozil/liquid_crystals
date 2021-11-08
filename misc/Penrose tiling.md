# Penrose tiling
## Initial setup
Six pentagons can almost fit within a larger one, forming a semi-periodic tiling
![[2021-10-28-173041_1920x1080_scrot.png]]
Idea: break the initial pentagons into smaller ones → Some of the gaps start forming rhombus shapes, other — three "spikes" → subdivide again → You can use pentagons to fill in the gaps within some shapes → All you're left with are rhombuses, stars and "justice caps" (fractions of a star) → subdivisions do not help
## Initial set
Pentagons, rhombuses, stars, and justice caps give you almost five-fold symmetry
## Distillation
Multiple tiles can be combined into just two: a thicc rhombus and a thin rhombus, plus bumps/notches, colors ora whatever are required to assure the right (aperiodic, full) tiling. Just two.
## Moiré pattern
The [[Moire pattern]] shows it all being pretty close to 5-fold symmetry but not being symmetric. You can match a transparency and a paper print of this pattern pretty closely but not 100%. There will always be some difference
# Kites and darts + curves on them
This is one of the possible distilations
## There are infinitely many patterns
The number of individual patterns is larger than your mom, but every finitely large section can be found on any arbitrary pattern if you extend it far enough. You can't tell the difference between them by looking on a local section. There are infinitely many, but just by looking at them, you could never tell them apart.
## Non-localization
These patterns seem to require some kind of long-range coordination, as just putting shapes together will lead you to gaps nothing fits in. Edge rules (curves etc.) are not defined enough to guarantee infinite tiling. However, there are sets of rules that do allow that (e.g., vertex rules).
## Why tf is the golden ratio here?
The ratio of kites to darts approaches the golden ratio $\phi$ as the pattern grows. This is because of five-fold symmetry (the ratio of the diagonal of a pentagon to the edge is $\phi$, and kites+darts are sections of pentagons). This proves that the pattern is aperiodic — if it wasn't the number of kites/darts in a period would be finite, thus, the ratio would be rational
## Paralel lines
When a certain pattern is drawn on kites/darts rather than curves, it connects to form five sets of paralell lines. This is the most visual proof of 5-fold semi-symmetry of the shape. Not really though because every set of lines is spaced very differently. For each, there are thwo spacings (long and short) that do not follow a periodic pattern (but longs/shorts will equal $\phi$).
# Main question
Can there be an analogue for this in nature? Perhaps a crystal? Penrose didn't think so, because there were only 14 already established basic units that compose crystals ([[Brasvais Lattices]] discovered in 1848), plus [[#Non-localization]]. How can a crystal "coordinate" this? Locally while condensing atoms form icosahedrons (a lot of five-fold symmetry). Scientists hypothesized that these shapes can only include about 100 atoms, but they created a 3d version of this tiling, what we now call a [[Quasicrystal]], and simulated x-ray difraction through it, finding rings of difraction points. Just a few kilometers away, completely unaware of their work another scientist created a flaky material from aluminium and manganese, and after scattering electrons off of his material he got almost the exact same pattern. The "coordination" happens because rules for how verticies connect with each other are much stronger and define the pattern much clearer than edge rules (i.e., curves) and allow you to actually tile to $\infty$. Um… Atoms kinda are verticies.
That paper also realized Kepler's pentagonal snowflake.

## explaination
Розповідь я хотів би розпочати з подій 400-річної давності, а саме з Йогана Кеплера. Він найбільш відомий своїм відкриттям еліптичності орбіт планет. Але ще до цього він запропонував іншу модель, де між сферами, на яких були розміщені орбіти, були правильні многогранники (або Платонові тіла). Він вірив, що у всесвіту була глибока геометрична закономірність - от тільки не вгадав, яка. Також він стверджував, цього не довівши, що спосіб складати гарматні ядра одне на одного гранецентрованим кубічним пакуванням (+еквівалентні), є найефективнішим. Навіть якщо нам це здається очевидним, перше доведення опубліковано лише у 2017 році. Це припущення тепер називають гіпотезою Кеплера. Також він задумувався про шестикутну форму сніжинок. Їхню завжди шестикутну форму він пов'язував з тою ж проблемою складання ядер, гіпотетизуючи про "найменшу одиницю рідини, як-от води" - те, що ми тепер знаємо як атоми. Досліджував він і вимощення площини - заповнення площини припасовуючи один до одного однакові многокутники.
![[Ступені симетрії]]
Кеплер цікавився вимощеннями площини - заповненням всієї площини малими "плиточками". Цікавився ступенями обертальної симетрії цих мозаїк - всі самоповторювані вимощення мали ступені 2 (як-от ромби), 3 (як-от трикутники), 4 (як-от квадрати) і 6 (як-от шестикутники). П'ятий ступінь не існував, п'ятикутники не вимощують площину. Але це не зупинило Кеплера. В його нотатках ми знаходимо ось цей малюнок, який майже збігається з собою при повороті.  

Вимощення площини бувають періодичними (самоповторюваними) та неперіодичними. Є нескінченно багато фігур, які можуть вимостити площину періодичнр. Є деякі фігури - як-от правильний шестикутник - які можуть вимостити площину лише періодично. Є безліч фігур - як-от трикутники, які можуть вимостити площину як періодично, так і неперіодично. Наприклад, повернімо два окремі трикутники. Мозаїка вже не самоповторювана. Питання таке: чи є шматочки, з яких можна скласти лише неперіодичну мозаїку?  

У 1961 Хао Уенг досліджував вимощення площини кольоровими квадратиками. Умова така: квадрати не можна повертати, доторкатися можуть лише однакові кольори. Він припустив, що якщо певний набір квадратиків може вимостити площину, він це може зробити лише періодично. Це твердження спростував його учень, Річард Бергер, знайшовши набір 20,426 квадратиків які могли вимостити площину лише аперіодично. Нове питання таке: якою є найменша необхідна кількість шматочків для аперіодичної мозаїки? Сам Бергер потім опустив це число до 104, Роберт Кенут опустив його до 92, і в 1969 Рафаель Робінсон вигадав лише 6. Після цього на сцену виходять Роджер Пенроуз, який зменшує число до двох.  

Він розпочав з п'ятикутника. Додав п'ятикутники навколо нього і, очікувано, помітив отвори. Але ця нова форма може вміститися в іншому п'ятикутнику, що дало ідею поділити п'ятикутники на менші. Деякі ділянки тепер можна об'єднати. Але тут Пенроуз не зупинився, і поділив їх знову - і в деякі з отворів вже вміщалися п'ятикутники. Знову пооб'єднувавши їх ми отримуємо такі фігури: п'ятикутники, ромби, зірки і фрагменти зірки, які Пенроуз називав коронами справедливості. Продовжуючи ділити п'ятикутники ми не знайдемо нічого, окрім цих фігур. Так ми знайшли аперіодичне вимощення з обертальною симетрією п'ятого ступеня.  
 
Якщо повернутися до малюнка Кеплера, і накласти його на Пенроузову мозаїку, вони ідеально збігаються.  
  
Маючи свій візерунок, Пенроуз його надалі спростив до двох ромбів, і правила, як їх з'єднувати, можна позначити або за допомогою виступів та виямок, або - що буде зручніше - як набір правил щодо того, які вершини можуть доторкатися до яких.  
  
Якщо буде час: [[More patterns]] [[Different tilings]] [[Parallel lines]] [[What is phi doing here?]] [[Non-local coordination]]  