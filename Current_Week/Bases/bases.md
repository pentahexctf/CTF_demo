# BASES
Difficulty: intro

---
## TUTORIAL
* Humans use a number system called Base10 because we have 10 fingers.
* We count to 10 then move into the next DECIMAL place (decimal means base10)
- We count to 10 then OVERFLOW into the next place
    * i.e. after 9 then you set the first int to 1 and the next to 0 --> 10
* In base2 the overflow is set to 2 and in base16 its overflowed at 16
```
Boundary is the base number
BASE2: 1 + 1 = 10
BASE4: 1 + 1 + 1 + 1 = 10
BASE5: 1 + 1 + 1 + 1 + 1 = 10 
```

```
Really common bases used in the world and in CTFs:
BASE64
BASE32
BASE16
BASE256
BASE2
BASE10
```

http://pentahex.tk/tutorials/numberbases.html

The letter/number system computers use normally is called ASCII, but wait does it also follow a base system?

You can also post emojis, write in Chinese, and arabic; Those are not numbers or letters though. This follows UTF encoding, the system was developed to supercede ASCII by using more bits to store possible characters, bit manipulation is a story for another time though.



## CHALLENGES

---

What base is ASCII in?

---

Convert 6D6F726E696E6770776E to ASCII (i.e. readable text)

hint: What base is the encoded text in?

---

Convert YXBwbGViZWFucw== to ASCII (i.e. readable text)

---

Convert 0110110101100001011100100110101101100100011011110111011101101110 to ASCII (i.e. readable text)

---