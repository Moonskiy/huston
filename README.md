<!DOCTYPE html>
<html>
    <head>
        <title>Хьюстон — что это?</title>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="styles.css">
        <style>
            body {
                margin-left: auto;
                margin-right: auto;
                width: 70%;
            }
            figure {
                clear: right;
                float: right;
            }
            table {
                width: 55;
            }
            .d {
            color:#8e8e8e;
            }
            div {
                padding: 20px;
                border-radius: 10px;
                background:#0e0f10;
                font-family: Roboto Regular, Roboto;
            }
            div.img-box {
                float: right;
                clear: right;
                margin: 0px 5px 10px 20px;
                border-radius: 5px;
                background-color: #111111;
                color: #fff;
                font-weight: 700;
                padding: 0.2em;
                box-shadow: 0px 0px 10px rgb(12, 12, 12);
            }
            div.img-box img {
                border-radius: 5px;
            }
            div.img-box figcaption {
                max-width: 200px;
                margin: 0 auto;
                padding: 10px 5px;
                word-wrap: break-word;
                text-align: center;
                font-size: 14px;
                font-family: Roboto, Poppins, Arial, Helvetica, sans-serif;
                letter-spacing: 1.5px;
                font-weight: 100;
                font-style: italic;
            }
            .main-img {
                display: block;
                height: 400px;
                margin: 30px auto;
            }
            header {
                min-height: 80vh;
                text-align: center;
                padding: 8px 50px;
                text-transform: uppercase;
                font-size: 40px;
            }
            header a {
                font-size: 30px;
                color: #fff;
                background: #141414;
                text-decoration: none;
                padding: 10px 15px;
                border-radius: 5px;
            }
            .nav-box {
                background: #060608;
                border-radius: 5px;
                width: 50%;
                margin: 0px auto;
                padding: 20px 60px;
            }

            nav ol {
                margin: 0 0 9px 0;
                padding: 0;
            }

            .nav-box li {
                list-style: none;
            }

            .nav-list-item {
                /* width: 100%; */
                margin: 0px auto 3px auto;
                padding: 7px 10px;
                background: #141414;
                border-left: 6px solid #fd8165;
            }

            nav a {
                text-decoration: none;
                font-size: 12px;
                color: #fff;
                font-variant: small-caps;
                text-transform: uppercase;
                letter-spacing: 1.5px;
            }

            .nav-list-item:hover {
                border-left: none;
                border-left: 8.5px solid #00ffc2;
                background: #060608;
            }

            .nav-list-item:active {
                border-left: 6px solid #00ffc2;
            }

            nav a:hover {
                color: #8e8e8e;
            }
            blockquote {
                background: #111111;
                padding: 15px 10px 15px 20px;
                margin: 40px 50px;
                border-left: 9px solid #02e2ac;
                border-radius: 3px;

                font-family: Roboto, Poppins, Arial, Helvetica, sans-serif;
                font-style: italic;
                font-weight: 200;
                letter-spacing: 1.5px;
            }
            table {
                width: 100%;
                border: 3px solid #161616;
                border-collapse: collapse;
                color: #8e8e8e;
                text-align: center;
                font-family: Roboto, Poppins, Arial, Helvetica, sans-serif;
                font-style: italic;
            }
            .table-box th,
            .table-box td {
                border: 2px solid #202020;
                padding: 5px;
            }
            .table-box th {
                color: grey;
            }
            .table-box td {
                color: #fd8165;
            }
            .table-box caption {
                color: #fff;
                font-weight: 700;

                margin: 30px 0px;
            }
            div.table-box {
                width: 90%;
                margin: 0px auto 30px auto;
                padding: 0px 10px 15px 10px;
                background: #111111;
                border-radius: 5px;
                }
            .border {
                list-style: none;
                padding: 0;
            }
            .border li {
                font-family: "Trebuchet MS", "Lucida Sans";
                padding: 7px 20px;
                margin-bottom: 10px;
                border-radius: 5px;
                border-left: 10px solid #f05d22; 
                box-shadow: 2px -2px 5px 0 rgba(0,0,0,.1),
                            -2px -2px 5px 0 rgba(0,0,0,.1),
                            2px 2px 5px 0 rgba(0,0,0,.1),
                            -2px 2px 5px 0 rgba(0,0,0,.1);
                font-size: 20px;
                letter-spacing: 2px;
                transition: 0.3s all linear;
            }
            .border li:nth-child(1){border-color: blanchedalmond;}
            .border li:nth-child(2){border-color: beige;}
            .border li:nth-child(3){border-color: brown;}
            .border li:nth-child(4){border-color: blue;}
            .border li:nth-child(5){border-color: yellow;}
            .border li:nth-child(6){border-color: green;}
            .border li:nth-child(7){border-color: navajowhite;}
            .border li:nth-child(8){border-color: teal;}
            .border li:nth-child(9){border-color: khaki;}
            .border li:nth-child(10){border-color: aqua;}
            .border li:nth-child(11){border-color: crimson;}
            .border li:nth-child(12){border-color: salmon;}
            .border li:nth-child(13){border-color: yellowgreen;}
            .border li:nth-child(14){border-color: honeydew;}
            .border li:nth-child(15){border-color: midnightblue;}
            .border li:nth-child(16){border-color: violet;}
            .border li:nth-child(17){border-color: palegreen;}
            .border li:nth-child(18){border-color: floralwhite;}
            .border li:hover {border-left: 10px solid transparent;}
            .border li:nth-child(1):hover {border-right: 10px solid blanchedalmond;}
            .border li:nth-child(2):hover {border-right: 10px solid beige;}
            .border li:nth-child(3):hover {border-right: 10px solid brown;}
            .border li:nth-child(4):hover {border-right: 10px solid blue;}
            .border li:nth-child(5):hover {border-right: 10px solid yellow;}
            .border li:nth-child(6):hover {border-right: 10px solid green;}
            .border li:nth-child(7):hover {border-right: 10px solid navajowhite;}
            .border li:nth-child(8):hover {border-right: 10px solid teal;}
            .border li:nth-child(9):hover {border-right: 10px solid khaki;}
            .border li:nth-child(10):hover {border-right: 10px solid aqua;}
            .border li:nth-child(11):hover {border-right: 10px solid crimson;}
            .border li:nth-child(12):hover {border-right: 10px solid salmon;}
            .border li:nth-child(13):hover {border-right: 10px solid yellowgreen;}
            .border li:nth-child(14):hover {border-right: 10px solid honeydew;}
            .border li:nth-child(15):hover {border-right: 10px solid midnightblue;}
            .border li:nth-child(16):hover {border-right: 10px solid violet;}
            .border li:nth-child(17):hover {border-right: 10px solid palegreen;}
            .border li:nth-child(18):hover {border-right: 10px solid floralwhite;}
        </style>
    </head>
  <body style="background-color:#060608;">
    <header>
        <h1 style="color: white;">Хьюстон</h1>
        <q style="color: grey;">у нас проблемы</q>
        <img class="main-img" src="2026512.png">
      </header>
    <div class="d">
    <font size="5">
      <b style="color:#fd8165;">Хьюстон</b> (англ. Houston) — четвёртый по количеству жителей город в
      Соединённых Штатах Америки и крупнейший город в штате Техас с населением 2
      319 603 человека на 2017 год. Хьюстон является административным центром
      округа Харрис, а также главным экономическим центром агломерации Большого
      Хьюстона с общим населением 6 772 470 человек на 2016 год. Город
      располагается в 50 километрах от Мексиканского залива на прибрежной
      равнине.
    </font>
    <p>
    <font size="5">
      Хьюстон был основан 30 августа 1836 года и включён в состав республики
      Техас 5 июня 1837 года, получив своё имя в честь Сэмюэла Хьюстона —
      главнокомандующего армией Техаса во время Техасской революции и президента
      Республики Техас. Быстрое развитие порта и железных дорог в XIX веке, а
      также начало добычи нефти и последовавшее развитие нефтяной промышленности
      в XX веке привели к быстрому росту населения. В 1960-е годы количество
      жителей превысило один миллион человек, а в 2000-е — два миллиона.
    </font>   
    </p>
    <p>
    <font size="5">
      Город является ведущим мировым центром энергетической промышленности, а
      экономика города также представлена предприятиями в области аэронавтики,
      транспорта и здравоохранения. Важнейшими объектами для экономики и
      инфраструктуры города являются космический центр имени Линдона Джонсона,
      крупнейший американский по международным грузоперевозкам порт, хьюстонский
      судоходный канал, крупнейший в мире Техасский медицинский центр.
    </font>
    </p>    
    <h1 align="center" style="color: white;">Содержание</h1>
    <div class="nav-box">
        <nav>
          <ol>
            <li>
              <a href="#1">
                <div class="nav-list-item" style="color:darkgray;">
                  История
                </div>
              </a> 
            </li>
            <ol>
              <li><a href="#2">
                  <div class="nav-list-item">Этимология, прозвища</div>
                </a></li>
              <li><a href="#3">
                  <div class="nav-list-item">Основание</div>
                </a></li>
              <li><a href="#4">
                  <div class="nav-list-item">XX век</div>
                </a></li>
            </ol>
            <li>
              <a href="#5">
                <div class="nav-list-item" style="color:darkgray;">Физико-географическая характеристика</div>
              </a>
            </li>
            <ol>
              <li>
                <a href="#6">
                  <div class="nav-list-item">Географическое положение и климат</div>
                </a>
              </li>
              <li><a href="#7">
                  <div class="nav-list-item">Рельеф, внутренние воды</div>
                </a></li>
              <li><a href="#8">
                  <div class="nav-list-item">Флора и фауна</div>
                </a></li>
            </ol>
            <li><a href="#9">
                <div class="nav-list-item" style="color:darkgray;">Экономика</div>
              </a></li>
            <ol>
              <li><a href="#10">
                  <div class="nav-list-item">Общее состояние</div>
                </a></li>
              <li>
                <a href="#11">
                  <div class="nav-list-item">Энергетика и нефтехимия</div>
                </a>
              </li>
              <li>
                <a href="#12">
                  <div class="nav-list-item">Авиакосмическая промышленность</div>
                </a>
              </li>
            </ol>
            <li><a href="#13">
                <div class="nav-list-item" style="color:darkgray;">Насление</div>
              </a></li>
            <ol>
              <li>
                <a href="#14">
                  <div class="nav-list-item">Динамика и структура населения</div>
                </a>
              </li>
              <li>
                <a href="#15">
                  <div class="nav-list-item">Этнический и конфессиональный состав, языки</div>
                </a>
              </li>
            </ol>
            <li><a href="#16">
                <div class="nav-list-item" style="color:darkgray;">Средства массовой информации</div>
              </a></li>
            <li><a href="#17">
                <div class="nav-list-item" style="color:darkgray;">Города-побратимы</div>
              </a></li>
    
          </ol>
        </nav>
      </div>
    <h1 id="1" style="color:white;" align="center"><div class="a"></div>История</h1>
    <h2 id="2" style="color:white;">Этимология, прозвища</h2>
    <div class="img-box">
    <figure>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ee/Sam_Houston_portrait.jpg/800px-Sam_Houston_portrait.jpg" width="278" height="300">
    <figcaption><i>Сэмюэл Хьюстон</i>
    </figcaption>
    </figure>
    </div>
    <p><font size="5">Город назван в честь Сэмюэла Хьюстона — главнокомандующего армией Техаса во время Техасской
        революции (1835—1836) и президента Республики Техас (1836—1838, 1841—1844).</font></p>
    <p><font size="5">Официальное прозвище Хьюстона — «Space city», которое можно перевести, как «космический
        город», «город космонавтики» или «космоград». Название дано из-за того, что здесь находится
        космический центр имени Линдона Джонсона. Всего город имеет 12 прозвищ.</font></p>
    <font size="5">
        В американской разговорной речи есть популярная фраза: «Хьюстон, у нас проблема» (англ.
        Houston, we've had a problem), появившаяся после неудачной миссии Аполлон-13. В Хьюстоне
        проходили съёмки фильма «Аполлон-13», в основу сюжета которого легли реальные события миссии.
    </font>
    <h2 id="3"style="color: white;">Основание</h2>
    <div class="img-box">
    <figure>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Allen%27s_Landing_Houston_bayou_view.jpg/1280px-Allen%27s_Landing_Houston_bayou_view.jpg" width="350" height="211">
    <figcaption><i>Allen's Landing — место, где был основан город</i>
    </figcaption>
    </figure>
    </div>
    <p><font size="5">После окончания войны за независимость Техаса, в августе 1836 года предприниматели братья Август
        и Джон Аллены купили 26,9 км² земли вдоль реки Буффало-Байю, планируя основать на ней
        населённый пункт. Они хотели, чтобы будущий город стал столицей Техаса и крупным торговым
        центром.</font></p>
    <p><font size="5">Датой основания города принято считать 30 августа 1836 года, когда братья Аллены разместили
        объявление о появлении города. Город назвали в честь генерала Сэма Хьюстона, возглавлявшего
        армию техасцев в битве при Сан-Хасинто во время войны против Мексики, позже избранного
        президентом Техаса. На январь 1837 года в посёлке проживало всего 12 человек, однако через четыре
        месяца население возросло до 1 500 человек. 5 июня 1837 года город был включён в округ Гаррисберг
        (ныне Харрис) и стал временной столицей Республики Техас, которой оставался до 1839 года.
        Первым мэром Хьюстона стал Джеймс Холман.</font></p>
    <h2 id="4" style="color: white;">XX век</h2>
    <div class="img-box">
    <figure>
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/e6/Main_Street_looking_south_Houston_Texas_%281908%29.jpg" width="250" height="158">
    <figcaption><i>Мэйн-Стрит в центре, 1908 год</i>
    </figcaption>
    </figure>
    </div>
    <p><font size="5">В 1900 году на Хьюстон обрушился Галвестонский ураган, продолжавшийся с 27 августа по 12
        сентября. В пересчете на сегодняшний курс ущерб составил бы $526 млн, погибло 8 тысяч человек. В
        следующем году было найдено большое месторождение нефти вблизи города Бомонт, что послужило
        началом развития нефтяной промышленности в Техасе. В 1902 году президент США Теодор Рузвельт
        утвердил проект стоимостью в $1 млн на реконструкцию хьюстонского судоходного канала. К 1910
        году численность населения города достигла 78 800 человек, почти в два раза превысив количество
        жителей проживавших в Хьюстоне в 1900 году. В 1914 году президент США Вудро Вильсон принял
        участие в открытии нового глубоководного порта Хьюстона, а через год был открыт хьюстонский
        судоходный канал.</font></p>
    <p><font size="5">В 1945 году было начато формирование Техасского медицинского центра. В конце 1940-х несколько
        пригородов были включены в городскую черту, в результате чего площадь Хьюстона увеличилась
        более чем в два раза. В 1950-е годы управления многих крупных (в основном нефтяных) компаний
        США переместились в Хьюстон, что благоприятно отразилось на экономике города, одним из
        поводов для переезда послужило массовое оснащение всех офисов кондиционерами.</font></p>
    <p align="center"><font size="5"><blockquote>Именно кондиционирование воздуха! Именно оно было основой для стремительного
        роста Хьюстона в 1950 году, когда он стал наиболее оснащённым кондиционерами
        городом в мире. Именно это стимулировало многие корпорации переместить свои штаб-
        квартиры в Хьюстон.</blockquote></font></p>
    <p><font size="5">В 1962—1964 годах в двадцати пяти милях к югу от центра Хьюстона, на землях, переданных
        федеральному правительству университетом Райса, был построен Центр управления космическими
        кораблями, с 1973 года носящий имя Линдона Джонсона. В 1960-х годах население Хьюстона
        достигло миллиона человек.</font></p>
    <h1 id="5" align="center" style="color: white;">Физико-географическая характеристика</h1>
    <h2 id="6" style="color: white;">Географическое положение и климат</h2>
    <div class="img-box">
    <figure>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/40/Houston_by_Sentinel-2%2C_2020-09-30_%28small_version%29.jpg/1024px-Houston_by_Sentinel-2%2C_2020-09-30_%28small_version%29.jpg" width="310" height="280">
    <figcaption><i>Хьюстон со спутника Landsat 7</i>
    </figcaption>
    </figure>
    </div>
    <p><font size="5">Хьюстон расположен в 50 километрах от Мексиканского залива на прибрежной равнине.
        Значительная часть города была построена на лесных угодьях, болотах и прериях, они до сих пор
        сохранились в близлежащих районах около Хьюстона. Город расположен на территории, для которой
        обычны частые ливни и дожди, поэтому для Хьюстона наводнения — постоянная проблема. Высота
        города над уровнем моря в среднем 15 метров, самая высшая точка — северо-запад Хьюстона (38
        метров). Площадь города составляет 1 552,9 км²</font></p>
    <p><font size="5">Весной и летом в городе жарко и влажно: средняя температура весной 21 °C, а летом — 28,8 °C. Из-за
        высокой температуры почти во всех транспортных средствах и зданиях установлены кондиционеры.
        Абсолютный максимум температуры был зарегистрирован в 2000 и 2011 годах, когда она составила
        42,8 °C. На Хьюстон часто обрушиваются ураганы, самые крупные из которых за последние
        десятилетия — «Эллисон» и «Айк». Осень — достаточно тёплое время года, особенно сентябрь.
        Температура в этом месяце выше, чем в мае. Средняя температура осенью составляет 21,8 °C, а
        среднее количество осадков — самое высокое в году (359,7 мм). Зима тёплая. Самая низкая
        температура была зарегистрирована в 1930 году — −15 °C. Средняя температура зимой составляет
        12,6 °C, а максимальная была зарегистрирована в 1986 году — 32,8 °C. 18 дней в году температура
        опускается ниже 0 °C. Обычно зимой осадки выпадают в виде дождя, но редко могут быть и в виде
        снега. Начиная с 1895 года, снег падал 35 раз, причём 21 раз устанавливался временный снежный
        покров.</font></p>
        <div class="table-box">
        <table>
        <tr>
            <caption>Дни с ясной и дождливой погодой в месяц (суммарно по часам)</caption>
        </tr>
        <tr>
            <td>Месяц</td>
            <td>Янв</td>
            <td>Фев</td>
            <td>Мар</td>
            <td>Апр</td>
            <td>Май</td>
            <td>Июн</td>
            <td>Июл</td>
            <td>Авг</td>
            <td>Сен</td>
            <td>Окт</td>
            <td>Ноя</td> 
            <td>Дек</td>
            <td>Год</td>
        </tr>
        <tr>
            <th>Солнечное сияние, день</th>
            <th>10</th>
            <th>10</th>
            <th>9</th>
            <th>8</th>
            <th>8</th>
            <th>8</th>
            <th>10</th>
            <th>9</th>
            <th>7</th>
            <th>7</th>
            <th>8</th>
            <th>9</th>
            <th>106</th>
        </tr>
        <tr>
            <th>Дождь, день</th>
            <th>14</th>
            <th>12</th>
            <th>12</th>
            <th>10</th>
            <th>10</th>
            <th>14</th>
            <th>13</th>
            <th>12</th>
            <th>10</th>
            <th>9</th>
            <th>10</th>
            <th>12</th>
            <th>136</th>
        </tr>
    </table>
    </div>
    <h2 id="7" style="color: white;">Рельеф, внутренние воды</h2>
    <p><font size="5">Для почв Хьюстона характерно наличие осадочных горных пород и песка. На поверхности часты
        эрозии, на территории города находится около 300 разломов, их общая длина примерно 500 км. Один
        из них — Long Point–Eureka Heights fault system. Также есть уникальные отложения из смеси песков и
        глин, благодаря ним, через определённое время, из разлагающихся органических веществ образуются
        нефть и природный газ. На окраинах Хьюстона встречается чёрная плодородная почва, на которой
        растят рис, сою, зерновые культуры, овощи и разводят крупный рогатый скот, лошадей, свиней и
        домашнюю птицу. В городе и его окрестностях имеется очень малая вероятность сильного
        землетрясения, а самое сильное землетрясение магнитудой 3,8 было в 1910 году.</font></p>
    <p><font size="5">В Хьюстоне протекают четыре реки. Основная, Буффало-Байю, проходит через центр города и
        хьюстонский судоходный канал, и имеет три притока. Брес-Байю протекает вдоль района Техасского
        медицинского центра, Симс-Байю проходит через южную часть города, Уайт-Ок-Байю — через
        северную часть города. Судоходный канал следует дальше до Галвестона, вплоть до Мексиканского
        залива. В пригороде находятся два озера: Конро и Хьюстон, которые являются водохранилищем и
        служат городскими источниками воды. На территории города протекает множество подземных вод,
        которые раньше активно использовали для водоснабжения, но перестали из-за медленного движения
        земной поверхности.</font></p>
    <h2 id="8" style="color: white;">Флора и фауна</h2>
    <div class="img-box">
    <figure>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Discovery_green.JPG/1280px-Discovery_green.JPG" width="250" height="167">
    <figcaption><i>Парк Discovery green в центре Хьюстона</i>
    </figcaption>
    </figure>
    </div> 
     <p><font size="5">В флоре и фауне округа Харрис преобладают виды животных и растений, обитающих в болотных
        местностях, так как значительная часть города построена на болотах и прериях.</font></p>
    <p><font size="5">Среди земноводных и пресмыкающихся наиболее известны хьюстонская жаба и техасская рогатая
        ящерица. Среди млекопитающих можно отметить рыжего волка, оцелота и канадскую выдру. Среди
        птиц замечаются американский клювач и белоголовый орлан. Численность большинства животных за
        последний век значительно сократилась в черте округа и находится под угрозой исчезновения из-за
        их истребления и ухудшения экологической обстановки. В городе также водятся комары,
        представляющие опасность человеку.</font></p>
    <p><font size="5">В городе и его пригородах растут сосны, пальмы и другие деревья, растущие в субтропическом
        климате. Среди растений, произрастающих в городе, можно выделить орхидеи и магнолии.</font></p>
    <h1 id="9" align="center" style="color: white;">Экономика</h1>
    <h2 id="10" style="color: white;">Общее состояние</h2>
    <h3></h3>
    <div class="table-box">
    <table>
            <caption>Крупнейшие компании, базирующиеся в Хьюстоне по версии Fortune 500 на 2016 год.</caption>
        <tr>
            <td>Техас</td>
            <td>Компания</td>
            <td>США</td>
        </tr>
        <tr>
            <th>3</th>
            <th>Phillips 66</th>
            <th>30</th>
        </tr>
        <tr>
            <th>5</th>
            <th>Sysco</th>
            <th>57</th>
        </tr>
            <th>8</th>
            <th>ConocoPhillips</th>
            <th>90</th>
        <tr>
            <th>10</th>
            <th>Enterprise Products Partners</th>
            <th>104</th>
        </tr>
        <tr>
            <th>12</th>
            <th>Halliburton</th>
            <th>117</th>
        </tr>
        <tr>
            <th>13</th>
            <th>Plains All American Pipeline</th>
            <th>121</th>
        </tr>
        <tr>
            <th>18</th>
            <th>Baker Hughes</th>
            <th>178</th>
        </tr>
        <tr>
            <th>20</th>
            <th>National Oilwell Varco</th>
            <th>192</th>
        </tr>
        <tr>
            <th>21</th>
            <th>Kinder Morgan</th>
            <th>198</th>
        </tr>
        <tr>
            <th>24</th>
            <th>Waste Management</th>
            <th>221</th>
        </tr>
        <tr>
            <th>25</th>
            <th>Occidental Petroleum</th>
            <th>225</th>
        </tr>
        <tr>
            <th>29</th>
            <th>Group 1 Automotive</th>
            <th>267</th>
        </tr>
        <tr>
            <th>34</th>
            <th>Cameron International</th>
            <th>319</th>
        </tr>
        <tr>
            <th>35</th>
            <th>EOG Resources</th>
            <th>322</th>
         </tr>
         <tr>
            <th>38</th>
            <th>Quanta Services</th>
            <th>352</th>
         </tr>
         <tr>
            <th>39</th>
            <th>CenterPoint Energy</th>
            <th>363</th>
         </tr>
         <tr>
            <th>40</th>
            <th>Targa Resources</th>
            <th>387</th>
         </tr>
         <tr>
            <th>41</th>
            <th>Apache</th>
            <th>388</th>
         </tr>
         <tr>
            <th>42</th>
            <th>Calpine</th>
            <th>402</th>
         </tr>
         <tr>
            <th>45</th>
            <th>FMC Technologies</th>
            <th>410</th>
         </tr>
         <tr>
            <th>49</th>
            <th>Marathon Oil</th>
            <th>438</th>
         </tr>
         <tr>
            <th>52</th>
            <th>Spectra Energy</th>
            <th>493</th>
         </tr>
    </table>
    </div>
    <div class="img-box">
    <figure>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/Houston_Ship_Channel.jpg/1024px-Houston_Ship_Channel.jpg" width="250" height="164">
        <figcaption><i>Хьюстонский судоходный канал</i>
        </figcaption>
        </figure>
        </div>
    <p><font size="5">Хьюстон является одним из ведущих городов мира в сферах добычи и переработки нефти и
        природного газа, из-за чего часто именуется «энергетической столицей мира», а также
        биомедицинских исследований и аэронавтики. Также Хьюстон имеет репутацию «зелёного города»,
        так как половина электроэнергии производится с помощью солнечных и ветряных установок.
        Большую роль в транспортной сфере города играет порт. В Хьюстоне базируется 22 компании из
        списка Fortune 500.</font></p>
    <p><font size="5">Международная исследовательская компания Mercer в 2017 году отвела Хьюстону 67 место в
        рейтинге самых удобных для проживания городов мира — между британским Белфастом и
        американским Майами, и 75 место среди городов мира по стоимости жизни — наравне с Бангкоком,
        Дохой и Мюнхеном. Город сильно снизил позиции из-за экономической ситуации и на 2016 год
        занимает лишь 63 место в США в категории «лучшие места для бизнеса и карьеры» по версии
        журнала Forbes. Исследовательская компания A.T. Kearney поставила Хьюстон на 38 место в списке
        глобальных городов мира. В исследованиях университета Лафборо о глобальных городах Хьюстону
        поставлена категория «Бета+», как и Дюссельдорфу, Монреалю, Тель-Авиву.</font></p>
    <p><font size="5">Минимальная заработная плата в Хьюстоне в час составляет $7,25 или $1 257 в месяц. Безработица на
        начало 2017 года составила 5,8 %. За чертой бедности находятся 9,2 % жителей. Средние доходы
        семьи на 2016 год по данным Forbes составляют $60 840, а средняя цена дома составляет $219 000.</font></p>
    <h2 id="11" style="color: white;">Энергетика и нефтехимия</h2>
    <p><font size="5">В Хьюстоне находится более 5 тысяч энергетических компаний, связанных с ведением бизнеса в этом
        регионе. В городе находятся штаб-квартиры множества энергетических и нефтяных компаний,
        входящих в список Fortune 500. Хьюстон является членом Всемирного партнёрства энергетических
        городов.</font></p>
        <div class="img-box">
        <figure>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Enron_Complex.jpg/1024px-Enron_Complex.jpg" width="250" height="167">
        <figcaption><i>Офис компании Chevron в Хьюстоне</i>
        </figcaption>
        </figure>
        </div>
    <p><font size="5">Одной из самых крупных компаний, обеспечивающих электроэнергией город, является компания
        CenterPoint Energy, которая поставляет электричество не только для Техаса, но и для Арканзаса,
        Луизианы, Миннесоты, Миссисипи, Оклахомы. Услугами компании пользуются более 5 млн человек.
        Другая крупная энергетическая компания Calpine занимает 42 место в Техасе и 402 в США в рейтинге
        Fortune 500. Корпорация обладает парком из 84 электростанций разных типов, разбросанных по всей
        территории США. Одна из них, Channel Energy Center, расположена в самом Хьюстоне, на берегу
        судоходного канала, ещё одна, Baytown Energy Center — в пригороде Бейтаун. Максимальная
        мощность хьюстонской электростанции — 808 мегаватт (базовая — 723 МВт), бейтаунская
        электростанция в пиковом режиме способна производить 842 мегаватт (базовая электрическая
        мощность — 782 МВт). На территории метрополии Большого Хьюстона действует восемь
        электростанций Calpine.</font></p>
    <p><font size="5">Хьюстон является одним из крупнейших производственных центров мира для нефтехимической
        промышленности. В городе располагаются больше 3 700 организаций, работающих в сфере
        нефтехимии. Также в хьюстонском регионе находятся 9 нефтеперерабатывающих заводов,
        перерабатывающих 2,3 миллиона баррелей в день, что составляет 13,2 % от всей переработки в США.
        Также в Хьюстоне имеется 719 предприятий по созданию химических и пласстмасовых изделий. В
        городе находится 17,5 % рабочих мест, занятых в сфере нефетехимии, из всех мест в США (112,6
        тысячи из 643,3 тысяч). Город занимает лидирующее место по производству товаров из полиэтилена
        (38,7 % от всего производства в США), поливинилхлорида (35,9 %) и полипропилена (48,4 %).</font></p>
    <h2 id="12" style="color: white;">Авиакосмическая промышленность</h2>
        <div class="img-box">
        <figure>
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f0/Aerial_View_of_the_Johnson_Space_Center_-_GPN-2000-001112.jpg?uselang=ru" width="250" height="250">
        <figcaption><i>Космический центр им. Джонсона</i>
        </figcaption>
        </figure>
        </div>
    <p><font size="5">В Хьюстоне располагается космический центр имени Линдона Джонсона, представляющий собой
        научно-исследовательское и проектно-конструкторское предприятие, в котором работают 15000
        человек (3000 инженеров и учёных, 12000 остальных рабочих). Всего в городе располагаются больше
        150 организаций, имеющих дело с космической отраслью.</font></p>
    <p><font size="5">В районе Хьюстона находятся производственные мощности компании Lockheed Martin, а также офис
        программы строительства космического корабля «Орион» для NASA. В городе расположены
        производственные мощности компании Boeing, а также штаб-квартира подразделения «Boeing Space
        Exploration», занимающаяся исследованием космических систем. Мощности компании Beechcraft,
        находящиеся в аэропорте им. Хобби, занимаются техническим обслуживаем и ремонтом воздушных
        судов. Компания Barrios Technology выполняет контракты для NASA, связанные с кораблём «Орион»,
        а также разрабатывает программное обеспечение для воздушных судов Boeing. Другими крупными
        исполнителями заказов NASA в Хьюстоне являются: Computer Sciences Corporation — техническое
        обслуживание и модификация самолётов, Jacobs Engineering Group — машиноведение, L-3
        Communications — роботехника, MEI Technologies — электрические инженерные системы,
        Oceaneering International — скафандры и прилагающееся аппаратное обеспечение, Raytheon —
        лаборатория нейтральной плавучести и макеты космических короблей, SAIC — безопасность и
        поддержка миссий, United Space Alliance — координационный центр информации, United
        Technologies — внекорабельная деятельность, Wyle Laboratories — космическая биология.</font></p>
    <h1 id="13" align="center" style="color: white;">Население</h1>
    <h2 id="14" style="color: white;">Динамика и структура населения</h2>
    <div class="table-box">
    <table>
            <caption>Перепись населения</caption>
        <tr>
            <td>Год переписи</td>
            <td>Нас.</td>
            <td>%±</td>
        </tr>
        <tr>
            <th>1850</th>
            <th>2396</th>
            <th>—</th>
        </tr>
        <tr>
            <th>1860</th>
            <th>4845</th>
            <th>102.2%</th>
        </tr>
        <tr>
            <th>1870</th>
            <th>9332</th>
            <th>92.6%</th>
        </tr>
        <tr>
            <th>1880</th>
            <th>16 513</th>
            <th>77%</th>
        </tr>
        <tr>
            <th>1890</th>
            <th>27 557</th>
            <th>66.9%</th>
        </tr>
        <tr>
            <th>1900</th>
            <th>44 633</th>
            <th>62%</th>
        </tr>
        <tr>
            <th>1910</th>
            <th>78 800</th>
            <th>76.6%</th>
        </tr>
        <tr>
            <th>1920</th>
            <th>138 276</th>
            <th>75.5%</th>
        </tr>
        <tr>
            <th>1930</th>
            <th>292 353</th>
            <th>111.4%</th>
        </tr>
        <tr>
            <th>1940</th>
            <th>384 514</th>
            <th>31.5%</th>
        </tr>
        <tr>
            <th>1950</th>
            <th>596 163</th>
            <th>55%</th> 
        </tr>
        <tr>
            <th>1960</th>
            <th>938 219</th>
            <th>57.4%</th>
        </tr>
        <tr>
            <th>1970</th>
            <th>1 232 802</th>
            <th>31.4%</th>
        </tr>
        <tr>
            <th>1980</th>
            <th>1 595 138</th>
            <th>29.4%</th>
        </tr>
        <tr>
            <th>1990</th>
            <th>1 630 553</th>
            <th>2.2%</th>
        </tr>
        <tr>
            <th>2000</th>
            <th>1 953 631</th>
            <th>19.8%</th>
        </tr>
        <tr>
            <th>2010</th>
            <th>2 100 263</th>
            <th>7.5%</th>
        </tr>
        <tr>
            <th>2020</th>
            <th>2 304 580</th>
            <th>9.7%</th>
        </tr>
    </table>
    </div>
    <div class="img-box">
    <figure>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/Race_and_ethnicity_2010-_Houston.png/220px-Race_and_ethnicity_2010-_Houston.png" width="250" height="250">
        <figcaption><i>Этническая карта Хьюстона</i>
        </figcaption>
    </figure>
    </div>
    <p><font size="5">Согласно данным переписи населения США в 2010 году в городе проживало 2 100 263 человек, это на
        7,5 % больше, чем в 2000 году. По оценке бюро переписи населения США на 1 января 2017 года
        население составило 2 319 603 человека. Население города, начиная с его основания, постоянно
        растёт: в 1960-х годах оно достигло 1 млн жителей, а в 2000-х годах превысило 2 млн. Плотность
        населения в среднем составляет 1494 чел./км².</font></p>
    <p><font size="5">Возрастной состав населения: до 19 лет — 28,67 %; от 20 до 44 лет — 39,83 %; от 45 до 64 лет —
        22,45 %; от 65 лет — 9,05 %. Средний возраст составляет 32 года. Количество женщин от всего
        населения — 49,82 %, мужчин — 50,18 %.</font></p>
    <h2 id="15" style="color: white;">Этнический и конфессиональный состав, языки</h2>
    <p><font size="5">Из-за близости к Мексике доля выходцев из Латинской Америки составляет 43,8 % от всего
        населения. В абсолютных цифрах численность латиноамериканцев выросла с 731 до 920 тысяч
        человек за период 2000—2010 годов. Второе место в расовом составе города занимают белые люди,
        которые составляют 25,6 % от городского населения — их численность за десятилетие снизилась на
        10 % с 602 до 538 тысяч человек. Также значительное население занимают афроамериканцы (23,1 %)
        и азиаты (6,15 %), чуть более 1 % составляют лица других национальностей. Иммиграция в Хьюстон
        в 2015 году составила 19 630 человек. 28 % жителей Хьюстона родились в другой стране: 72,5 % —
        из Латинской Америки, 18,9 % — из Азии, 3,9 % и 3,8 % — из Африки и Европы соответственно, 0,2
        % — из Океании. До 1960-х годов основными иммигрантами были люди из Европы, но с принятием в
        1965 году нового закона об иммиграции и гражданстве, отменившего квоты по национальности,
        большинство иммигрантов стало приезжать из Латинской Америки, Азии и Африки. В 2005 году 240
        тысяч жителей Нового Орлеана, на который обрушился ураган «Катрина», эвакуировались в
        Хьюстон. Впоследствии, до 40 тыс. человек осталось жить в городе.</font></p>
    <p><font size="5">50 % жителей города разговаривают только на английском языке. 34 % жителей разговаривают на
        испанском языке, по 1 % — на вьетнамском и китайском, по 0,2-0,4 % — на французском, урду,
        арабском, хинди, тагальском и корейском языках. Всего в городе разговаривают более чем на 100
        языках.</font></p>
    <p><font size="5">18,44 % жителей исповедуют католицизм, 16,29 % — баптизм, 4,68 % — методизм, 2,86 % — ислам,
        0,53 % — иудаизм. Всего исповедуют религию 58,4 % хьюстонцев, 41,6 % — неверующие.</font></p>
    <h1 id="16" align="center" style="color: white;">Средства массовой информации</h1>
    <div class="img-box">
    <figure>
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/aa/Melcher_Center_for_Public_Broadcasting.jpg" width="250" height="200">
        <figcaption><i>Вещательный центр, откуда вещают радиостанции KUHT и KUHF</i>
        </figcaption>
    </figure>
    </div>
    <p><font size="5">В Хьюстоне вещают 19 телеканалов. Наиболее известные телеканалы являются аффилированными
        каналами крупных телекомпаний: KPRC-TV (NBC), KHOU-TV (CBS), KTRK-TV (ABC), KRIV (Fox),
        KIAH (The CW) и KTXH (MyNetworkTV). Телеканал KUHT является членом национальной
        общественной телевещательной службы PBS.</font></p>
    <p><font size="5">В Хьюстоне вещают 29 радиостанций. Одна из крупнейших радиостанций, KUHF, принадлежит
        Хьюстонской университетской системе.</font></p>
    <p><font size="5"><i>Houston Chronicle</i> — крупнейшая ежедневная газета Хьюстона и штата Техас, которая принадлежит
        нью-йоркской корпорации Hearst Corporation. В 2014 году ежедневный тираж газеты составлял 356
        347 экземпляров, что ставит её на 16 место по тиражу среди всех газет США. До 1995 года
        существовала <i>Houston Post</i>, но была поглощена <i>Houston Chronicle</i>. На сегодняшний день
        единственным основным альтернативным городским изданием остаётся еженедельник <i>Houston Press</i>,
        его еженедельный тираж 2016 году составлял 43 810 экземпляров. В Хьюстоне выпускается газета
        <i>Houston Business Journal</i>, которая является частью компании American City Business Journals.</font></p>
    <h1 id="17" align="center" style="color: white;">Города-побратимы</h1>
    <p><font size="5">Согласно городскому сайту, у Хьюстона 18 городов-побратимов (в последний раз этот список
        расширялся в 2015 году, когда к нему присоединилась Басра):</font></p>
    <ul class="border">
    <font size="5">
        <li>Абу-Даби (ОАЭ);</li>
        <li>Абердин (Шотландия);</li>
        <li>Гуаякиль (Эквадор);</li>
        <li>Карачи (Пакистан);</li>
        <li>Баку (Азербайджан);</li>
        <li>Лейпциг (Германия);</li>
        <li>Ницца (Франция);</li>
        <li>Луанда (Ангола);</li>
        <li>Ставангер (Норвегия);</li>
        <li>Тайбэй (Тайвань);</li>
        <li>Стамбул (Турция);</li>
        <li>Перт (Австралия);</li>
        <li>Тюмень (Россия);</li>
        <li>Тампико (Мексика);</li>
        <li>Уэльва (Испания);</li>
        <li>Тиба (Япония);</li>
        <li>Шэньчжэнь (Китай);</li>
        <li>Басра (Ирак)</li>
    </font>
    </ul>
    </body>
</html>
