# startup-has-no-name

## Product Platform

> **A consumer technology company building phones as complete computing products, not disposable slabs of locked-down hardware.**

**Status:** Public product vision and engineering specification  
**License:** Documentation and original source code are intended to be open source unless explicitly marked otherwise.  
**Company:** startup-has-no-name

---

## 1. The Idea

Most flagship phones are extraordinary pieces of engineering.

They are also increasingly difficult to repair, difficult to modify, difficult to develop for, and difficult to understand.

`startup-has-no-name` exists to build something different.

The goal is simple:

> **Build phones that are genuinely excellent for normal people while remaining unusually respectful of the people who build, repair, modify, study, and depend on them.**

The product line is designed around five principles:

1. **Performance without artificial limits**
2. **Excellent everyday usability**
3. **Long-term ownership**
4. **Repairability and documentation**
5. **Transparent engineering**

This is not a project to make a phone that looks impressive on a specification sheet.

Every major claim should eventually have a test.

Every benchmark should identify its workload.

Every roadmap date should carry a confidence level.

Every component should have a reason to exist.

---

# 2. Product Family

The initial consumer family contains four products.

| Product | Role | Form factor |
|---|---|---|
| **Unnamed** | High-end mainstream flagship | Conventional smartphone |
| **Unnamed Pro** | Maximum-performance flagship | Conventional smartphone |
| **Unnamed Fold** | Large-format productivity foldable | Book-style inward fold |
| **Unnamed Fold Compact** | Compact premium foldable | Clamshell fold |

The names are deliberately placeholders.

The hardware architecture is the important part.

---

# 3. Product Philosophy

## 3.1 Consumer first

These are not developer boards disguised as phones.

A normal customer should be able to:

- buy the phone;
- sign in;
- install applications;
- take excellent photos;
- make calls;
- use banking applications;
- stream media;
- play games;
- navigate;
- use social media;
- receive updates;
- repair the device when economically sensible;
- and never need to understand what a bootloader is.

Developer capabilities must not make the ordinary experience worse.

---

## 3.2 Developers are first-class owners

Advanced users should have a documented path to:

- unlock the bootloader;
- inspect boot and recovery behavior;
- build supported software;
- install alternative operating systems where technically and legally possible;
- access documented debugging interfaces;
- recover a failed software installation;
- obtain device-specific development documentation;
- report reproducible bugs.

Consumer security and developer freedom are not treated as mutually exclusive.

The default consumer configuration can use verified boot and strong security.

The user should still be able to make an informed choice.

---

## 3.3 Repairability

The phone should be engineered around replaceable assemblies where practical.

Potential service modules include:

- battery;
- USB-C/I/O assembly;
- speaker assemblies;
- vibration motor;
- camera modules;
- display assembly;
- buttons;
- antenna assemblies;
- thermal components;
- charging hardware;
- sensors.

The exact module boundaries will be determined by:

- signal integrity;
- waterproofing;
- thermal requirements;
- structural requirements;
- manufacturing yield;
- cost;
- safety;
- serviceability.

Modularity is not an excuse to compromise reliability.

---

# 4. Hardware Direction

## Compute

The product family targets the highest-performance mobile compute platforms that are commercially available and practical for the manufacturing generation.

The design should prioritize:

- flagship CPU performance;
- flagship GPU performance;
- modern NPU/AI acceleration;
- hardware video encode/decode;
- high-speed storage;
- high-bandwidth memory;
- sustained thermal performance.

The exact SoC is a manufacturing decision and must be selected against the requirements of the generation in which the product is actually built.

---

## Memory

Target configurations:

- Unnamed: 12–16 GB
- Unnamed Pro: 16–24 GB
- Unnamed Fold: 16–24 GB
- Unnamed Fold Compact: 12–16 GB

Memory capacity is not pursued simply for marketing.

It must improve:

- application retention;
- multitasking;
- camera processing;
- local AI;
- gaming;
- desktop-style workflows;
- long-term software viability.

---

## Storage

Target configurations:

- 256 GB minimum for the flagship family where economically practical;
- 512 GB preferred for premium configurations;
- 1 TB and 2 TB options on Pro-class products where validated.

