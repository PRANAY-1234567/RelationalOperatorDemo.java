# ☕ Java Relational Operators Example

## 📌 Description

This Java program demonstrates the use of **relational operators** to compare integer values. It checks whether one number is greater than another and prints the result as `true` or `false`.

---

## 🚀 Features

* Uses relational operator `>` (greater than)
* Compares multiple integer values
* Displays boolean results (`true` / `false`)

---

## 🛠️ How It Works

1. Four integer variables are declared:

   * `a = 10`
   * `b = 5`
   * `c = 15`
   * `d = 10`
2. The program compares:

   * `a > b`
   * `a > c`
   * `a > d`
3. Each comparison returns a boolean value (`true` or `false`).
4. The results are printed using `System.out.println()`.

---

## 💻 Code

```java
class Relational
{
	public static void main(String args[])
	{
		int a=10,b=5,c=15,d=10;
		System.out.println("a>b :"+(a>b));
		System.out.println("a>c :"+(a>c));
		System.out.println("a>d :"+(a>d));
	}
}
```

---

## ▶️ Example Output

```
a>b :true
a>c :false
a>d :false
```

---

## 📚 Concepts Used

* Java basic syntax
* Variables and data types (`int`)
* Relational operators (`>`, `<`, `==`, etc.)
* Output using `System.out.println()`

---

## 🎯 Use Case

This program helps beginners understand:

* How comparisons work in Java
* How boolean values are generated from conditions

---

## 🔧 Future Improvements

* Add more relational operators (`<`, `==`, `!=`, `>=`, `<=`)
* Take user input using `Scanner`
* Use conditions (`if-else`) based on comparison results

---

## 📄 License

This project is open-source and free to use.
