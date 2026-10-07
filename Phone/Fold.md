# Unnamed Fold Family

## Two Foldable Architectures

> **One platform, two radically different ways to use a large screen.**

**Products covered by this document:**

1. **Unnamed Fold** — large-format book-style foldable
2. **Unnamed Fold Compact** — compact clamshell foldable

**Status:** Product concept / engineering specification

---

# 1. Why Two Foldables?

Foldables should not be treated as one product category.

A large book-style foldable and a compact clamshell solve different problems.

The large foldable is a phone that becomes a tablet-like workspace.

The compact foldable is a normal phone that becomes substantially smaller when carried.

The platform should share:

- software architecture;
- security architecture;
- core compute platform;
- development tools;
- repair philosophy;
- component standards where practical.

The mechanical systems remain different.

---

# 2. Unnamed Fold

## The Large-Format Foldable

### Product role

Unnamed Fold is the productivity-oriented foldable.

Its purpose is to provide:

- phone portability;
- large-screen multitasking;
- document work;
- media consumption;
- gaming;
- reading;
- drawing;
- development;
- desktop-style workflows.

---

# 3. Outer Display

Target:

- approximately 6.3–6.7 inch class;
- OLED;
- LTPO;
- 1–120 Hz or better;
- high brightness;
- high touch sampling.

The outer display must be good enough to function as a normal phone display.

It should not feel like an emergency screen that exists solely to justify the unfolded panel.

---

# 4. Inner Display

Target:

- approximately 8.0–8.8 inch class;
- premium flexible OLED;
- LTPO;
- 1–120 Hz or better;
- high brightness;
- HDR;
- low crease visibility;
- strong touch performance.

Higher refresh rates may be considered if the power and thermal budget supports them.

---

# 5. Hinge

The hinge is one of the most important components in the device.

Target requirements:

- high cycle life;
- controlled opening force;
- minimal mechanical play;
- dust management;
- water-resistance engineering;
- display stress control;
- repairable service strategy.

The final hinge architecture must be validated through extensive cycle testing.

---

# 6. Display Protection

The inner flexible display requires a layered protection system.

Potential architecture:

- flexible OLED;
- protective layers;
- ultra-thin glass or equivalent;
- protective surface;
- hinge-side mechanical shielding.

The design must make normal operation reliable without pretending flexible displays are indestructible.

---

# 7. Battery

Target:

**approximately 6,500–8,000 mAh class**

The battery may use multiple cells to fit the two halves of the chassis.

The system must carefully manage:

- cell balancing;
- thermal distribution;
- charging;
- aging;
- serviceability.

---

# 8. Camera System

Target:

### Main

- large flagship-class sensor;
- OIS;
- fast autofocus.

### Ultrawide

- high-resolution sensor;
- autofocus preferred.

### Telephoto

- approximately 3x–5x optical range;
- OIS preferred.

Foldables have limited internal volume.

The camera system should prioritize real image quality rather than pretending the hinge has infinite room.

---

# 9. Performance

Target:

- current-generation flagship SoC;
- 16–24 GB RAM;
- 512 GB–1 TB storage;
- high-performance thermal system.

The device should perform like a flagship phone when folded and remain capable under sustained large-screen workloads when unfolded.

---

# 10. Software

The software must understand the two physical states.

### Folded

The device behaves like a conventional phone.

### Unfolded

The system can provide:

- multi-window;
- split-screen;
- drag-and-drop;
- desktop-style applications;
- large-screen media controls;
- expanded camera controls;
- document workflows;
- developer tools.

Applications should transition between states without restarting whenever the operating system and application permit.

---

# 11. Developer Workflow

The Fold should provide:

- bootloader unlock;
- recovery;
- debugging;
- external display;
- external storage;
- keyboard/mouse support;
- documented development interfaces.

The large screen is especially useful for development and terminal-style workflows.

---

# 12. Repairability

Candidate replaceable modules:

- battery cells/assembly;
- USB/I/O assembly;
- speakers;
- cameras;
- buttons;
- haptics;
- sensors;
- selected antenna assemblies.

The flexible display and hinge require specialized service procedures.

The project should publish service documentation when manufacturing and safety constraints allow it.

---

# 13. Water and Dust Resistance

