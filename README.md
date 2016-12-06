# La-Z-Boy

[![Join the chat at https://gitter.im/La-Z-Boy/Lobby](https://badges.gitter.im/La-Z-Boy/Lobby.svg)](https://gitter.im/La-Z-Boy/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The end result of extreme boredom and the sufferings after watching some really low-rated movies on TV.

This script is really helpful when you want to know the the Movies that are to be telecasted on TV
along with their `"Timing"` and `"IMDb Rating"`, so you never miss out a good watch right when you sit
on your La-Z-Boy.

This project is still under development.


### Dependencies
-----------------

Install all the dependencies using `pip install -r requirements.txt` before using the script.

   * BeautifulSoup
   * mechanize
   * tabulate
   * fpdf

### Usage
-----------------
 **Run the commands to install the package:**

 $  sudo python setup.py install



Where the supported channels are:

- star-movies
- sony-max
- movies-now
- romedy-now
- movies-ok
- sony-pix
- hbo
- filmy
- star-gold

**Run the commands to execute:**

  $  python La-Z-Bo

**Example:**

    $ python La-Z-Boy

    Enter name of the TV Channel: hbo



**Output:**

Movies                                      Time              Rating
------------------------------------------  ----------------  --------
Lara Croft Tomb Raider: The Cradle of Life  6:50 PM-9:00 PM   5.5
Mission: Impossible - Rogue Nation          9:00 PM-11:23 PM  7.4
Super 8                                     11:23 PM-1:38 AM  7.1
A Nightmare on Elm Street                   1:38 AM-3:05 AM   7.5
Inside HBO                                  3:05 AM-3:08 AM   -
Only God Forgives                           3:08 AM-4:25 AM   5.7
21 Jump Street                              4:25 AM-6:00 AM   7.2
Inside HBO                                  6:00 AM-6:23 AM   -
Jonah Hex                                   6:23 AM-7:41 AM   4.7
Mission Impossible                          7:41 AM-9:39 AM   7.1




And it's done! You have the name of the movie, timings and most importantly, the IMDb rating for the movie
right in front of you on the Terminal.

### Features
-----------------

Currently supported:

- [x] Provides IMDb ratings for movies

**TODOs**:

- [x] Print output in `Prettytable` format
- [ ] Allow search for Entertainment Channels
- [x] Provide option to save details as PDF
- [ ] Send notification to the user

### Contribute

Have any suggestions? Please feel free to report as issues/pull requests.
