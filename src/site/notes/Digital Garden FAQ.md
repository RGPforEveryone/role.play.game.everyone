---
{"dg-publish":true,"permalink":"/digital-garden-faq/","hide":true,"hideInGraph":true}
---



> [!cards|4]
> **[[2-World/Regions/Island of Screams\|Island of Screams]]**
> ![The Island of Screams.jpg|200](/img/user/z_Assets/The%20Island%20of%20Screams.jpg)
> 
> **[[1-DM Toolkit/Journey Board\|Journey Board]]**
> [![[JourneyBoard.png\|sban htiny ctr]]](Journey%20Board)
>
> **[[2-World/Hubs/City of Trade\|City of Trade]]**
> ![AdventureIcon.png|200](/img/user/z_Assets/Placeholder%20Images/AdventureIcon.png)
> 
> **[[1-Party/Example Party 1/Example Party 1\|Example Party 1]]**
> ![PartyLogo.jpg|200](/img/user/z_Assets/Placeholder%20Images/PartyLogo.jpg)



> [!cards|3]
> **[[2-World/Regions/Island of Screams\|Island of Screams]]**
> ![gremishka.jpg|250](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)
>
> **[[2-World/Hubs/City of Trade\|City of Trade]]**
>![gremishka.jpg|250](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)
> 
> **[[1-Party/Example Party 1/Example Party 1\|Example Party 1]]**
> ![gremishka.jpg|250](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)


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
```

<div class="book-covers">

- ![cover](https://books.google.com/books/publisher/content/images/frontcover/mNzZCwAAQBAJ?fife=w600-h900&source=gbs_api)
- ![cover](https://standardebooks.org/ebooks/charles-dickens/a-tale-of-two-cities/downloads/thumbnail_e7100f2595c474ea5c996db1f72fc4bd94dac8dd_EBOK_portrait.jpg)
- ![cover](https://books.google.com/books/publisher/content/images/frontcover/gS9GEAAAQBAJ?fife=w600-h900&source=gbs_api)

{ .block-language-dataview}

</div>

```




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

[Збереження та синхронізація обсидіан](https://imazingrace.vercel.app/Obsidian/Remotely%20Save/)

[книга рецептів, нотатки з книг](https://notebook.ddeepak95.com/cookbook/)

[Як вбудувати розсилку на сайт](https://www.emhabayu.com/notes/how-to-embed-newsletter-on-obsidian/)

[Альтернативні комантар]і(https://utteranc.es/?ref=obsidian-gallery.craftengineer.com)

[Альтернативний веб сад](https://quartz.jzhao.xyz/)
[Приклад сайту на Quartz v4.5.0](https://neovoid.is-cool.dev/quartz/)

Ідея для футера
![Pasted image 20250530205328.png](/img/user/z_Assets/Pasted%20image%2020250530205328.png)

[блог фотографа](https://cave.niallbell.com/?ref=obsidian-gallery.craftengineer.com)

[цифровий сад edav. Таблиці html, анімація на головній сторінці](https://edav-garden.netlify.app/area/)

[Перемикач теми, рандомна нотатка, надіслати електронни лист](https://www.nonlinear.top/A0-%20%E5%85%B3%E4%BA%8E%E8%AF%A5%E7%BD%91%E7%AB%99/%E5%85%B3%E4%BA%8E%E8%AF%A5%E7%BD%91%E7%AB%99/) на GitHub(https://github.com/UNLINEARITY/Atlas-of-Control-and-AI)

[Алекс Райнхарт — письменник, оповідач та розробник рольових ігор](https://garden.alexrinehart.net/about-me/about-me/)
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

## Код

**Мій підхід:**  
у мене є папка «Вхідні» за замовчуванням для нових файлів (основна функція у розділі «Файли та посилання» → розташування за замовчуванням для нових нотаток → у вказаній папці).  
Я налаштував шаблонизатор (який я все одно використовую) для застосування шаблону до кожної нової нотатки в цій папці.  
Цей шаблон виглядає так:

```typescript
<%* let filetype = await tp.system.suggester(["Book Note", "Kanban Project", "Project Note", "Standard"], ["Book Note", "Kanban Project", "Project Note", "Standard"], false, "Which template do you want to use?") %>
<%-* if (filetype === "Book Note") { %> 
<% tp.file.include("[[Book Note Template]]") %> <% tp.file.move("/030 Media/031 Books/" + tp.file.title) %>
<%-* } else if (filetype === "Kanban Project") { %>
<% tp.file.include("[[Project Kanban]]") %> 
<%-* } else if (filetype === "Project Note") { %>
<% tp.file.include("[[Project Note Template]]") %>
<%-* } else if (filetype === "Standard") { %>
<% tp.file.include("[[New File Template]]") %>
<%-* } else { %>
<% tp.file.cursor(1) %>
<%* } -%>
```

## Пояснення

Щоразу, коли я створюю новий файл у папці "Вхідні" (=коли я натискаю посилання на неіснуючий файл), я отримую пропозицію з шаблонами, а потім створюється файл із зазначеним шаблоном.  
Нотатка до книги навіть переміщується до зазначеної папки. Ви також можете додати це до інших шаблонів або скористатися плагіном " [auto file mover 62](https://github.com/farux/obsidian-auto-note-mover) ", який нещодавно вийшов.

Звичайно, це все ще трохи складно, і вам потрібно налаштовувати це для кожного шаблону, який ви хочете використовувати, але поки що це працює для опції переходу за посиланням.  
Сподіваюся, це трохи допомогло.

[приклад з сайту текст + зображення](https://www.yourpulse.cc/)

[сайт для безпечного пошуку ДМів платно](https://startplaying.games/)
сайт для створення кампейну(https://www.worldanvil.com/)
перенесення кампейну WorldAnvil в нотатки(https://github.com/magejosh/WorldAnvil-to-MD?tab=readme-ov-file)
magejosh(https://github.com/magejosh?page=1&tab=repositories)

```
<div class="w-full text-center md:text-left md:flex md:flex-row md:items-center">

    <div class="md:w-1/2"><h3 class="text-4xl font-bold mb-4">

     <font style="vertical-align: inherit;">

        <font style="vertical-align: inherit;">

        Про нас

        </font>

        </font>

    </h3>

    <p class="mb-4">

<font style="vertical-align: inherit;">

<font style="vertical-align: inherit;">

У YourPulse ми вважаємо, що ваші нотатки є відображенням вашого унікального процесу мислення та інтелектуальної подорожі. Як користувачі Obsidian, ми усвідомили потребу в інструменті, який міг би оживити наші сховища, демонструючи багатство знань та творчості, що містяться в них.</font></font></p><p class="mb-4"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ми створили YourPulse, щоб надати таким користувачам Obsidian, як ви, можливість побачити весь потенціал вашого цифрового розуму.

</font>

</font>

</strong>

</p>

</div>

<div class="mt-6 md:mt-0 md:ml-6 md:w-1/2 p-4">

<img alt="Мем про плагіни" loading="lazy" width="400" height="300" decoding="async" data-nimg="1"

class="rounded-lg" style="color:transparent" srcset="/_next/image?url=%2Fplugins-list.jpg%3Fheight%3D300%26width%3D400&amp;w=640&amp;q=75 1x,

/_next/image?url=%2Fplugins-list.jpg%3Fheight%3D300%26width%3D400&amp;w=828&amp;q=75 2x"

src="/_next/image?url=%2Fplugins-list.jpg%3Fheight%3D300%26width%3D400&amp;w=828&amp;q=75">

</div>

</div>
```