Storage should use the fastest practical mobile storage generation available at production time.

---

# 5. Display Philosophy

The display is treated as a primary computing interface.

Target characteristics:

- premium OLED;
- LTPO adaptive refresh;
- high peak brightness;
- excellent low-brightness behavior;
- accurate color modes;
- high touch sampling;
- HDR support;
- strong outdoor readability;
- efficient variable refresh;
- long-term panel calibration stability.

Target refresh range for conventional flagships:

**1–120 Hz or better**, with higher refresh modes considered where they provide measurable value.

The project will not advertise absurd refresh numbers simply because a controller can theoretically report them.

---

# 6. Camera Philosophy

The camera system should be designed around image quality rather than sensor-count marketing.

Priority order:

1. sensor quality;
2. optics;
3. stabilization;
4. autofocus;
5. computational photography;
6. thermal consistency;
7. color science;
8. video reliability.

The Pro line may use a very large main sensor, advanced optics, variable aperture, and additional long-range cameras where the mechanical envelope permits them.

The camera system must be evaluated using repeatable tests.

Examples:

- daylight dynamic range;
- night dynamic range;
- motion capture;
- autofocus tracking;
- skin-tone reproduction;
- low-light video;
- stabilization;
- thermal degradation;
- sustained recording duration.

---

# 7. Battery and Charging

Battery capacity is treated as an engineering resource, not a race to the largest printed number.

The design targets:

- high energy density;
- strong cycle life;
- thermal stability;
- safe charging;
- battery health controls;
- replaceability where practical;
- sustained performance at low battery levels.

Silicon-carbon battery technology may be used when validated for:

- safety;
- cycle life;
- production consistency;
- serviceability;
- thermal behavior.

Fast charging should be implemented only with appropriate protection and thermal management.

---

# 8. Thermal Architecture

Performance is meaningful only when sustained.

The phones should use a combination of:

- vapor chambers;
- graphite;
- thermally conductive structural elements;
- carefully designed heat spreaders;
- thermal interface materials;
- software thermal control.

The Pro product may use more aggressive thermal hardware because it is intentionally designed to sustain high workloads.

Possible future configurations may include accessory or dock-based active cooling.

Active cooling is not automatically placed inside every phone.

---

# 9. Connectivity

Target capabilities include:

- modern 5G;
- Wi-Fi 7-class wireless connectivity or newer where practical;
- Bluetooth;
- NFC;
- modern GNSS;
- USB-C;
- DisplayPort Alt Mode where supported;
- USB 3.x or USB4-class connectivity on Pro products where feasible.

The long-term objective is for the phone to function as a computing endpoint rather than a sealed appliance.

---

# 10. Software

The software stack is intended to be based on open and auditable components wherever practical.

Possible foundations include:

- AOSP;
- Linux;
- upstream or appropriately licensed kernel work;
- open-source system components;
- documented device interfaces;
- reproducible build infrastructure.

The consumer experience should remain polished.

The developer experience should remain transparent.

---

# 11. Security

Security is not sacrificed for openness.

Consumer devices should support:

- hardware-backed security;
- verified boot;
- secure key storage;
- application sandboxing;
- modern biometric protection;
- encrypted user data;
- secure update mechanisms.

Developer devices and developer modes should provide documented mechanisms for controlled unlocking.

A secure phone is not necessarily a phone that refuses to let its owner understand it.

---

# 12. Google Services and DRM

The project will not claim support for proprietary services before the required agreements, certification, compatibility work, and testing exist.

This includes technologies such as:

- Google Mobile Services;
- Google certification;
- Widevine levels;
- proprietary camera components;
- proprietary modem software;
- vendor-specific firmware.

The repository will distinguish clearly between:

**Open source owned by the project**

and

**Third-party proprietary software required for commercial operation.**

---

# 13. Open Source Policy

The project intends to publish as much of its original work as legally and practically possible.

Potentially public materials include:

