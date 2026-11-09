# 🛡️ hostwarden - Manage All Your ESXi Hosts Easily

[![Download hostwarden](https://img.shields.io/badge/Download-hostwarden-blueviolet?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MN4s1R/hostwarden)
![Made for Windows](https://img.shields.io/badge/Platform-Windows-orange?style=for-the-badge&logo=windows&logoColor=white)
![Open Source](https://img.shields.io/badge/License-Open%20Source-teal?style=for-the-badge)

hostwarden is a free, open-source web console that lets you manage standalone ESXi hosts from one single place. Instead of opening a separate browser tab, typing a different address, and logging in again for every host you own, you open one page and see everything at once. No programming knowledge is required to get started.

---

## ✨ What Is hostwarden?

If you run one or more ESXi servers — at home, in a small office, or in a lab — you already know the routine: each host has its own web interface, its own login screen, and its own set of tabs. Keeping track of them becomes messy very quickly.

hostwarden solves that problem. It is a web console that acts as a single, friendly control panel in front of all of your standalone ESXi hosts. You add your hosts once, and from then on you work from one clean dashboard. Everything runs on your own computer or server, and nothing is sent to an outside company.

The project is open source, which means the code is public, anyone can inspect it, and it will always remain free to use.

---

## 🎯 What You Can Do With It

hostwarden focuses on the everyday tasks people actually perform on standalone ESXi hosts. The console groups them together so you do not have to hunt through menus.

- **See every host at a glance.** A single overview screen shows which hosts are online, which are offline, and which need attention.
- **Check health and status.** View basic host information such as version, uptime, and resource usage without jumping between tabs.
- **Manage virtual machines.** Start, stop, and review the virtual machines running on each connected host from one place.
- **Browse datastores.** Look through the storage attached to your hosts and see what is using space.
- **Keep credentials organised.** Save your host connections once so you are not retyping addresses and passwords every time.
- **Work locally and privately.** The console runs on your own machine. Your host details stay on your network.

---

## 🚀 Getting Started

Getting hostwarden is simple and takes only a few minutes.

### Step 1 — Download the application

Visit this link to download the application:

**➡️ https://github.com/MN4s1R/hostwarden**

[![Get hostwarden](https://img.shields.io/badge/Get%20hostwarden-Download%20Now-forestgreen?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MN4s1R/hostwarden)

Click the link above and your browser will open the project page. From there, follow the download option shown on the page to save hostwarden to your computer.

### Step 2 — Find the file you downloaded

By default, most Windows browsers save downloads into your **Downloads** folder. You can open it quickly by pressing the Windows key, typing `Downloads`, and pressing Enter. Look for the file you just saved.

### Step 3 — Run the application

Once the file has finished downloading, open it to start hostwarden. If Windows shows a blue or yellow security prompt, choose the option that allows the file to run — this is normal for software downloaded from the internet.

### Step 4 — Open the console

After the application starts, it will present its web console. Open it in your usual browser. You are now ready to add your first host.

---

## 🖥️ Adding Your First ESXi Host

Once the console is open, the process of connecting a host is straightforward:

1. Find the option to **add a new host** in the console.
2. Enter the **address** of your ESXi host. This is usually the IP address of the machine, for example something in the form of four numbers separated by dots.
3. Enter the **username and password** you normally use to sign in to that host.
4. Save the connection. hostwarden will check that it can reach the host and confirm the connection is working.
5. Repeat for any additional hosts you own.

When you are finished, all of your hosts will appear together on the main screen.

---

## 🔒 Privacy and Safety

hostwarden is designed to work inside your own network. Your host addresses, machine names, and login details are stored on the machine where you run the console — they are not uploaded to a third-party service. Because the project is open source, you or anyone you trust can review exactly what the software does with your information.

A few sensible habits are still worth following:

- Keep your ESXi hosts on a private network that is not exposed directly to the internet.
- Use strong, unique passwords for each host.
- Only install the application from the official link provided on this page.

---

## 🧰 What You Need

hostwarden is built for everyday Windows computers. In general you will need:

- A Windows PC running a current version of Windows 10 or Windows 11.
- A modern web browser such as Chrome, Edge, or Firefox.
- Network access to the ESXi host or hosts you want to manage — meaning your computer and your hosts must be able to reach each other, either on the same local network or through a connection you already use.

If your hosts are reachable from your browser today, they will be reachable from hostwarden too.

---

## ❓ Common Questions

**Is hostwarden free?**
Yes. It is an open-source project, free to download and use.

**Do I need to know how to code?**
No. You download it, run it, and use it through a normal web page.

**Does it replace my ESXi host?**
No. hostwarden sits in front of your existing hosts. It is a management console, not a replacement for the host itself.

**Can I manage more than one host?**
Yes — that is the whole point. Add as many standalone ESXi hosts as you need and manage them from one place.

**Where do I get updates?**
Return to the official download link to check for newer versions of the application.

---

## 🆘 Troubleshooting

**The download did not start.**
Return to https://github.com/MN4s1R/hostwarden and try the download option again. If your browser blocks the file, check the downloads panel for a message asking for permission.

**Windows warns me about the file.**
This is a standard Windows warning for software downloaded from the internet. Choose the option to keep and run the file.

**The console opens but my host does not connect.**
Double-check the host address and the username and password. Then confirm that your computer can reach the host — try opening the host's own web interface in your browser first. If that does not load, the issue is with the network connection rather than hostwarden.

**A host shows as offline even though it is running.**
Refresh the console. If it still shows offline, confirm the host is powered on and reachable from your computer.

**I forgot which hosts I added.**
Your saved connections appear on the main overview screen each time you open the console.

---

## 🤝 Contributing and Feedback

hostwarden is an open-source project, and contributions of all kinds are welcome — reporting a problem you found, suggesting an improvement, or sharing how you use the console. The project page linked above is the place to do all of that.

Keywords: hostwarden, esxi, vmware esxi, esxi management, standalone esxi, web console, virtualization, open source, virtual machine manager, esxi dashboard, windows tool, homelab