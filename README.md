# APK dosyasına Toast Mesajı Nasıl Eklenir? 

```smali
.line 14
    const-string v0, "Toast Mesajınız"

    const/4 v1, 0x1

    invoke-static {p0, v0, v1}, Landroid/widget/Toast;->makeText(Landroid/content/Context;Ljava/lang/CharSequence;I)Landroid/widget/Toast;

    move-result-object v0

    invoke-virtual {v0}, Landroid/widget/Toast;->show()V
```


---

## Adım 1: APK Dosyasını seçin

![Adım 1](./images/1.jpg)

---

## Adım 2: 

![Adım 2](./images/2.jpg)

---

## Adım 3: 

![Adım 3](./images/3.jpg)

---

## Adım 4: 

![Adım 4](./images/4.jpg)

---

## Adım 5: 

![Adım 5](./images/5.jpg)

---

## Adım 6: 

![Adım 6](./images/6.jpg)

---

## Adım 7: 

![Adım 7](./images/7.jpg)

---

## Adım 8: 

![Adım 8](./images/8.jpg)

---

## Adım 9: 

![Adım 9](./images/9.jpg)

---

## Adım 10: 

![Adım 10](./images/10.jpg)

---

## Adım 11: 

![Adım 11](./images/11.jpg)

---

## Adım 12: 

![Adım 12](./images/12.jpg)

---

## Adım 13: 

![Adım 13](./images/13.jpg)

---

