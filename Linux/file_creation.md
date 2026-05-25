# AlmaLinux এ File Create এবং Vi Editor দিয়ে Edit করার বাংলা টিউটোরিয়াল

## ১) নতুন File তৈরি করা

টার্মিনাল খুলে নিচের command লিখুন:

```bash
touch myfile.txt
```

এতে `myfile.txt` নামে একটি নতুন file তৈরি হবে।

File তৈরি হয়েছে কিনা দেখার জন্য:

```bash
ls
```

---

# ২) Vi Editor দিয়ে File Open করা

নিচের command লিখুন:

```bash
vi myfile.txt
```

এখন file টি `vi editor` এ open হবে।

---

# ৩) লেখা Edit করা

`vi` editor open হওয়ার পরে keyboard থেকে নিচের key চাপুন:

```text
i
```

এটি `Insert Mode` চালু করবে।

এখন আপনি লেখা লিখতে পারবেন।

উদাহরণ:

```text
Hello World
Welcome to AlmaLinux
```

---

# ৪) লেখা Save করা

লেখা শেষ হলে:

### Step 1:

Keyboard থেকে চাপুন:

```text
ESC
```

### Step 2:

তারপর নিচের command লিখুন:

```bash
:w
```

তারপর Enter চাপুন।

এতে file save হবে।

---

# ৫) Save করে Exit করা

`ESC` চাপার পরে লিখুন:

```bash
:wq
```

তারপর Enter চাপুন।

এতে file save হয়ে editor বন্ধ হবে।

---

# ৬) Save না করে Exit করা

যদি save না করে বের হতে চান:

```bash
:q!
```

তারপর Enter চাপুন।

---

# ৭) File এর Content দেখা

টার্মিনালে লিখুন:

```bash
cat myfile.txt
```

---

# গুরুত্বপূর্ণ Vi Commands

| Command | কাজ |
|---|---|
| i | Insert Mode |
| ESC | Command Mode এ ফিরে যাওয়া |
| :w | Save |
| :wq | Save + Exit |
| :q! | Save ছাড়া Exit |

---

# Complete Example

```bash
touch myfile.txt
vi myfile.txt
```

তারপর:

1. `i` চাপুন
2. লেখা লিখুন
3. `ESC` চাপুন
4. `:wq` লিখে Enter চাপুন



# AlmaLinux এ Nano Editor দিয়ে File Edit করার বাংলা টিউটোরিয়াল

## ১) নতুন File তৈরি করা

টার্মিনালে নিচের command লিখুন:

```bash
touch myfile.txt
```

এতে `myfile.txt` নামে একটি file তৈরি হবে।

---

# ২) Nano Editor দিয়ে File Open করা

নিচের command লিখুন:

```bash
nano myfile.txt
```

এখন file টি `nano editor` এ open হবে।

---

# ৩) লেখা Edit করা

Nano editor open হওয়ার পরে সরাসরি keyboard থেকে লেখা লিখুন।

উদাহরণ:

```text
Hello World
Welcome to AlmaLinux
```

---

# ৪) File Save করা

Keyboard থেকে চাপুন:

```text
CTRL + O
```

তারপর Enter চাপুন।

এতে file save হবে।

---

# ৫) Nano Editor থেকে Exit করা

Keyboard থেকে চাপুন:

```text
CTRL + X
```

এতে nano editor বন্ধ হবে।

---

# ৬) File এর Content দেখা

টার্মিনালে লিখুন:

```bash
cat myfile.txt
```

---

# গুরুত্বপূর্ণ Nano Shortcut

| Shortcut | কাজ |
|---|---|
| CTRL + O | File Save |
| CTRL + X | Exit |
| CTRL + K | Line Cut |
| CTRL + U | Paste |
| CTRL + W | Search |

---

# Complete Example

```bash
touch myfile.txt
nano myfile.txt
```

তারপর:

1. লেখা লিখুন
2. `CTRL + O` চাপুন
3. Enter চাপুন
4. `CTRL + X` চাপুন



