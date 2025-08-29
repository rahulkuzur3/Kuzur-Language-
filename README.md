# Kuzur language  🐍✨

**Kuzur language ** is a tiny, learnable programming language designed by Rahul Kuzur.  
It’s inspired by Python and allows you to run `.kz` files easily on Windows and Linux.  

## 🚀 Features

- Variables, arithmetic, strings, booleans  
- If / elif / else conditional statements  
- While loops  
- Functions with return values  
- Built-in functions: `print`, `input`, `len`, `int`, `str`  
- Blocks with `{ ... }` like C/JavaScript  
- Single-line comments with `//`  
- Cross-platform: Windows & Linux standalone executables  

---

## 💻 Installation

### **Windows**

1. Download the latest **KuzurLang executable** from the `dist` folder.  
2. Open Command Prompt and navigate to the folder containing `kuzur.exe`.  
3. Run your `.kz` program:

```bat
kuzur myprogram.kz
```
Optional: Add kuzur.exe to your PATH for global access.


---

### **Linux**

1. Download the latest KuzurLang executable from the dist folder.


2. Open terminal and navigate to the folder containing kuzur.


3. Make it executable (first time only):

```

chmod +x kuzur
```
4. Run your .kz program:


```
./kuzur myprogram.kz
```
Optional: Move it to /usr/local/bin/ for global access:
```
sudo mv kuzur /usr/local/bin/
```
Now you can run:
```
kuzur myprogram.kz
```
from anywhere!


---

📝 Quick Start

Example program:
```
// hello_world.kz
print("Hello, KuzurLang!")

func add(a, b) {
    return a + b
}

print("2 + 3 =", add(2, 3))
```
Run it:
```
kuzur hello_world.kz
```
Output:
```
Hello, KuzurLang!
2 + 3 = 5

```

🤝 Contributing

Feel free to submit pull requests or open issues.
Follow the code style in kuzurlang.py and add examples to examples/.


---

📜 License

MIT License. See LICENSE for details.


---

Made with ❤️ by Rahul Kuzur 

