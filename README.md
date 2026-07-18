Accountant.exe // Fiscal Ledger System

A self-contained corporate auditing environment simulating a legacy financial terminal. This platform equips the user with a collection of lightweight, reactive ledger utilities designed to handle bookkeeping notes, flat tax modeling, basic math operations, and live asset valuation simulations.
Core Ledger Modules

    LEDGER.EXE (Corporate Journal)

    A specialized general journal scratchpad optimized for recording quick debit and credit adjustments or client audit logs. It includes a local export tool to save entries as flat text files directly to your machine.

    AUDIT.EXE (Tax Balancing Matrix)

    An interactive financial modeling table that computes crucial margins on the fly. Input Gross Revenues, Cost of Goods Sold, and Standard Deductions to instantly analyze Gross Margins, Estimated Corporate Tax Liability at a flat 21 percent, and Net Operating Income.

    ROI_CALC.EXE (Financial Calculator)

    A traditional mathematical terminal for verifying transaction fractions, interest accruals, or simple baseline accounting balance sheets.

    ASSET_VAL.EXE (Asset Valuation Terminal)

    A real-time equity tracker that monitors cash flow and capital portfolios. Users can acquire or liquidate contract blocks of Industrial Machinery or 10-Year Treasury Bills while an integrated ticker stream logs simulated depreciation adjustments and macroeconomic interest shifts.

Getting Started

The entire system is completely self-contained in a single web document with zero external dependencies, making it straightforward to run locally.
Prerequisites

    Any standard desktop web browser like Chrome, Firefox, Edge, or Safari.

Launch Instructions

1   Copy the source code provided in the project files.

2    Paste it into a new text document on your computer.

3    Save the file with an .html extension, such as AccountantOS.html.

4    Double-click the saved file to launch the workspace immediately in your default browser.

Technical Details & Architecture

    Front-End Framework: Raw HTML5 semantic markup structured around a retro UI workspace grid.

    Styling & Interaction: Clean, responsive CSS configurations featuring traditional depth emulation window borders and an operational layered window stacking manager for focus control.

    Execution Engine: Pure JavaScript event handling optimized to bypass click conflicts inside input components, ensuring a smooth window-dragging experience while keeping fields fully editable.
