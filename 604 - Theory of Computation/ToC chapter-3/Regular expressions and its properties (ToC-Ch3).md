1. *Define regular expression.* #board_2020 #board_2021 #board_2019  
2. *Write down the rules of regular expression.* #board_2021 #board_2019 
3. Write down the operators used in regular expression. #board_2020 
4. Let r be a regular expression. Then there exists an NFA with E-transitions that accepts L(r). #board_2022 #board_2018 
5. Convert the following regular expression to NFA with E-transition. 
	1. $01*+1$ #board_2022 #board_2019 
	2. $10+(0+11)0*1$ #board_2022 
	3. $10(0+1)*010$ #board_2018 
	4. $(a+b)*ab(a|b)$ #board_2018 
	5. $(0+1)(01)*$ #board_2018 
	6. $a*(ab)$ #board_2018 
	7. $(a|b)*abb$ #board_2019 
	   
> [!abstract] 📝 *Note: There are 4 common cases when you can understand that the conversion to NFA with ε (epsilon) transitions is expected (ε-NFA) -*
> - a) When it say convert **Regular Expression to NFA**
> - b) When it explicitly mentions **ε-transitions**, **E-transitions**, or **ε-NFA**/**E-NFA**.
> - c) When the regular expression includes operators like **`|`, `*`, or concatenation**, and suggests combining automata.
> - When the problem references or follows **Thompson’s Construction** method.

6. Convert the following regular expression to s-NFA [standard-NFA]
	1. $(0+1)*1(0+1)$ #board_2021 
	2. $(a|b)*abb(a|b)$ #board_2021 

7. Minimize the following DFA by minimization algorithm: #board_2022 #board_2020 #board_2018  [Figure is provided on chapter-3 question no. 19]