# WCH CH32 Application Notes — Persian Collection

<p align="center">
  <img src="../Images/GitHub-Assets/MES-Hero-Banner.svg" width="100%" alt="MEMAR ELECTRONIC SANAT — MES">
</p>

[🇮🇷 فارسی](README.md) | [🇬🇧 English](README_EN.md) | [Back to repository root](../README_EN.md)

## About This Directory

The **fa** directory is the Persian-language collection of WCH **CH32 microcontroller Application Notes (AN)**. It is intended for translating, technically reviewing, organizing, and publishing Persian editions of the original application notes.

Each document is stored in a dedicated directory named after its original document ID, such as `AN01000`. This keeps the Persian guide, downloadable PDF, browser-readable HTML, and supporting figures or diagrams together.

The collection is intended for electronics engineers, hardware designers, firmware developers, and users of development tools such as **MounRiver Studio (MRS)**. Its subjects include low-power operation, clocks, peripherals, memory, communication interfaces, display systems, debugging, and development tools.

## Current Collection Status

At the time this README was prepared, the Persian directory contains **49 application-note folders**:

- **20 notes have both Persian PDF and HTML editions**, suitable for offline reading/printing and online viewing.
- **29 notes are awaiting translation and technical review.** Their individual guide pages and any available supporting media are present, but final Persian PDF and HTML editions have not yet been published.
- **49 individual README guides** describe each note and provide access to its original source.

> **Important:** The presence of a directory or README does not mean that the full translation is complete. The table below reflects the files actually present in the repository. PDF and HTML links are provided only where those files exist.

## Directory Structure

A typical translated note uses the following layout:

```text
fa/
├── README.md
├── README_EN.md
├── AN01000/
│   ├── README.md
│   ├── AN01000 FA.pdf
│   ├── AN01000-FA.html
│   └── media/
│       ├── image1.png
│       └── ...
├── AN01001/
│   ├── README.md
│   └── ...
└── ...
```

| Path or file | Purpose |
| :--- | :--- |
| `README.md` | Persian overview and index for this collection |
| `README_EN.md` | English overview of the Persian collection |
| `ANxxxxx/README.md` | Note-specific introduction, translation status, technical scope, and links |
| `*.pdf` | Persian edition for offline reading, printing, and archiving, when available |
| `*.html` | Browser-readable Persian edition with document structure and figures, when available |
| `media/` | Figures, diagrams, and image assets used by the HTML or document |

## How to Read and Use the Notes

1. Find the required document by its ID or subject in the index below.
2. Open its **note guide** first to review the scope, translation status, and available files.
3. Use the HTML edition for online reading, or the PDF edition for offline reading, printing, and archiving.
4. A dash (—) in the PDF or HTML column means that the final Persian edition has not yet been published in this directory. Open the note guide and follow its link to the original WCH source.
5. Refer to the original Chinese materials in the [zh](../zh/) directory when checking terminology or technical details.

## Complete Persian Note Index

The PDF and HTML columns link only to files currently present in the repository. Every listed note also has an individual guide.

