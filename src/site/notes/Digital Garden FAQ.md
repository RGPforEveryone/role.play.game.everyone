---
{"dg-publish":true,"dg-hide":true,"dg-hide-in-graph":true,"tags":null,"permalink":"/digital-garden-faq/","hide":true,"hideInGraph":true,"dgPassFrontmatter":true}
---



>прихований текст без кавичок(нотатки для редактора, які не попадуть на сайт.)
>>":::hidden"
>>сам текст
>>:::


<[[gremishka\|gremishka]] />


<img
  src="[[gremishka\|gremishka]]"
  alt="The head and torso of a dinosaur skeleton;
          it has a large head with long sharp teeth"
  width="400"
  height="341" />



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
 