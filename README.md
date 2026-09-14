# lenslog 

**lenslog** is a photography portfolio management application built with **Python, Tkinter, and MySQL**.

the project was originally developed as my **Class 12 Computer Science school project**. after completing the academic version, i continued working on it independently and created this version with additional features, interface improvements, and usability changes.

## what it does

lenslog allows photographers to keep track of their photographs and the technical details behind them.

you can store information such as:

* camera and lens used
* location
* date taken
* ISO, shutter speed, and aperture
* personal rating
* editing status
* image path and preview

the application also provides tools for searching, sorting, viewing, and analyzing your photography data.

## changes from the school project

this version builds on the original Class 12 project with several improvements.

### search by any category

the original project had limited search functionality. this version allows photographs to be searched using **different categories/fields**, making it easier to find specific photos or groups of photos.

### sorting

photographs can now be **sorted using different headers**, making it easier to organize and compare records.

for example, you can sort your collection based on fields such as:

* title
* category
* date
* rating
* camera
* ISO
* aperture
* editing status

### dark theme

added a **dark theme** to make the interface more comfortable to use and give the application a more modern look.

### continued development

rather than leaving lenslog as a completed school submission, this repository represents my **independent continuation of the project**, where i experimented with improving the original application and its usability.

## tech stack

* **Python**
* **Tkinter** — graphical user interface
* **MySQL** — database
* **mysql-connector-python** — Python/MySQL connection
* **Pillow** — image handling and previews
* **Pandas** — data analysis and export
* **Matplotlib** — data visualization

## features

* add photograph records
* update existing records
* delete records
* search photographs
* sort records using table headers
* preview photographs
* open full-resolution photographs
* track camera and lens information
* track photography settings
* rate photographs
* track editing status
* analyze photography data
* export data to CSV
* dark theme

## database

lenslog uses a MySQL database to store photograph metadata.

the main `photographs` table contains fields including:

```text
photo_id
title
category
location
date_taken
camera_used
lens_used
iso
shutter_speed
aperture
rating
editing_status
image_path
```

images themselves are not stored directly in the database. instead, lenslog stores the **local file path** of each photograph.

## application structure

```text
lenslog/
│
├── main.py
├── database/
├── images/
├── assets/
└── README.md
```

the exact structure may vary depending on the current version of the project.

## why i continued working on it

lenslog started as a school assignment, but it became a useful opportunity to explore how a basic academic project could be turned into a more practical application.

working on the project independently allowed me to experiment with:

* improving an existing codebase
* designing a better user interface
* making data easier to search and organize
* adding new functionality after the original project was completed
* working with databases in a more practical setting

## future improvements

some features i may explore in future versions:

* automatic image tagging
* more advanced photography analytics
* cloud image storage
* user accounts
* better image organization
* EXIF metadata extraction
* machine learning-based photo analysis
* responsive/customizable UI

## project background

**original project:** Class 12 Computer Science school project
**continued as:** independent personal project
**originally developed at:** Birla Public School, Doha
**language:** Python

lenslog started as a school project, but this repository represents my continued development of the idea beyond the original academic requirements.

