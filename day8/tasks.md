Дано:

    db = [
        {
            "name": "Anora",
            "phone": "992123456789",
        },
        {
            "name": "Kamila",
            "phone": None,
            "city": "Dushanbe",
        },
        {
            "name": "Marhabo",
            "phone": "992123456789",
        },
        {
            "name": "Tamano",
            "phone": None,
        },
        {
            "name": "Sabina",
            "phone": "42123456789",
            "city" : "NewYork"
        },
        {
            "name": "Nilufar",
            "phone": "992123456789",
        },
    ]

1. Написать:
    
- функцию которая вернет список строк только существующих номеров телефонов
 - функцию которая вернет список словарей, только тех в которых есть номер телефона
 - функцию которая вернет список словарей в которых нет номеров телефонов

2. Дано:

        def get_phones(db):
            l = []
            for obj in db:
                l.append(obj["city"])

            return l

        get_phones(db)

- почините функцию так, чтобы в тех случаях, когда нет city, в список добавлялось None