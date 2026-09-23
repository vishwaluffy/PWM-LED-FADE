# PWM-LED-FADE
To perfrom Fade LED In and Out using Software-Controlled PWM Ramp
---

## Apparatus Required

| S. No. | Apparatus / Software | Specification |
|:---:|---|---|
| 1 | Microcontroller Development Board | **NXP S32K144 Development Board** |
| 2 | IDE | **S32 Design Studio** |
| 3 | Programming Language | **Embedded C** |
| 4 | SDK | **S32K144 SDK** |
| 5 | LED | On-board LED / External LED |
| 6 | Programmer / Debugger | On-board Debugger / OpenSDA |
| 7 | USB Cable | For programming and power supply |

---
## Procedure

1. Connect the **S32K144 Development Board** to the computer.
2. Open **S32 Design Studio** and create/open the S32K144 project.
3. Configure the LED GPIO pin as a **Digital Output**.
4. Implement **software-controlled PWM** for the LED.
5. Start with the PWM duty cycle at **0%**.
6. Gradually increase the duty cycle in small steps up to **100%** to fade the LED **IN**.
7. Maintain a short delay between each duty-cycle step.
8. Gradually decrease the duty cycle from **100% to 0%** to fade the LED **OUT**.
9. Repeat the increase and decrease sequence continuously.
10. Build and download the program to the **S32K144** board.
11. Observe the LED and verify the smooth fading effect.

---

## output


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/13f5afdb-742b-4769-a649-5e5baaa5a1ea" />







---

## Result

The LED was successfully **faded IN and OUT** using a software-controlled PWM ramp. The LED brightness increased gradually from **0% to 100%** and decreased from **100% to 0%**, producing a smooth and continuous fading effect.
