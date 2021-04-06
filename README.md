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
* For private works, contact me on Discord! (Bots, Plugins, FiveM Resources, Scripts, Cheats, etc...)

---

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=KillStr3aK&show_icons=true&theme=radical)

![Profile views](https://gpvc.arturio.dev/KillStr3aK)
