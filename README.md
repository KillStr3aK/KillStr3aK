<div align = "center"><img src="https://media.discordapp.net/attachments/871054615737671730/878381455535915038/ico_highres.png?ex=670ae1fa&is=6709907a&hm=fa0199a4e17267b79300d1c686ff674ceeec74236fb58bd455bd5f979162ec1f&=&format=webp&quality=lossless&width=256&height=256"></div>

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

---

<!--- ![Github Stats](https://github-readme-stats.vercel.app/api?username=KillStr3aK&show_icons=true&theme=radical) --->
<!--- ![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=KillStr3aK&theme=2077) --->
![](http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KillStr3aK&theme=2077)
![](http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=KillStr3aK&theme=2077)
![](http://github-profile-summary-cards.vercel.app/api/cards/stats?username=KillStr3aK&theme=2077)
![](http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=KillStr3aK&theme=2077&utcOffset=8)

![](https://komarev.com/ghpvc/?username=KillStr3aK)
