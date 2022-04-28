# Beautiful Console

## installation :

install :
```bash
pip install beautiful-console
```

import :
```python
from beautiful_console.beautiful_console import beautiful_console
```

## defined colors : 
>black, red, green, yellow, blue, magenta, cyan, white

## defined styles :
>**bold**, _italic_, underline, underline_bold, overline, ~~strikethrough~~

<br>

## beautiful_console()
Returns beautiful text.

```python
# only the text-parameter is required, then you can use any option you need

print(beautiful_console(
    "text",
    "text_color", # color of text
    "highlight_color", # color of background
    "continuous_color", # color of text when typing input
    "style", # style of text
    "blink", # blinking text <True or False>
    "text_color_degree", # intensity of text color <0 or 1>
    "highlight_color_degree", # intensity of background color <0 or 1>
    "continuous_color_degree", # intensity of continuous color <0 or 1>
    "get_input" # if this option is True, beautiful_console automatically generates a input-function (and returns input text)
))
```
# Tips : 

>**Tip** : some things may not work on some consoles.


>**Tip** : get_input can only be filled as a keyword argument (get_input=True). 
---
send your feedbacks to : pourya90091@gmail.com