| ID | Topic | Note Guide | Persian PDF | Persian HTML | Status |
| :---: | :--- | :---: | :---: | :---: | :---: |
| AN01000 | Low-Power Modes and Wake-Up Guide | [Persian guide](./AN01000/README.md) | [AN01000 FA.pdf](./AN01000/AN01000%20FA.pdf) | [AN01000-FA.html](./AN01000/AN01000-FA.html) | Published |
| AN01001 | External VDD12 Power Supply | [Persian guide](./AN01001/README.md) | [AN01001 FA.pdf](./AN01001/AN01001%20FA.pdf) | [AN01001-FA.html](./AN01001/AN01001-FA.html) | Published |
| AN01002 | Low-Power Strategies for CH32L103 | [Persian guide](./AN01002/README.md) | [AN01002 FA.pdf](./AN01002/AN01002%20FA.pdf) | [AN01002-FA.html](./AN01002/AN01002-FA.html) | Published |
| AN01003 | Analysis of Chip Reset Causes | [Persian guide](./AN01003/README.md) | [AN01003 FA.pdf](./AN01003/AN01003%20FA.pdf) | [AN01003-FA.html](./AN01003/AN01003-FA.html) | Published |
| AN03000 | Using ICache on CH32H417 | [Persian guide](./AN03000/README.md) | [AN03000-FA.pdf](./AN03000/AN03000-FA.pdf) | [AN03000-FA.html](./AN03000/AN03000-FA.html) | Published |
| AN03001 | Interrupt Allocation and Wake-Up in Dual-Core MCUs | [Persian guide](./AN03001/README.md) | [AN03001 FA.pdf](./AN03001/AN03001%20FA.pdf) | [AN03001-FA.html](./AN03001/AN03001-FA.html) | Published |
| AN03002 | CoreMark and Benchmark Configuration | [Persian guide](./AN03002/README.md) | [AN03002 FA.pdf](./AN03002/AN03002%20FA.pdf) | [AN03002-FA.html](./AN03002/AN03002-FA.html) | Published |
| AN03003 | QingKe RISC-V Custom Instructions | [Persian guide](./AN03003/README.md) | [AN03003 FA.pdf](./AN03003/AN03003%20FA.pdf) | [AN03003-FA.html](./AN03003/AN03003-FA.html) | Published |
| AN03004 | Execution Speed Across Memory Types | [Persian guide](./AN03004/README.md) | [AN03004.pdf](./AN03004/AN03004.pdf) | [AN03004-FA.html](./AN03004/AN03004-FA.html) | Published |
| AN03005 | CH32H417 Core-Specific Features | [Persian guide](./AN03005/README.md) | [AN03005 FA.pdf](./AN03005/AN03005%20FA.pdf) | [AN03005-FA.html](./AN03005/AN03005-FA.html) | Published |
| AN08000 | DMA Considerations for CH32H417/415/416 | [Persian guide](./AN08000/README.md) | [AN08000 FA.pdf](./AN08000/AN08000%20FA.pdf) | [AN08000-FA.html](./AN08000/AN08000-FA.html) | Published |
| AN09000 | ADC Usage and Considerations | [Persian guide](./AN09000/README.md) | [AN09000 FA.pdf](./AN09000/AN09000%20FA.pdf) | [AN09000-FA.html](./AN09000/AN09000-FA.html) | Published |
| AN09001 | Using the ADC on CH32X315 | [Persian guide](./AN09001/README.md) | [AN09001 FA.pdf](./AN09001/AN09001%20FA.pdf) | [AN09001-FA.html](./AN09001/AN09001-FA.html) | Published |
| AN10000 | WCH Touch-Key Application Guide | [Persian guide](./AN10000/README.md) | [AN10000 FA.pdf](./AN10000/AN10000%20FA.pdf) | [AN10000-FA.html](./AN10000/AN10000-FA.html) | Published |
| AN11000 | RTC/Systick/TIM/LPTIM Comparison and Applications | [Persian guide](./AN11000/README.md) | [AN11000 FA.pdf](./AN11000/AN11000%20FA.pdf) | [AN11000-FA.html](./AN11000/AN11000-FA.html) | Published |
| AN11001 | Reduced Timer Features and Applications | [Persian guide](./AN11001/README.md) | [AN11001 FA.pdf](./AN11001/AN11001%20FA.pdf) | [AN11001-FA.html](./AN11001/AN11001-FA.html) | Published |
| AN11002 | TIM Techniques for Motor Applications | [Persian guide](./AN11002/README.md) | [AN11002 FA.pdf](./AN11002/AN11002%20FA.pdf) | [AN11002-FA.html](./AN11002/AN11002-FA.html) | Published |
| AN14000 | SerDes Fundamentals | [Persian guide](./AN14000/README.md) | [AN14000 FA.pdf](./AN14000/AN14000%20FA.pdf) | [AN14000-FA.html](./AN14000/AN14000-FA.html) | Published |
| AN16001 | I2C vs. I3C and I3C Usage | [Persian guide](./AN16001/README.md) | [AN16001 FA.pdf](./AN16001/AN16001%20FA.pdf) | [AN16001-FA.html](./AN16001/AN16001-FA.html) | Published |
| AN17000 | SPI Host Mode and NSS Usage | [Persian guide](./AN17000/README.md) | [AN17000 FA.pdf](./AN17000/AN17000%20FA.pdf) | [AN17000-FA.html](./AN17000/AN17000-FA.html) | Published |
| AN21000 | SDIO Slave Mode Usage | [Persian guide](./AN21000/README.md) | — | — | Translation pending |
| AN22000 | SDMMC and Slave-Mode Communication | [Persian guide](./AN22000/README.md) | — | — | Translation pending |
| AN23000 | PIOC Features and Usage | [Persian guide](./AN23000/README.md) | — | — | Translation pending |
| AN24000 | Using OPA on General CH32 MCUs | [Persian guide](./AN24000/README.md) | — | — | Translation pending |
| AN24001 | Using CMP on General CH32 MCUs | [Persian guide](./AN24001/README.md) | — | — | Translation pending |
| AN25001 | SAI vs. I2S and SAI Usage | [Persian guide](./AN25001/README.md) | — | — | Translation pending |
| AN26001 | SPI vs. QSPI and QSPI Usage | [Persian guide](./AN26001/README.md) | — | — | Translation pending |
| AN29000 | FMC-Based SDRAM Driver Fundamentals | [Persian guide](./AN29000/README.md) | — | — | Translation pending |
| AN31001 | Digital Filter Usage on CH32H417 | [Persian guide](./AN31001/README.md) | — | — | Translation pending |
| AN35000 | ARGB Comparison and Fundamentals | [Persian guide](./AN35000/README.md) | — | — | Translation pending |
| AN36000 | PSRAM Usage Guide | [Persian guide](./AN36000/README.md) | — | — | Translation pending |
| AN36001 | Running Code from PSRAM | [Persian guide](./AN36001/README.md) | — | — | Translation pending |
| AN36002 | Porting LVGL to V467 and Driving Displays with PSRAM | [Persian guide](./AN36002/README.md) | — | — | Translation pending |
| AN37000 | USB PD Usage and MCU Comparison | [Persian guide](./AN37000/README.md) | — | — | Translation pending |
| AN90000 | CH32H417QEU-R1-1v1 Development Board Guide | [Persian guide](./AN90000/README.md) | — | — | Translation pending |
| AN90001 | Lightweight WCHGUI Development: Control-Box Example | [Persian guide](./AN90001/README.md) | — | — | Translation pending |
| AN90002 | Using the User Area as DataFlash | [Persian guide](./AN90002/README.md) | — | — | Translation pending |
| AN90003 | Porting FatFs to MounRiver Studio | [Persian guide](./AN90003/README.md) | — | — | Translation pending |
| AN91000 | Debug Configuration for Dual-Core MCUs | [Persian guide](./AN91000/README.md) | — | — | Translation pending |
| AN91001 | Offline Programmer User Guide | [Persian guide](./AN91001/README.md) | — | — | Translation pending |
| AN91002 | LD and Startup File Configuration | [Persian guide](./AN91002/README.md) | — | — | Translation pending |
| AN91003 | LINK Download Procedure for External FLASH | [Persian guide](./AN91003/README.md) | — | — | Translation pending |
| AN91004 | LINK and MRS Tips | [Persian guide](./AN91004/README.md) | — | — | Translation pending |
| AN91005 | Command-Line Debugging | [Persian guide](./AN91005/README.md) | — | — | Translation pending |
| AN91006 | Diagnosing MCU Issues During Debugging | [Persian guide](./AN91006/README.md) | — | — | Translation pending |
| AN93000 | Comparison of Display Interfaces | [Persian guide](./AN93000/README.md) | — | — | Translation pending |
| AN94000 | M030 Power and Motor-Application Features | [Persian guide](./AN94000/README.md) | — | — | Translation pending |
| AN94001 | EMI Design Considerations | [Persian guide](./AN94001/README.md) | — | — | Translation pending |
| AN97000 | Firmware Upgrade via CH32 USB DFU | [Persian guide](./AN97000/README.md) | — | — | Translation pending |

