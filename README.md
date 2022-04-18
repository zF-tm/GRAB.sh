* The Instagram GRAB Tool gets a range of information from an Instagram account that you normally wouldn't be able to get
from just looking at their profile

* The information includes:

* [ profile ] : Username, Profile Name, URL, Followers, Following, Number of Posts, Bio, Profile Picture URL, Is Business Account ?, Connected to a FB account ?, External URL, Joined Recently ?, Business Category Name, Is private ?, Is Verified ?,

* [ tags ] : most used , and by -t all used tags

* [ posts ] : accessability caption, location, timestamp, comments disabled, Caption, picture url

---

## • How To Install

`$ pkg install -y git`

`$ git clone https://github.com/AmshenShanu07/GRAB.git`

`$ chmod +x install.sh && ./install.sh`

## • Usage

`$ python3 grab.py -u username`

`$ python3 main.py -h`

`usage: grab.py [-h] -u USERNAME [-p] [-s]`

`optional arguments:`

`  -h, --help            show this help message and exit`

`  -u USERNAME, --username USERNAME`
`                        username of account to scan`

`  -p, --postscrap       scrape all uploaded images info`

`  -s, --savedata        save data to file `
`                        ( save profile pic, info , post info )`

---
