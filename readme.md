## Апісаньне (be)
Вітаю!

Гэты інтэрактыўны ноўтбук дапаможа табе спампаваць аўдыя зь любога відэа на youtube. 
Без усталяваньня лішніх плагінаў у свой браўзер і без аніякай рэкламы.

Мабыць пазьней я дадам магчымасьць спампоўваць і відэа.

Увесь код выконваецца на бясплатнай віртуальнай машыне ў воблаку Google Colab. Таму табе не спатрэбіцца нічога ўсталёўваць на свой камп'ютар. 

### Запуск
* Каб запусьціць ноўтбук табе спатрэбіца толькі 
  **зайсьці ў свой Google-акаўнт**, каб атрымаць доступ да бясплатнай віртуальнай машыны ў воблаку Google Colab
* Ніякія даныя пра твой акаўнт не выкарыстоўваюцца.<br>
  Доступ да твайго Google-дыску таксама не адбываецца.
* Табе неабходна толькі ўвесьці спасылку на відэа ў форму ніжэй і запусьціць **"клеткі"** з кодам
* Запускаць клеткі можна з дапамогай трохкутнічка ў левым верхнім куце клеткі
* Пры першым запуску віртуальнай машыны неабходна выканаць клеткі "Ініцыялізацыі"
* Калі захочаш, то можаш адкрыць "Праваднік" на віртуальнай машыне кнопкай з выявай тэчкі ў самым левым куце старонкі. 
  Але гэта рабіць неабавязкова: ў ноўтбуку ўжо ёсьць гатовы код, які спампуе ўсе файлы зь віртуальнай машыны на твой лакальны камп'ютар
* Па змоўчаньні аўдыяфайлы спампоўваюцца на віртуальную машыну ў тэчку `audio`.


Код выкарыстоўвае бібліятэку [yt-dlp](https://github.com/yt-dlp/yt-dlp). 
Насамрэч усё можна зрабіць у 2 радкі коду (таму можаш сьмела эксьперыментаваць самастойна!), 
але для максімальна простага ўзаемадзеяньня з карыстальнікам коду тут трошку больш :)

---

## Description (en)
Hello!

Use this notebook to download audio from any youtube video. With no add-ons and no adds.

Probably later I'll add support to download videos.

All code is run on free Virtual Machines (VM) in Google Colab. Thus you don't need to install anything on your computer.

### Run
* To run the notebook you have to login to your Google Account in order to launch free VM in Google Colab
* No data from your Google Account is used, your Google Drive is never accessed.
* You have to enter link to the youtube video and execute **code cells**
* Cells are executed with a triangle icon to the left of the code cell
* You have to run "Initialization" cells on the VM startup
* If necessary, you can access VM's file system by clicking a "Folder" icon on the left side of your screen.
  However, this is not required - the notebook already contains all code for you to download files from VM to your computer
* By default audio is downloaded to `audio` folder on VM

Code uses [yt-dlp](https://github.com/yt-dlp/yt-dlp) library. 
In fact, you can download anything in ~2 lines of python code (so feel free to write your own scripts!).
However this notebook contains boilerplate code to simplify user interaction and minimize user input.
