# CellarMap

CellarMap is a Windows desktop app for wine collectors who use [CellarTracker](https://www.cellartracker.com). It lets you build a visual version of your physical cellar, import your bottle list from CellarTracker mapped to your layout, and see where everything is stored. You can also explore your collection with charts and filters, check for mapping issues, and create printable cellar views.

CellarMap is **not made by, affiliated with, or endorsed by CellarTracker! LLC**. CellarTracker remains your official wine inventory system. CellarMap simply reads your CellarTracker data and helps you visualize and explore it locally. You can link to your wines and bottles on the CellarTracker website in order to manage them.

## What you can do

- **Design your cellar** — Create areas, racks, single bins, grid bins, front/back sections, and grouped rack layouts. Save your layout to a file and automatically reopen it whenever the app is started.
- **Import your bottles** — Sign in with your CellarTracker account and refresh your current bottle list. CellarMap caches the last import on your computer.
- **View your cellar visually** — Browse your racks in Front, Back, or Depth view, with bottles shown in their matching bins. Customize bin colors, choose what text appears in the bin view, and export the current view as a PDF.
- **Explore your collection** — Use the Dashboard to filter and chart your wines by country, type, vintage, price, drinking window, and more. Link to a bottle in **View Cellar Areas** to see where it is racked. Link to a specific wine or bottle on the CellarTracker website to drink, create notes, move its location, and so on.
- **Find and fix problems** — Review bottles that are pending delivery, unmapped to your layout, or in bins that are over capacity. You can also keep a personal bottle check list and link to individual bottles or the bulk editor on the CellarTracker website to manage your inventory.

## What you need

- A **CellarTracker account** for importing bottle data.
- A **Windows PC** with the CellarMap installer.
- A **cellar layout file** created in CellarMap.

Your layout and imported bottle data are stored **on your own computer**. Layout files are ordinary files, so you can back them up like any other document. CellarMap never changes any of your CellarTracker data. It only creates a local cached copy of your inventory data and allows you to link to the CellarTracker site to make changes.

## How CellarMap matches bottles to bins

CellarTracker stores each bottle with a **Location** and **Bin**. CellarMap maps those fields to the bin slots from the rack layout you design.

A bottle appears in a CellarMap slot when its CellarTracker Location and Bin **exactly match** one of the slots in your layout.

If there is no match, the bottle appears under **Unmapped Bottles**. Bottles with a pending location appear under **Pending Delivery**. If more bottles are mapped to a bin than the slot can hold, the bin appears under **Red bins**.

When setting up racks in **Layout Setup**, use the same Location and Bin names you use in CellarTracker.

## Typical workflow

1. **Layout Setup** — Create your areas, racks, sections, and bins. Set each rack’s Location and bin naming to match CellarTracker. Save your layout.
2. **Import Bottles from CT** — Fetch your latest bottle list from CellarTracker.
3. **View Cellar Areas** — Browse your cellar visually. Click a bin to see what bottles it holds. From there you can link directly to that wine or bottle on the CellarTracker website. Adjust bin colors or labels, and export layout maps when needed.
4. **Dashboard** — Filter, chart, and review your collection. Click a bin name to show it in View Cellar Areas. Click a bottle barcode or wine name to open it in CellarTracker. Shift-click a bottle barcode to add it to the Bottle Check List.
5. Use **Pending Delivery**, **Unmapped Bottles**, **Red bins**, and **Bottle Check List** to correct or verify your physical cellar, CellarMap layout, and CellarTracker data.

## Tabs at a glance

| Tab | Purpose |
|-----|---------|
| **Dashboard** | Charts, filters, and wine summaries based on imported bottles. Open a bin in the viewer or open a wine in CellarTracker. |
| **View Cellar Areas** | Visual map of the selected cellar area, with Front, Back, and Depth views, bottle info popups, bin display options, and PDF export. |
| **Pending Delivery** | Bottles that still need a real cellar location in CellarTracker. |
| **Unmapped Bottles** | Bottles whose Location and Bin do not match any slot in your CellarMap layout. |
| **Bottle Check List** | A working list of bottles to verify physically in the cellar, with links back to CellarTracker. |
| **Red bins** | Bins that contain more bottles than their configured capacity. |
| **Import Bottles from CT** | Sign in, refresh bottle data, and review import status. |
| **Layout Setup** | Edit areas, racks, and sections; save, load, or start a new layout. |

## Keeping data up to date

CellarMap does **not** automatically sync with CellarTracker. It shows a **local copy** of the bottle list from your last import.

If you change anything on the **CellarTracker website**—add or remove bottles, move locations, update bins, mark bottles consumed, and so on—those changes will **not** appear in CellarMap until you refresh:

1. Open **Import Bottles from CT**.
2. Sign in if needed and **fetch** your bottles again (same action as your first import).

Until you import again, charts, View Cellar Areas, unmapped lists, and red-bin checks all use the **previous** cached data. Your layout file is separate: saving the layout does not refresh bottle data.

## Layout files

Use **Save Cellar Layout** to save your cellar project. Use **Load Cellar Layout** to open a saved layout, or **New Cellar Layout** to start over.

Keep backups of your layout file. If you rename Locations or change bin naming in CellarTracker, update your CellarMap layout and re-import your bottles so everything continues to map correctly.

## Privacy and CellarTracker

- Import uses your CellarTracker login. You can choose whether CellarMap remembers your password on your PC.
- Imported bottle data is cached locally for faster startup and viewing of your last import without contacting CellarTracker every time you open the app.
- CellarMap does not change your CellarTracker account; it only reads data when you import and opens links when you choose to manage bottles on the website.

## License

CellarMap is distributed under the **CellarMap Software License**.

Use of CellarTracker is subject to **CellarTracker! LLC**’s own [Terms](https://www.cellartracker.com/terms.asp).
