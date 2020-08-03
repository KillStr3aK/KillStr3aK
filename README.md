```assembly
section	.text
	global _start
_start:
	mov	edx, len
	mov	ecx, msg
	mov	ebx, 1
	mov	eax, 4
	int	0x80
	mov	eax, 1
	int	0x80

section	.data

msg	db	'Hi there 👋', 0xa
len	equ	$ - msg
```

---

### About Me

* 🔜🎓 Computer Science
* You can find my works / contributions in almost every CS:S / CS:GO server
* For private works, contact me on Discord! (Bots, Plugins, FiveM Resources, Scripts, etc...)

---

### Languages
<a href = "https://github.com/KillStr3aK"><img src = "https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg" width = "30"> <img src = "https://upload.wikimedia.org/wikipedia/commons/0/0d/C_Sharp_wordmark.svg" width = "30"> <img src = "https://1.bp.blogspot.com/-fvbv9STbxrA/XS2C5q6q-gI/AAAAAAAAHtc/xcRKAakArcwKTo20DNuO05lq2L50nb7JACLcBGAs/s400/Pascal.jpg" width = "30"> <img src = "https://steamcdn-a.akamaihd.net/steamcommunity/public/images/avatars/d1/d12991a4f919417c846817232165db091c4a13c9_full.jpg" width = "30"> <img src = "https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" width = "30"> <img src = "https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" width = "21"> <img src = "https://upload.wikimedia.org/wikipedia/commons/2/27/PHP-logo.svg" width = "30" height = "30"> <img src = "https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg" width = "30"> <img src = "https://nodejs.org/static/images/logos/nodejs-new-pantone-black.svg" width = "30" height = "30"></a>

---

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=KillStr3aK&show_icons=true&theme=radical)

![Profile views](https://gpvc.arturio.dev/KillStr3aK)
