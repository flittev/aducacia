<template>
  <div class="container mx-auto px-4 tracking-tighter">
    <div class="desktop:w-2/3 flex justify-end py-2 backdrop-blur-2xl ">
      <label class="p-2 font-semibold text-gray-400 " for="city_choice" >Выберите город:</label>
      <select class="bg-white border-2 border-green-600 rounded-full px-8 font-semibold tracking-tighter text-gray-400 " name="cars" id="city_choice" >
        <option class="bg-green-100" value="minsk">Минск</option>
        <option class="bg-green-100" value="gomel">Гомель</option>
        <option class="bg-green-100" value="hrodna">Гродно</option>
      </select>
    </div>

    <div id="paginator" class="flex justify-center text-gray-400 font-semibold desktop:w-2/3 py-4">
      <a href="#" class="transition hover:text-green-400 ml-6 flex items-center justify-center">&laquo;</a>
      <a href="#" class="ml-6 transition hover:bg-green-400 rounded-full h-8 w-8 flex items-center justify-center hover:text-white">1</a>
      <a class="active ml-6 bg-green-400 rounded-full h-8 w-8 border-2 border-green-600 flex items-center justify-center text-white" href="#">2</a>
      <a href="#" class="ml-6 transition hover:bg-green-400 rounded-full h-8 w-8 flex items-center justify-center hover:text-white">3</a>
      <a href="#" class="ml-6 transition hover:bg-green-400 rounded-full h-8 w-8 flex items-center justify-center hover:text-white">4</a>
      <a href="#" class="ml-6 transition hover:bg-green-400 rounded-full h-8 w-8 flex items-center justify-center hover:text-white">5</a>
      <a href="#" class="ml-6 transition hover:bg-green-400 rounded-full h-8 w-8 flex items-center justify-center hover:text-white">6</a>
      <a href="#" class="ml-6 transition hover:text-green-400 flex items-center justify-center">&raquo;</a>
    </div>

    
    <div class="bg-green-100 flex justify-center text-gray-400 font-semibold desktop:w-2/3">
      <div class="mr-5">
      Интересует:
      </div>
      <div>Начальная школа (4 класс) </div>
    </div>

    <figure class="desktop:w-2/3 text-justify ">
      <blockquote class="my-2 mb-8 text-gray-400 px-4">
        <h2 class="border-b-2 border-green-100 uppercase text-xl text-green-400 font-medium py-2">ребенок глазами родителей</h2>
       <p class="font-medium">Шкундалева Елизавета 29.07.2012 </p>
       <p>С малых лет я замечала (на детской площадке, в садике), что Лиза не очень нуждалась в общении со сверстниками. Она легко находила, чем заняться сама с собой. Ей легче было не дружить, чем уступить. С другой стороны, для Лизы всегда была важна личность взрослого. Отношения со взрослыми для нее были важнее, чем отношения с детьми. Так и в школе поступки, отношение учителя больше влияет на ее эмоциональное состояние, чем отношения с детьми. У Лизы остро выражено чувство справедливости. Если Лиза видит несправедливость, то не может ощущать себя спокойно, будет бунтовать, капризничать, уходить в отрицание. Она должна понимать почему она должна что-то делать, может легко обидеться.
          Поэтому часто наладить с ней контакт немного сложнее, чем с другими детьми (не работают такие методы как обнимашки, захваливание) и сложно разглядеть через ее ""колючесть"" что-то другое.
          Но, если взрослому удается войти в доверие, то у Лизы довольно гибкий ум, она быстро соображает, присутствует логическое мышление, хорошее воображение, чувство юмора, артистичность. Когда она работает вместе со взрослым, то она как пластилин: можно лепить любую форму. Но в сопротивлении результат получается нулевой.
          Увлечение: акробатика, занятия, связанные с решением логических задач (logic.by, шахматы)
       </p>
      </blockquote>
      <blockquote class="my-2 text-gray-400 bg-green-100 px-4 ">
        <h2 class="uppercase text-xl text-green-400 font-medium border-b-2 border-gray-100 py-2">учитель от бога глазами родителей</h2>
        "Кто такой учитель от Бога в моем понимании:
        1. Учитель хочет стать другом, опорой и защитой для Ребенка. Учитель умеет понимать, принимать (не пытается изменить) Ребенка, считается с его мыслями и чувствами, желаниями и нежеланиями, усталостью и страхами, с его правом на ошибку, с его правом выбора, с его уникальностью и единственностью. Помогает искать средства для преодоления трудностей (а не создает эти трудности для Ребенка сам)
        2. Учитель влюблен в свой предмет и хочет поделиться именно этими знаниями, умениями и любовью к ним. Учитель ориентирован на настоящее, а не будущее: учитель делится своими знаниями и навыками, чтобы Ребенок сейчас ощутил радость от познания, а не для того, чтобы Ребенок добился в будущем какого-то успеха.
        3. Учитель чувствует внутреннюю ответственность:
          - за результат. Придерживается принципа: """"Если Ребенок не может научиться, как мы учим, мы должны учить так, как он сможет научиться""""
          - за то влияние, которое он оказывает на Ребенка. Высокая степень осознанности. Учитель осознает, что его безответственность может нанести вред, соизмеримый с ущербом, наносимым, например, безответственным хирургом
        4. Учитель любит развиваться и в личностном и в профессиональном смысле
        5. Учитель идет ЗА Ребенком, а не НА ПОВОДУ у Ребенка

          Взгляды:
          ""Ребёнок создан развиваться, а в любви Ребенок находит в два раза больше сил для развития""

          Качества: честность с самим собой и окружающими, смелость взглянуть на себя, на уровень своих компетенций, внутренняя свобода, высокая степень эмпатии, критическое мышление, наполняется восторгом от общения с детьми, воспринимает знакомство с Ребенком, как знакомство с новым миром, а не как встреча с трудностями и новыми опасностями

          Умения: выстраивание собственных границ и умение помогать ребенку с приобретением этого навыка"
      </blockquote>
      
      <blockquote class="my-2 text-gray-400 px-4 ">
        <h2 class="uppercase text-xl text-green-400 font-medium border-b-2 border-green-100 py-2">мысли родителей</h2>
        <h3 class="uppercase text-base text-gray-400 font-medium mt-3">отношение к государственной школе</h3>
        Больше всего в гос. образовании мне не нравится система, в которую попадает молодой Учитель. Эта система построена на неуважении к личности Учителя. Система, которая принуждает выполнять то, что не относится к профессиональным компетенциям Учителя. Система, которая не возносит профессию Учителя как самую ценную, а унижает человека, подавляет волю. Система меняет фокус: Учитель должен больше думать, как приспособиться к системе, а не как стать проводником для Ребенка. В такой системе Учитель быстро теряет свои первоначальные цели (даже если они были) и перестраивается на подчинение системе. Учитель привыкает мириться с обстоятельствами, быть ничтожным, недооцененным, не иметь опору и поддержку. Таким Учителям трудно поверить, что их жизнь в их руках, что у них есть право выбора. Соответственно и научить они этому не могут. Как следствие, Учителя не мотивированы на общение с Ребенком, на эмпатию. Целью становятся подготовка к тестированию, поддержание дисциплины, а не научить Ребенка осознанно развивать свои способности. Меняются критерии оценки и самого Учителя. Заслуженный Учитель - это не всегда Учитель, который защищает интересы Ребенка. Учитель начинает чувствовать ответственность перед системой, а не перед Ребенком. Хороший Учитель в такой системе взращивается вопреки, а не благодаря ей.
        <div class="py-4">По большому счету, мне нравится школьная программа: все предметы школьной программы кажутся мне важными, и я бы хотела, чтобы мой ребенок имел возможность познакомиться с ними и освоить азы, понять о чем каждый из предметов, почувствовать, есть ли у него желание осваивать этот предмет глубже</div>      
        <h3 class="uppercase text-base text-gray-400 font-medium mt-3">Какая главная причина того, что Вы сейчас ищите Учителя? </h3>
        "Первый класс Лиза училась в гос. школе, второй и третий - в частной.
