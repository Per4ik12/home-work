Задание №2
А теперь мы с тобой напишем форму ввода ответа на тест по биологии для студентов. Он должен запрашивать по порядку этапы развития человека (проверим твое умение гуглить, что тоже очень важно для программиста. ) и в конце вывести все стадии, разделенные знаком =>, что будет означать постепенный переход от одного к другому. В следующих уроках мы дополним эту форму до полноценного теста, который будет проверять правильность ответов, а пока - начнем с малого. Напоминаем, что разделить эти данные тебе поможет команда sep внутри команды print, например, чтобы разделить переменные знаком + нужно ввести: 
print(a1, a2, a3, sep='+')
Подсказка: последняя стадия развития - Homo sapiens sapiens.

# homo sapiens
dryopithecus = input("Введите Dryopithecus: ")
ramapithecus = input("Введите Ramapithecus: ")
australopithecus = input("Введите Australopithecus: ")
homo_erectus = input("Введите Homo Erectus: ")
homo_sapiens_neanderthalensis = input("Введите Homo Sapiens Neanderthalensis: ")
homo_sapiens_sapiens = input("Введите Homo Sapiens Sapiens: ")
print(dryopithecus, ramapithecus, australopithecus, homo_erectus, homo_sapiens_neanderthalensis, homo_sapiens_sapiens, sep=' => ')
