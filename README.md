# Chrome Apps for TechNews

![Chrome Apps logo](images/chrome_apps.png)

## Installation

### 1. Clone this repository and see its contents.
Open a terminal give the following command:

```bash
$ git clone https://github.com/enogrob/chromeapps-webtools.git
```

As we can see a subdirectory is created for each TechNews app.

```bash
$ ls -la
total 984
drwxr-xr-x@   9 enogrob  staff    306 Oct  9 12:31 .
drwxr-xr-x@ 304 enogrob  staff  10336 Oct  9 17:00 ..
-rw-r--r--@   1 enogrob  staff   6148 Oct  5 23:25 .DS_Store
drwxr-xr-x   13 enogrob  staff    442 Oct  9 13:53 .git
-rw-r--r--@   1 enogrob  staff      6 Aug  1  2016 .gitignore
-rw-r--r--@   1 enogrob  staff      0 Nov 17  2016 Icon?
-rw-r--r--@   1 enogrob  staff    964 Oct  9 17:13 README.md
drwxr-xr-x    5 enogrob  staff    170 Oct  9 13:51 apps
drwxr-xr-x    4 enogrob  staff    136 Oct  9 12:25 images

$ tree -L 1 apps/
apps
├── TechNews-DZone
├── TechNews-HN
└── TechNews-InfoQ

21 directories, 0 files
```

### 2. Open Chrome with the following url:
In order to load the `Chrome Apps` for TechNews, check `Developer Mode` and press `Load unpacked extension...` to load each App selecting its corresponding directory inside `apps` e.g. `TechNews-InfoQ`, and then repeat that for the wanted apps. Or just drag and drop the app folder on the [Extensions page](chrome://extensions).

[chrome://extensions](chrome://extensions)

### 3. After load the Chrome Apps wanted for TechNews, Chrome will look like the screenshot below:

![Chrome screenshot](images/chrome_screenshot1.png)