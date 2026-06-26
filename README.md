## 🟢 Junior daraja (1-5)

**1.** Berilgan ro'yxatdagi sonlarning kvadratlaridan dictionary yasang.
```python
nums = [1, 2, 3, 4, 5]
# natija: {1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
```

**2.** Berilgan so'zlar ro'yxatidan har bir so'zning uzunligini dictionary qilib chiqaring.
```python
words = ["olma", "anor", "behi", "uzum"]
# natija: {"olma": 4, "anor": 4, "behi": 4, "uzum": 4}
```

**3.** 1 dan 10 gacha bo'lgan sonlardan faqat juft sonlarni va ularning kvadratini dictionary qilib yozing.
```python
# natija: {2: 4, 4: 16, 6: 36, 8: 64, 10: 100}
```

**4.** Berilgan dictionary'dagi key va value larni almashtiring (teskari dictionary yasang).
```python
d = {"a": 1, "b": 2, "c": 3}
# natija: {1: "a", 2: "b", 3: "c"}
```

**5.** Harflar ro'yxatidan har bir harfning katta (upper) shaklini value qilib dictionary tuzing.
```python
letters = ["a", "b", "c", "d"]
# natija: {"a": "A", "b": "B", "c": "C", "d": "D"}
```

## 🟡 Middle daraja (6-10)

**6.** Berilgan dictionary'dan faqat qiymati (value) 50 dan katta bo'lgan elementlarni ajratib, yangi dictionary yasang.
```python
scores = {"Ali": 45, "Vali": 78, "Hasan": 60, "Husan": 30}
# natija: {"Vali": 78, "Hasan": 60}
```

**7.** Ikkita ro'yxatni (keys va values) birlashtirib, dictionary comprehension orqali yangi dictionary yasang (zip ishlatib).
```python
keys = ["ism", "yosh", "shahar"]
values = ["Aziz", 25, "Toshkent"]
# natija: {"ism": "Aziz", "yosh": 25, "shahar": "Toshkent"}
```

**8.** Berilgan matndagi har bir harfning nechta marta uchrashini hisoblang (faqat harflar, bo'shliqsiz).
```python
text = "salom dunyo"
# natija: {'s':1, 'a':1, 'l':1, 'o':2, 'm':1, 'd':1, 'u':1, 'n':1, 'y':1}
```

**9.** Ichma-ich (nested) dictionary'dan faqat ma'lum shartga mos studentlarni ajratib oling — masalan, bahosi 70dan yuqori bo'lganlarning faqat ismi va bahosini chiqaring.
```python
students = {
    "Ali": {"yosh": 20, "baho": 85},
    "Vali": {"yosh": 22, "baho": 60},
    "Hasan": {"yosh": 19, "baho": 90}
}
# natija: {"Ali": 85, "Hasan": 90}
```

**10.** 1 dan 100 gacha bo'lgan sonlardan faqat 3 ga ham, 5 ga ham bo'linadigan sonlarni va ularning yig'indisini (raqamlar yig'indisini) dictionary qilib chiqaring.
```python
# masalan: 15 -> 1+5=6, 30 -> 3+0=3
# natija: {15: 6, 30: 3, 45: 9, 60: 6, 75: 12, 90: 9}
```

---

Agar xohlasangiz, har biriga **yechim kodi** bilan to'liq variantini ham tayyorlab beraman, yoki bu masalalarni **qiyinroq (senior)** darajaga ham kengaytirib bera olaman. Qaysi birini xohlaysiz?
Mana, **10dan 20gacha** raqamlangan, barchasi **nested (ichma-ich) dictionary comprehension** uslubida, darajasi bilan:

---

