
# Вопросы для собеседования по PHP

:information_source: В этом репозитории содержаться вопросы и ответы с помощью которых вы можете подготовиться к собеседованию по PHP

:iphone: Telegram-канал - [@phpquiz](https://t.me/phpquiz)

:bar_chart: Вопросов - 2.

:pencil: Вы можете добавить свой вопрос или обьяснение, исправить/дополнить существующий с помощью пул реквеста :)

# Todo:
- разделить вопросы по категориям
- разделить вопросы по сложности

# Список вопросов и ответов

<details>
<summary><b>1. Что выведет код?</b></summary><br>

```php
<?php declare(strict_types=1);

function foo(int $x): ?void {
    if($x === 1) {
        return;
    }

    return null;
}

var_dump(foo('1'));
```


<details>
<summary><b>Ответ</b></summary><br>
Fatal error:  Void type cannot be nullable
</details>

</details>

<details>
<summary><b>2. Что выведет код?</b></summary><br>

```php
<?php

function printer() {  
    while (true) {     
        echo yield;       
    }                             
}                                

$print = printer();
$print->send('Hello ');
$print->send('proghub');
$print->send('!');
```


<details>
<summary><b>Ответ</b></summary><br>
Hello proghub!
</details>

</details>