## Translation and Technical Review Policy

To preserve engineering accuracy:

- MCU and component part numbers, peripheral names, register and bit identifiers, function names, macros, and technical identifiers are retained as in the source.
- Source code and commands are not translated or altered; explanatory text around them is provided in Persian.
- Units, numeric values, equations, diagrams, waveforms, and references must be checked against the original document.
- Any feature limited to specific MCU variants or packages must remain explicitly qualified in the Persian edition.
- Where useful, specialized terminology is introduced with its English term so readers can cross-reference Datasheets and Reference Manuals.
- Translation edits must not unintentionally change technical meaning, test conditions, or the applicability of examples.

## Engineering Notes for Real Designs

Application Notes complement official documentation; they do not replace it:

1. **Datasheet:** Use the datasheet for the exact MCU part number to verify electrical characteristics, voltage/current limits, package, pinout, and device restrictions.
2. **Reference Manual:** Consult the reference manual for register definitions, peripheral initialization sequences, interrupts, and internal peripheral behavior.
3. **Toolchain and library versions:** Examples may depend on a specific MRS, compiler, Peripheral Library, or firmware version.
4. **Exact MCU variant:** Do not assume that features or pin mappings are identical across all CH32 devices. Check family, package, and silicon revision.
5. **Hardware validation:** Verify power, clock, memory, USB, RF, EMI, and programming configurations through measurements and tests on the target hardware.

