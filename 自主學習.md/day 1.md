# day 1 to learn


## 1.print (" ") 印出

```
print(" ") 就是列印出什麼東西
Ex: print("Hello world ! ")
A: Hello world ! 
```

## 2.Strings 就是字串


## 3.\n 換行
```
\n 就是換行的意思
Ex: print("Hello world ! \nHello world ! ")
A: Hello world ! 
   Hello world !
輸入\n就會換去下一行
```
## 4.input (" ")  也是印出
```
input 也是印出的一種，但是他是可以讓使用者輸入訊息在印出
Ex: input("what is your name?") 當我輸入我的名字ex: brad
A:就會印出 what is your name?brad
第二個就是 Ex: print ("Hello @ " + input("what your name ? "))
A:what your name ? brad     input的會先執行
Hello brad                  後面print才會執行
```
## 5.len() 這個函數可以讓電腦計算說你電腦有幾個字串
```
Ex:print(len(input("what your name?") 
然後我輸入brad
他的答案就會出現 4 因為brad 是4個字母
步驟是先顯示what your name?
第二步是len 會計算出使用者輸入幾個字串 當我輸入brad的
最後print 就印出len 就是四個字串
```

```
根據上提如果程式碼長點可以用代號來取代
Ex:name = input("what your name?")
length = len (name)
print (lenght)
答案就會顯示 4 
```
## 額外測驗 1
```
如果有兩個數字 當我們輸入兩個數值的時候答案給出來的是兩個相反
Ex: a:12  b:15
A:  a:15 b:12 
答案出來就會給相反的
該如何做到？
```
## 答案
```
a = input ("a :") 
b = input ("b :")
c = a
a = b 
b = c
print(" a :" + a )
print(" b :" + b )
就等於準備三杯杯子的意思換來換去而已
```
## 額外測驗 3 
```
Hello welcome  to the band name gerator!(歡迎來到樂團名稱生成器）
what name of city you grew up in? (你在哪個城市長大的）
回答是A:Taiwan 
what your pet's name ? (你的寵物叫什麼？）
A:brad
Your Band name could be taiwan brad （你的樂團名字將會是 taiwan brad )
```
