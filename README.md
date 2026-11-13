# KVS CPD Certificate Studio

A free tool that runs in your web browser and produces bilingual (Hindi and English) **Continuous Professional Development (CPD) certificates** in the Kendriya Vidyalaya Sangathan format: A4 landscape, ready to print or share.

### ▶ Open the studio: **https://vnyvkc.github.io/kvs-cpd-certificate/**

There is nothing to install and no account to create. Open the link in Google Chrome or Microsoft Edge on a computer and start.

---

## Contents

1. [What it does](#what-it-does)
2. [Privacy: your data stays on your computer](#privacy-your-data-stays-on-your-computer)
3. [Quick start (5 minutes)](#quick-start-5-minutes)
4. [The screen at a glance](#the-screen-at-a-glance)
5. [Step 1: Set up a course](#step-1-set-up-a-course)
6. [Step 2: Add participants](#step-2-add-participants)
7. [Step 3: Page Setup (emblem, background, saved work)](#step-3-page-setup-emblem-background-saved-work)
8. [Step 4: Check the preview](#step-4-check-the-preview)
9. [Step 5: Export certificates](#step-5-export-certificates)
10. [The two header options explained](#the-two-header-options-explained)
11. [Saving, backing up and moving your work](#saving-backing-up-and-moving-your-work)
12. [CSV file formats](#csv-file-formats)
13. [Tips and troubleshooting](#tips-and-troubleshooting)
14. [Frequently asked questions](#frequently-asked-questions)
15. [For developers](#for-developers)
16. [Credits](#credits)

---

## What it does

- **Fills in the official bilingual certificate.** Both the Hindi paragraph and the English paragraph of the KVS CPD certificate are filled in for every participant. Options that don't apply (for example *Workshop* when the programme was a *Training Programme*) can be struck through automatically.
- **Keeps one master list of people.** Enter each teacher once, then tick who attended each course. The same teacher can be a *Participant* in one course and a *Resource Person* in another.
- **Handles many courses at once.** Create, duplicate or import courses from a spreadsheet (CSV).
- **Imports from spreadsheets.** Bring in courses and participants from CSV files saved from Excel or Google Sheets.
- **Checks your work before export.** A review step lists missing names, missing Hindi names or designations, missing hours, duplicate names and a missing signature, so mistakes are caught before printing.
- **Exports print-ready files:**
  - one certificate as PDF or PNG
  - one PDF for a whole course (a page per person)
  - a ZIP with one PDF per person
  - a ZIP of all courses, with a folder per course
- **Adds the principal's signature.** Upload a photo or scan of the signature; its white background is removed automatically.
- **Prints on pre-printed certificate paper.** Upload a scan of your printed form, hide the printed headings, and nudge the text into place.

The certificate design follows the blank format in [`CPC Certificate KVS format.pdf`](CPC%20Certificate%20KVS%20format.pdf). Check with your Principal or Regional Office that the format matches current requirements before issuing certificates.

---

## Privacy: your data stays on your computer

- Everything happens **inside your browser**: reading CSV files, removing the signature background, drawing certificates and making PDFs and ZIPs.
- **Nothing is uploaded.** No staff names, signatures or templates are sent to any server. The website only delivers the app itself.
- Your work is **saved automatically in this browser on this computer** (the bottom bar shows *"Saved in this browser at …"*). Other people, and other computers, cannot see it.
- Once the page has loaded, the studio keeps working even if the internet connection drops.

---

## Quick start (5 minutes)

1. Open **https://vnyvkc.github.io/kvs-cpd-certificate/**. The sample courses and people show you how everything looks.
2. **1. Course Setup** tab: type your programme title, year, hours, category, mode, school and Regional Office. Upload the principal's signature.
3. **2. Participants** tab → **Master list** → **+ Add person** (or **Import CSV**). Add each teacher once, with their name and designation in English and Hindi.
4. **2. Participants** → **This course**: tick everyone who attended and choose their role.
5. Look at the preview on the right. Use **Prev Member / Next Member** to check a few certificates.
6. Click **Export course (N)** → read the review → choose **One PDF** or **ZIP** → **Export**.

To remove the sample data:
- **Courses:** import your own **Course CSV** with *Replace existing courses* ticked, or delete the extra sample course with 🗑 and edit the one that's left. At least one course always remains.
- **People:** import your own participants into the **Master list** with *Replace the whole master list* ticked, or remove the sample people with ✕.

---

## The screen at a glance

| Area | What's there |
|---|---|
| **Top bar** | Two certificate options (*Strike out options that don't apply*, *Fill empty Hindi fields with English*), **Save Project** and **Load Project**. |
| **Left panel** | Three tabs: **1. Course Setup**, **2. Participants**, **3. Page Setup**. |
| **Right panel** | The live certificate preview. Above it: **Prev / Next Member**, zoom (− **Fit** +), **This certificate: PDF / PNG**, **Export course (N)**, **Export all courses…**. |
| **Bottom bar** | Who is being previewed, whether they are included in export, the current course, the autosave status and the credits. |

On a phone or narrow window the preview appears first, with the panels below it.

---

## Step 1: Set up a course

Open the **1. Course Setup** tab.

### Managing courses
The **Programme / Course Manager** card at the top shows all your courses in a drop-down. Each course is listed with the number of certificates it will produce.

| Button | What it does |
|---|---|
| **+ New** | Adds an empty course. School, RO, year, mode, principal and date are copied from the current course to save typing. |
| ⧉ (duplicate) | Copies the current course, including who attended. Useful for a second batch of the same programme. |
| 🗑 (delete) | Deletes the current course. An **Undo** button appears for 8 seconds. People in the master list are not deleted. |
| **Course CSV** | Imports several courses at once from a spreadsheet (see [Courses CSV](#courses-csv)). |

### Course details
| Field | Printed where | Notes |
|---|---|---|
| **वर्ष / Year** | Top right, *वर्ष / Year* | e.g. `2026-27`. If left blank, an empty line is printed. |
| **Duration (घंटे / Hours)** | Both paragraphs | Numbers only, e.g. `50`. |
| **Programme / Workshop / Activity Title (English)** | English paragraph | The course name. |
| **कार्यक्रम / कार्यशाला शीर्षक (Hindi)** | Hindi paragraph | The course name in Hindi. If blank, see [Fill empty Hindi fields](#fill-empty-hindi-fields-with-english). |
| **Category Focus** | Strikes out the other options | Training Programme, Workshop, Paper Publishing, Question Paper Setting or Editing a Publication. |
| **Mode** | Strikes out the other option | Offline (मुखाभिमुख) or Online (आभासी). |
| **School Category** | Strikes out the other option | PM Shri (पीएम श्री) or Kendriya Vidyalaya. |
| **Default Vidyalaya Name / Default Regional Office** | Both paragraphs | Used for every participant whose own school or RO is left blank. |
| **विद्यालय नाम / क्षेत्रीय कार्यालय (Hindi)** | Hindi paragraph | Hindi names of the school and RO. They are used only for participants from this course's own school and RO. |
| **Principal Name** (optional) | Above *प्राचार्य / Principal* | e.g. `Dr. S. K. Sharma`. |
| **Issue Date / Ref** (optional) | Bottom left | Printed exactly as typed, e.g. `Date: 13.11.2026`. |

### Principal's signature
1. Click **Upload Principal Signature (PNG/JPG)** and choose a clear photo or scan of the signature on white paper.
2. Keep **Transparent background** ticked. The white paper is removed so only the ink prints.
3. Use the **Height** slider to make the signature larger or smaller.
4. **Remove** takes the signature off.

The signature is used for every course.

---

## Step 2: Add participants

Open the **2. Participants** tab. At the top are two buttons:

- **This course (N)**: who gets a certificate for the course selected in Course Setup.
- **Master list (N)**: everyone you issue certificates to, kept once and shared by all courses.

### The master list
Use the master list for staff who attend many programmes, so you enter them once and never retype them.

1. Click **Master list**.
2. Click **+ Add person**, or **Import CSV** to add many at once (see [Participants CSV](#participants-csv)).
3. For each person, fill in:
   - **Salutation**: Mr / श्री, Mrs / श्रीमती, Ms / सुश्री or Dr. / डॉ.
   - **Full Name (English)** and **नाम (हिन्दी)**
   - **Designation** (e.g. `PGT (Computer Science)`) and **पदनाम (हिन्दी)** (e.g. `स्नातकोत्तर शिक्षक (कंप्यूटर विज्ञान)`)
   - **Usually Participant / Usually Resource Person**: the role they get by default when ticked in a course
   - **Vidyalaya** and **Regional Office**: leave blank if they are from the course's own school; fill in only for staff from another school.
4. Each card shows **"In N courses"**. Editing a person here updates their certificate in every course.
5. ✕ removes a person from the master list *and* from every course. An **Undo** button appears for 8 seconds.

Use the **search box** to find people by name, designation or school.

### Ticking who attended a course
1. In **1. Course Setup**, choose the course from the drop-down.
2. In **2. Participants**, click **This course**.
3. In **From the master list**, tick everyone who attended.
4. A **role** drop-down appears next to each ticked person. Choose *Participant* or *Resource Person* for **this course only**.
5. Click a ticked name to preview their certificate.

To tick many people quickly, type in the search box (for example `TGT`, or a school name) and click **Tick all shown**. **Clear** unticks everyone currently shown.

### People only in this course
For a one-off guest such as a university resource person, use **Only in this course**:

- **+ Add person** adds a card that belongs to this course only.
- **Import CSV** with **This course only** chosen adds several at once.
- The checkbox on each card includes or leaves out that person when exporting. **All / None** sets every card at once.
- **To master list** moves the person into the master list (they stay ticked for this course) so other courses can use them.

### Warning chips
Small coloured labels on the cards point out gaps:

| Chip | Meaning |
|---|---|
| **No name** (red) | The English name is empty. The certificate would have a blank name. |
| **No Hindi name** (amber) | The Hindi name is empty and the Hindi blank will print empty. |
| **Hindi name in English** (amber) | The Hindi name is empty, so the English name will print in the Hindi paragraph. |

---

## Step 3: Page Setup (emblem, background, saved work)

Open the **3. Page Setup** tab.

### Certificate Heading
The two heading lines at the top of the certificate can be changed, for example to name your Regional Office or Vidyalaya.
- **पहली पंक्ति (हिन्दी) / Line 1 (Hindi)** always prints first, and **Line 2 (English)** always prints below it.
- Long headings shrink automatically to fit between the two emblems.
- Leave a line empty to leave it out.
- **Restore official heading** puts back *केन्द्रीय विद्यालय संगठन, नई दिल्ली / KENDRIYA VIDYALAYA SANGATHAN, NEW DELHI*.
- The heading applies to every certificate. It is autosaved, and included when you use **Save Project**.

### KVS Emblem
- The official KVS emblem is built into the studio and appears in both top corners. You don't need to do anything.
- **Replace with another emblem image** lets you use a different image if required. **Restore the official emblem** switches back.
- **Emblem size** changes the size of both emblems.
- If an emblem image can't be loaded, the studio shows a warning and **won't export** until an emblem is restored. It never draws a substitute.

### Certificate Background Layer
- **Official KVS Layout** (default): the studio draws the full certificate, including the border, emblems, headings and wording, on plain paper.
- **Uploaded PDF / Scan**: use this to print onto **pre-printed certificate forms**.
  1. Click **Upload Official PDF or Image** and choose a scan or PDF of the blank form.
  2. Tick **Hide static printed headers (for pre-printed scans)** so the headings aren't printed twice.
  3. Use **Nudge text position** (*Left / right*, *Up / down*) to line the text up with the blanks on your form. **Reset** puts it back.
  4. Do a test print on plain paper and hold it against a printed form before printing the batch.

### Saved Work
Shows that your work is saved automatically in this browser. **Clear saved work from this browser** deletes that saved copy. Use **Save Project** first if you want to keep it.

---

## Step 4: Check the preview

- **Prev Member / Next Member** steps through everyone in the current course. The counter shows *1 of N*.
- **−**, **Fit** and **+** zoom the preview. **Fit** sizes it to the window.
- The bottom bar shows who you are previewing and whether they are **Selected for Export**.

How the text is laid out:
- Filled-in values (names, schools, titles, hours) are **underlined and kept together**. A value that doesn't fit at the end of a line moves to the next line as a whole.
- Paragraphs are **justified**: the extra space on each line goes into the underlines, like a printed form.
- If a very long name and title would run into the signature, the text is made slightly smaller **for that certificate only**.

---

## Step 5: Export certificates

### One certificate
Above the preview: **This certificate → PDF** or **PNG** downloads just the certificate shown.

### A whole course
1. Click **Export course (N)**. N is the number of certificates.
2. The **review** window opens:
   - **Red** items block export, for example *No participants are selected* or *The KVS emblem isn't loaded*.
   - **Amber** items are warnings to check, such as missing Hindi names or designations, missing hours, duplicate names or no signature. You can still export.
3. Choose **Download as**:
   - **One PDF, a page per person**: best for printing the whole batch. File: `KVS_CPD_<course title>_Certificates.pdf`.
   - **ZIP, one PDF per person**: best for emailing each teacher their own certificate. File: `KVS_CPD_<course title>.zip`, containing `01_<name>.pdf`, `02_<name>.pdf` and so on.
4. Click **Export N certificates**. A progress bar shows each certificate. **Cancel** stops the export, and nothing is downloaded.

### All courses at once
**Export all courses…** → review → **Export**. You get one ZIP, `KVS_All_CPD_Certificates_<date>.zip`, with **a folder per course** and one PDF per person inside.

### Print settings
The PDFs are exactly **A4 landscape (297 × 210 mm)**. When printing, choose **A4, Landscape, Actual size / 100 %** and turn off *Fit to page*. Otherwise the certificate may shrink.

---

## The two header options explained

### Strike out options that don't apply
When ticked, options that don't apply are struck through (~~Workshop~~) and the chosen one is printed in bold. This covers Mr/Mrs/Ms/Dr., PM Shri/Kendriya Vidyalaya, Online/Offline, Training Programme/Workshop/Activities, the activity type, and Participant/Resource Person. When unticked, all options print normally with the chosen one in bold.

### Fill empty Hindi fields with English
Hindi values are **always** used when they are filled in. This option only decides what happens when a Hindi value is **empty**:

| Option | Empty Hindi name, designation, title, school or RO |
|---|---|
| ✅ Ticked | The English value is printed in the Hindi paragraph. |
| ⬜ Not ticked | The blank is left empty, so it can be filled in by hand. |

---

## Saving, backing up and moving your work

| Action | How |
|---|---|
| **Automatic save** | Every change is saved in this browser on this computer. Close the tab and come back later; your work reappears. |
| **Keep a backup** | Click **Save Project**. A file named `KVS_CPD_Project_<date>.json` is downloaded, containing courses, the master list, signature, emblem and settings. Keep it somewhere safe. |
| **Move to another computer or browser** | **Save Project** on the old one, then **Load Project** on the new one. Loading replaces what's on screen, so the studio asks first. |
| **Start fresh** | **3. Page Setup → Clear saved work from this browser**, then reload the page. |

> Autosave is per browser and per website. Clearing your browser's history or site data, or using a private / incognito window, removes the automatic save. **Save Project** regularly.

---

## CSV file formats

You can prepare lists in Excel or Google Sheets and import them as CSV.

**Saving a CSV that keeps Hindi text:**
- **Excel:** *File → Save As → CSV UTF-8 (Comma delimited) (.csv)*. Plain "CSV" may turn Hindi into question marks.
- **Google Sheets:** *File → Download → Comma-separated values (.csv)*.

The first row should be the column headings shown below; it is skipped automatically. Cells containing commas need double quotes, e.g. `"IOC Noonmati, Guwahati"`. Excel adds them for you. You can also **paste** CSV text straight into the import box instead of choosing a file.

### Participants CSV
Used by **Import CSV** on the Participants tab. Choose **Master list** or **This course only** in the import window.

| # | Column | Required | Example | Notes |
|---|---|---|---|---|
| 1 | `Salutation` | | `Mr` | `Mr`, `Mrs`, `Ms` or `Dr.` (blank means Mr) |
| 2 | `Name_EN` | **Yes** | `Rajesh Kumar Sharma` | Rows without it are skipped and reported. |
| 3 | `Name_HI` | | `राजेश कुमार शर्मा` | |
| 4 | `Designation` | | `PGT (Computer Science)` | |
| 5 | `Role` | | `Participant` | Anything containing "resource" means Resource Person. |
| 6 | `Vidyalaya` | | `IOC Noonmati, Guwahati` | Blank means the course default. |
| 7 | `Regional_Office` | | `Guwahati` | Blank means the course default. |
| 8 | `Designation_HI` | | `स्नातकोत्तर शिक्षक (कंप्यूटर विज्ञान)` | Optional column. Older 7-column files still work. |

```csv
Salutation,Name_EN,Name_HI,Designation,Role,Vidyalaya,Regional_Office,Designation_HI
Mr,Rajesh Kumar Sharma,राजेश कुमार शर्मा,PGT (Computer Science),Participant,,,स्नातकोत्तर शिक्षक (कंप्यूटर विज्ञान)
Mrs,Sunita Devi,सुनीता देवी,TGT (Mathematics),Resource Person,,,प्रशिक्षित स्नातक शिक्षक (गणित)
```

**Importing into the master list:**
- People already in the list (same English name and designation) are **matched, not added twice**. Their missing Hindi name or designation is filled in from the file.
- When you import from the *This course* view, everyone in the file is also **ticked for that course**.
- **Replace the whole master list instead of adding** removes everyone first, after asking you.

**Download Sample CSV** in the import window gives you a ready-made file to fill in.

### Courses CSV
Used by **Course CSV** in Course Setup.

| # | Column | Required | Example | Notes |
|---|---|---|---|---|
| 1 | `Year` | | `2026-27` | |
| 2 | `Title_EN` | **Yes** | `NEP 2020 & Experiential Pedagogy` | Rows without it are skipped and reported. |
| 3 | `Title_HI` | | `राष्ट्रीय शिक्षा नीति 2020 …` | |
| 4 | `Category` | | `Training Programme` | `Training Programme`, `Workshop`, `Paper Publishing`, `Question Paper Setting`, `Editing a Publication` |
| 5 | `Mode` | | `Offline` | `Online` or `Offline` |
| 6 | `Hours` | | `50` | |
| 7 | `School_Type` | | `PM Shri` | `PM Shri` or `Kendriya Vidyalaya` |
| 8 | `Vidyalaya` | | `IOC Noonmati, Guwahati` | |
| 9 | `Regional_Office` | | `Guwahati` | |
| 10 | `Principal_Name` | | `Dr. S. K. Sharma` | |
| 11 | `Issue_Date` | | `Date: 13.11.2026` | Printed exactly as written. |
| 12 | `Vidyalaya_HI` | | `आई.ओ.सी. नूनमाटी, गुवाहाटी` | Optional |
| 13 | `Regional_Office_HI` | | `गुवाहाटी` | Optional |

Upper or lower case doesn't matter for Category, Mode and School_Type. Imported courses start with nobody ticked; tick who attended on the Participants tab.

---

## Tips and troubleshooting

| Problem | What to do |
|---|---|
| Hindi shows as `???` or boxes after import | Save the spreadsheet as **CSV UTF-8** (see [CSV file formats](#csv-file-formats)). |
| English appears in the Hindi paragraph | That person or course has an empty Hindi field. Fill in the Hindi name, designation, title, school or RO, or untick *Fill empty Hindi fields with English* to leave the blank empty. |
| A word appears twice in the Hindi title | Check the Hindi title field in Course Setup; the studio prints exactly what is typed there. |
| "Export" button is greyed out in the review | Fix the red item: tick at least one participant, or restore the emblem under Page Setup. |
| Printed certificate is smaller than the page | Print at **Actual size / 100 %**, A4 landscape, with *Fit to page* off. |
| Text doesn't line up with a pre-printed form | Page Setup → **Nudge text position**, then test print on plain paper. |
| Signature has a grey box around it | Use a photo with plain white paper and good light, and keep **Transparent background** ticked. |
| My work disappeared | Autosave is per browser. Use the same browser on the same computer, or **Load Project** from your saved `.json` backup. |
| Very large batches are slow | Each certificate is made at full print quality. For hundreds of certificates, export course by course and keep the tab in front while it works. |

---

## Frequently asked questions

**Is any of my data sent to the internet?**
No. The studio works entirely in your browser. The only things downloaded from the internet are the app itself, fonts and some helper libraries, when the page first loads.

**Can several teachers use it at the same time?**
Yes. Each person's work is saved separately in their own browser. To share a set of courses and people, send the **Save Project** file and the other person uses **Load Project**.

**Does it work on a phone?**
It opens and works on phones and tablets, but entering data and printing are much easier on a computer.

**Which browsers are supported?**
The studio is tested in **Google Chrome**. Microsoft Edge uses the same engine and should behave the same. Firefox and Safari haven't been tested yet, so use Chrome or Edge for important batches.

**Can I change the certificate wording or design?**
The paragraphs, layout and emblem follow the official KVS format and are intentionally fixed. You can change the **two-line heading** (Page Setup → Certificate Heading), the emblem size, the signature size and the text position, and you can print on your own pre-printed forms.

**What happens to people when I delete a course?**
Only the course and its course-only people are deleted. People in the master list stay, and an Undo button appears for 8 seconds.

---

## For developers

- The whole app is a single file, [`index.html`](index.html): HTML, Tailwind CSS (loaded from a CDN) and plain JavaScript. There is no build step.
- Libraries loaded from cdnjs: [PDF.js](https://mozilla.github.io/pdf.js/) 3.11.174 (reading uploaded PDF backgrounds), [jsPDF](https://github.com/parallax/jsPDF) 2.5.1 (making PDFs) and [JSZip](https://stuk.github.io/jszip/) 3.10.1 (making ZIPs). Fonts: Inter, Noto Serif, Noto Sans Devanagari and JetBrains Mono from Google Fonts.
- Certificates are drawn on a 2970 × 2100 pixel canvas (10 pixels per mm at A4 landscape). The border artwork is traced from the official PDF, and the official emblem is embedded in the file.
- To run it locally, serve the folder and open it:
  ```bash
  python3 -m http.server 8000
  ```
  then visit http://127.0.0.1:8000/
- **Publishing:** this repository is served by GitHub Pages from the `main` branch. Push a change and the site updates within about a minute.

---

## Credits

Developed by **Vinay Kumar Chauhan**, PGT (Computer Science), KV IOC Noonmati, Guwahati.

The certificate follows the Kendriya Vidyalaya Sangathan CPD certificate format. The KVS name and emblem belong to Kendriya Vidyalaya Sangathan.
