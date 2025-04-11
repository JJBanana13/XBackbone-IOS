[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R5R213KNI5)
# XBackbone iOS Shortcut Uploader

This Shortcut allows you to upload any file from the iOS Share Sheet directly to your XBackbone instance.  
After uploading, it:
- Appends `/raw` to the resulting URL
- Copies the final link to your clipboard
- Shows a QR code for quick scanning
---

## ✨ Features

- Upload any file directly via the iOS Share Sheet
- Automatically includes your XBackbone token
- Copies the final `/raw` link to clipboard
- Displays a scannable QR code

---

## ⚙️ Setup

### 1. Import the Shortcut

Download and open the provided `.shortcut` file or [iCloud Shortcut link](https://www.icloud.com/shortcuts/3e2fd031facf4093afff6b99d1f04c23)

### 2. Configure your URL and token

At the **top of the Shortcut**, you’ll find two text fields that must be replaced:

#### a) Replace the upload URL:

From:
```
https://your-xbackbone-instance.com/upload
```
To:
```
https://cdn1.jjbanana13.wtf/upload
```

#### b) Replace the token:

From:
```
token_yourtokenhere
```
To:
```
token_2946f2b60a190d7bb618eaf3ca00aebb
```

You can find your upload token in your XBackbone profile settings.

---

## ✅ Usage

1. Open any file in Files, Safari, Mail, etc.
2. Tap the **Share** button
3. Choose **“XBackbone Uploader”** from the Share Sheet
4. The Shortcut will:
   - Upload the selected file to your server
   - Copy the resulting URL with `/raw` to the clipboard
   - Show a QR code with the file link for quick sharing

---

## Example Output

After uploading a file like `document.pdf`, you will get:

```
https://cdn1.jjbanana13.wtf/file/abc123.pdf/raw
```

This link is:
- Copied to your clipboard
- Shown as a QR code

---

## 🔒 Privacy & Security

- All uploads go directly to **your own** XBackbone instance.
- No third-party services are involved.
- You control access through your own token.

---

## 🛠 Requirements

- iOS 14 or later
- Shortcuts app
- A running [XBackbone](https://github.com/XBackBone/XBackBone) instance
- An active upload token from your XBackbone user profile

---

## License

MIT
This project is open source and free to use.

---
