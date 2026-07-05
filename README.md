# Epic Games Email Generator
Developed by **Trenjamin Button**

A lightweight utility designed to generate unique Epic Games account registration emails using a single, primary Gmail address. By utilizing the "Gmail Dot Trick," this tool creates dozens of variations that Epic Games treats as unique accounts, while all incoming verification and marketing emails are still delivered directly to your main Gmail inbox.

---

## 💡 How It Works (The Gmail Dot Trick)

Google's email system completely ignores periods (`.`) within a username before the `@gmail.com` domain. However, many external services—including Epic Games—treat every variation containing a dot as a completely distinct account string. 

For example, if your primary email is `johnsmith@gmail.com`, this tool will generate variations like:
* `j.ohnsmith@gmail.com`
* `jo.hnsmith@gmail.com`
* `j.o.h.n.s.m.i.t.h@gmail.com`

> 📩 **Result:** You can register dozens of Epic Games accounts using these generated strings, but every single verification code, receipt, or notification will land safely in your original `johnsmith@gmail.com` inbox.

---

## 🚀 How to Use

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/epic-games-email-gen.git](https://github.com/YOUR_USERNAME/epic-games-email-gen.git)
   cd epic-games-email-gen
