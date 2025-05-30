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


![gremishka.jpg|right|200](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)

Ліцензія MIT
Авторське право (c) 2024 нелінійність
Дозвіл надається безкоштовно будь-якій особі, яка отримує копію
цього програмного забезпечення та пов'язаних з ним файлів документації («Програмне забезпечення»), для вирішення
у Програмному забезпеченні без обмежень, включаючи, без обмежень, права
використовувати, копіювати, змінювати, об'єднувати, публікувати, розповсюджувати, субліцензувати та/або продавати
копії Програмного забезпечення, а також дозволяти особам, яким надається Програмне забезпечення
надані для цього, за таких умов:
Вищезазначене повідомлення про авторські права та це повідомлення про дозвіл мають бути включені до всіх
копії або суттєві частини Програмного забезпечення.
ПРОГРАМНЕ ЗАБЕЗПЕЧЕННЯ НАДАЄТЬСЯ "ЯК Є", БЕЗ БУДЬ-ЯКИХ ГАРАНТІЙ, ЯВНИХ АБО
НЕЯВНІ, ВКЛЮЧАЮЧИ, АЛЕ НЕ ОБМЕЖУЮЧИСЬ, ГАРАНТІЇ ТОВАРНОЇ ПРИДАТНОСТІ,
ПРИДАТНІСТЬ ДЛЯ ПЕВНОЇ МЕТИ ТА НЕПОРУШЕННЯ ПРАВ. ЗА ЖОДНИХ ОБСТАВИН
АВТОРИ АБО ВЛАСНИКИ АВТОРСЬКИХ ПРАВ НЕ НЕСУТЬ ВІДПОВІДАЛЬНОСТІ ЗА БУДЬ-ЯКІ ПРЕТЕНЗІЇ, ЗБИТКИ АБО ІНШІ
ВІДПОВІДАЛЬНІСТЬ, ЧИ ВИНИКЛА В ВИНІ ДІЇ ЗА ДОГОВОРОМ, ДЕЛІКТОМ ЧИ ІНШИМ ЧИНОМ, ЩО ВИНИКЛА ВНАСЛІДОК,
ПОЗА АБО У ЗВ'ЯЗКУ З ПРОГРАМНИМ ЗАБЕЗПЕЧЕННЯМ АБО ВИКОРИСТАННЯМ ЧИ ІНШИМИ ДІЯМИ В
ПРОГРАМНЕ ЗАБЕЗПЕЧЕННЯ.





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

Приклад кнопки по центру
<div style="display: flex; justify-content: center; cursor: pointer;">
	<a href="https://github.com/oleeskild/obsidian-digital-garden/issues/55" target="_blank">
		<button style=" font-size: 24px; padding: 10px; height: fit-content; margin-top: 50px; background: var(--text-accent); font-weight: 600; color: var(--text-on-accent); cursor: pointer; ">
			Submit your site
		</button>
	</a>
</div>


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

Як вбудувати розсилку на сайт(https://www.emhabayu.com/notes/how-to-embed-newsletter-on-obsidian/)

Альтернативні комантарі(https://utteranc.es/?ref=obsidian-gallery.craftengineer.com)

Альтернативний веб сад(https://quartz.jzhao.xyz/)
Приклад сайту на Quartz v4.5.0(https://neovoid.is-cool.dev/quartz/)

Ідея для футера
![Pasted image 20250530205328.png](/img/user/z_Assets/Pasted%20image%2020250530205328.png)

блог фотографа(https://cave.niallbell.com/?ref=obsidian-gallery.craftengineer.com)

цифровий сад edav. Таблиці html, анімація на головній сторінці(https://edav-garden.netlify.app/area/)

Перемикач теми, рандомна нотатка, надіслати електронни лист(https://www.nonlinear.top/A0-%20%E5%85%B3%E4%BA%8E%E8%AF%A5%E7%BD%91%E7%AB%99/%E5%85%B3%E4%BA%8E%E8%AF%A5%E7%BD%91%E7%AB%99/) на GitHub(https://github.com/UNLINEARITY/Atlas-of-Control-and-AI)

Алекс Райнхарт — письменник, оповідач та розробник рольових ігор(https://garden.alexrinehart.net/about-me/about-me/)
Ліцензія MIT
Авторське право (c) 2024 нелінійність
Дозвіл надається безкоштовно будь-якій особі, яка отримує копію
цього програмного забезпечення та пов'язаних з ним файлів документації («Програмне забезпечення»), для вирішення
у Програмному забезпеченні без обмежень, включаючи, без обмежень, права
використовувати, копіювати, змінювати, об'єднувати, публікувати, розповсюджувати, субліцензувати та/або продавати
копії Програмного забезпечення, а також дозволяти особам, яким надається Програмне забезпечення
надані для цього, за таких умов:
Вищезазначене повідомлення про авторські права та це повідомлення про дозвіл мають бути включені до всіх
копії або суттєві частини Програмного забезпечення.
ПРОГРАМНЕ ЗАБЕЗПЕЧЕННЯ НАДАЄТЬСЯ "ЯК Є", БЕЗ БУДЬ-ЯКИХ ГАРАНТІЙ, ЯВНИХ АБО
НЕЯВНІ, ВКЛЮЧАЮЧИ, АЛЕ НЕ ОБМЕЖУЮЧИСЬ, ГАРАНТІЇ ТОВАРНОЇ ПРИДАТНОСТІ,
ПРИДАТНІСТЬ ДЛЯ ПЕВНОЇ МЕТИ ТА НЕПОРУШЕННЯ ПРАВ. ЗА ЖОДНИХ ОБСТАВИН
АВТОРИ АБО ВЛАСНИКИ АВТОРСЬКИХ ПРАВ НЕ НЕСУТЬ ВІДПОВІДАЛЬНОСТІ ЗА БУДЬ-ЯКІ ПРЕТЕНЗІЇ, ЗБИТКИ АБО ІНШІ
ВІДПОВІДАЛЬНІСТЬ, ЧИ ВИНИКЛА В ВИНІ ДІЇ ЗА ДОГОВОРОМ, ДЕЛІКТОМ ЧИ ІНШИМ ЧИНОМ, ЩО ВИНИКЛА ВНАСЛІДОК,
ПОЗА АБО У ЗВ'ЯЗКУ З ПРОГРАМНИМ ЗАБЕЗПЕЧЕННЯМ АБО ВИКОРИСТАННЯМ ЧИ ІНШИМИ ДІЯМИ В
ПРОГРАМНЕ ЗАБЕЗПЕЧЕННЯ.