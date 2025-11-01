================================================================================
                         MoB XML Parser
================================================================================

VERSION: Lite  
DEVELOPED BY: Leonardo Camilo and Enzo Souto  
DATE: October 2025

================================================================================
                              ABOUT THE PROGRAM
================================================================================

The MoB XML Parser is a lightweight Ericsson XML converter that transforms raw network configuration files into structured TXT, CSV, or XLSX outputs.

MAIN FEATURES:
- Batch processing of multiple XML and ZIP files  
- Modern and intuitive graphical interface  
- Drag & Drop support  
- 21 automatic post-processing stages  
- Export to TXT, CSV, and XLSX  
- Secure licensing system

================================================================================
                           SYSTEM REQUIREMENTS
================================================================================

OPERATING SYSTEM: Windows 7/10/11  
RAM MEMORY: Minimum 4 GB (8 GB recommended)  
DISK SPACE: 100 MB of storage  
SCREEN RESOLUTION: Minimum 800x600 (1920x1080 recommended)

⚠️ IMPORTANT: The file **license.moblic** must be in the same folder as the executable!

================================================================================
                              QUICK START
================================================================================

1. ADD FILES  
   - Click “Add XML” or “Add ZIP” to select files  
   - OR drag and drop files directly into the window  
   - Supported file types: `.xml` and `.zip`

2. SELECT OUTPUT FOLDER  
   - Click “Browse” and choose where to save the results

3. CONFIGURE OPTIONS (OPTIONAL)  
   - **Extract ZIPs:** Automatically extracts ZIP files  
   - **Delete XMLs:** Removes original XMLs after processing  
   - **Format:** Choose output format (TXT, CSV, or XLSX)

4. PROCESS  
   - Click “PROCESS XMLs” and wait for completion  
   - Track progress via the bar and log window

5. POST-PROCESS (RECOMMENDED)  
   - Click “POST-PROCESS” to enrich the data  
   - The system will automatically perform 21 processing stages

================================================================================
                            GENERATED FILES
================================================================================

After processing, you will get files such as:

BASIC DUMPS (after PROCESS XMLs):
- ENodeBFunction.txt        (eNodeB data)
- EUtranCellFDD.txt         (4G cells)
- NRCellCU.txt              (5G cells)
- ... and more

PROCESSED DUMPS (after POST-PROCESS):
- 5G_NRCellCU.txt           (Enriched 5G cells)
- 5G_NRCellRelation.txt     (Processed 5G relations)
- EUtranCell_TDD_FDD.txt    (Unified 4G cells)
- ... and more

================================================================================
                        COMMON ISSUES & SOLUTIONS
================================================================================

**ISSUE:** “License not found” or “License expired”  
**SOLUTION:** Ensure the file `license.moblic` is in the same folder as  
the executable. If expired, contact us for renewal.

**ISSUE:** Program won’t start  
**SOLUTION:**  
1. Check if the license file is present  
2. Run as administrator  
3. Install Microsoft Visual C++ Redistributable

**ISSUE:** XML processing error  
**SOLUTION:**  
1. Ensure the XML file is not corrupted  
2. Verify it’s a valid mobile network XML  
3. Check available disk space

**ISSUE:** Post-Processing failure  
**SOLUTION:**  
1. Run “PROCESS XMLs” first  
2. Ensure `.txt` files were generated in the output folder  
3. Close other programs to free memory

**ISSUE:** Empty result  
**SOLUTION:**  
1. Make sure the XML type is correct (CMExport or Bulk CM)  
2. Check the log at the bottom of the window for details  
3. Contact technical support

================================================================================
                            LICENSE STATUS
================================================================================

The license status is displayed in the window title:

**VALID:**  
  `MoB XML Parser Lite - License valid until 2025-12-31 (245 days)`

**EXPIRED:**  
  `MoB XML Parser Lite - License expired on 2025-01-01`

To renew your license, please contact the vendor.

================================================================================
                              USEFUL TIPS
================================================================================

**PRODUCTIVITY:**  
- Use Drag & Drop to add multiple files at once  
- Choose XLSX format for easy Excel analysis  
- Enable “Delete XMLs” to save disk space  
- ALWAYS run POST-PROCESS for complete data!

**PERFORMANCE:**  
- Estimated time for 100 XMLs: 2–5 minutes  
- Additional Post-Processing: 1–2 minutes  
- Use SSD for best performance

**BEST PRACTICES:**  
1. Run PROCESS XMLs first  
2. Then run POST-PROCESS  
3. Check the log to identify errors  
4. Keep backups of original XML files

================================================================================
                            OUTPUT FORMATS
================================================================================

**TXT (Default):**  
- Pipe-separated text (`|`)  
- Lightweight and fast  
- Easy to parse with scripts

**CSV (Comma Separated Values):**  
- Comma-separated values  
- Opens in Excel  
- Compatible with most tools

**XLSX (Excel):**  
- Microsoft Excel spreadsheet  
- RECOMMENDED for analysis  
- Supports multiple sheets  
- Preserves formatting

================================================================================
                              GLOSSARY
================================================================================

MO         - Managed Object (configuration object)  
CGI        - Cell Global Identity (unique cell ID)  
PCI        - Physical Cell ID (cell’s physical ID)  
eNodeB     - 4G base station (LTE)  
gNodeB     - 5G base station (NR)  
FDD        - Frequency Division Duplex  
TDD        - Time Division Duplex  
ARFCN      - Absolute Radio Frequency Channel Number  
NR         - New Radio (5G)

================================================================================
                          TECHNICAL SUPPORT
================================================================================

Before requesting support, please provide:

1. Screenshot of the error message  
2. Log content (bottom of the window)  
3. Program version (Lite)  
4. Operating system (Windows 7/10/11)

For support, contact us through official channels.

================================================================================
                          LEGAL INFORMATION
================================================================================

This software is proprietary and protected by copyright.  
All rights reserved © 2024–2025.

Use of this software requires a valid license.  
Redistribution, modification, or reverse engineering is prohibited.

================================================================================
                            CREDITS
================================================================================

**DEVELOPED BY:**  
  Leonardo Camilo  
  Enzo Souto

**TECHNOLOGIES USED:**  
  - Python 3.13  
  - Tkinter (Graphical Interface)  
  - lxml (XML Processing)  
  - pandas (Data Analysis)  
  - Cython (Compilation and Security)

================================================================================
                          VERSION HISTORY
================================================================================

**Version Lite (Current) – October 2025**  
  - Completely redesigned interface  
  - Support for multiple resolutions and DPI scaling  
  - 21 post-processing stages  
  - XLSX export  
  - Robust licensing system  
  - Compiled and optimized code

================================================================================
                          ACKNOWLEDGMENTS
================================================================================

Special thanks to everyone who contributed to the development  
and testing of this application.

================================================================================

               Thank you for using MoB XML Parser Lite!

           Made with love by Leonardo Camilo and Enzo Souto

================================================================================