**10.** *(O'rta-yuqori)* 1 dan 50 gacha sonlardan juft sonlarni olib, har biriga **kvadrati va kubini** ichma-ich dictionary qilib chiqaring.
```python
# masalan: 4 -> {"kvadrat": 16, "kub": 64}
# natija: {2: {"kvadrat": 4, "kub": 8}, 4: {"kvadrat": 16, "kub": 64}, ...}
```

**11.** *(Yuqori)* 1 dan 30 gacha sonlardan faqat tub (prime) sonlarni olib, har biriga **o'zi, kvadrati va raqamlar yig'indisi**ni ichma-ich dictionary qilib chiqaring.
```python
# masalan: 13 -> {"son": 13, "kvadrat": 169, "raqam_yigindisi": 4}
```

**12.** *(Yuqori)* 1 dan 100 gacha sonlardan 4 ga bo'linadiganlarni olib, har biriga **bo'luvchilari ro'yxati va bo'luvchilar sonini** ichma-ich dictionary qilib chiqaring.
```python
# masalan: 8 -> {"boluvchilar": [1,2,4,8], "soni": 4}
```

**13.** *(Yuqori, murakkab)* Berilgan so'zlar ro'yxatidagi har bir so'z uchun **uzunligi va unli harflar sonini** ichma-ich dictionary qilib chiqaring.
```python
so_zlar = ["olma", "kitob", "daftar", "qalam"]
# masalan: "olma" -> {"uzunlik": 4, "unlilar": 2}
```

**14.** *(Yuqori, murakkab)* 1 dan 100 gacha sonlardan 6 ga ham, 9 ga ham bo'linadiganlarni olib, har biriga **raqamlar yig'indisi va o'zi juft yoki toqligini** ichma-ich dictionary qilib chiqaring.
```python
# masalan: 18 -> {"raqam_yigindisi": 9, "juft_yoki_toq": "toq"}
```

**15.** *(Yuqori, murakkab)* 1 dan 50 gacha sonlardan 3 ga bo'linadiganlarni olib, har biriga **o'zi, kvadrati va sonning juft/toqligini** ichma-ich dictionary qilib chiqaring.
```python
# masalan: 9 -> {"kvadrat": 81, "tur": "toq"}
```

**16.** *(Eng yuqori)* Berilgan studentlar lug'atida har bir student uchun **eng yuqori va eng past bahosini** ichma-ich dictionary qilib chiqaring.
```python
students = {
    "Ali": {"matematika": 80, "fizika": 90, "ingliz": 70},
    "Vali": {"matematika": 60, "fizika": 65, "ingliz": 75}
}
# masalan: "Ali" -> {"max": 90, "min": 70}
```

**17.** *(Eng yuqori)* 1 dan 100 gacha sonlardan 5 ga bo'linadiganlarni olib, har biriga **bo'linish natijasi (5ga) va qoldiq (3ga bo'lganda)**ni ichma-ich dictionary qilib chiqaring.
```python
# masalan: 20 -> {"5ga_bolingan": 4, "3ga_qoldiq": 2}
```

**18.** *(Eng yuqori)* Berilgan so'zlar ro'yxatidagi har bir so'z uchun **birinchi va oxirgi harfini, uzunligini** ichma-ich dictionary qilib chiqaring, lekin faqat uzunligi 5dan katta bo'lganlarini.
```python
so_zlar = ["kompyuter", "telefon", "stol", "daftar", "kitob"]
```

**19.** *(Eng yuqori, murakkab)* 1 dan 100 gacha sonlardan tub (prime) bo'lmaganlarini olib, har biriga **bo'luvchilar yig'indisi va bo'luvchilar soni**ni ichma-ich dictionary qilib chiqaring (faqat 10dan 30gacha sonlar uchun).
```python
# masalan: 12 -> {"boluvchilar_yigindisi": 28, "soni": 6}
```

**20.** *(Eng yuqori, murakkab)* Ichma-ich dictionary berilgan — har bir studentning bir nechta fani bor. Har bir student uchun **o'rtacha baho, eng yuqori fan nomi va eng past fan nomi**ni ichma-ich dictionary qilib chiqaring.
```python
students = {
    "Ali": {"matematika": 80, "fizika": 90, "ingliz": 70},
    "Vali": {"matematika": 60, "fizika": 65, "ingliz": 75},
    "Hasan": {"matematika": 95, "fizika": 85, "ingliz": 100}
}
```

---

Yechimlarini xohlasangiz, ayting — barchasini kod bilan yechib beraman! 😊
