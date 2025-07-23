# 🛠️ Arduino IDE কোড সাজেশন প্রবলেম

কখনো কখনো Arduino IDE তে অটো কোড সাজেশন (autocompletion suggestions) কাজ করে না। নিচের ধাপগুলো অনুসরণ করলে এই সমস্যার সমাধান পাওয়া যাবে।

---

## ✅ Step 1: Latest Arduino IDE ইনস্টল করুন

আপনার পিসিতে অবশ্যই Latest version এর Arduino IDE ইনস্টল থাকতে হবে।

অনেক সময় পুরাতন version ব্যবহারের কারণে কোড সাজেশন কাজ করে না।

🔗 [Latest Arduino IDE Download লিংক](https://support.arduino.cc/hc/en-us/articles/360019833020-Download-and-install-Arduino-IDE)

---

## ✅ Step 2: Board এবং Port সিলেক্ট করুন

কোড করার আগে অবশ্যই Arduino ডিভাইস সংযুক্ত করুন এবং:

- `Tools > Board` এ গিয়ে আপনার বোর্ড সিলেক্ট করুন
- `Tools > Port` থেকে COM Port সিলেক্ট করুন

এটা না করলে কোড সাজেশন কাজ নাও করতে পারে।

---

## ✅ Step 3: Autocompletion Enable করুন

1. IDE এর উপরের মেনু থেকে **File > Preferences** এ যান  
2. “**Editor Quick Suggestions**” অপশনটি খুঁজে বের করে টিক মার্ক দিন  
3. এরপর OK চাপুন

এখন থেকে যখন আপনি কোড টাইপ করবেন, তখন Arduino IDE অটো সাজেশন দিবে ✅

---

📌 Extra Tip:
- Suggestion না এলে IDE একবার **রিস্টার্ট** করুন
- অথবা নতুন স্কেচে চেষ্টা করুন

---

