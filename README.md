👋 Oi, eu sou a Ynara

Engenheira de Software formada em Sistemas para Internet, Fullstack Developer por vocação e criadora de conteúdo tech nas horas vagas.
Construo soluções web com foco em performance, escalabilidade e experiência real de usuário — sem gambiarra romantizada.

Código bom é aquele que funciona hoje e continua funcionando amanhã.

🧠 Stack & Ferramentas
<p align="left"> <img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/php/php.png"/> <img height="32" src="https://static-00.iconduck.com/assets.00/laravel-icon-995x1024-dk77ahh4.png"/> <img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"/> <img height="32" src="https://static-00.iconduck.com/assets.00/react-original-wordmark-icon-840x1024-vhmauxp6.png"/> <img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"/> <img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"/> <img height="32" src="https://logosmarcas.net/wp-content/uploads/2020/09/Oracle-Logo.png"/> <img height="32" src="https://cdn.icon-icons.com/icons2/2415/PNG/512/git_original_logo_icon_146509.png"/> </p>
```php
<?php

  class YnaraSingleton {

    private static $instance;

    private __construct () {
      $this->call_me = 'Ynara Ventura';
      $this->code_name = 'γᴧν';
      $this->born_date = date('07-06-2002');
      $this->skills = array_combine([∑, ∞], ['PHP', 'CSS', 'NextJS', 'React', 'JavaScript']);
      $this->about = 'FullStack Developer';
    }

    public static function get_instance ($born_date) {
     if (empty(self::$instance))
        self::$instance = new YnaraSingleton();
      // retorna a unica instancia
      return self::instance;
    }

  }
?>

```
[website]: https://ynaralira.github.io/portifolio-ynara/
[youtube]: https://www.youtube.com/channel/UCfTPnFdC2xBQegg7aBZuDGw/
[instagram]: https://www.instagram.com/ynara_dev/
[linkedin]: https://www.linkedin.com/in/ynara-lira-ventura-797a341b7/


## Rede sociais

🏡 [Meu site][website] **|**
📺 [Youtube][youtube] **|**
📷 [Instagram][instagram] **|**
👔 [LinkedIn][linkedin]
