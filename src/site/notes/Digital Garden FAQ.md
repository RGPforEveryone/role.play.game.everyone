---
{"dg-publish":true,"permalink":"/digital-garden-faq/","hide":true,"hideInGraph":true}
---



>прихований текст - писати без кавичок(нотатки для редактора, які не попадуть на сайт.)
>>":::hidden"
>>сам текст
>>:::


>зменшений текст - писати без кавичок
>>"<font size=1>"
>>сам текст
>>"</font>"
>
![[myfilename.png\|200]]


|![[gremishka.jpg\|200]]|![[gremishka.jpg\|200]]| 
| -------------------- | ---------------- | 
<center> <img width=500 src="![gremishka.jpg](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)"> </center>


<center> <img width=500 src="https://imgur.com/ZFElAHT.jpeg"> </center>
<right> <img width=500 src="https://imgur.com/ZFElAHT.jpeg"> </right>


​```cardlink
url: https://obsidian.md/
title: "Obsidian"
description: "Obsidian: A knowledge base that works on local Markdown files."
host: obsidian.md
favicon: https://obsidian.md/favicon.ico
image: https://obsidian.md/images/banner.png
​```

<font size=1> The code block style in my local vault is created using the Code Styler plugin. </font>



[Найкращий спосіб додати dg-publish: true для сотень нотаток?](https://github.com/oleeskild/obsidian-digital-garden/discussions/238)

Ось кращий шаблон, який вимагає лише перегляду даних, без потреби в metaedit (використовуючи функцію, яка може бути використана для встановлення будь-якого значення будь-якого поля фронтматера)
```
<%*
let tag = await tp.system.prompt("Enter tag (without #)")
var files = DataviewAPI.pages("#"+tag).file.map(file => tp.file.find_tfile(file.path));
let count = 0;
for (let file of files) {
	await setFrontmatter(file, "dg-publish", true);
	count++;
}
console.log("Parsed "+count+" files.");

function setFrontmatter(file, fmfield, thing) {
	try {
		this.app.fileManager.processFrontMatter(file, fm => fm[fmfield] = thing);
	} catch (error) {
		console.log(`Error adding frontmatter ${thing} to ${fmfield}.`)
	}
}
-%>
```
[Додавання каталогів/папок для користувацьких компонентів](https://github.com/oleeskild/obsidian-digital-garden/discussions/577)

[Альтернативні прапорці з теми minimal за допомогою userSetup.js](https://github.com/oleeskild/obsidian-digital-garden/discussions/576)

[Перемикач тем на сайті](https://github.com/oleeskild/obsidian-digital-garden/discussions/688)

Як додати коментарі на сайт за допомогою disqus
 [приклад сайту: topobon](https://topobon.utsob.me/). 
 [приклад реалізації коду на git](https://github.com/uroybd/topobon/tree/main/src/site/_includes/components/user)
 [Інший приклад коментарів](https://koeberlin.netlify.app/)

[Автоматичне створення картки з посилання](https://github.com/nekoshita/obsidian-auto-card-link)

Збереження та синхронізація обсидіан(https://imazingrace.vercel.app/Obsidian/Remotely%20Save/)

книга рецептів, нотатки з книг(https://notebook.ddeepak95.com/cookbook/)

