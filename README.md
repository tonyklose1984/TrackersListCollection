# [XIU2/TrackersListCollection](https://github.com/XIU2/TrackersListCollection)

[![GitHub license](https://img.shields.io/github/license/XIU2/TrackersListCollection.svg?style=flat-square)](https://github.com/XIU2/TrackersListCollection/blob/master/LICENSE)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg?style=flat-square)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg?style=flat-square)](https://996.icu)
[![GitHub Star](https://img.shields.io/github/stars/XIU2/TrackersListCollection.svg?style=flat-square&label=Star)](https://github.com/XIU2/TrackersListCollection/stargazers)
[![GitHub Fork](https://img.shields.io/github/forks/XIU2/TrackersListCollection.svg?style=flat-square&label=Fork)](https://github.com/XIU2/TrackersListCollection/network/members)

Updated daily! A list of popular public BitTorrent trackers.  

The project only makes a list of popular public trackers into collections.  

> 「[简体中文](https://github.com/XIU2/TrackersListCollection/blob/master/README-ZH.md)」([trackerslist.com](https://trackerslist.com) 访客，请通过右上角切换语言 ↗)

> ***Note: To simplicity, the prefix [trackers_] of the old file name is deleted uniformly. Currently, the old and new file names coexist, but the old file name will be canceled after two months.***

****

### What is Tracker ?

Tracker is a required role in BT downloads.  

High-quality Tracker can effectively improve BT download speed.  

The more people use these Trackers, the faster the BT download speed will be, **so please recommend it to your friends!**

***The figure below shows the BT download speed after using Tracker. (Complete list)***  

![BitComet](https://trackerslist.com/img/en-01.png)
![qBittorrentEE](https://trackerslist.com/img/en-06.png)

****

### Updated: 2019-12-05

*These lists are automatically updated every day at 6:30:*

> Better public tracker list is relatively more stable, concise.  
> Complete public tracker list is more in number and theoretically better. but there may be some invalid trackers.  
> **The number of Tracker does not affect the operation of the BT software, so I recommend using the `complete list` to maximize the download speed !**

* **Better public tracker list:** (73 trackers)  
[https://trackerslist.com/best.txt](https://trackerslist.com/best.txt)
* **Complete public tracker list:** (356 trackers)  
[https://trackerslist.com/all.txt](https://trackerslist.com/all.txt)

****

#### Aria2 Format Tracker:

To make it easier for people using Aria2 to add Tracker, I made a separate copy in the Aria2 configuration format. The update is consistent.

* **Better public tracker list:**  
[https://trackerslist.com/best_aria2.txt](https://trackerslist.com/best_aria2.txt)
* **Complete public tracker list:**  
[https://trackerslist.com/all_aria2.txt](https://trackerslist.com/all_aria2.txt)

****

### How to use ?

#### Aria2:

After copying the contents of the Aria2 Format Tracker file, paste it into the `bt-tracker=` tail in the `aria2.conf` configuration file. Example:
``` ini
bt-tracker=http://xxx.xx:80/announce,udp://yyy.yy:80/announce
```
> **Note:** Please delete the old Tracker content before pasting to avoid formatting errors!

****

#### BitComet:  

> ***http://www.bitcomet.com***

![BitComet Tracker](https://trackerslist.com/img/en-03.png)  

****

#### qBittorrent Enhanced Edition:

> ***Github: https://github.com/c0re100/qBittorrent-Enhanced-Edition***  

> Based qBittorrent, added many useful features, such as **subscription Tracker URL** , you can easily use with this project.  

After saving the settings, be sure to **restart qBittorrent Enhanced Edition.**

![qBittorrent Enhanced Edition Tracker](https://trackerslist.com/img/en-05.png)

****

#### qBittorrent:

> ***https://www.qbittorrent.org***

![qBittorrent Tracker](https://trackerslist.com/img/en-04.png)

****

### Tracker Source

This project brings together the following list of public trackers:
* [https://github.com/ngosang/trackerslist](https://github.com/ngosang/trackerslist)
* [https://newtrackon.com/list](https://newtrackon.com/list)
* [https://torrents.io/tracker-list/](https://torrents.io/tracker-list/)
* [http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt](http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt)
* [https://tinytorrent.net/best-torrent-tracker-list-updated/](https://tinytorrent.net/best-torrent-tracker-list-updated/)
* [https://torrenttrackerss.com/torrent-tracker-list/](https://torrenttrackerss.com/torrent-tracker-list/)
* [http://www.torrenttrackerlist.com/torrent-tracker-list](http://www.torrenttrackerlist.com/torrent-tracker-list)

Thanks for these projects!

****

### Contribute

* Do you know more public trackers list? (E.g: ngosang/trackerslist) => [Open a new issue](https://github.com/XIU2/TrackersListCollection/issues/new)

****

### License
The GPL-3.0 License.  
The Anti-996 License.
