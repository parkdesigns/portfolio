# i18n g10n of Images with Text

I pointed out problem of images with text in terms of target language (ie internationalization and globalization). Business was not easily convinced of UX/UI impact to people of different language origins.

My recommendation to remove images with text or replace with alternatives was taken, improving the UX/UI.

Improvements

* No image version alternate needed for i18n g10n
  * Fewer image assets
* More readable
* More accessible

## Image i18n / g10n

### Example Image with Text,

"Powerful Backing" text in English

<img src="./img/i18n-g10n-images-w-text/Amex-Powerful-Backing-animated_contrived_2026-08-19.gif" width="80" />

* sourced and derived from [BB_Flip.gif](https://www.americanexpress.com/content/dam/amex/en-us/benefits/membership/elevated-membership/content-assets/blue-box/BB_Flip.gif)

### Example Image without Text,

Above "Powerful Backing" image was replaced with a spinner CSS animation.

<img src="./img/i18n-g10n-images-w-text/WebChat-CM-UI-loading-spinner_cropped_2026-08-24.gif" width="80" />

### Internationalized / Globalized Image

Below is result of all images being internationalized / globalized.

![](./img/i18n-g10n-images-w-text/WebChat-Unauth-chat-window-spinner-Establishing-Secure-Connection_cropped_2026-08-10.png)

## Button i18n / g10n

### Example Button using Image with Text,

"Chat" text in English in image

<img src="./img/i18n-g10n-images-w-text/WebChat-auth-chat-button-pill_cropped_2026-08-10.png" height="50" />

```
<div id="chatInvite" style="display: block;">
    <div class="flex legacy" id="chatButtonInvite" alt="Chat">
        <button>
            <img src="https://icm.aexp-static.com/content/dam/chat/pill-button.jpg" width="80px" />
        </button>
    </div>
</div>
```

### Example Button using CSS,

"チャット" (Chat) text in Japanese in HTML (not in an image)

<img src="./img/i18n-g10n-images-w-text/WebChat-auth-chat-button-pill-ja-JP_contrived_cropped_2026-08-21.png" height="50" />

```
<div id="chatInvite" style="display: block;">
    <div class="flex legacy" id="chatButtonInvite" alt="Chat">
        <button class="btn btn-icon btn-sm icon-hover dls-icon-chat dls-chat-pill dls-chat-pill-blue aa-chat-pill" style="background-color:#00175A;border-radius: 2rem;" aria-label="Chat" tabindex="0">
            <span class="lbl-chat">Chat</span>
        </button>
    </div>
</div>
```
