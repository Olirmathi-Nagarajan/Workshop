
## RTL Design & Synthesis on Cloud (GitHub Codespace)

This repository provides a ready-to-use **cloud-based lab** for RTL Design and Synthesis using open-source tools such as **Yosys**, **Icarus Verilog**, and **GTKWave**.
All tools run inside a **GitHub Codespace** with **noVNC desktop access**, requiring no local installation.

---

### Step 1 – Launch Codespace

Click **“Code → Codespaces → Create codespace on main”** to start your workspace on the cloud.
GitHub will automatically build and set up your environment.

![1_launchCodeSpace](https://github.com/user-attachments/assets/2de19226-670a-4b7b-941d-5314ce035b45)


---
### Step 2 – Codespace Setup and Logs

During setup, the Codespace installs all required tools.
Wait for the setup logs to complete (approximately 7–10 minutes).

![2_codespaceLog](https://github.com/user-attachments/assets/25bece6f-f3b2-46e2-9669-30f77f658234)

After successful configuration, your container environment is ready.

<img width="953" height="461" alt="3_codepsaceCreated" src="https://github.com/user-attachments/assets/a06e09dd-dbcd-4da5-b8e5-d92c2d70e74b" />

---

### Step 3 – Open a Terminal

Use **Terminal → New Terminal** inside VS Code to begin executing synthesis and simulation commands.

<img width="872" height="369" alt="4_openTerminal" src="https://github.com/user-attachments/assets/23277291-2ef5-4eb6-99f0-480e286deae0" />

---

### Step 4 – Verify Tool Installation

Run the following commands to verify tool installation:

```bash
yosys
iverilog
```

Both should display their version information, confirming correct setup.

<img width="580" height="700" alt="5_testYosys_Iverilog" src="https://github.com/user-attachments/assets/8f47dafe-85ff-4278-a325-eb1f4e2cd594" />

---

### Step 5 – Launch noVNC Desktop

Go to the **Ports** tab and click the **globe icon** next to the forwarded port (6080) to open the desktop environment in your browser.

![6_openVNC](https://github.com/user-attachments/assets/2244cded-230c-4f25-bd8e-372f668f7b8c)

---

### Step 6 – Access VNC Interface

In the directory listing, select `vnc_lite.html` to open a lightweight graphical desktop.

![7_vnc_lite](https://github.com/user-attachments/assets/0b2988cf-25a0-4aa9-953d-0559280afea9)

---

### Step 7 – Run Workshop Files and GTKWave

Navigate to your workspace folder and open GTKWave to analyze waveform outputs:

```bash
cd /workspaces/vsd-rtl/
ls
gtkwave
```

![8_workshopFolderAndgtkwaveTesting](https://github.com/user-attachments/assets/aac5f17b-9f9d-40bc-b09a-0446e8d4315a)


---

### Summary

Your cloud lab is now fully set up.
You can perform RTL design, synthesis, simulation, and waveform analysis directly from your browser, without installing any local software.

---
