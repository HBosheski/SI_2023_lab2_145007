# SI_2023_lab2_145007

Задача 1:Hristijan Bosheski 145007

Задача 2:![xxcxcxxcxc](https://github.com/HBosheski/SI_2023_lab2_145007/assets/130303520/b508c335-993b-4090-82a5-7eb4cb386510)

Задача 3:Цикломатската комплексност на овој код е 3, истата ја добив преку формулата CC = E - V + 2, според дадениот граф на контрола на текот, имаме 20 патеки и 19 јазли, па според формулата погоре CC = 20-19+2 = 3

Задача 4: Според критериумот Every Branch, возможни се 8 тест примери за првиот if услов (истите кои се наведени во Задача 5), потоа постојат уште по два посебни тест примери за условите if (existingUser.getEmail() == user.getEmail()) и if (existingUser.getUsername() == user.getUsername()), како и уште два за делот каде се проверува валидноста на лозинката, со што доаѓаме до 12 тест примери.

Задача 5: ![multiple](https://github.com/HBosheski/SI_2023_lab2_145007/assets/130303520/5880a9c6-17ce-47bf-aae4-6807d0695a88)
Според сликата погоре, можеме да забележиме дека според методот Multiple Condition за дадениот услов, можни се 8 комбинации на тест примери, односно за секој од трите услови комбинирани со TRUE или FALSE. Од табелата може да се забележи дека за 7 од 8 тест примери, на крај ќе се добие резултат FALSE, што во случајот значи дека корисникот не постои, односно ќе се испринта пораката "Mandatory information missing!". Во последниот тест случај кога ниту еден од трите услови е точен, тогаш имаме ситуација кога сите параметри се веќе постоечки во базата, па оттука се заклучува дека корисникот е веќе постоечки во базата.
