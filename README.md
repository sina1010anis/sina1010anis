
<div  align="center">
    <h2 style="color:#fff">
        <b>
            💫 About Me: I am Sina, I am interested in web programming and I work mostly in the back-end area.
        </b>
    </h2>
</div>
<br>

## 🌐 Socials:
<div id="badges" align="center">
    <a href="https://instagram.com/sina_nbzh">
        <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white"/>
    </a>      
     <a href="https://www.linkedin.com/in/sina-nayebzadeh/">
        <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white"/>
    </a>
     <a href="https://stackoverflow.com/users/20596419">
        <img src="https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white"/>
    </a>
</div>      

### :man_technologist: About Me

```php
<?php

namespace Developer\FullStack;

use Skills\Facade\Languages;
use Skills\Facade\Databases;
use Skills\Facade\Frameworks;
use Skills\Facade\Others;
use About\Facade\Bio;
class SinaNayebzade extends Developer
{
    use Languages, Databases, Frameworks, Others, Bio;

    const ABOUT_MY = 'I am a full stack developer but I am more interested in backend';
    public function skills()
    {

        Languages::push(['PHP', 'JavaScript']);

        Databases::push(['MySQL', 'MongoDB', 'Elasticsearch']);

        Frameworks::push(['Laravel', 'PHPUnit', 'Vuejs', 'Bootstrap', 'jquery']);

        Others::push([ 'OOP','Design Pattern', 'SOLID', 'MVC', 'HMVC', 'Laravel modules', 'Docker', 'Broadcasting', 'Git']);

    }

    public function bio()
    {

        Bio::about('Sina Nayebzade', 'Full-stack Developer(interest: Back-End)', 'sina1010anis@gmail.com', 'Iran, Mashhad')
            ->social(['Telegram' => 'sina_nayb', 'Instagram' => '@sina_nbzh', 'Stack overflow' => 'stackoverflow.com/users/20596419/sina-nbxh', 'Linkedin' => 'www.linkedin.com/in/sina-nayebzadeh'])
            ->behavior(['Interested in web programming', 'love to learn', 'regular', 'Strong interest in backend programming']);
        self::ABOUT_MY;

    }

}


```
<div id="badges" align="center">
    <a>
        <img src="https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white"/>
    </a>
    <a>
        <img src="https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white"/>
    </a>
    <a>
        <img src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white"/>
    </a> 
    <a>
        <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white"/>
    </a>
    <a>
        <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white"/>
    </a>
    <a>
        <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
    </a>
    <a>
        <img src="https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D"/>
    </a>  
    <a>
        <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/>
    </a>      
</div>      
</div>
<br>



# 📊 GitHub Stats:

<div id="github_stats" align="center">

![GitHub Streak](https://github-readme-stats.vercel.app/api?username=sina1010anis&theme=vision-friendly-dark&hide_border=true&include_all_commits=false&count_private=false)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=sina1010anis&layout=compact&theme=vision-friendly-dark)

</div>


