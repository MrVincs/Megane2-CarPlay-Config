# Megane2-CarPlay-Config
Raspberry, Android, CarPlay config and files. 
```

Git
└── Megane2-CarPlay-Config
    │
    │
    ├── Android
    │   ├── Application
    │   │   └── AirPlay
    │   │       └── autoplaybox.apk        -> Move to /sdcard/Download 	Action; Intall Apk
    │   ├── Overlays
    │   │   └── Fix
    │   │       └── 91fixoverlays          -> Move to /etc/init.d       Action; None
    │   └── Renault
    │       ├── BootAnimation
    │       │   └── bootanimation.zip      -> Move to /system/media     Action; Rename original file: bootanimation.zip.backup
    │       └── Wallpaper
    │           └── Renault.png            -> Move to /sdcard/Download  Action; Set as Android background
    │
    │
    └── Raspberry
        ├── config.txt                     -> Move to /boot/            Action; Rename original file: config.txt.backup
        └── resolution.txt                 -> Move to /boot/            Action; Rename original file: resolution.txt.backup
```
