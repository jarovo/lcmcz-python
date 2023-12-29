# Zadání projektíků
Toto není test. Nebudeme se hodnotit. Ani mezi sebou. Jediný s kým se můžete hodnotit jste vždycky vy v minulosti abyste viděli své zlepšení. Jenom si budeme povídat o tom co bychom mohli jak udělat.

## Scratch
Animace
Vytvořte animaci s vánočním tématem.
Nechte sprity reagovat jeden na druhý.

> [!Important]
> Jak můžete změnit Váš projekt aby uživatel mohl ovlivňovat děj animace?

> [!Important]
> Jak byste animaci/hru popsali kamarádovi?

## Turle
Vánoční stormeček
1. Nakresli trojůhelník.
2. Nakresli Vánoční stromeček. Můžeš znovu-použít  kód z 1. pomocí definice funkce?
3. Můžeš přidat dárečky. Můžeš použít funkce tak abys udělal nějaký větší a jiný menší pomocí stejného kódu?
   
> [!Important]
> Jak byste váš kód popsali kamarádovi?

## Python
### První program “Ahoj světe”
Potřebujeme ověřit, že tvé vývojové prostředí funguje. Cílem tedy bude vytisknout na obrazovku pomocí funkce print(“Ahoj světe”) řetězec “Ahoj světe” neboli “Hello world” na obrazovku. Při učení-se novému jazyku v programování často začínáme výpisem řetězce “Hello world” na obrazovku. Existuje spousta návodů na to jak vypsat tento řetězec v mnoha různých programovacích jazycích. Určitě někde na internetu najdete způsob jak toho jednoduše dosáhnout v Pythonu. Můžete použít již připravené online platformy jako je 
[replit.com](replit.com) nebo pokud se chcete zabývat pouze Pythonem, pak můžete začít s [Google colab](https://colab.research.google.com/)

> [!Important]
> Jestli chceš vypisovat řetězec v Pythonu, budeš určitě potřebovat pochopit funkci print().

> [!Important]
> K čemu v Pythonu slouží funkce print()?

Dále můžete program rozšířit o to aby se tento řetězec vypsal na obrazovku 1000x.

> [!Important]
>Jak byste Váš kód popsali spolupracujícímu kamarádovi tak aby mohl pokračovat ve vaší práci?

Další úkol je program změnit tak, aby nejprve přijmul text, který má vypsat 1000x a poté ihned vypsal.

> [!Important]
> Jak byste Váš kód popsali spolupracujícímu kamarádovi tak aby mohl pokračovat ve vaší práci?

Co dál? Co takhle vypsat text 1000x ale tak, že každý řádek bude vypsán zvlášť, po vteřinách.

> [!Important]
> Jakým způsobem jste vypsali text na obrazovku 1000x - použili jste nějaký druh programové smyčky?
 
> [!Important]
> Jaký a proč zrovna ten?

### Python a počty.
Potřebujeme program co přijme na řádku několik čísel oddělených vždy alespoň jednou mezerou. Potřebujeme aby tento program čísla sečetl a matematicky správný výsledek dal na výstup.
V případě, že nastane chyba, program musí skončit s exit status kódem jiným, než 0, takže v linuxu
```
$ pocty 
123 456 789
1368
$ echo $?
0
$ pocty
123 456 7aa
Na vstupu přijat řetězec “7aa”, který není číslem.
$ echo $?
128
```

> [!Important]
> Které problémy je potřeba při řešení tohoto úkolu vyřešit?

> [!Important]
> Jak nám poslouží funkce input() a str.split() a print()?

### Program Zdravič
Cílem programu je najít způsob jak nahradit učitelovy pozdravy různými způsoby. Když zadám oslovení: Pepo
```
Ahoj Pepo, jak se ti daří?
```
```
Dobré ráno pane Pepo, co jsi měl k snídani?
```
```
Dnes je krásně Pepo, jaké sluneční brýle si nevezmeš?
```
