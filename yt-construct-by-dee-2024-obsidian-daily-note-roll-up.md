---
title: Obsidian Daily Note roll-up (Weekly, Monthly, Quarterly, and Yearly) - Full setup from scratch!
description: 
permalink: bibli/yt-obsidian-journal-by-dee
aliases:
  - Obsidian Journal by Dee
tags: 
draft: false
date: 2024-10-31
indexes:
  - "[[cm-obsidian|MOC Obsidian]]"
media_link: https://www.youtube.com/watch?v=m5SYja0V29w
c_creator:
  - Construct By Dee
c_platform: YouTube
c_published: 2024-08-23
---
- [02:59](https://www.youtube.com/watch?t=179&v=m5SYja0V29w) Buat vault baru
 
- [05:26](https://www.youtube.com/watch?t=326&v=m5SYja0V29w) Setup folder
	- Attachments
	- Journal 
		- 01 Daily
		- 02 Weekly 
		- 03 Monthly 
		- 04 Quarterly
		- 05 Yearly
	- Notes
	- Templates 
		- log Templates


- Plugin
	- [09:29](https://www.youtube.com/watch?t=569&v=m5SYja0V29w) Templater
		- [10:03](https://www.youtube.com/watch?t=603&v=m5SYja0V29w) Setting:
			- Automatic Jump to Cursor (ON)
			- Trigger Template on new file creation (ON)
			- Template folder location: set ke folder `Templates` 
	- [10:42](https://www.youtube.com/watch?t=642&v=m5SYja0V29w) Dataview
		- [12:04](https://www.youtube.com/watch?t=724&v=m5SYja0V29w) Setting:
			- Enable Javascript queries (ON)
			- Enable Inline Javascript queries (ON)
			- Date format: `yyyy-MM-dd`
			- Date + time format: `yyyy-MM-dd HH:mm`
	- [13:21](https://www.youtube.com/watch?t=801&v=m5SYja0V29w) Journals
		- [13:52](https://www.youtube.com/watch?t=832&v=m5SYja0V29w) Setting:
			- Tambah (+) Journal Baru:
				- Name: Journal
				- ID: journal
				- Open on startup (ON)
				- Daily notes (ON)
					- [22:53](https://www.youtube.com/watch?t=1373&v=m5SYja0V29w) Setting:
						- Folder: `Journal/01 Daily`
						- Template: `Templates/Daily Note Template`
						- Default date format: `YYYY/MM/YYYY-MM-DD`
				- Weekly notes (ON)
					- [58:18](https://www.youtube.com/watch?t=3498&v=m5SYja0V29w) Setting:
						- Folder: `Journal/02 Weekly`
						- Template: `Templates/Weekly Note Template`
						- Default date format: `YYYY/MM/YYYY-[W]ww`
				- Monthly notes (ON)
					- [1:23:30](https://www.youtube.com/watch?t=5010&v=m5SYja0V29w) Setting:
						- Folder: `Journal/03 Monthly`
						- Template: `Templates/Monthly Note Template`
						- Default date format: `YYYY/YYYY-MM`
				- Quarterly notes (ON)
					- [1:33:33](https://www.youtube.com/watch?t=5613&v=m5SYja0V29w) Setting:
						- Folder: `Journal/04 Quarterly
						- Template: `Templates/Quarterly Note Template`
						- Default date format: `YYYY/YYYY-[Q]Q`
				- Yearly notes (ON)
					- [1:37:47](https://www.youtube.com/watch?t=5867&v=m5SYja0V29w) Setting:
						- Folder: `Journal/05 Yearly`
						- Template: `Templates/Yearly Note Template`
						- Default date format: `YYYY`
	- [15:40](https://www.youtube.com/watch?t=940&v=m5SYja0V29w) Callout Manager
		- [34:17](https://www.youtube.com/watch?t=2057&v=m5SYja0V29w) Custom Callout
			- name: journal
			  color: gray
			  icon: lucide-history
			- name: calendar
			  color: gray
			  icon: lucide-pen-box
			- name: picture
			  color: gray
			  icon: lucide-image
			- name: task
			  color: gray
			  icon: lucide-check-square
			- name: highlight
			  color: gray
			  icon: star-list
			- **NB: Reload Obsidian tiap kali selesai membuat Callout baru atau memodifikasi Callout.**
	- [16:46](https://www.youtube.com/watch?t=1006&v=m5SYja0V29w) Charts
	- [17:16](https://www.youtube.com/watch?t=1036&v=m5SYja0V29w) Heatmap Calendar
	- [17:40](https://www.youtube.com/watch?t=1060&v=m5SYja0V29w) Tracker
	- [39:00](https://www.youtube.com/watch?t=2340&v=m5SYja0V29w) Style Setting
	- [52:08](https://www.youtube.com/watch?t=3128&v=m5SYja0V29w) Minimal Theme Settings
		- [52:23](https://www.youtube.com/watch?t=3143&v=m5SYja0V29w) Setting
			- Image grids (ON) → membuat gambar lebih rapi dengan kolom (grid)
	- [1:44:37](https://www.youtube.com/watch?t=6277&v=m5SYja0V29w) Contribution Graph

> [!note] Daily Note Template
> [18:38](https://www.youtube.com/watch?t=1118&v=m5SYja0V29w) Cek fail berikut: [[8.3a-journal-plugin-daily-note-template-by-dee|Daily Note Template by Dee]]
> - [21:03](https://www.youtube.com/watch?t=1263&v=m5SYja0V29w) `calendar-nav` berasal ldari pugin Journal
> - [22:43](https://www.youtube.com/watch?t=1363&v=m5SYja0V29w) Journal calendar bisa diakses dari sidebar kanan
> - [27:57](https://www.youtube.com/watch?t=1677&v=m5SYja0V29w) Filter untuk task bisa perbulan atau per tanggal tertentu pada dataview Task


- [33:35](https://www.youtube.com/watch?t=2015&v=m5SYja0V29w) Tema: Minimal
	- [38:35](https://www.youtube.com/watch?t=2315&v=m5SYja0V29w) Style Setting:
		- Heading 1: `1.75em`
		- Heading 2: `1.5em`
		- Heading 3: `1.25em`
		- Heading 4: `1em`
		- Heading 5: `0.85em`


# Weekly
- [41:55](https://www.youtube.com/watch?t=2515&v=m5SYja0V29w) Setting → Files and links
	- Default location for new notes: `in the folder specified below`
	  Folder to create new notes in: `Notes`
	- Default location for new attachments: `In the folder specified below`
	  Attachment folder path: `Attachments`

> [!note] Weekly Note Template
> [42:25](https://www.youtube.com/watch?t=2545&v=m5SYja0V29w) Cek fail templat berikut: [[8.3b-journal-plugin-weekly-note-template-by-dee|Weekly Note Template by Dee]]
> - [44:07](https://www.youtube.com/watch?t=2647&v=m5SYja0V29w) Fungsi kode untuk menampilkan semua gambar
> - [44:24](https://www.youtube.com/watch?t=2664&v=m5SYja0V29w) Fungsi highlight, sesuatu yang bermakna, hal yang tidak ingin di lupakan
> - [45:28](https://www.youtube.com/watch?t=2728&v=m5SYja0V29w)  Wheel of life
> 	- [How to Make 2024 The Best Year of Your Life](https://www.youtube.com/watch?v=c_DOG_mXz5w)
> 	- [How to Do a Personal Retreat in Obsidian](https://www.youtube.com/watch?v=D2VfeT1dsxY)
> 	- [Walkthrough: Epic Life Audit (Obsidian Template)](https://www.youtube.com/watch?v=o9811FmW21A)
> - [49:55](https://www.youtube.com/watch?t=2995&v=m5SYja0V29w) Statistik dengan Tracker plugin
> - [1:01:46](https://www.youtube.com/watch?t=3706&v=m5SYja0V29w) Penjelasan threshold pada tracker
> - [1:14:17](https://www.youtube.com/watch?t=4457&v=m5SYja0V29w) Menambahkan section `Weekly Prep` pada template

- [50:55](https://www.youtube.com/watch?t=3055&v=m5SYja0V29w) Contoh penggunaan Weekly Template
	- [54:03](https://www.youtube.com/watch?t=3243&v=m5SYja0V29w) Jika aliases terisi artinya hari itu sangat penting dan berarti.
- [1:00:05](https://www.youtube.com/watch?t=3605&v=m5SYja0V29w) Plugin Journal membuat metadata (properties) otomatis untuk metadata `journal`, `journal-start-date`, `journal-end-date`, dan `journal-section`
- [1:03:35](https://www.youtube.com/watch?t=3815&v=m5SYja0V29w) Mini template
	- [1:04:01](https://www.youtube.com/watch?t=3841&v=m5SYja0V29w) Log highlight [1:04:19](https://www.youtube.com/watch?t=3859&v=m5SYja0V29w) Templater code: cursor.
- [1:07:16](https://www.youtube.com/watch?t=4036&v=m5SYja0V29w) Mengisi data Wheel of Life.
	- [1:07:40](https://www.youtube.com/watch?t=4060&v=m5SYja0V29w) Kebiasaan Dee biasanya membuat section bernama `Week Prep` untuk menjelaskan apa saja yang ingin digapai dalam pekan. 
	- [1:10:09](https://www.youtube.com/watch?t=4209&v=m5SYja0V29w) Untuk memonitoring suatu aktivitas bisa memanfaatkan dataview milik `highlight` lalu ubah tagnya sesuai kebutuhan, misal, (#log/meditation).



[1:15:25](https://www.youtube.com/watch?t=4525&v=m5SYja0V29w) Monthly
> [!note] Monthly Note Template
> [1:15:39](https://www.youtube.com/watch?t=4539&v=m5SYja0V29w) Cek fail templat berikut: [[8.3c-journal-plugin-monthly-note-template-by-dee|Monthly Note Template by Dee]]
> - [1:17:38](https://www.youtube.com/watch?t=4658&v=m5SYja0V29w) Stand-out days: Untuk jurnal harian yang mempunyai alias
> - Potongan code untuk Wheel of life dan statistic mirip seperti weekly note
> - [1:28:54](https://www.youtube.com/watch?t=5334&v=m5SYja0V29w) Menambahkan section `Month Prep` pada templat


[1:30:15](https://www.youtube.com/watch?t=5415&v=m5SYja0V29w) Quarterly
> [!note] Quarterly Note Template
> [1:30:31](https://www.youtube.com/watch?t=5431&v=m5SYja0V29w) Cek fail templat berikut: [[8.3d-journal-plugin-quarterly-note-template-by-dee|Quarterly Note Template by Dee]]
> Templat mirip montly template, hanya beberapa penyesuaian pada tanggal dan gambar.
> 


[1:36:34](https://www.youtube.com/watch?t=5794&v=m5SYja0V29w) Yearly
> [!note] Yearly Note Template
> [1:36:42](https://www.youtube.com/watch?t=5802&v=m5SYja0V29w) Cek fail templat berikut: [[8.3e-journal-plugin-yearly-note-template-by-dee|Yearly Note Template by Dee]]
> Templat merupakan pengembangan dari quarter note template


[1:41:29](https://www.youtube.com/watch?t=6089&v=m5SYja0V29w) New Note
> [!note] New Note Template
> [1:41:34](https://www.youtube.com/watch?t=6094&v=m5SYja0V29w) cek fail templat berikut: [[8.3f-journal-plugin-new-note-template-by-dee|New Note Template by Dee]]


- [1:43:50](https://www.youtube.com/watch?t=6230&v=m5SYja0V29w) Visualize Data with Heatmap Contribution Map
	- [1:46:29](https://www.youtube.com/watch?t=6389&v=m5SYja0V29w) Graph 1
		- Basic Settings
			- Title: Sleep Hours
			- Graph Type: Git Style
			- Date Range: Latest Whole Year
				- 1
			- Source: Page → `Journal/01 Daily`
			- Date Field: File Name
			- Date Field Format: Auto Detect
			- Count Field: Page Property
				- log-sleep-hours
		- Style Settings: 
			- Theme: default
			- Cell Style Rules:
				- 0 ≤ contributions < 4 = (Red)
				- 4 ≤ contributions < 5 = (Orange)
				- 6 ≤ contributions < 7 = (Light green)
				- 7 ≤ contributions < 24 = (Dark green)
	- [1:52:04](https://www.youtube.com/watch?t=6724&v=m5SYja0V29w) Graph 2
		- Basic Settings
			- Title: Sleep Hours
			- Graph Type: Month Track
			- Date Range: Latest Whole Month
				- 6
			- Source: Page 
			- Date Field: File Name
			- Date Field Format: Auto Detect
			- Count Field: Page Property
				- log-sleep-hours
		- Style Settings: 
			- Theme: default
			- Cell Style Rules:
				- 0 ≤ contributions < 4 = (Red)
				- 4 ≤ contributions < 5 = (Orange)
				- 6 ≤ contributions < 7 = (Light green)
				- 7 ≤ contributions < 24 = (Dark green)
	- [1:56:26](https://www.youtube.com/watch?t=6986&v=m5SYja0V29w) Graph 3
		- Basic Settings
			- Title: Log Day Rating
			- Graph Type: Git Style
			- Date Range: Latest Days
				- 180
			- Source: Page 
			- Date Field: File Name
			- Date Field Format: Auto Detect
			- Count Field: Page Property
				- log-day-rating
		- Style Settings: 
			- Theme: default
			- Cell Style Rules:
				- -2 ≤ contributions < -1 = (Red)
				- -1 ≤ contributions < -0.01 = (Orange)
				-  ≤ contributions <  = (Transparent)
				- 0.01 ≤ contributions < 1.01 = (Light green)
				- 1.01 ≤ contributions < 2.01 = (Dark green)
- [2:05:41](https://www.youtube.com/watch?t=7541&v=m5SYja0V29w) Mengubah tampilan logredis task box menggunakan CSS



---
Sumber [Construct By Dee, 2024, Obsidian Daily Note roll-up (Weekly, Monthly, Quarterly, and Yearly) - Full setup from scratch!](https://www.youtube.com/watch?v=m5SYja0V29w)