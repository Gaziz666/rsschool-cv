![foto](http://smexkartinka.ru/uploads/posts/2011-07/1311854899_image00040.jpg)
# Gaziz Tuleukulov
### Contacts
   * whatsapp: **+77017000666**
   * Telegram: **@Gaziz_T**
   * Email: **gaziz.cyprus@gmail.com**
### About Me 
  I have a 10-year experience in management and project management. but I like to do something more 
myself, than to manage and control employees.

From January 2020 I started learning programming. I a'm finished freecodecamp.org courses, learn.javascript.ru, htmlbook.ru. Now I am undergoing training in the Belarusian company AIS in the direction FrontEnd and Node.js.

I'm hoping to become a FullStack developer. and get a job in a big IT company, where I can learn and realize myself.

I have [portfolio](http://gazizdev.com/)
### Skills 
HTML5, CSS3, JavaScript, DOM, JSON,

basic knowledge in REACT/REDUCE, MongoDB, MYSQL, Node.js, Express, D3, GIT.
### Experience
[portfolio](http://gazizdev.com/),

[projects from courses](https://codepen.io/gaziz)      
### Educations:
* courses:  [freecodepen.org](https://www.freecodecamp.org/gaziz_cyprus)

* Bachelor of Systems Engineer (2003 – 2008)
  Karagandy State Technical University, 
  Karagandy city, Kazakhstan

* Bachelor of Laws (2010 – 2012)
  Femida Law Academy ,
  Karagandy city, Kazakhstan
  Education (including courses, seminars, lectures, online learning)
### English 
level B1. English courses.
### Code examples
    document.addEventListener("DOMContentLoaded", function () {
    //при нажатии кнопки меню или тело сайта то всплвающее меню должно скрыться
    let x = document.getElementById("checkbox-menu");
    let menuToch = document.getElementById("menuTouch");
    menuTouch.onclick = () => {
        if (x.checked == true) {
            x.checked = false;
        }
    };

    // настройка секции ABOUT блок knowledge
    let script = document.getElementById("script");
    let all = document.getElementById("all");
    let marckup = document.getElementById("marckup");
    let web = document.getElementById("web");
    let db = document.getElementById("db");
    let frameworks = document.getElementById("frameworks");

    //находим заголовки блока knowledge
    let areasOfKnowHeader = document.getElementById("areasOfKnowHeader");
    let areasHeaderLi = areasOfKnowHeader.querySelectorAll("li");

    //доступ к блокам через контейнер
    let knouwBlocks = document.getElementById("areasOfKnowBlock");
    let knowBlock = knouwBlocks.querySelectorAll("div"); // доступ ко всем блокам по классу

    // действие при нажатии на all, все становится непрозрачным
    all.onclick = function () {
        for (let i = 0; i < knowBlock.length; i++) {
        knowBlock[i].style.opacity = "1";
        knowBlock[i].style.animation = "scaling_full .6s steps(20) 1";
        knouwBlocks.classList.add("allArea");
        //удоляем все стили из других кнопок
        knouwBlocks.classList.remove("scriptArea");
        knouwBlocks.classList.remove("marckupArea");
        knouwBlocks.classList.remove("webArea");
        knouwBlocks.classList.remove("dbArea");
        knouwBlocks.classList.remove("frameworksArea");
        }
        // меням цвет фона при нажатии
        for (let i = 0; i < areasHeaderLi.length; i++) {
        if (areasHeaderLi[i].id == "all") {
            areasHeaderLi[i].style.background = "rgb(55, 80, 126)";
        } else {
            areasHeaderLi[i].style.background = "";
        }
        }
    };
