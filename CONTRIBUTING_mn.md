# Хамтран ажиллах удирдамж

Learn-Git-д хувь нэмэр оруулахаар шийдсэн танд баярлалаа! Энэхүү агуулах нь Git суралцаж буй хүмүүст зориулсан нөөц байх зорилготой бөгөөд таны оруулсан хувь нэмэр түүнийг илүү сайн болгоход туслах болно.

Хэрэв та энэхүү агуулахад хичээлийг сайжруулж эсвэл өөр хэл рүү орчуулах замаар хувь нэмэр оруулахыг хүсвэл тухайн санаа эсвэл сайжруулалтыг агуулсан шинэ асуудлыг үүсгэнэ үү. Хэрэв санаа нь хангалттай сайн бол би эсвэл энэхүү агуулахын гишүүдийн хэн нэг нь үүнийг батлах болно. Тэр үед та өөрчлөлтийг хийж, дараа нь таталтын хүсэлт үүсгэж болно.

## Ёс зүйн дүрэм
Эхлэхээс өмнө ёс зүйн дүрмийг уншиж, мөрдөхийг хүсье. Бүх оролцогчдод хүндэтгэлтэй, эелдэг харилцаатай хамт олныг бүрдүүлэхийг хүсэж байна.

## Эхлэх нь
Learn-Git-д хувь нэмэр оруулах үндсэн алхмууд энд байна:

- **Агуулахыг салаалах**

![fork_image](./images/Readme_images/fork.png)

- **Өөрчлөлтөө хийх шинэ салбар үүсгэх**

```
git branch "салбарын-нэр"
```
### Лавлагаа зураг
![branch_image](./images/Contributing_images/branch_making.png)

Дараа нь уг салбар дээр шилжихийн тулд дараах синтаксыг ашиглана уу:

### Синтакс
```
git checkout "салбарын-нэр"
```

### Лавлагаа зураг
![checkout_branch](./images/Contributing_images/checkout_image.png)

- **Өөрчлөлтөө хийгээд, тухайн салбартаа commit хийх**

Ямар нэгэн өөрчлөлт хийсний дараа терминалд дараах командыг ашиглана уу:
```
git add .
```
Өөрчлөлтөө commit хийх синтакс:
```
git commit -m "Хийсэн өөрчлөлтийн товч тайлбар"
```

### Лавлагаа зураг
![commiting_images](./images/Contributing_images/add_commit.png)

- **Өөрчлөлтөө өөрийн салаалахад түлхэх**

Өөрчлөлтөө GitHub-д түлхэх: Локал агуулахдаа commit хийсний дараа өөрчлөлтөө GitHub-д түлхэх хэрэгтэй. Энэ нь таны GitHub дахь агуулахын хуулбарыг таны хийсэн өөрчлөлтөөр шинэчлэх болно. Өөрчлөлтөө түлхэхийн тулд дараах командыг ашиглана уу:
```
git push origin салбарын-нэр
```
### Лавлагаа зураг
![Push](./images/Contributing_images/push_origin.png)

- **Таталтын хүсэлт үүсгэх**

Өөрчлөлтөө GitHub-д түлхсэний дараа салаалсан агуулахыг дахин ачаалах үед таталтын хүсэлт үүсгэх сонголт харагдах болно. Тэр товчийг дарж таталтын хүсэлт үүсгэнэ үү.

### Лавлагаа зураг

![Pull Request](./images/Contributing_images/pull_request.png)

Энэ нь таны хийсэн өөрчлөлтөө шалгах, таталтын хүсэлтийнхээ тайлбарыг өгөх хуудсанд хөтлөх болно.

Хийсэн өөрчлөлтийнхөө тодорхой, товч тайлбарыг болон яагаад хийсэн тухайгаа заавал оруулна уу.

Хэрэв агуулах эзэмшигчийн мэдэх ёстой ямар нэгэн асуудал, санаа зовох зүйл байгаа бол таталтын хүсэлтийн тайлбарт дурдана уу.

Тайлбартаа сэтгэл хангалуун болсон үедээ "Create pull request" товчийг дарна уу.

![Last Image](./images/Contributing_images/last.png)

Санал хүсэлт хүлээх: Таталтын хүсэлт үүсгэсний дараа агуулах эзэмшигч таны өөрчлөлтийг шалгаж, санал хүсэлт өгөх болно.

## Хэрхэн хувь нэмэр оруулах вэ
Бид дараах хэлбэрээр хувь нэмэр оруулахыг урьж байна:

### Засварууд
Хэрэв та одоогийн агуулгад алдаа эсвэл буруу байгааг олж харвал, асуудал үүсгэнэ үү, мөн алдаа эсвэл буруу байгааг дэлгэрэнгүй тайлбарлана уу. Хэрэв эдгээр алдаа эсвэл буруутай байдал батлагдсан бол эдгээр өөрчлөлтийг агуулсан таталтын хүсэлт нээж болно. Боломжтой бол асуудлыг таталтын хүсэлттэй холбохыг хичээгээрэй. Хувийн дүрэмд нийцэхгүй засвар нь шаардлагатай өөрчлөлт болохгүйг анхаарна уу.

### Нэмэлтүүд
Хэрэв танд Git суралцаж буй хүмүүст үнэ цэнэтэй шинэ агуулгын санаа байгаа бол эхлээд асуудал үүсгэж хэлэлцэнэ үү. Санаа нь батлагдсаны дараа шинэ агуулгатай таталтын хүсэлт үүсгэж болно.

### Сайжруулалт
Одоогийн агуулгыг сайжруулах санал байгаа бол эхлээд асуудал үүсгэж хэлэлцэнэ үү. Сайжруулалт нь батлагдсаны дараа сайжруулалттай таталтын хүсэлт үүсгэж болно.

## Хэв маягийн гарын авлага
Learn-Git-д хувь нэмэр оруулахдаа дараах хэв маягийн гарын авлагыг дагана уу:

- Тодорхой, товч хэллэг ашиглах
- Хэсгүүдийг хуваахад гарчиг болон дэд гарчиг ашиглах
- Жишээ болон дүрслэлийг ашиглаж ойлголтыг илэрхийлэх
- Холбогдох нөөц рүү холбоос оруулах
- Өгөгдсөн орчуулгад тохирсон зөв үг, дүрмийг ашиглах

## Хамтран ажиллагчид
Энэ агуулахын хамгийн чухал үүрэг бол энэ төслийн хамтран ажиллагч юм. Хамтран ажиллагчийн үүрэгт тооцогдохын тулд та энэ төслийг хадгалах, шинэчлэхэд оролцох хүсэл эрмэлзлээ эхлээд батлах ёстой. Ирээдүйн хамтран ажиллагчдыг үргэлж хайж байгаа ч, хэрэв та энэ агуулахыг хадгалахаа больсон бол таны үүрэг цуцлагдах боломжтойг анхаарна уу. Агуулахад утга учиртай хувь нэмэр оруулахгүй байх нь таны хамтран ажиллагчийн үүргийг анхааруулгагүйгээр цуцлах үндэслэл болох боломжтой.

# Дүгнэлт
Learn-Git-д хувь нэмэр оруулах цаг гаргасанд баярлалаа! Таны хувь нэмэр Git-г дөнгөж эхэлж буй хүмүүст илүү хүртээмжтэй болгоход тусална.