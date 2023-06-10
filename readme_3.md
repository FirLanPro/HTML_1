## CSS

# синтаксис 
	    селектор{
		    свойство1:значение1;
		    свойство2:значение2;
	    }
### пример:
	p{
		color:green;
	} 

### сокращённо

    селектор свойство1:значение1 свойство2:значение2;}	

## комментарии
    /*
	текст
    */

## Способы объявления:
### Inline-стили(email рассылка)
	<h1 style="color: blueviolet;">Текст</h1>
	<h2 style="color: green;">Текст</h2>
	<h2 style="color: darkblue;">Текст</h2>

### стили в разделе head:

	<style>
		h2 {
			color:darkcyan;

		}
	</style>

## подключение внешнего файла:

	style.css
	в разделе head--> link:css 

## class:
	.border {
		border: 1px solid black;
	}

## единицы измерения:
	относительные:
 	px - пиксель
 	% - процент
 	em -высота текущего шрифта
	абсолютные:
 	cm - см
 	mm - мм
 	in - дюйм
 	pt - пункт

 ## ---

 	width - ширина
 	height - высота

 ## background - фон элемента:
	background-color:#ff0;
	background-image:.....;
	background-position:....;

## 
	<h1 class="title">текст</h1>

	в файле style.css:
	.title{
	background-color:gray;
	}

## border рамка:

	h1 {
		border: 1px solid black;
	}
## font шрифт текста:

	serif с засечками
	sans-serif без засечек
	cursive курсивные
	fantasy декоративные
	monospace моноширинные

## list-style вид маркера 
## редактирование текста:
	text-align
	text-decoration
	text-transform


