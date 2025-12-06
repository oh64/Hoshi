# Hoshi

Hoshi is a cross-platform Spacebar client built with Flutter, currently in devlopment. Expect bugs. Well, what does that mean?

Hoshi works on:

* iOS
* Android
* Web
* Windows
* Linux
* macOS

The web version will be available when the first release is out. You'll be able to try it on **[https://hoshi.oh64.moe](https://hoshi.oh64.moe)**.

As the only maintainer of Hoshi, tests are made for Linux and Android only. I may test the Windows version sometimes. There may be some testing on iOS by someone I know who has an iPhone, but it remains very basic.

### On what devices will it be tested?

* **Android**: POCO X6 Pro (Unofficial Voltage OS 5.2 | Android 16) and Mi 10 (Official MIUI 12.0.3 | Android 10)
* **Linux**: Arch Linux (as default stratum, with kernel Linux 6.17.9-arch1-1, using GNOME Wayland) with Bedrock Linux installed above it
* **Windows**: Atlas OS 11 (no specification needed)
* **Web**: Zen Browser (Firefox and Chrome), on the official instance and a private one

## Screenshot

### On android
<img width="30%" height="30%" alt="image" src="https://github.com/user-attachments/assets/6de07dce-0340-43cf-b370-38cb79108943" /><img width="30%" height="30%" alt="image" src="https://github.com/user-attachments/assets/9f61078c-faef-412f-9bf2-9e414a827d75" /><img width="30%" height="30%" alt="image" src="https://github.com/user-attachments/assets/e1de2cff-5b27-498f-a1b1-ecf1b574b083" /><img width="30%" height="30%" alt="image" src="https://github.com/user-attachments/assets/b9007be5-3fce-4f5b-b37b-4763a18c304b" /><img width="30%" height="30%" alt="image" src="https://github.com/user-attachments/assets/10a14a79-6f91-4ca9-9db2-1f8d3a289f10" />

### On linux
<img width="100%" height="100%" alt="image" src="https://github.com/user-attachments/assets/1b6b849b-cc1e-46b7-b545-e78c43f187f7" />


---

### Why isn't Hoshi open-source?

That's temporary. I want to make it stable and learn Flutter all by myself. Plus, Hoshi uses Sentry (with messages and images not shared), because I want to learn how to use it.
So yeah, it will be open-source one day.

---

### Is Hoshi stable?

The latest version (0.1.0) isn't stable. It can crash, there are cache and optimisation issues, some behaviours aren't fully implemented (like in settings). It has **0 fail-safe**: for example, if it doesn't understand a server response, it just doesn't care and renders it anyway.

---

### Why are some texts in French?

Hoshi was originally meant to be used only by me (so I started doing everything in French, bad idea, I would've translated it anyway).
I tried to translate everything, but bruh, I may have missed something.

---

### Will Hoshi have themes and plugins?

That was one of the first things I wanted to do, so I just have to upgrade the code. But since I wanted to finish the app first, it will take a long time.
A basic page to change colors and some UI size is already implemented but not used (it's too ugly).
So yeah, Hoshi will have that when it actually works.

---

### Does Hoshi work with old Spacebar server versions?

Maybe, but that would only be luck. Hoshi will only support the latest Spacebar version at build time.

---

### Does Hoshi work with the official Discord?

I haven't tried it.
Wait I should!
Uh why am I writing to myself like that.

---

### Who is on the Hoshi icon?

It represents nobody. It's just there because I don't know how to make a proper icon.
It may be removed in future versions.
Also every time I open Ibis Paint, I see some lines that aren't right, so yeah, I will change it EVERY BUILD.

---

### Hoshi doesn't work with my server!!!

Did you properly create your `.well-known`?
Hoshi will try to find your API link, but bro, don't make it harder than it already is.

---

### Does anyone really use this client when Fermi exists?

I don't know, and I don't really care. That's why I don't create a guild or something.
My friends already use it and tell me what's bad.
I will read and try to fix issues if you make one.

---

### When will an update be released?

When it works.
The web version will be updated faster than the builds in the release.

---

### Can I self-host the web version?

Nah. And anyway the code can only work with my URL because I didn't prepare it.
