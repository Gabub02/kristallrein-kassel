# 📱 Social Media Links Anpassen

## 🎯 Wo finde ich die Social Media Links?

Die Social Media Links befinden sich in der `index.html` Datei im **Social Media Bereich** (ca. Zeile 1847-1878).

## 🔧 So änderst du die Links:

### Schritt 1: Datei öffnen
Öffne die Datei `index.html` mit einem Text-Editor.

### Schritt 2: Social Media Section finden
Suche nach dem Kommentar:
```html
<!-- ===== SOCIAL MEDIA SECTION ===== -->
```

### Schritt 3: Links anpassen

#### Instagram Link:
**Aktuell:**
```html
<a href="https://www.instagram.com/kristallrein_kassel" target="_blank" rel="noopener noreferrer" class="platform-card instagram">
```

**So änderst du es:**
- Ersetze `kristallrein_kassel` mit deinem Instagram Nutzernamen
- Beispiel: `https://www.instagram.com/dein_username`

#### Facebook Link:
**Aktuell:**
```html
<a href="https://www.facebook.com/kristallrein.kassel" target="_blank" rel="noopener noreferrer" class="platform-card facebook">
```

**So änderst du es:**
- Ersetze `kristallrein.kassel` mit deiner Facebook Seite
- Beispiel: `https://www.facebook.com/deine.seite`

#### TikTok Link:
**Aktuell:**
```html
<a href="https://www.tiktok.com/@kristallrein_kassel" target="_blank" rel="noopener noreferrer" class="platform-card tiktok">
```

**So änderst du es:**
- Ersetze `kristallrein_kassel` mit deinem TikTok Nutzernamen (mit @)
- Beispiel: `https://www.tiktok.com/@dein_username`

## 📍 Vollständiger Code zum Kopieren & Anpassen:

```html
<div class="social-platforms">
    <!-- Instagram -->
    <a href="https://www.instagram.com/DEIN_INSTAGRAM_USERNAME" target="_blank" rel="noopener noreferrer" class="platform-card instagram">
        <div class="platform-icon">
            <i class="fab fa-instagram"></i>
        </div>
        <h3>Instagram</h3>
        <p>Before/After Bilder & Stories</p>
    </a>

    <!-- Facebook -->
    <a href="https://www.facebook.com/DEINE_FACEBOOK_SEITE" target="_blank" rel="noopener noreferrer" class="platform-card facebook">
        <div class="platform-icon">
            <i class="fab fa-facebook-f"></i>
        </div>
        <h3>Facebook</h3>
        <p>Bewertungen & Updates</p>
    </a>

    <!-- TikTok -->
    <a href="https://www.tiktok.com/@DEIN_TIKTOK_USERNAME" target="_blank" rel="noopener noreferrer" class="platform-card tiktok">
        <div class="platform-icon">
            <i class="fab fa-tiktok"></i>
        </div>
        <h3>TikTok</h3>
        <p>Reinigungs-Videos & Trends</p>
    </a>
</div>
```

## 🚀 Weitere Social Media Plattformen hinzufügen

### YouTube hinzufügen:
```html
<a href="https://www.youtube.com/@DEIN_KANAL" target="_blank" rel="noopener noreferrer" class="platform-card youtube">
    <div class="platform-icon">
        <i class="fab fa-youtube"></i>
    </div>
    <h3>YouTube</h3>
    <p>Video-Tutorials & Vlogs</p>
</a>
```

Füge dann dieses CSS hinzu (im `<style>` Bereich, ca. Zeile 940):
```css
.youtube .platform-icon {
    background: #FF0000;
}
```

### Twitter/X hinzufügen:
```html
<a href="https://twitter.com/DEIN_USERNAME" target="_blank" rel="noopener noreferrer" class="platform-card twitter">
    <div class="platform-icon">
        <i class="fab fa-twitter"></i>
    </div>
    <h3>Twitter / X</h3>
    <p>News & Updates</p>
</a>
```

CSS für Twitter/X:
```css
.twitter .platform-icon {
    background: #1DA1F2;
}
```

### LinkedIn hinzufügen:
```html
<a href="https://www.linkedin.com/company/DEINE_FIRMA" target="_blank" rel="noopener noreferrer" class="platform-card linkedin">
    <div class="platform-icon">
        <i class="fab fa-linkedin-in"></i>
    </div>
    <h3>LinkedIn</h3>
    <p>Business Updates</p>
</a>
```

CSS für LinkedIn:
```css
.linkedin .platform-icon {
    background: #0077B5;
}
```

## 💡 Wie finde ich meine Social Media URLs?

### Instagram:
1. Öffne dein Instagram Profil
2. Die URL ist: `https://www.instagram.com/DEIN_USERNAME`
3. Kopiere den Username und ersetze ihn im Code

### Facebook:
1. Gehe zu deiner Facebook Seite
2. Die URL steht in der Adressleiste
3. Kopiere die komplette URL und ersetze sie im Code

### TikTok:
1. Öffne dein TikTok Profil
2. Tippe auf "Profil teilen"
3. Kopiere den Link (z.B. `https://www.tiktok.com/@username`)
4. Ersetze ihn im Code

## ✅ Testen

Nach dem Ändern der Links:
1. Speichere die `index.html` Datei
2. Öffne die Website im Browser
3. Klicke auf die Social Media Symbole
4. Überprüfe, ob sie zu den richtigen Profilen führen

## 🔧 Wichtige Attribute erklärt

```html
target="_blank"
```
→ Öffnet den Link in einem neuen Tab

```html
rel="noopener noreferrer"
```
→ Sicherheitsfeature für externe Links

```html
class="platform-card instagram"
```
→ Styling für die Karte (Farben, Hover-Effekte)

## 📧 Support

Bei Fragen:
- E-Mail: info@kristallrein-kassel.de
- Telefon: +49 1515 1816181
