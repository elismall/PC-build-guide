
# **PC Building Basics**

This page explains each core PC component, the key specs that matter, and how they interact. Use this as a quick primer before diving into compatibility and example builds.

---

## **Core Components Overview**
- **CPU (Processor):** The “brain” that executes instructions. Affects general speed, multitasking, and CPU-bound tasks (compiling, simulations, some games).
- **GPU (Graphics Card):** Handles graphics/rendering and GPU-accelerated workloads (gaming, video, AI/ML). Often the biggest performance driver in games.
- **Motherboard:** The platform that connects all parts. Defines socket, chipset features, expansion, I/O, and memory support.
- **RAM (Memory):** Short-term working space. Impacts multitasking and minimum FPS. Capacity first, then speed/latency.
- **Storage:** Where data lives. NVMe SSDs are fastest; SATA SSDs are solid; HDDs for bulk storage only.
- **PSU (Power Supply):** Feeds stable power. Choose reliable wattage, quality, and connectors for your parts.
- **Cooling:** Keeps components within safe temps—affects performance, noise, and longevity.
- **Case (Chassis):** Physical enclosure that determines airflow, size compatibility, and build experience.

---

## **CPU (Processor)**
- **Key specs:** Cores/threads, architecture, clock speeds (base/boost), cache, TDP/“PPT”.
- **Use cases:** High core count for heavy multitasking/creation; higher single-core for latency-sensitive tasks and many games.
- **Sockets:** Must match the motherboard (e.g., AMD AM5, Intel LGA1700 — check current gen).
- **Tips:** Pair strong CPUs with fast RAM on supported platforms; avoid mismatching a top GPU with a very low-end CPU (bottleneck).

---

## **GPU (Graphics Card)**
- **Key specs:** VRAM capacity/speed, core count, boost clock, memory bus, power draw.
- **Use cases:** 1080p vs 1440p vs 4K gaming, high-refresh esports, content creation (encode/decode), AI/ML (CUDA/ROCm support).
- **Fit & power:** Check card length, slot thickness (2–3.5 slots), PCIe power connectors, PSU wattage.
- **Display support:** HDMI/DP versions, max refresh/VRR/G-SYNC/FreeSync.

---

## **Motherboard**
- **Socket & Chipset:** Defines CPU support and features (PCIe lanes, USB/Thunderbolt, storage, overclocking).
- **Form factors:** ATX (standard), mATX (compact), ITX (small). Smaller = fewer slots/headers but smaller builds.
- **VRMs & Cooling:** Better VRMs help CPU stability, especially under heavy loads/overclocking.
- **Memory support:** Capacity, speed (XMP/EXPO), max DIMM count, ECC on some boards.
- **Expansion:** PCIe x16 slots, M.2 NVMe slots (PCIe Gen4/Gen5), SATA ports, headers (ARGB, fans, USB-C front panel).

---

## **RAM (Memory)**
- **Capacity:** 16 GB is entry gaming; 32 GB is comfortable; 64 GB+ for heavy creation/AI.
- **Speed/Latency:** DDR4/DDR5 with XMP/EXPO profiles. Faster RAM can improve 1% lows in some games.
- **Channels:** Dual-channel (2 sticks) is standard; populate recommended slots (per manual).
- **Clearance:** Check heatsink height vs CPU cooler overhang.

---

## **Storage**
- **NVMe SSD (M.2):** Best performance; PCIe Gen4 widely supported, Gen5 emerging. Great for OS, games, active projects.
- **SATA SSD:** Cost-effective; still fast for most tasks.
- **HDD:** High capacity archival/backups; slow for active workloads.
- **Tips:** Use at least one SSD for OS; plan multiple drives by role (OS/apps, games, scratch, archive).

---

## **Power Supply (PSU)**
- **Wattage:** Size for peak system draw + headroom (typically 20–30%).
- **Quality:** Reputable brands, good reviews, protections (OVP/UVP/OCP/OTP), solid warranty.
- **Efficiency:** 80 Plus (Bronze → Titanium). Efficiency affects heat/noise.
- **Connectors:** EPS for CPU, PCIe 8-pin/12VHPWR for GPUs, enough SATA/MOLEX for accessories.
- **Form factor:** ATX vs SFX for small cases.

