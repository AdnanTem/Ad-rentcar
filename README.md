السلام عليكم .

أول سكربت خاص فيني و إنشالله مو آخر سكربت , المهم فكرة السكربت هي : إستأجار مركبة في قراج الحديقة العامة .

https://youtu.be/AOAF8cy6710 : الفيديو خاص في السكربت


متطلبات السكربت : context , target .

كود العين : ``lua

  AddCircleZone("RentCar", vector3(112.11727, -1088.44, 29.302469), 0.9, {
    name="RentCar",
    debugPoly=false,
    useZ=false,
    },
    {
    options = {
        {
            event = "RentCar",
            icon = "fas fa-car",
            label = "إستأجار مركبة",
            job = {"all"},
        },
    },
    distance = 1.5  
})

``

تنويه : يمكنك إضافة عدد إحداثيات لانهائي و عدد مركبات لانهائي .

رابط الدسكورد الخاص فيني في حال كان عندكم أي أسألة : https://discord.gg/uQSeM8r2ue .