В гос. школе у нас была требовательная учительница, которую Лиза просто очень боялась. Ребенок потух. Она была послушной, исполнительной, но это не принесло ни счастья, ни успехов в учебе (чтение, письмо шли туго, математика - в рамках учебной программы, интерес пропал).
Что было неприемлемо лично для меня: учительница запугивала (например, ""тот, кто …, останется на второй год""), унижала учеников при всех (например, ""как не стыдно сделать … ошибок!""). Мировоззрение учителя не совпадало с моим. Учительница видела мир враждебным, где выживает сильнейший, и готовила детей выживать. ""Никто их по головке гладить не будет. Пусть привыкают."" Также учительница хотела высоких результатов за счет больших объемов дз. 
В частной школе не было атмосферы страха. Лиза перестала быть задавленной и начала проявлять свою протестную часть, начала показывать какие-то свои недовольства. И сложилась ситуация конфликта между Лизой и учительницей, которая так и не перетекла в конструктивное русло. Я могу охарактеризовать ситуацию как ""противостояние"" (что для меня уже странно между ребенком и взрослым, а тем более учителем. В моих глазах учитель - это помощник, опора, пример, а не соперник.) В такой ситуации у Лизы сложилось ощущение, что если она прекратит противостояние и начнет учиться, то это станет ее поражением.
Получилось, что в двух школах не создалась атмосфера, благоприятная для получения навыков и знаний. В первой Лиза просто была ведома страхом, а во второй уже раскрылась личность, но ее, такую как она есть, учитель принять, понять, подружиться и договориться не смогла.
Сейчас хочется сделать еще один шаг и встретить учителя, с которым Лизе будет комфортно такой какая она есть, и начнется то, ради чего я хочу водить ребенка в школу, процесс обучения."      
      <h3 class="uppercase text-base text-gray-400 font-medium mt-3">сотрудничество с учителем </h3>
       "Для меня важны две вещи: академические знания и здоровое психическое состояние ребенка. Я бы не хотела жертвовать знаниями ради здоровья и здоровьем ради знаний. Я верю, что с Ребенком можно делиться знаниями не травмируя психику ни Ребенка, ни Родителя, ни Учителя. Но так как система еще не выстроена должным образом, я понимаю, что Учителю в данной ситуации нужно быть больше, чем Учитель. И готова к сотрудничеству, чтобы разделить эту ношу. Но  у меня сложилось впечатление, что, когда я говорила учителям о готовности к сотрудничеству, эти слова понимались ими следующим образом:
