# Installation

1. Clone/download this repository.

2. Copy the files into the [Spicetify Themes folder](https://spicetify.app/docs/development/themes). Run:

**Linux**
```bash
cd spicetify-yakuza
cp -r * ~/.config/spicetify/Themes
```

**MacOS**
```bash
cd spicetify-yakuza
cp -r * ~/.config/spicetify/Themes
```

**Windows**
```powershell
cd spicetify-yakuza
cp * "$(spicetify -c | Split-Path)\Themes\" -Recurse
```

3. Apply theme using spicetify cli
```bash
spicetify config current_theme Yakuza
```
