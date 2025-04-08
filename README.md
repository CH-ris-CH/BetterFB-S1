# 🚀 Optimized Klipper Configuration for FlyingBear S1  

The **FlyingBear S1** is a budget-friendly 3D printer with impressive hardware, but its stock Klipper setup lacks polish. This repo provides **tuned macros, optimized configurations, and hardware mod guides** to elevate your printing experience without breaking the bank.  

---

## **Key Features & Improvements**  
**🔹 Smarter Print Start Macros**  
- Proper **bed/nozzle heating sequence** to measure actual hotbed surface.  
- Optimized **nozzle cleaning routine** for consistent priming.  

**🔹 Quiet Night Mode**  
- Lowers stepper motor parameters and fan speeds for silent operation. Adjusted acceleration, jerk, and speed limits for smoother prints  
- Disables LED backlight for dark rooms.   

**🔹 Hardware Upgrade Roadmap** *(Optional but Recommended)*  
- Coming soon:  

---

## **Why Use This Configuration?**  
The stock FlyingBear S1 Klipper config works, but it’s **unrefined**:  
- Inconsistent nozzle cleaning and bed meshing.  
- Noisy fans/steppers and bright LEDs disrupt night printing.  
- Suboptimal constuctional decisions.  

This repo fixes those issues while keeping the printer’s **budget-friendly spirit** intact.  

---

## **Installation**  
1. **Back up** your current `printer.cfg` and `macros.cfg`.  
2. **Copy** the configs from this repo to your Klipper directory.  
3. **Adjust** parameters like `bed_mesh`, `z_offset`, and `max_accel` for your hardware.  
4. **Optional**: Follow the hardware mod guides *(coming soon)* for even better results.  

