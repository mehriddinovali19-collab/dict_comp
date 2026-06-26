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
