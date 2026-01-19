
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
