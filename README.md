hello, my friend change the branch to the one without bootstrap and fix some errors: 1. От ширина на екрана от 350px до 768px има бяло пространство в началото на сайта 2. Брандовете не са с еднаква големина виж “Calvin Klein” 3. Снимките не се виждат в цял размер; 

Цените не са добре позиционирани също и не се виждат почти на никоя резолюция; 4. Няма начално отстояние на footer-a 5. От ширина на екрана от 768px до 900px не се вижда част от менюто (липсват иконките: количка и потребител) 6. На продуктовата страница пак се режат снимките на продуктите Препоръки:

Изнеси всички общи стилове и всички променливи като:

:root {

   --footer-bg: #f3ecec;

  --footer-radius: 1.5625rem; /* 25px */

  --footer-padding: 0 0;

  --footer-grid-gap: 2rem; /* 32px */

  --footer-grid-gap-md: 1.5rem; /* 24px */

  --footer-grid-gap-sm: 1.25rem; /* 20px */

…

}

* {

  box-sizing: border-box;

}

html, body {

  margin: 0;

  padding: 0;

  width: 100%;

  max-width: 100vw;

  overflow-x: hidden;

}

В един файл применро sтyles.css, а в останалите css файлове остави само стиловете засягащи компонента.

Направи папка assets и в нея направи папка styles премести всички стилове там, както и папката images sorry for giving the instructions in bulgarian but I hope you can manage to fix everything I asked you in another chat to help with this but you stopped without finishing. Please, finish your work
