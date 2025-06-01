---
{"dg-publish":true,"permalink":"/digital-garden-faq/","hide":true,"hideInGraph":true}
---


Вбудований файл пдф:
<iframe src="https://drive.google.com/file/d/1PacJp3YdhrNR9wzc5ylpH6nkcmLvHjVM/preview" width="100%" height="480" allow="autoplay" aspect-ratio="4 / 4" overflow="hidden" position="absolute" scrolling="no"> </iframe>

Вбудоване відео з ютуба

<iframe width="560" height="315" src="https://www.youtube.com/embed/AwRSTH72MYw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

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

> [!infobox]+
> # Гремішка
> ![gremishka.jpg|300](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)
> ###### Соцмережі
> ###### [Telegram](https://t.me/gremishkaua)
> ###### [BlueSky](https://bsky.app/profile/gremishka.bsky.social)
> ###### [Instagram](https://www.instagram.com/gremyshkaua/)

> [!infobox]+
> Type |  Stat |
> ---|---|
> Telegram | Testing |
> Test | Testing |
> Test | Testing |
> Test | Testing |



> [!cards|3]
> **[[2-World/Regions/Island of Screams\|Island of Screams]]**
> ![gremishka.jpg|250](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)
>
> **[[2-World/Hubs/City of Trade\|City of Trade]]**
>![gremishka.jpg|250](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)
> 
> **[[1-Party/Example Party 1/Example Party 1\|Example Party 1]]**
> ![gremishka.jpg|250](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)

---
type: beerCard
Rating: 9
ABV: 6.5%
Cost: £
Producer: Pressure Drop
Type: Porter
Bought-From: "[[Beer and Burger\|Beer and Burger]]"
Tasting-Notes: "Great porter, really balanced flavour, not to sweet and can taste the coffee and chocolate. Really easy drinker. Would definitely get again"
Image: "[[gremishka.jpg]]"
Description: "Roasty, Coffee Chocolate"
---

Tags: 
``` dataviewjs
// Nicely Render all the inlinks to the current note on a single line
// Checks if an alias exists for inlinks and will render the alias
// if it exists
//
let myInlinks = [];
for (let inlink of dv.current().file.inlinks){
	let inlinkFile = dv.page(inlink.path).file
	let displayName = inlinkFile.aliases ? inlinkFile.aliases[0] : inlinkFile.name
	let fileLink = dv.fileLink(inlinkFile.path, false, displayName)
	myInlinks.push(fileLink)
}
let myInlinksStr = `**Inlinks**: ${myInlinks.join(', ')}`
dv.paragraph(myInlinksStr)
```
**Oulinks**: [[_MOC Products\|Products]], [[Beer Tasting Notes\|Beer Tasting Notes]]

# Fashion Porter

``` dataviewjs
let page = dv.current();
dv.paragraph(
	"**Description** " + page.Description
)
```

![gremishka.jpg|left|250](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)
``` dataviewjs
let page = dv.current();

dv.paragraph(
	"**Rating:** " + page.Rating + "\n"
	+ "**ABV:** " + page.ABV + "\n"
	+ "**Cost:** " + page.Cost + "\n"
	+ "**Type:** " + page.Type + "\n"
	+ "**Producer:** " + page.Producer + "\n"
	+ "**Bought From**: " + page["Bought-From"] + "\n"
	+ "**Tasting Notes**: " + page["Tasting-Notes"]
)
```


![gremishka.jpg|left|250](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)
``` dataviewjs
let page = dv.current();

dv.paragraph(
	"**Rating:** " + page.Rating + "\n"
	+ "**ABV:** " + page.ABV + "\n"
	+ "**Cost:** " + page.Cost + "\n"
	+ "**Type:** " + page.Type + "\n"
	+ "**Producer:** " + page.Producer + "\n"
	+ "**Bought From**: " + page["Bought-From"] + "\n"
	+ "**Tasting Notes**: " + page["Tasting-Notes"]
)
```



>прихований текст - писати без кавичок(нотатки для редактора, які не попадуть на сайт.)
>>":::hidden"
>>сам текст
>>:::