- Я даю согласие принуждать своего ребенка к выполнению домашнего задания, которое дает учитель
- Если мой ребенок ведет себя неудобным образом, то я могу запретить ребенку так себя вести, если учитель меня об этом попросит
Для меня это не является сотрудничеством. Я под сотрудничеством понимаю достижение какой-то общей цели совместными усилиями. И это сотрудничество может принимать очень разные формы в зависимости от ситуации. Чтобы понять, какая форма нужно в каждом конкретном случае, важно иметь возможность открыто пообщаться между собой. Открытое общение - для меня самое главное в сотрудничестве с учителем. Поэтому первым шагом к сотрудничеству для меня является личное знакомство. Только при личном общении мы сможем понять, получится ли у нас честное общение на равных. Сможем ли мы выстроить отношения, не базирующиеся на подчинении (учителя родителю, родителя учителю), а на заботе и бережном отношении друг к другу. Сможем ли мы спокойно воспринимать критику друг друга, честно говорить про свои ощущения и сомнения, делиться идеями, слышать друг друга и приходить к общему знаменателю."
      </blockquote>
<figcaption class="py-4 font-medium w-1/4 bg-gradient-to-b from-green-400 to-green-100 text-gray-600 rounded-xl p-8">
        <div>Контакты</div>
        <div>показать</div>
        <div>+375291234567</div>
      </figcaption>
    </figure>
  </div>
</template>

