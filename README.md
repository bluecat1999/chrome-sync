# chrome-sync

A tool that fetching saved password,cookies and bookmarks etc from chrome storages,and merg other chrome resource to local chrome as google-sync

- Support Linux,Windows and MacOS(Now only test under Linux,chrome >80.)

## Why

1. Because someone live in the area with GFW,Google-chrome's upgrade is terrible:you download a .deb file ,when you upgrade chrome,your previous version will be uninstall, and some important thing would be missed and then it would be recreated after new installing ...So you always lost your password,cookies etc encrypted information ,especially in my ubuntu env.

2. If you use chrome in tow or more equiments,Synchronization always is bigger problem,not only google-chrome-sync but also security .

## We Can do by this tool

1. backup db to db
2. backup db to a json file
3. restore db
4. Sync other or local chrome's resource(in a json file) to your local chrome's resource when you want to sync other equiments or reinstall/upgrade chrome(esp in ubuntu)

## final

Remember reboot or logout after you do Sync！

eonjoy it!
