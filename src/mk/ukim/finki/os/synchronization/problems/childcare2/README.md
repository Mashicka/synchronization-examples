Маша Беќковиќ 121135

Во една градинка има правило дека секогаш мора има една присутна воспитувачка за најмногу три деца.
Во почетниот код кој е даден, дефинирани се класите Adult и Child, кои ги симболизираат воспитувачките и  децата од градинката.

При тоа, воспитувачка смее да влезе кога сака. Воспитувачката не смее да излезе доколку има деца за чување.

Детето може да влезе само доколку има место за него, односно само доколку има воспитувачка за да го чува.
Детето смее да си оди кога сака.

Во решението мора да се искористат неколку методи кои ќе ја дефинираат состојбата.
state.adultArrived()
- Го симболизира пристигнувањето на воспитувачка

state.adultEntered()
- Го симболизира влегувањето на воспитувачка

state.adultLeft()
- Го симболизира заминувањето на воспитувачка

state.childArrived()
- Го симболизира пристигнувањето на детето

state.childEntered()
- Го симболизира влегувањето на детето

state.childLeft()
- Го симболизира заминувањето на детето

Се користат семафори и бројачи по желба. Тие треба да се дефинираат на почетокот од класата и треба да се static. Се иницијализираат во методот init().
Вашата задача е да ги имплементирате методите Child.execute(),  Adult.execute() и init(). При имплементацијата, не смеете да додадете try-catch блок во нив. Потребните семафори, глобални променливи и променливи за состојбата треба да ги дефинирате самите.
Доколку имате грешка, ќе ја добиете пораката:
Procesot ne e sinhroniziran spored uslovite na zadacata.

По што ќе ви се прикаже логот на повикување на акциите и настанатите грешки. Овој лог треба да ви послужи за увидување на тоа каде имате грешка во извршувањето на вашата задача.
Напомена: Поради конкурентниот пристап за логирањето, можно е некои од пораките да не се на позицијата каде што треба да се. Токму затоа, овие пораки користете ги само како информација, но не се ослонувајте на нив.