## Related Resources

- [Main application-note index — Persian](../README.md)
- [Original document collection — Chinese](../zh/)
- [MES-ch32_application_notes repository](https://github.com/MEMAR-ELECTRONIC-SANAT/MES-ch32_application_notes)
- [Official WCH website](https://www.wch.cn/)
- [Official WCH forum](https://www.wch.cn/bbs/forum-106-1.html)

## Contributions and Issue Reports

For translation corrections, technical issues, broken links, or improvement suggestions, use the repository's [Issues page](https://github.com/MEMAR-ELECTRONIC-SANAT/MES-ch32_application_notes/issues). Include the AN ID, page or section, exact MCU part number, and a clear description of the proposed correction whenever possible.

<p align="center">
  <img src="../Images/GitHub-Assets/MES-Divider.svg" width="100%" alt="MES Divider">
</p>

## Images and Reference Diagrams

- [MES graphic assets](../Images/GitHub-Assets/)
- Note-specific figures and diagrams are stored in each note's `media/` directory.

## Compiled and Maintained by

**معمار الکترونیک صنعت**  
**MEMAR ELECTRONIC SANAT (MES)**

همراه شما در مسیر طراحی و ساخت مدارهای مطمئن

Electronic circuit and PCB design, embedded systems, and microcontroller configuration tools.

- Telegram: [https://t.me/Memar_Electronic](https://t.me/Memar_Electronic)
- Instagram: [https://www.instagram.com/Memar.Electronic](https://www.instagram.com/Memar.Electronic)
- GitHub: [MEMAR-ELECTRONIC-SANAT](https://github.com/MEMAR-ELECTRONIC-SANAT)

<p align="center">
  <img src="../Images/GitHub-Assets/MES-Thank-You-Footer.svg" width="100%" alt="Thank you for visiting MES">
</p>
