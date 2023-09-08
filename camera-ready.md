---
layout: default
title: Camera-Ready Instructions
group: Author Information

---

# {{ page.title }}


| Paper type | Number of pages | MANUSCRIPT UPLOAD DEADLINE | AUTHOR REGISTRATION DEADLINE |
| --- | --- | --- | --- |
| Main conference papers | 10 | August 21th, 2023 (11:59 PM EDT) | August 21th, 2023 (11:59 PM EDT) |
| Workshop papers | 6 | August 30th, 2023 (11:59 PM EDT) | August 30th, 2023 (11:59 PM EDT) |
| Workshop extended abstracts | 3 | August 30th, 2023 (11:59 PM EDT) | August 30th, 2023 (11:59 PM EDT) |
| Workshop Posters| 3 | August 30th, 2023 (11:59 PM EDT) | August 30th, 2023 (11:59 PM EDT) |
| Poster papers | 2 | August 30th, 2023 (11:59 PM EDT) | August 30th, 2023 (11:59 PM EDT) |
| Demo papers | 2 | August 30th, 2023 (11:59 PM EDT) | August 30th, 2023 (11:59 PM EDT) |


## Checklist for Authors
1. [Complete the ACM e-Rights agreement as soon as possible.](#1-complete-the-acm-e-rights-agreement)
2. [Register for the conference](#2-register-for-the-conference)
3. [Prepare your camera-ready manuscript](#3-prepare-your-camera-ready-manuscript)
4. [Upload your camera-ready manuscript](#4-upload-your-camera-ready-manuscript)

Note: if any of the above steps are skipped, the paper will not be included in the conference proceedings.

### 1. Complete the ACM e-Rights agreement
Click the “Edit” tab on the upper left-hand portion of the HotCRP page of your paper, then you can access the ACM e-Rights form. **Please complete the form as soon as possible.**

Note that ACM will use its automated system upon completion of the form to email you additional instructions for your camera-ready manuscript preparation. Please set your email spam settings to allow messages from [rightsreview@acm.org](rightsreview@acm.org).

### 2. Register for the conference
To ensure the inclusion of the paper in the final proceedings, at least one author per paper must complete a full conference registration before uploading the camera-ready version.

**The registration site will open soon.**

Once the registration is completed, please send an email to the Registration Chair, Laura Galluccio ([laura.galluccio@unict.it](laura.galluccio@unict.it)), to **confirm the registration**, with the subject [ACM Mobihoc 2023 Registration] and then report in the body the paper number, paper title, and the registered author. We need to verify the name of the author who is registered for each paper.

### 3. Prepare your camera-ready manuscript
- Use the ACM templates from: [http://www.acm.org/publications/proceedings-template](http://www.acm.org/publications/proceedings-template). Modifications to the ACM templates are not allowed. The final PDF will be checked for consistency with these templates. Non-compliance may result in your publication being rejected.
- If you are using LaTeX, please refer to the sample file “sample-sigconf.tex” after you download the .zip templates file and unzip it.
- Note that the document class “\\documentclass[sigconf]{acmart}” should be used
- The rights and permissions information, conference information, and bibliographic strip (your paper’s DOI and ACM MobiHoc’s ISBN) must appear on the lower left-hand portion of the first page, following the instructions you have received from ACM after filling out the e-Rights form via the ACM rights-management tool on the HotCRP page of the paper.
- Choose the appropriate ACM CCS concepts or categories from this website: [https://dl.acm.org/ccs/ccs.cfm](https://dl.acm.org/ccs/ccs.cfm). Specifically, you need to assign the CCS concepts, click “Generate CCS Codes” and copy the TeX code to your LaTeX for your camera-ready paper.
- **CCS Concepts, user-defined keywords, and ACM Reference Format text are mandatory** for all papers and should be included in the camera-ready PDF as well as on HotCRP.
- **Page numbers should not appear in the camera-ready PDF.**
- The page limit for publications in the main conference is **10 pages**. Workshop papers are limited to **6 pages** (or **3** if extended abstracts/poster papers). Demo and poster papers in the main conference are limited to **2 pages**.
- The demo title should begin with "Demo: ", and the poster title should begin with "Poster: ".
- Your PDF submission should have all fonts embedded. If you are unsure about how to check for this, see: [http://www.acm.org/binaries/content/assets/publications/word-to-pdf-instructions-.txt](http://www.acm.org/binaries/content/assets/publications/word-to-pdf-instructions-.txt).
- Your PDF should not include **Type 3 fonts**. Embedded *matplotlib* figures are a common source of Type3 fonts. If your submission uses *matplotlib*, try rebuilding your figures with these parameter settings:
  - import matplotlib
  - matplotlib.rcParams['pdf.fonttype'] = 42
  - matplotlib.rcParams['ps.fonttype'] = 42
  - Another common sources of Type3 fonts are LaTeX packages (e.g., bbm).
- Submit through HotCRP all of the following:
  - source files
  - ACM keywords
  - ACM CCS concepts (the CCS XML codes that were generated, not the CCS TeX code)
  - references
  - camera-ready PDF.


### 4. Upload your camera-ready manuscript
**Conference papers:** Please use the HotCRP submission website for the main conference ([https://mobihoc23.hotcrp.com/](https://mobihoc23.hotcrp.com/)) to upload your camera-ready manuscript.

**Workshop papers:** Please use your respective workshop’s HotCRP submission website to upload your camera-ready manuscript.

**Poster/demo papers:** Please use the HotCRP submission website for the poster/demo track ([https://mobihoc23posterdemo.hotcrp.com/](https://mobihoc23posterdemo.hotcrp.com/)) to upload your camera-ready manuscript.
