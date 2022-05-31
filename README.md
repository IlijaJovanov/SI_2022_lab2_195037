# Втора лабораториска вежба по Софтверско инженерство


</br>
Илија Јованов бр. на индекс 195037
</br>
Control Flow Graph
</br>

![lab2_SII](https://user-images.githubusercontent.com/94320385/171292720-bf128e9e-1737-4a26-aba4-d437b5cd029b.png)

</br>

![kod](https://user-images.githubusercontent.com/94320385/171293921-010dc32d-8833-49a9-9540-05a2b900c3b9.png)

</br>

Цикломатска комплексност
</br>
Цикломатската комплексност на графот е 9

Ја одредив на сите начини и од сите испадна 9.
Пример по број на внатрешните  региони вкупно 8 и тој од надвор 1 =9
Друг начин 
број на ребра=32
број на јазли 25
ги одзимаме и добиваме 7 и + 2 според формулата = 9
</br>
Тест случаи според критериумот Every statement
</br>
![testovi tabeli](https://user-images.githubusercontent.com/94320385/171293240-81f3e0ca-e71e-4756-aa62-c3bf001407ca.png)
</br>
1.void everyStatementsTest(){
        IllegalArgumentException ex;
        ex= assertThrows(IllegalArgumentException.class, () ->lab2_si.function(newArrayList(Arrays.asList())));
        assertTrue(ex.getMessage().contains("List length should be greater than 0"));
        ex= assertThrows(IllegalArgumentException.class, () ->lab2_si.function(new ArrayList(Arrays.asList("22", "45", "99","65", "0"))));
        assertTrue(ex.getMessage().contains("List length should be a perfect square"));
}
Во првиот тест ја ставаме должината на низата да биде 0 и според кодот фрла ексепшан и завршува.
Во вториот случај ставме бројот на елементи да биде непарен број и пак завршува програмата.
И двата теста се успешно поминати.
</br>
</br>
</br>
</br>
</br>


