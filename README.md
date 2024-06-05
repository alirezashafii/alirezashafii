```php
<?php

class ITEngineer {
    private $name;
    private $role;
    private $language_spoken;

    public function __construct() {
        $this->name = "Alireza Shafi'i";
        $this->role = "IT Engineer";
        $this->language_spoken = ["fa_IR", "en_US"];
    }

    public function say_hi() {
        echo "Thanks for dropping by, hope you find some of my work interesting.";
    }
}

$me = new ITEngineer();
$me->say_hi();

?>
```

<!--
**alirezashafii/alirezashafii** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