---

## **Cooling**
- **CPU cooling:** Air (tower) vs AIO liquid (120–360 mm). Choose per CPU power and case support.
- **Case airflow:** Front intake + rear/top exhaust. Positive pressure helps dust control with filters.
- **Thermal paste:** Small pea/rice-sized dot; even pressure from cooler mount.
- **Noise:** Use BIOS or software fan curves; larger, slower fans are quieter.

---

## **Case (Chassis)**
- **Compatibility:** GPU length, cooler height, radiator support, motherboard size, PSU length.
- **Airflow:** Mesh front panels breathe better than solid glass.
- **Build quality:** Cable management space, grommets, fan hubs, dust filters.

---

## **Peripherals & Monitor Basics**
- **Monitor:** Resolution (1080p/1440p/4K), refresh (144–240 Hz for esports), panel type (IPS/VA/OLED), VRR (G-SYNC/FreeSync).
- **Keyboard/Mouse/Headset:** Choose for comfort and task; wired for lowest latency.
- **Networking:** Ethernet for stability; Wi‑Fi 6/6E/7 depending on router and use.

---

## **Operating System & Drivers**
- **Windows/Linux:** Choose based on software/games. Verify app compatibility (anticheat, NLEs, CUDA/ROCm).
- **Drivers:** Install chipset, GPU, LAN/Wi‑Fi, audio. Keep BIOS reasonably up-to-date for stability and CPU support.

---

## **Compatibility Fundamentals**
- **CPU ↔ Motherboard:** Socket and chipset must match; verify supported CPU list (QVL) from the board vendor.
- **RAM ↔ Motherboard/CPU:** Check memory QVL for tested kits and max speeds; use XMP/EXPO.
- **GPU ↔ Case/PSU:** Ensure physical clearance and power connectors/wattage.
- **Storage ↔ Motherboard:** M.2 slot keying and PCIe Gen support; note lanes shared with SATA ports on some boards.
- **Front panel & USB:** Verify headers (USB‑C, USB 3.2, audio) exist on both case and motherboard.

---

## **Bottlenecks & Balance**
- **Balance budget:** Avoid pairing a top-tier GPU with a very low-end CPU (or vice versa) unless use-case justifies it.
- **Resolution targets:** GPU matters more as resolution/settings increase; CPU limits high-FPS 1080p esports.
- **RAM capacity:** Running out of RAM tanks performance; prioritize capacity before chasing extreme speed.

---

## **Form Factors & Expansion**
- **Motherboard size:** ATX (most expansion), mATX (compact), ITX (smallest, fewer slots).
- **PCIe & M.2:** Count slots you’ll need for GPU, capture cards, NVMe drives now and in the future.
- **Power and thermals:** Smaller cases need careful part selection and airflow planning.

---

## **Build Prep, Tools & ESD**
- **Tools:** #2 Phillips screwdriver, zip ties/Velcro, isopropyl alcohol + lint-free cloth, thermal paste (if needed), flashlight.
- **ESD:** Build on non‑carpeted surface; touch grounded metal periodically; handle parts by the edges.
- **Firmware/USB:** Prepare OS installer USB; download motherboard LAN/Wi‑Fi driver to a second USB just in case.

---

## **First Boot Checklist**
1. POST on motherboard (check debug LEDs/Q‑Codes if no display).
2. Enter BIOS: enable XMP/EXPO, set boot order, verify temps and detected devices.
3. Install OS, then chipset/GPU/network/audio drivers.
4. Run updates, set fan curves, and test with a few benchmarks or games.

---

## **Glossary (Quick Reference)**
- **POST:** Power‑On Self‑Test; initial hardware check on boot.
- **XMP/EXPO:** One‑click memory profiles for rated RAM speed.
- **VRM:** Voltage Regulator Module; feeds stable power to CPU.
- **TDP/PPT:** Thermal/power guidelines; actual limits vary by platform.
- **PCIe Gen:** Interface generation; higher gen = more bandwidth.

---

## **Helpful External Tools**
- PCPartPicker — compatibility and pricing reference.
- Motherboard/Memory QVL pages from manufacturers for CPU/RAM validation.
- GPU and CPU vendor pages for drivers and feature support.