Foldables present unusual sealing challenges.

The project will not claim a specific rating until:

- hinge sealing;
- display protection;
- port protection;
- internal pressure behavior;
- repeated-cycle testing

have been validated.

---

# 14. Unnamed Fold Compact

## The Compact Clamshell

Unnamed Fold Compact is designed for people who want flagship capability in a much smaller physical footprint when carried.

It should function as a normal smartphone when opened and become substantially more compact when closed.

---

# 15. Main Display

Target:

- approximately 6.7–7.0 inch class unfolded;
- premium flexible OLED;
- LTPO;
- 1–120 Hz or better;
- HDR;
- high brightness.

---

# 16. Cover Display

Target:

- approximately 3.5–4.0 inch class;
- OLED;
- high brightness;
- touch capable.

The cover display should support useful actions without requiring the user to unfold the phone for every trivial task.

Potential uses:

- notifications;
- calls;
- music;
- navigation;
- camera preview;
- quick replies;
- timers;
- widgets;
- authentication.

---

# 17. Hinge

Target:

- high cycle life;
- controlled opening;
- strong structural stability;
- minimized display stress;
- robust dust management.

The hinge should be designed as a long-life mechanical system, not a disposable novelty.

---

# 18. Battery

Target:

**approximately 4,500–6,500 mAh class**, subject to final thickness, weight, cell technology, and thermal requirements.

The target is to provide full-day flagship use without requiring a giant external battery.

---

# 19. Camera System

Target:

- high-quality main camera;
- high-quality ultrawide;
- optional telephoto depending on chassis constraints;
- strong selfie camera;
- cover-screen camera functionality.

The clamshell architecture creates an opportunity for unusual camera usage.

For example, the outer display can act as a preview screen while the main camera system is used for self-portraits.

---

# 20. Performance

Target:

- flagship-class mobile SoC;
- 12–16 GB RAM;
- 256–512 GB storage;
- strong thermal design.

The phone should not become a slower product simply because it folds.

---

# 21. Software

The software should support:

- cover-screen modes;
- unfolded modes;
- adaptive widgets;
- camera preview;
- notifications;
- media controls;
- quick actions;
- seamless state transitions.

---

# 22. Common Foldable Platform

Both foldables should share as much infrastructure as practical:

- operating system;
- update system;
- security model;
- bootloader architecture;
- developer tools;
- camera framework;
- testing infrastructure;
- component sourcing standards.

This reduces software fragmentation.

---

# 23. Foldable Reliability Program

Both products require dedicated testing.

### Hinge

- repeated opening/closing;
- temperature cycling;
- dust exposure;
- mechanical load;
- misalignment tolerance.

### Display

- folding cycles;
- pressure testing;
- scratch resistance;
- touch consistency;
- brightness stability;
- crease development.

### Battery

- repeated charging;
- thermal cycling;
- aging;
- cell balancing.

### Water/Dust

- controlled environmental tests;
- post-cycle inspection.

---

# 24. Foldable Repair Strategy

The project recognizes that foldables are inherently harder to repair.

Therefore the design should maximize what can reasonably be replaced without compromising the folding mechanism.

Priority:

1. battery;
2. charging/I/O;
3. speakers;
4. cameras;
5. buttons;
6. haptics;
7. display assemblies through trained service;
8. hinge assembly through trained service.

Repair documentation should clearly identify which procedures are suitable for ordinary service and which require specialized equipment.

---

# 25. Why These Two Exist

## Unnamed Fold

> **A phone that becomes a large computing surface.**

Best for:

- productivity;
- reading;
- multitasking;
- media;
- gaming;
- development.

## Unnamed Fold Compact

> **A flagship phone that becomes dramatically smaller when carried.**

Best for:

- portability;
- fashion-conscious users;
- compact pockets;
- quick interactions;
- one-handed use when folded.

---

# 26. The Foldable Principle

The company should not build a foldable merely because foldables are fashionable.

A foldable must provide a meaningful change in how the device is used.

If the unfolded state does not unlock new workflows, the hinge is just an expensive place for physics to become angry.

---

# 27. Product Promise

> **Unnamed Fold gives you more screen when you need it. Unnamed Fold Compact gives you less phone when you carry it. Both remain real flagship devices when the novelty wears off.**