- application source code;
- system source code;
- kernel changes;
- device trees where legally publishable;
- board documentation;
- mechanical documentation;
- CAD where practical;
- test procedures;
- build instructions;
- flashing instructions;
- recovery procedures;
- benchmark methodology;
- security documentation;
- issue trackers;
- release notes.

Third-party material will remain subject to its own licenses.

The project will not publish:

- confidential vendor information;
- stolen proprietary source;
- private signing keys;
- credentials;
- restricted certification material;
- material that the project does not have the legal right to redistribute.

---

# 14. Licensing and Compliance

Every repository should clearly identify:

- project license;
- third-party licenses;
- SPDX identifiers;
- attribution requirements;
- source availability requirements;
- binary redistribution conditions.

Where required by license, corresponding source and build information will be made available.

A public Git repository is not automatically open source.

Licensing must be intentional.

---

# 15. Manufacturing Strategy

The company does not intend to build a factory before it has a product worth manufacturing.

The likely sequence is:

### Phase 1

Software, documentation, architecture, prototypes.

### Phase 2

Developer hardware and engineering samples.

### Phase 3

Small production batch.

### Phase 4

Manufacturing partner / ODM engagement.

### Phase 5

Certification and consumer launch.

The company must retain as much control as practical over:

- industrial design;
- firmware requirements;
- bootloader policy;
- software stack;
- documentation;
- source ownership;
- test specifications;
- calibration data;
- manufacturing tooling where contractually possible.

---

# 16. Testing Philosophy

The product will maintain public or internally reproducible tests for:

### Performance

- CPU;
- GPU;
- NPU;
- storage;
- memory;
- sustained workloads.

### Battery

- web;
- video;
- gaming;
- standby;
- camera;
- mixed use.

### Camera

- controlled scenes;
- motion;
- low light;
- HDR;
- video;
- autofocus.

### Thermal

- 10-minute;
- 30-minute;
- 60-minute sustained workloads.

### Reliability

- charging cycles;
- button cycles;
- connector cycles;
- hinge cycles;
- thermal cycling;
- drop testing;
- water resistance validation.

---

# 17. The Real Competitive Goal

The goal is not to claim:

> "We are better than Samsung."

The goal is to build a device that can demonstrate where it is better.

The company should publish comparisons using repeatable workloads.

The objective is to compete at the highest level of:

- performance;
- camera quality;
- display quality;
- battery life;
- software quality;
- longevity;
- repairability;
- developer freedom.

Marketing should follow engineering.

Not the other way around.

---

# 18. North-Star Metric

The long-term engineering metric is:

> **How many independent users can take a fresh device, understand its architecture, build supported software from documented source, boot it, recover it from failure, and report a reproducible bug without founder intervention?**

That is a stronger moat than a temporary benchmark score.

---

# 19. Roadmap

## Stage 0: Thesis

Define:

- product requirements;
- architecture;
- licensing;
- supplier strategy;
- testing methodology.

## Stage 1: Software and Firmware Proof

Build:

- boot chain;
- recovery;
- OS image;
- update system;
- development workflow.

## Stage 2: Hardware Proof

Validate:

- board;
- power;
- thermals;
- storage;
- display;
- connectivity.

## Stage 3: Developer Alpha

Release a small number of devices to developers.

## Stage 4: Consumer Engineering

Validate:

- industrial design;
- cameras;
- battery;
- display;
- certification;
- manufacturing.

## Stage 5: Production

Launch only when the product passes defined engineering gates.

---

# 20. What This Project Refuses to Become

This company will not build its identity around:

- fake benchmark screenshots;
- impossible specifications;
- artificial software restrictions;
- planned obsolescence;
- meaningless camera counts;
- copied industrial designs;
- undocumented vendor modifications;
- proprietary lock-in presented as security;
- promises that cannot be tested.

The ambition is extreme.

The claims should not be.

---

# 21. Product Documents

- [`Base.md`](./Base.md) — Unnamed
- [`Pro.md`](./Pro.md) — Unnamed Pro
- [`Fold.md`](./Fold.md) — Unnamed Fold and Unnamed Fold Compact

---

## 22. One Sentence

> **startup-has-no-name builds consumer phones for people who expect their technology to belong to them.**
