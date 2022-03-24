# Julia Oreshkina

### Contact information

**Phone:** +79376682006  
**E-mail:** filosofiaJulia@gmail.com  
**Telegram:** @JuliaOreshkina  
**GitHub:** [FilosofiaJulia](https://github.com/FilosofiaJulia)

### About myself

I’ve got some professional background as Russian teacher (2015-2021) and forensic linguist (2017-2019). While working at the school, I was in charge of the methodological part and participated in the teaching process improvement. Also I dealt with a large amount of data and successfully interacted with children, parents and colleagues.  
In 2021, I decided to change my profession and focused on different IT career paths as promising directions for me. My management experience made it possible to participate in SimbirSoft Summer Workshop and 
find out what project managers do. During Workshop I got interested in different types of development and especially in Front-end development.  
Currently I’m learning pure JavaScript on my own and looking forward to begin learning React. I’m also interested in software development methodologies such as Waterfall and Agile. I’m ready for challenges, hard work, new technologies and high-level mentoring.  
I’d like to complete the course successfully and find a job where I could improve my skills and become a good developer with strong soft skills as well as technical skills.

### Skills

- HTML5
- CSS3
- JavaScript (basic)
- Git
- Agile

### Code Example

**Replace With Alphabet Position:**  
*In this kata you are required to, given a string, replace every letter with its position in the alphabet. If anything in the text isn't a letter, ignore it and don't return it.*

```
function alphabetPosition(text) {
  return text.toLowerCase().split('')//возвращаем строку,где символы в нижнем регистре. преобразуем её в массив с символами
        .filter( symbol => symbol >= 'a' & symbol <= 'z' )//фильтруем его и создаем массив, где только символы от 'a' до 'z'
        .map( symbol => symbol.charCodeAt(0) - 'a'.charCodeAt(0) + 1)//на его основе создаем массив, где символы были заменены числовым значением
        .join(' ');// элементы полученного массива преобразуем в строку
}
```

### Education

Togliatti State University with Master’s degree in Philology (Forensic Linguistics) 2015-2017

##### Courses:
- Summer workshop for project managers by SimbirSoft
- JavaScript Manual on [learn.javascript.ru] (https://learn.javascript.ru/) (in progress)
- Сourse "JavaScript + React" on [udemy.com] (https://www.udemy.com/course/javascript_full/) 
(in progress: completed the section "Javascript basics")
- RS Schools Course "JavaScript/Front-end. Stage 1" (in progress)

### Languages

- Russian (native speaker)
- English B1 (according online test at [Inglex.ru](https://englex.ru/your-level/placement/?answer_id=3360623))