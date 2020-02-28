# **Nikolay Kasperovich**

* Email:                            kolya.kasperovich@gmail.com
* Phone:                            +375 (25) 984-50-19
* Linkedin:                         [https://www.linkedin.com/in/nikolai-kasperovich]

# **Summary**
> Currently I'm working as Web developer and have more than 5 years of coding expirience. Constantly learning new trends and techologies. Everything changes, so I decided to try change my professonal area. This brought me to The Rolling Scopes. Since my college years I've been inspired by Steve Jobs. He is truly legend. And Apple products really bringing difference and innovations. So I registered to this course without hesitations. I have never develop for iOS before and eager to start brand new chapter in my career.
>
# **Main Skills**
* PHP
* Html
* CSS
* Java Script
* PHP frameworks
* C
* OOP
* Java
* Git
* MySql

# **Code examples**
Проверка строки на сбалансированность. На входе есть строка, содержащая только скобки из набора {}()[]

```
 <?php

        function isBalanced($string)
        {
            //массив скобок, где ключи - закрывающиеся скобки, а значения - соответствующие им открывающиеся.
            $bracesArray = [
        		'}' => '{',
        		')' => '(',
        		']' => '[',
        	];
            //объявляем массив, в который будем складывать все открывающиеся скобки
            $bracesFromStringStack = [];
            //создаем цикл по всей входящей строке
            for($i = 0; $i < strlen($string); $i++) {
                //берем текущий элемения строки
                $currentChar = $string[$i];
                //если текущий элемент - закрывающая скобка, заходим в условие
                if (isset($bracesArray[$currentChar])) {
                    //берем последнее значение массива, в  котором хранятся по порядку открывающиеся скобки, удаляя при этом это значение
                    $lastStackElement = array_pop($bracesFromStringStack);
                    //если взятое значение не равно текущему т.е не является соответствующей открывающейся скобкой, следовательно нарушено условие сбалансированности.
                    if ($lastStackElement != $bracesArray[$currentChar]) {
                        //выходим из цикла. Строка - не сбалансированная
                        return 'NO';
                    }

                } else {
                    //каждую открывающуюся скобку помещаем в массив, для дальнейшого стравнения
                    array_push($bracesFromStringStack, $currentChar);
                }
            }
            //после прохода цикла, если массив не пустой, то сбалансированность нарушена, пустой - строка сбалансирована.
            return $bracesFromStringStack ? "NO" : "YES";
        }
        ?>
```

# **Experience**
>I have more than 5 years expirience in web development, especially in e-commerce. I worked in several IT companies, 
and now is looking for new opportunities.

# **Education**
## Minsk radio engineering college' 2012
## Courses:
#### ***Java programming***
#### ***C language***
#### ***Android development***

# **English level**
My English level is B2 (Upper-Intermediate) according to online testing tool. I've learned it at school, college, and several courses. I don't have experience in spoken english with native speakers, but I think, I could express my thoughts quite confidently. 