>зменшений текст - писати без кавичок
>>"<font size=1>"
>>сам текст
>>"</font>"

> розмістити зображення по центру, з посилання
>> <center> <img width=500 src="https:посилання вставити сюди"> </center>

> розмістити текст або посилання по центру
>>  <center> <a href="https://obsidian-space-delta.vercel.app/">atan's OuOb Space!</a> </center>


​```cardlink
url: https://obsidian.md/
title: "Obsidian"
description: "Obsidian: A knowledge base that works on local Markdown files."
host: obsidian.md
favicon: https://obsidian.md/favicon.ico
image: https://obsidian.md/images/banner.png
​```




# Коментарі та реакції
Як додати коментарі на сайт за допомогою disqus
інструція (https://ericliaointerpreting.com/obsidian-digital-garden-plugin-netlify/)
 [приклад сайту: topobon](https://topobon.utsob.me/). 
 [приклад реалізації коду на git](https://github.com/uroybd/topobon/tree/main/src/site/_includes/components/user)

[Альтернативні комантар]і(https://utteranc.es/?ref=obsidian-gallery.craftengineer.com)
[utteranc.es](https://utteranc.es/)

альтернативні коментарі   (https://www.yarden-zamir.com/docs/readme/)
[giscus](https://giscus.app/)

 [Інший приклад коментарів](https://koeberlin.netlify.app/)
 гітхаб

Реакція + коментарі, банери знизу сайта (https://www.aizatto.com/personal-goals)
гітхаб (https://github.com/aizatto/gitbook-public?tab=readme-ov-file)
![Pasted image 20250531131429.png](/img/user/z_Assets/Pasted%20image%2020250531131429.png)
![Pasted image 20250531131459.png](/img/user/z_Assets/Pasted%20image%2020250531131459.png)

# Розсилка (підписка), перемикач тем
[Як вбудувати розсилку (підписку) на сайт](https://www.emhabayu.com/notes/how-to-embed-newsletter-on-obsidian/)

[Перемикач теми, рандомна нотатка, надіслати електронни лист](https://www.nonlinear.top/A0-%20%E5%85%B3%E4%BA%8E%E8%AF%A5%E7%BD%91%E7%AB%99/%E5%85%B3%E4%BA%8E%E8%AF%A5%E7%BD%91%E7%AB%99/) на GitHub(https://github.com/UNLINEARITY/Atlas-of-Control-and-AI)

[Перемикач тем на сайті](https://github.com/oleeskild/obsidian-digital-garden/discussions/688)


# додаткові гайди та приклади
[Додавання каталогів/папок для користувацьких компонентів](https://github.com/oleeskild/obsidian-digital-garden/discussions/577)

[Альтернативні прапорці з теми minimal за допомогою userSetup.js](https://github.com/oleeskild/obsidian-digital-garden/discussions/576)

[Автоматичне створення картки з посилання](https://github.com/nekoshita/obsidian-auto-card-link)

Ідея для футера
![Pasted image 20250530205328.png](/img/user/z_Assets/Pasted%20image%2020250530205328.png)

[цифровий сад edav. Таблиці html, анімація на головній сторінці](https://edav-garden.netlify.app/area/)

Гарне оформлення + повернення на верх сторінки https://lyz-code.github.io/blue-book/galego/
гітхаб
![Pasted image 20250531131735.png](/img/user/z_Assets/Pasted%20image%2020250531131735.png)

як змінити доменне ім'я(https://ericliaointerpreting.com/netlify-with-go-daddy-domain-name/)

Додайте медіафайли до цифрового саду або обсидіанової нотатки(https://wisdump.work/blog-management/digital-garden-management/add-media-to-a-digital-garden-or-obsidian-note/)

Захист вашої особистості та домену за допомогою безпеки електронної пошти(https://wisdump.work/blog-management/digital-garden-management/protecting-your-identity-and-your-domain-with-email-security/)

Вкладені впорядковані списки в цифрових садах(https://wisdump.work/blog-management/digital-garden-management/nested-ordered-lists-in-digital-gardens/)



# Клас розташування картинок в рядок

```

<div class="book-covers">

- ![cover](https://books.google.com/books/publisher/content/images/frontcover/mNzZCwAAQBAJ?fife=w600-h900&source=gbs_api)
- ![cover](https://standardebooks.org/ebooks/charles-dickens/a-tale-of-two-cities/downloads/thumbnail_e7100f2595c474ea5c996db1f72fc4bd94dac8dd_EBOK_portrait.jpg)
- ![cover](https://books.google.com/books/publisher/content/images/frontcover/gS9GEAAAQBAJ?fife=w600-h900&source=gbs_api)

{ .block-language-dataview}

</div>

```
# Приклад кнопки по центру

<div style="display: flex; justify-content: center; cursor: pointer;">
	<a href="https://github.com/oleeskild/obsidian-digital-garden/issues/55" target="_blank">
		<button style=" font-size: 24px; padding: 10px; height: fit-content; margin-top: 50px; background: var(--text-accent); font-weight: 600; color: var(--text-on-accent); cursor: pointer; ">
			Submit your site
		</button>
	</a>
</div>

# Ліцензії

Контент, елементи дизайну чи будь-що інше з цього проєкту ліцензовано за ліцензією [Creative Commons CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) , якщо прямо не зазначено інше.

Аналогічно, будь-які фрагменти коду ліцензуються на ваш вибір за однією з наступних ліцензій, якщо прямо не зазначено інше:

- [Ліцензія Apache, версія 2.0](https://www.apache.org/licenses/LICENSE-2.0)
- [Ліцензія GPL 3.0](https://opensource.org/licenses/GPL-3.0)
- [MIT](https://tldrlegal.com/license/mit-license)


# Швидка нотатка з YAML

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

Пояснення

Щоразу, коли я створюю новий файл у папці "Вхідні" (=коли я натискаю посилання на неіснуючий файл), я отримую пропозицію з шаблонами, а потім створюється файл із зазначеним шаблоном.  
Нотатка до книги навіть переміщується до зазначеної папки. Ви також можете додати це до інших шаблонів або скористатися плагіном " [auto file mover 62](https://github.com/farux/obsidian-auto-note-mover) ", який нещодавно вийшов.

Звичайно, це все ще трохи складно, і вам потрібно налаштовувати це для кожного шаблону, який ви хочете використовувати, але поки що це працює для опції переходу за посиланням.  
Сподіваюся, це трохи допомогло.


# Приклад коду з зображенням збоку від тексту

[приклад з сайту текст + зображення](https://www.yourpulse.cc/)

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

# Швидкий спосіб додати YAML до великої кількості нотаток

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



> [!caption|left] Floats to the left
> ![gremishka.jpg|250](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)
> Caption text here

> [!caption|right] Floats to the right
> ![gremishka.jpg|250](/img/user/%D0%A4%D0%B0%D0%B9%D0%BB%D0%B8/gremishka.jpg)
> Caption text here

зображення по боках тексту



> [!cards]
> **[[Link\|Link]]**
> ![Image link|sban htiny ctr](https://images.unsplash.com/photo-1574375927938-d5a98e8ffe85?ixlib=rb-1.2.1&q=85&fm=jpg&crop=entropy&cs=srgb&w=1200)
> 
> **[[Link\|Link]]**
> ![[Image Link.png\|sban htiny ctr]]

> [!cards|4]
> **[[Link\|Link]]**
> ![Image link|sban htiny ctr](https://images.unsplash.com/photo-1574375927938-d5a98e8ffe85?ixlib=rb-1.2.1&q=85&fm=jpg&crop=entropy&cs=srgb&w=1200)
> 
> **[[Link\|Link]]**
> ![[Image Link.png\|sban htiny ctr]]
> 
> **[[Link\|Link]]**
> ![Image link|sban htiny ctr](https://images.unsplash.com/photo-1574375927938-d5a98e8ffe85?ixlib=rb-1.2.1&q=85&fm=jpg&crop=entropy&cs=srgb&w=1200)
> 
> **[[Link\|Link]]**
> ![[Image Link.png\|sban htiny ctr]]

