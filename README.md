# sos9533scr
Made by sos9533
[OmletArcade](https://omlet.gg/profile/sos9533)
[KakaoTalk OpneChat](https://open.kakao.com/me/sos9533)

## function

```
┌
├ join event
│  └ welcome message
│
├ OP command
│  ├ kick command
│  ├ mute command
│  ├ ban command
│  └ get info command
│
├ user command
│  ├ spawn command
│  ├ custom tp command (3개)
│  ├ my info command
│  └ basic command
│
├ anti cheat
│  ├ kick toolbox
│  ├ chatcut
│     ├ block long chat
│     ├ block fast chat
│     └ block long whisper
│  ├ anti crasher
│  └ kick long nickname
│  
├ etc
│  ├ block §
│  └ bossbar command
│
├ prefix
│  ├ /prefix (prefix) - user command
│  ├ /prefix (name) (prefix) - op command
│  └ /prefix - user command [UI]
└
```


open source
[ [mdisprgm/bdsx-anticrasher] ](https://github.com/mdisprgm/bdsx-anticrasher)
[ [kdg7313/bdsx-script] ](https://github.com/kdg7313/bdsx-script)

## How to use

1. Unzip and put all files in bdsx-master

ex)
```
└─bdsx-master
      └─ index.ts
      └─ LICENSE
      └─ sos9533scr.ts
```

2. Refer to below and set `bdsx-master/sos9533scr.ts`

> when you choose y/n, write true/false behind  ': boolean ='

```ts
//use welcomemessage (true/false)
let usewelcomemessage: boolean = true;
```

```ts
//use welcomemessage (true/false)
let usewelcomemessage: boolean = false;
```

---

> when you write something, use " "

```ts
//welcomemessage
const welcomemessage = "§l§7welcome! this is steve's server!";
```

```ts
//welcomemessage
const welcomemessage = "§l§Hello! this is my server!";
```

---

> when write number, dont use " "

```ts
//prefix max length  (not include 'How to use' style A)
const chinlength = 20;
```

```ts
//prefix max length  (not include 'How to use' style A)
const chinlength = 10;
```

---

> when you write coordinate, use " "

```ts
//spawn coordinate (x y z)
const spawncoordinate = "0 10 0";
```

```ts
//spawn coordinate (x y z)
const spawncoordinate = "10 10 10";
```

---

> when you choose style, write style's uppercase alphabet
```ts
//output style
//style A     <prefix> <Name> : message
//style B     <prefix> Name : message
//style C     [prefix] <Name> : message
//style D     [prefix] Name : message
let chinchatset = "A";
```

```ts
//output style
//style A     <prefix> <Name> : message
//style B     <prefix> Name : message
//style C     [prefix] <Name> : message
//style D     [prefix] Name : message
let chinchatset = "D";
```
