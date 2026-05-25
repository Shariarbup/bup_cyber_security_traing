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

