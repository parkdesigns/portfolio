# American Express Icons


```
ls *' '* | awk '{orig=$0; gsub(/ /, "_"); print "mv -n -- \"" orig "\" \"" $0 "\""}' | bash                                              
```

```
for file in dls*.svg; do
  sips -s format png "$file" -o "${file%.svg}.png" -Z 130
done
```

```
ls dls*.png | sed -E 's|(.*).png|<img alt="\1" src="./img/Amex/&" height="30px" />  \1 \[SVG\]\(./img/Amex/\1.svg\)<br />|'
```

```
ls *.png | sed -E 's|(.*).png|    <div>\n        <img alt="\1" src="./img/Amex/&" />\n        <div>\n            <a href="./img/Amex/\1.svg">SVG</a>\n            <div class="img-title">\1</div>\n        </div>\n    </div>|' > html-of-images.txt
```

## Icons

<style>
  div.icon-table {
    width: 100%;
    overflow: auto;
  }

  .icon-table > div {
    float: left;
    width:220px;
    margin-right: 10px;
    margin-bottom: 10px;
  }

  .icon-table div img {
    float: left;
    max-width: 40px;
    margin-right: 8px;
    max-height: 40px;
  }

  .icon-table > div > div {
    float: left;
  }

  .icon-table div.img-title  {
    font-size: 8px;
  }
</style>

<div class="icon-table">
    <div>
        <img alt="dls-glyph-account" src="./img/Amex/dls-glyph-account.png" />
        <div>
            <a href="./img/Amex/dls-glyph-account.svg">SVG</a>
            <div class="img-title">dls-glyph-account</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-cancel-circle" src="./img/Amex/dls-glyph-cancel-circle.png" />
        <div>
            <a href="./img/Amex/dls-glyph-cancel-circle.svg">SVG</a>
            <div class="img-title">dls-glyph-cancel-circle</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-check" src="./img/Amex/dls-glyph-check.png" />
        <div>
            <a href="./img/Amex/dls-glyph-check.svg">SVG</a>
            <div class="img-title">dls-glyph-check</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-close" src="./img/Amex/dls-glyph-close.png" />
        <div>
            <a href="./img/Amex/dls-glyph-close.svg">SVG</a>
            <div class="img-title">dls-glyph-close</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-double-left" src="./img/Amex/dls-glyph-double-left.png" />
        <div>
            <a href="./img/Amex/dls-glyph-double-left.svg">SVG</a>
            <div class="img-title">dls-glyph-double-left</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-double-right" src="./img/Amex/dls-glyph-double-right.png" />
        <div>
            <a href="./img/Amex/dls-glyph-double-right.svg">SVG</a>
            <div class="img-title">dls-glyph-double-right</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-down" src="./img/Amex/dls-glyph-down.png" />
        <div>
            <a href="./img/Amex/dls-glyph-down.svg">SVG</a>
            <div class="img-title">dls-glyph-down</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-equal" src="./img/Amex/dls-glyph-equal.png" />
        <div>
            <a href="./img/Amex/dls-glyph-equal.svg">SVG</a>
            <div class="img-title">dls-glyph-equal</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-favorite" src="./img/Amex/dls-glyph-favorite.png" />
        <div>
            <a href="./img/Amex/dls-glyph-favorite.svg">SVG</a>
            <div class="img-title">dls-glyph-favorite</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-info" src="./img/Amex/dls-glyph-info.png" />
        <div>
            <a href="./img/Amex/dls-glyph-info.svg">SVG</a>
            <div class="img-title">dls-glyph-info</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-left" src="./img/Amex/dls-glyph-left.png" />
        <div>
            <a href="./img/Amex/dls-glyph-left.svg">SVG</a>
            <div class="img-title">dls-glyph-left</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-link-out" src="./img/Amex/dls-glyph-link-out.png" />
        <div>
            <a href="./img/Amex/dls-glyph-link-out.svg">SVG</a>
            <div class="img-title">dls-glyph-link-out</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-minus" src="./img/Amex/dls-glyph-minus.png" />
        <div>
            <a href="./img/Amex/dls-glyph-minus.svg">SVG</a>
            <div class="img-title">dls-glyph-minus</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-nav" src="./img/Amex/dls-glyph-nav.png" />
        <div>
            <a href="./img/Amex/dls-glyph-nav.svg">SVG</a>
            <div class="img-title">dls-glyph-nav</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-plus-circle" src="./img/Amex/dls-glyph-plus-circle.png" />
        <div>
            <a href="./img/Amex/dls-glyph-plus-circle.svg">SVG</a>
            <div class="img-title">dls-glyph-plus-circle</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-plus" src="./img/Amex/dls-glyph-plus.png" />
        <div>
            <a href="./img/Amex/dls-glyph-plus.svg">SVG</a>
            <div class="img-title">dls-glyph-plus</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-right" src="./img/Amex/dls-glyph-right.png" />
        <div>
            <a href="./img/Amex/dls-glyph-right.svg">SVG</a>
            <div class="img-title">dls-glyph-right</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-sort-down" src="./img/Amex/dls-glyph-sort-down.png" />
        <div>
            <a href="./img/Amex/dls-glyph-sort-down.svg">SVG</a>
            <div class="img-title">dls-glyph-sort-down</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-sort-up" src="./img/Amex/dls-glyph-sort-up.png" />
        <div>
            <a href="./img/Amex/dls-glyph-sort-up.svg">SVG</a>
            <div class="img-title">dls-glyph-sort-up</div>
        </div>
    </div>
    <div>
        <img alt="dls-glyph-up" src="./img/Amex/dls-glyph-up.png" />
        <div>
            <a href="./img/Amex/dls-glyph-up.svg">SVG</a>
            <div class="img-title">dls-glyph-up</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-accessibility-filled" src="./img/Amex/dls-icon-accessibility-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-accessibility-filled.svg">SVG</a>
            <div class="img-title">dls-icon-accessibility-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-accessibility" src="./img/Amex/dls-icon-accessibility.png" />
        <div>
            <a href="./img/Amex/dls-icon-accessibility.svg">SVG</a>
            <div class="img-title">dls-icon-accessibility</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-account-filled" src="./img/Amex/dls-icon-account-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-account-filled.svg">SVG</a>
            <div class="img-title">dls-icon-account-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-account" src="./img/Amex/dls-icon-account.png" />
        <div>
            <a href="./img/Amex/dls-icon-account.svg">SVG</a>
            <div class="img-title">dls-icon-account</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-activity-filled" src="./img/Amex/dls-icon-activity-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-activity-filled.svg">SVG</a>
            <div class="img-title">dls-icon-activity-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-activity" src="./img/Amex/dls-icon-activity.png" />
        <div>
            <a href="./img/Amex/dls-icon-activity.svg">SVG</a>
            <div class="img-title">dls-icon-activity</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-airplane-filled" src="./img/Amex/dls-icon-airplane-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-airplane-filled.svg">SVG</a>
            <div class="img-title">dls-icon-airplane-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-airplane" src="./img/Amex/dls-icon-airplane.png" />
        <div>
            <a href="./img/Amex/dls-icon-airplane.svg">SVG</a>
            <div class="img-title">dls-icon-airplane</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-alert-filled" src="./img/Amex/dls-icon-alert-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-alert-filled.svg">SVG</a>
            <div class="img-title">dls-icon-alert-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-alert" src="./img/Amex/dls-icon-alert.png" />
        <div>
            <a href="./img/Amex/dls-icon-alert.svg">SVG</a>
            <div class="img-title">dls-icon-alert</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-archive-filled" src="./img/Amex/dls-icon-archive-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-archive-filled.svg">SVG</a>
            <div class="img-title">dls-icon-archive-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-archive" src="./img/Amex/dls-icon-archive.png" />
        <div>
            <a href="./img/Amex/dls-icon-archive.svg">SVG</a>
            <div class="img-title">dls-icon-archive</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-attach-filled" src="./img/Amex/dls-icon-attach-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-attach-filled.svg">SVG</a>
            <div class="img-title">dls-icon-attach-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-attach" src="./img/Amex/dls-icon-attach.png" />
        <div>
            <a href="./img/Amex/dls-icon-attach.svg">SVG</a>
            <div class="img-title">dls-icon-attach</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-autopay-filled" src="./img/Amex/dls-icon-autopay-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-autopay-filled.svg">SVG</a>
            <div class="img-title">dls-icon-autopay-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-autopay" src="./img/Amex/dls-icon-autopay.png" />
        <div>
            <a href="./img/Amex/dls-icon-autopay.svg">SVG</a>
            <div class="img-title">dls-icon-autopay</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-baht-autopay-filled" src="./img/Amex/dls-icon-baht-autopay-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-baht-autopay-filled.svg">SVG</a>
            <div class="img-title">dls-icon-baht-autopay-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-baht-autopay" src="./img/Amex/dls-icon-baht-autopay.png" />
        <div>
            <a href="./img/Amex/dls-icon-baht-autopay.svg">SVG</a>
            <div class="img-title">dls-icon-baht-autopay</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-baht-cashback-filled" src="./img/Amex/dls-icon-baht-cashback-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-baht-cashback-filled.svg">SVG</a>
            <div class="img-title">dls-icon-baht-cashback-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-baht-cashback" src="./img/Amex/dls-icon-baht-cashback.png" />
        <div>
            <a href="./img/Amex/dls-icon-baht-cashback.svg">SVG</a>
            <div class="img-title">dls-icon-baht-cashback</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-baht-filled" src="./img/Amex/dls-icon-baht-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-baht-filled.svg">SVG</a>
            <div class="img-title">dls-icon-baht-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-baht" src="./img/Amex/dls-icon-baht.png" />
        <div>
            <a href="./img/Amex/dls-icon-baht.svg">SVG</a>
            <div class="img-title">dls-icon-baht</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bank-app-filled" src="./img/Amex/dls-icon-bank-app-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-bank-app-filled.svg">SVG</a>
            <div class="img-title">dls-icon-bank-app-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bank-app" src="./img/Amex/dls-icon-bank-app.png" />
        <div>
            <a href="./img/Amex/dls-icon-bank-app.svg">SVG</a>
            <div class="img-title">dls-icon-bank-app</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bank-filled" src="./img/Amex/dls-icon-bank-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-bank-filled.svg">SVG</a>
            <div class="img-title">dls-icon-bank-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bank-mobile-filled" src="./img/Amex/dls-icon-bank-mobile-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-bank-mobile-filled.svg">SVG</a>
            <div class="img-title">dls-icon-bank-mobile-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bank-mobile-landscape-filled" src="./img/Amex/dls-icon-bank-mobile-landscape-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-bank-mobile-landscape-filled.svg">SVG</a>
            <div class="img-title">dls-icon-bank-mobile-landscape-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bank-mobile-landscape" src="./img/Amex/dls-icon-bank-mobile-landscape.png" />
        <div>
            <a href="./img/Amex/dls-icon-bank-mobile-landscape.svg">SVG</a>
            <div class="img-title">dls-icon-bank-mobile-landscape</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bank-mobile" src="./img/Amex/dls-icon-bank-mobile.png" />
        <div>
            <a href="./img/Amex/dls-icon-bank-mobile.svg">SVG</a>
            <div class="img-title">dls-icon-bank-mobile</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bank" src="./img/Amex/dls-icon-bank.png" />
        <div>
            <a href="./img/Amex/dls-icon-bank.svg">SVG</a>
            <div class="img-title">dls-icon-bank</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bar-chart-filled" src="./img/Amex/dls-icon-bar-chart-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-bar-chart-filled.svg">SVG</a>
            <div class="img-title">dls-icon-bar-chart-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bar-chart" src="./img/Amex/dls-icon-bar-chart.png" />
        <div>
            <a href="./img/Amex/dls-icon-bar-chart.svg">SVG</a>
            <div class="img-title">dls-icon-bar-chart</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-billing-filled" src="./img/Amex/dls-icon-billing-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-billing-filled.svg">SVG</a>
            <div class="img-title">dls-icon-billing-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-billing" src="./img/Amex/dls-icon-billing.png" />
        <div>
            <a href="./img/Amex/dls-icon-billing.svg">SVG</a>
            <div class="img-title">dls-icon-billing</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bookmark-filled" src="./img/Amex/dls-icon-bookmark-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-bookmark-filled.svg">SVG</a>
            <div class="img-title">dls-icon-bookmark-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-bookmark" src="./img/Amex/dls-icon-bookmark.png" />
        <div>
            <a href="./img/Amex/dls-icon-bookmark.svg">SVG</a>
            <div class="img-title">dls-icon-bookmark</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-business-filled" src="./img/Amex/dls-icon-business-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-business-filled.svg">SVG</a>
            <div class="img-title">dls-icon-business-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-business-services-filled" src="./img/Amex/dls-icon-business-services-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-business-services-filled.svg">SVG</a>
            <div class="img-title">dls-icon-business-services-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-business-services" src="./img/Amex/dls-icon-business-services.png" />
        <div>
            <a href="./img/Amex/dls-icon-business-services.svg">SVG</a>
            <div class="img-title">dls-icon-business-services</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-business" src="./img/Amex/dls-icon-business.png" />
        <div>
            <a href="./img/Amex/dls-icon-business.svg">SVG</a>
            <div class="img-title">dls-icon-business</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-calculator-filled" src="./img/Amex/dls-icon-calculator-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-calculator-filled.svg">SVG</a>
            <div class="img-title">dls-icon-calculator-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-calculator" src="./img/Amex/dls-icon-calculator.png" />
        <div>
            <a href="./img/Amex/dls-icon-calculator.svg">SVG</a>
            <div class="img-title">dls-icon-calculator</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-calendar-filled" src="./img/Amex/dls-icon-calendar-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-calendar-filled.svg">SVG</a>
            <div class="img-title">dls-icon-calendar-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-calendar" src="./img/Amex/dls-icon-calendar.png" />
        <div>
            <a href="./img/Amex/dls-icon-calendar.svg">SVG</a>
            <div class="img-title">dls-icon-calendar</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-camera-filled" src="./img/Amex/dls-icon-camera-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-camera-filled.svg">SVG</a>
            <div class="img-title">dls-icon-camera-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-camera" src="./img/Amex/dls-icon-camera.png" />
        <div>
            <a href="./img/Amex/dls-icon-camera.svg">SVG</a>
            <div class="img-title">dls-icon-camera</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cancel-circle-filled" src="./img/Amex/dls-icon-cancel-circle-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-cancel-circle-filled.svg">SVG</a>
            <div class="img-title">dls-icon-cancel-circle-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cancel-circle" src="./img/Amex/dls-icon-cancel-circle.png" />
        <div>
            <a href="./img/Amex/dls-icon-cancel-circle.svg">SVG</a>
            <div class="img-title">dls-icon-cancel-circle</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-captions-off-filled" src="./img/Amex/dls-icon-captions-off-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-captions-off-filled.svg">SVG</a>
            <div class="img-title">dls-icon-captions-off-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-captions-off" src="./img/Amex/dls-icon-captions-off.png" />
        <div>
            <a href="./img/Amex/dls-icon-captions-off.svg">SVG</a>
            <div class="img-title">dls-icon-captions-off</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-captions-on-filled" src="./img/Amex/dls-icon-captions-on-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-captions-on-filled.svg">SVG</a>
            <div class="img-title">dls-icon-captions-on-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-captions-on" src="./img/Amex/dls-icon-captions-on.png" />
        <div>
            <a href="./img/Amex/dls-icon-captions-on.svg">SVG</a>
            <div class="img-title">dls-icon-captions-on</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-car-filled" src="./img/Amex/dls-icon-car-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-car-filled.svg">SVG</a>
            <div class="img-title">dls-icon-car-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-car" src="./img/Amex/dls-icon-car.png" />
        <div>
            <a href="./img/Amex/dls-icon-car.svg">SVG</a>
            <div class="img-title">dls-icon-car</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card-benefit-filled" src="./img/Amex/dls-icon-card-benefit-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-card-benefit-filled.svg">SVG</a>
            <div class="img-title">dls-icon-card-benefit-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card-benefit" src="./img/Amex/dls-icon-card-benefit.png" />
        <div>
            <a href="./img/Amex/dls-icon-card-benefit.svg">SVG</a>
            <div class="img-title">dls-icon-card-benefit</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card-contactless-filled" src="./img/Amex/dls-icon-card-contactless-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-card-contactless-filled.svg">SVG</a>
            <div class="img-title">dls-icon-card-contactless-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card-contactless" src="./img/Amex/dls-icon-card-contactless.png" />
        <div>
            <a href="./img/Amex/dls-icon-card-contactless.svg">SVG</a>
            <div class="img-title">dls-icon-card-contactless</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card-filled" src="./img/Amex/dls-icon-card-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-card-filled.svg">SVG</a>
            <div class="img-title">dls-icon-card-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card-insert-filled" src="./img/Amex/dls-icon-card-insert-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-card-insert-filled.svg">SVG</a>
            <div class="img-title">dls-icon-card-insert-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card-insert" src="./img/Amex/dls-icon-card-insert.png" />
        <div>
            <a href="./img/Amex/dls-icon-card-insert.svg">SVG</a>
            <div class="img-title">dls-icon-card-insert</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card-swipe-filled" src="./img/Amex/dls-icon-card-swipe-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-card-swipe-filled.svg">SVG</a>
            <div class="img-title">dls-icon-card-swipe-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card-swipe" src="./img/Amex/dls-icon-card-swipe.png" />
        <div>
            <a href="./img/Amex/dls-icon-card-swipe.svg">SVG</a>
            <div class="img-title">dls-icon-card-swipe</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card-tap-filled" src="./img/Amex/dls-icon-card-tap-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-card-tap-filled.svg">SVG</a>
            <div class="img-title">dls-icon-card-tap-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card-tap" src="./img/Amex/dls-icon-card-tap.png" />
        <div>
            <a href="./img/Amex/dls-icon-card-tap.svg">SVG</a>
            <div class="img-title">dls-icon-card-tap</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-card" src="./img/Amex/dls-icon-card.png" />
        <div>
            <a href="./img/Amex/dls-icon-card.svg">SVG</a>
            <div class="img-title">dls-icon-card</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cards-contactless-filled" src="./img/Amex/dls-icon-cards-contactless-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-cards-contactless-filled.svg">SVG</a>
            <div class="img-title">dls-icon-cards-contactless-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cards-contactless" src="./img/Amex/dls-icon-cards-contactless.png" />
        <div>
            <a href="./img/Amex/dls-icon-cards-contactless.svg">SVG</a>
            <div class="img-title">dls-icon-cards-contactless</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cards-filled" src="./img/Amex/dls-icon-cards-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-cards-filled.svg">SVG</a>
            <div class="img-title">dls-icon-cards-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cards" src="./img/Amex/dls-icon-cards.png" />
        <div>
            <a href="./img/Amex/dls-icon-cards.svg">SVG</a>
            <div class="img-title">dls-icon-cards</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cart-filled" src="./img/Amex/dls-icon-cart-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-cart-filled.svg">SVG</a>
            <div class="img-title">dls-icon-cart-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cart" src="./img/Amex/dls-icon-cart.png" />
        <div>
            <a href="./img/Amex/dls-icon-cart.svg">SVG</a>
            <div class="img-title">dls-icon-cart</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cashback-filled" src="./img/Amex/dls-icon-cashback-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-cashback-filled.svg">SVG</a>
            <div class="img-title">dls-icon-cashback-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cashback" src="./img/Amex/dls-icon-cashback.png" />
        <div>
            <a href="./img/Amex/dls-icon-cashback.svg">SVG</a>
            <div class="img-title">dls-icon-cashback</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cd-filled" src="./img/Amex/dls-icon-cd-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-cd-filled.svg">SVG</a>
            <div class="img-title">dls-icon-cd-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cd" src="./img/Amex/dls-icon-cd.png" />
        <div>
            <a href="./img/Amex/dls-icon-cd.svg">SVG</a>
            <div class="img-title">dls-icon-cd</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-change-filled" src="./img/Amex/dls-icon-change-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-change-filled.svg">SVG</a>
            <div class="img-title">dls-icon-change-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-change" src="./img/Amex/dls-icon-change.png" />
        <div>
            <a href="./img/Amex/dls-icon-change.svg">SVG</a>
            <div class="img-title">dls-icon-change</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-chat-filled" src="./img/Amex/dls-icon-chat-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-chat-filled.svg">SVG</a>
            <div class="img-title">dls-icon-chat-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-chat" src="./img/Amex/dls-icon-chat.png" />
        <div>
            <a href="./img/Amex/dls-icon-chat.svg">SVG</a>
            <div class="img-title">dls-icon-chat</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-check-banking-filled" src="./img/Amex/dls-icon-check-banking-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-check-banking-filled.svg">SVG</a>
            <div class="img-title">dls-icon-check-banking-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-check-banking" src="./img/Amex/dls-icon-check-banking.png" />
        <div>
            <a href="./img/Amex/dls-icon-check-banking.svg">SVG</a>
            <div class="img-title">dls-icon-check-banking</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-check-filled" src="./img/Amex/dls-icon-check-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-check-filled.svg">SVG</a>
            <div class="img-title">dls-icon-check-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-check-scan-filled" src="./img/Amex/dls-icon-check-scan-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-check-scan-filled.svg">SVG</a>
            <div class="img-title">dls-icon-check-scan-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-check-scan" src="./img/Amex/dls-icon-check-scan.png" />
        <div>
            <a href="./img/Amex/dls-icon-check-scan.svg">SVG</a>
            <div class="img-title">dls-icon-check-scan</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-check" src="./img/Amex/dls-icon-check.png" />
        <div>
            <a href="./img/Amex/dls-icon-check.svg">SVG</a>
            <div class="img-title">dls-icon-check</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-chip-filled" src="./img/Amex/dls-icon-chip-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-chip-filled.svg">SVG</a>
            <div class="img-title">dls-icon-chip-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-chip" src="./img/Amex/dls-icon-chip.png" />
        <div>
            <a href="./img/Amex/dls-icon-chip.svg">SVG</a>
            <div class="img-title">dls-icon-chip</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-close-filled" src="./img/Amex/dls-icon-close-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-close-filled.svg">SVG</a>
            <div class="img-title">dls-icon-close-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-close" src="./img/Amex/dls-icon-close.png" />
        <div>
            <a href="./img/Amex/dls-icon-close.svg">SVG</a>
            <div class="img-title">dls-icon-close</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-collapse-filled" src="./img/Amex/dls-icon-collapse-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-collapse-filled.svg">SVG</a>
            <div class="img-title">dls-icon-collapse-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-collapse" src="./img/Amex/dls-icon-collapse.png" />
        <div>
            <a href="./img/Amex/dls-icon-collapse.svg">SVG</a>
            <div class="img-title">dls-icon-collapse</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-concierge-filled" src="./img/Amex/dls-icon-concierge-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-concierge-filled.svg">SVG</a>
            <div class="img-title">dls-icon-concierge-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-concierge" src="./img/Amex/dls-icon-concierge.png" />
        <div>
            <a href="./img/Amex/dls-icon-concierge.svg">SVG</a>
            <div class="img-title">dls-icon-concierge</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-construction-filled" src="./img/Amex/dls-icon-construction-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-construction-filled.svg">SVG</a>
            <div class="img-title">dls-icon-construction-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-construction" src="./img/Amex/dls-icon-construction.png" />
        <div>
            <a href="./img/Amex/dls-icon-construction.svg">SVG</a>
            <div class="img-title">dls-icon-construction</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-copy-filled" src="./img/Amex/dls-icon-copy-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-copy-filled.svg">SVG</a>
            <div class="img-title">dls-icon-copy-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-copy" src="./img/Amex/dls-icon-copy.png" />
        <div>
            <a href="./img/Amex/dls-icon-copy.svg">SVG</a>
            <div class="img-title">dls-icon-copy</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-credit-score-filled" src="./img/Amex/dls-icon-credit-score-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-credit-score-filled.svg">SVG</a>
            <div class="img-title">dls-icon-credit-score-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-credit-score" src="./img/Amex/dls-icon-credit-score.png" />
        <div>
            <a href="./img/Amex/dls-icon-credit-score.svg">SVG</a>
            <div class="img-title">dls-icon-credit-score</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cruise-ship-filled" src="./img/Amex/dls-icon-cruise-ship-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-cruise-ship-filled.svg">SVG</a>
            <div class="img-title">dls-icon-cruise-ship-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-cruise-ship" src="./img/Amex/dls-icon-cruise-ship.png" />
        <div>
            <a href="./img/Amex/dls-icon-cruise-ship.svg">SVG</a>
            <div class="img-title">dls-icon-cruise-ship</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-data-protection-filled" src="./img/Amex/dls-icon-data-protection-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-data-protection-filled.svg">SVG</a>
            <div class="img-title">dls-icon-data-protection-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-data-protection" src="./img/Amex/dls-icon-data-protection.png" />
        <div>
            <a href="./img/Amex/dls-icon-data-protection.svg">SVG</a>
            <div class="img-title">dls-icon-data-protection</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-declined-filled" src="./img/Amex/dls-icon-declined-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-declined-filled.svg">SVG</a>
            <div class="img-title">dls-icon-declined-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-declined" src="./img/Amex/dls-icon-declined.png" />
        <div>
            <a href="./img/Amex/dls-icon-declined.svg">SVG</a>
            <div class="img-title">dls-icon-declined</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-dental-filled" src="./img/Amex/dls-icon-dental-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-dental-filled.svg">SVG</a>
            <div class="img-title">dls-icon-dental-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-dental" src="./img/Amex/dls-icon-dental.png" />
        <div>
            <a href="./img/Amex/dls-icon-dental.svg">SVG</a>
            <div class="img-title">dls-icon-dental</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-desktop-filled" src="./img/Amex/dls-icon-desktop-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-desktop-filled.svg">SVG</a>
            <div class="img-title">dls-icon-desktop-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-desktop" src="./img/Amex/dls-icon-desktop.png" />
        <div>
            <a href="./img/Amex/dls-icon-desktop.svg">SVG</a>
            <div class="img-title">dls-icon-desktop</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-dining-filled" src="./img/Amex/dls-icon-dining-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-dining-filled.svg">SVG</a>
            <div class="img-title">dls-icon-dining-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-dining" src="./img/Amex/dls-icon-dining.png" />
        <div>
            <a href="./img/Amex/dls-icon-dining.svg">SVG</a>
            <div class="img-title">dls-icon-dining</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-direct-deposit-filled" src="./img/Amex/dls-icon-direct-deposit-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-direct-deposit-filled.svg">SVG</a>
            <div class="img-title">dls-icon-direct-deposit-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-direct-deposit" src="./img/Amex/dls-icon-direct-deposit.png" />
        <div>
            <a href="./img/Amex/dls-icon-direct-deposit.svg">SVG</a>
            <div class="img-title">dls-icon-direct-deposit</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-direction-filled" src="./img/Amex/dls-icon-direction-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-direction-filled.svg">SVG</a>
            <div class="img-title">dls-icon-direction-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-direction" src="./img/Amex/dls-icon-direction.png" />
        <div>
            <a href="./img/Amex/dls-icon-direction.svg">SVG</a>
            <div class="img-title">dls-icon-direction</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-document-filled" src="./img/Amex/dls-icon-document-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-document-filled.svg">SVG</a>
            <div class="img-title">dls-icon-document-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-document" src="./img/Amex/dls-icon-document.png" />
        <div>
            <a href="./img/Amex/dls-icon-document.svg">SVG</a>
            <div class="img-title">dls-icon-document</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-dollar-filled" src="./img/Amex/dls-icon-dollar-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-dollar-filled.svg">SVG</a>
            <div class="img-title">dls-icon-dollar-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-dollar" src="./img/Amex/dls-icon-dollar.png" />
        <div>
            <a href="./img/Amex/dls-icon-dollar.svg">SVG</a>
            <div class="img-title">dls-icon-dollar</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-donate-filled" src="./img/Amex/dls-icon-donate-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-donate-filled.svg">SVG</a>
            <div class="img-title">dls-icon-donate-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-donate" src="./img/Amex/dls-icon-donate.png" />
        <div>
            <a href="./img/Amex/dls-icon-donate.svg">SVG</a>
            <div class="img-title">dls-icon-donate</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-down-filled" src="./img/Amex/dls-icon-down-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-down-filled.svg">SVG</a>
            <div class="img-title">dls-icon-down-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-down" src="./img/Amex/dls-icon-down.png" />
        <div>
            <a href="./img/Amex/dls-icon-down.svg">SVG</a>
            <div class="img-title">dls-icon-down</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-download-filled" src="./img/Amex/dls-icon-download-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-download-filled.svg">SVG</a>
            <div class="img-title">dls-icon-download-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-download" src="./img/Amex/dls-icon-download.png" />
        <div>
            <a href="./img/Amex/dls-icon-download.svg">SVG</a>
            <div class="img-title">dls-icon-download</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-e-check-filled" src="./img/Amex/dls-icon-e-check-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-e-check-filled.svg">SVG</a>
            <div class="img-title">dls-icon-e-check-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-e-check" src="./img/Amex/dls-icon-e-check.png" />
        <div>
            <a href="./img/Amex/dls-icon-e-check.svg">SVG</a>
            <div class="img-title">dls-icon-e-check</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-edit-filled" src="./img/Amex/dls-icon-edit-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-edit-filled.svg">SVG</a>
            <div class="img-title">dls-icon-edit-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-edit" src="./img/Amex/dls-icon-edit.png" />
        <div>
            <a href="./img/Amex/dls-icon-edit.svg">SVG</a>
            <div class="img-title">dls-icon-edit</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-email-filled" src="./img/Amex/dls-icon-email-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-email-filled.svg">SVG</a>
            <div class="img-title">dls-icon-email-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-email" src="./img/Amex/dls-icon-email.png" />
        <div>
            <a href="./img/Amex/dls-icon-email.svg">SVG</a>
            <div class="img-title">dls-icon-email</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-entertainment-filled" src="./img/Amex/dls-icon-entertainment-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-entertainment-filled.svg">SVG</a>
            <div class="img-title">dls-icon-entertainment-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-entertainment" src="./img/Amex/dls-icon-entertainment.png" />
        <div>
            <a href="./img/Amex/dls-icon-entertainment.svg">SVG</a>
            <div class="img-title">dls-icon-entertainment</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-error-triangle" src="./img/Amex/dls-icon-error-triangle.png" />
        <div>
            <a href="./img/Amex/dls-icon-error-triangle.svg">SVG</a>
            <div class="img-title">dls-icon-error-triangle</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-euro-autopay-filled" src="./img/Amex/dls-icon-euro-autopay-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-euro-autopay-filled.svg">SVG</a>
            <div class="img-title">dls-icon-euro-autopay-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-euro-autopay" src="./img/Amex/dls-icon-euro-autopay.png" />
        <div>
            <a href="./img/Amex/dls-icon-euro-autopay.svg">SVG</a>
            <div class="img-title">dls-icon-euro-autopay</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-euro-cashback-filled" src="./img/Amex/dls-icon-euro-cashback-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-euro-cashback-filled.svg">SVG</a>
            <div class="img-title">dls-icon-euro-cashback-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-euro-cashback" src="./img/Amex/dls-icon-euro-cashback.png" />
        <div>
            <a href="./img/Amex/dls-icon-euro-cashback.svg">SVG</a>
            <div class="img-title">dls-icon-euro-cashback</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-euro-filled" src="./img/Amex/dls-icon-euro-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-euro-filled.svg">SVG</a>
            <div class="img-title">dls-icon-euro-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-euro" src="./img/Amex/dls-icon-euro.png" />
        <div>
            <a href="./img/Amex/dls-icon-euro.svg">SVG</a>
            <div class="img-title">dls-icon-euro</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-expand-filled" src="./img/Amex/dls-icon-expand-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-expand-filled.svg">SVG</a>
            <div class="img-title">dls-icon-expand-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-expand" src="./img/Amex/dls-icon-expand.png" />
        <div>
            <a href="./img/Amex/dls-icon-expand.svg">SVG</a>
            <div class="img-title">dls-icon-expand</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-faceid-filled" src="./img/Amex/dls-icon-faceid-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-faceid-filled.svg">SVG</a>
            <div class="img-title">dls-icon-faceid-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-faceid" src="./img/Amex/dls-icon-faceid.png" />
        <div>
            <a href="./img/Amex/dls-icon-faceid.svg">SVG</a>
            <div class="img-title">dls-icon-faceid</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-favorite-filled" src="./img/Amex/dls-icon-favorite-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-favorite-filled.svg">SVG</a>
            <div class="img-title">dls-icon-favorite-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-favorite" src="./img/Amex/dls-icon-favorite.png" />
        <div>
            <a href="./img/Amex/dls-icon-favorite.svg">SVG</a>
            <div class="img-title">dls-icon-favorite</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-feedback-filled" src="./img/Amex/dls-icon-feedback-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-feedback-filled.svg">SVG</a>
            <div class="img-title">dls-icon-feedback-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-feedback" src="./img/Amex/dls-icon-feedback.png" />
        <div>
            <a href="./img/Amex/dls-icon-feedback.svg">SVG</a>
            <div class="img-title">dls-icon-feedback</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-filter-down-filled" src="./img/Amex/dls-icon-filter-down-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-filter-down-filled.svg">SVG</a>
            <div class="img-title">dls-icon-filter-down-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-filter-down" src="./img/Amex/dls-icon-filter-down.png" />
        <div>
            <a href="./img/Amex/dls-icon-filter-down.svg">SVG</a>
            <div class="img-title">dls-icon-filter-down</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-filter-filled" src="./img/Amex/dls-icon-filter-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-filter-filled.svg">SVG</a>
            <div class="img-title">dls-icon-filter-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-filter-up-filled" src="./img/Amex/dls-icon-filter-up-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-filter-up-filled.svg">SVG</a>
            <div class="img-title">dls-icon-filter-up-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-filter-up" src="./img/Amex/dls-icon-filter-up.png" />
        <div>
            <a href="./img/Amex/dls-icon-filter-up.svg">SVG</a>
            <div class="img-title">dls-icon-filter-up</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-filter" src="./img/Amex/dls-icon-filter.png" />
        <div>
            <a href="./img/Amex/dls-icon-filter.svg">SVG</a>
            <div class="img-title">dls-icon-filter</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-flash-filled" src="./img/Amex/dls-icon-flash-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-flash-filled.svg">SVG</a>
            <div class="img-title">dls-icon-flash-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-flash-off-filled" src="./img/Amex/dls-icon-flash-off-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-flash-off-filled.svg">SVG</a>
            <div class="img-title">dls-icon-flash-off-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-flash-off" src="./img/Amex/dls-icon-flash-off.png" />
        <div>
            <a href="./img/Amex/dls-icon-flash-off.svg">SVG</a>
            <div class="img-title">dls-icon-flash-off</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-flash" src="./img/Amex/dls-icon-flash.png" />
        <div>
            <a href="./img/Amex/dls-icon-flash.svg">SVG</a>
            <div class="img-title">dls-icon-flash</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-fraud-protection-filled" src="./img/Amex/dls-icon-fraud-protection-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-fraud-protection-filled.svg">SVG</a>
            <div class="img-title">dls-icon-fraud-protection-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-fraud-protection" src="./img/Amex/dls-icon-fraud-protection.png" />
        <div>
            <a href="./img/Amex/dls-icon-fraud-protection.svg">SVG</a>
            <div class="img-title">dls-icon-fraud-protection</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-freeze-card-filled" src="./img/Amex/dls-icon-freeze-card-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-freeze-card-filled.svg">SVG</a>
            <div class="img-title">dls-icon-freeze-card-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-freeze-card" src="./img/Amex/dls-icon-freeze-card.png" />
        <div>
            <a href="./img/Amex/dls-icon-freeze-card.svg">SVG</a>
            <div class="img-title">dls-icon-freeze-card</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-gas-station-filled" src="./img/Amex/dls-icon-gas-station-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-gas-station-filled.svg">SVG</a>
            <div class="img-title">dls-icon-gas-station-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-gas-station" src="./img/Amex/dls-icon-gas-station.png" />
        <div>
            <a href="./img/Amex/dls-icon-gas-station.svg">SVG</a>
            <div class="img-title">dls-icon-gas-station</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-geolocation-filled" src="./img/Amex/dls-icon-geolocation-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-geolocation-filled.svg">SVG</a>
            <div class="img-title">dls-icon-geolocation-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-geolocation" src="./img/Amex/dls-icon-geolocation.png" />
        <div>
            <a href="./img/Amex/dls-icon-geolocation.svg">SVG</a>
            <div class="img-title">dls-icon-geolocation</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-gift-card-filled" src="./img/Amex/dls-icon-gift-card-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-gift-card-filled.svg">SVG</a>
            <div class="img-title">dls-icon-gift-card-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-gift-card" src="./img/Amex/dls-icon-gift-card.png" />
        <div>
            <a href="./img/Amex/dls-icon-gift-card.svg">SVG</a>
            <div class="img-title">dls-icon-gift-card</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-gift-filled" src="./img/Amex/dls-icon-gift-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-gift-filled.svg">SVG</a>
            <div class="img-title">dls-icon-gift-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-gift" src="./img/Amex/dls-icon-gift.png" />
        <div>
            <a href="./img/Amex/dls-icon-gift.svg">SVG</a>
            <div class="img-title">dls-icon-gift</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-global-filled" src="./img/Amex/dls-icon-global-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-global-filled.svg">SVG</a>
            <div class="img-title">dls-icon-global-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-global" src="./img/Amex/dls-icon-global.png" />
        <div>
            <a href="./img/Amex/dls-icon-global.svg">SVG</a>
            <div class="img-title">dls-icon-global</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-grid-filled" src="./img/Amex/dls-icon-grid-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-grid-filled.svg">SVG</a>
            <div class="img-title">dls-icon-grid-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-grid" src="./img/Amex/dls-icon-grid.png" />
        <div>
            <a href="./img/Amex/dls-icon-grid.svg">SVG</a>
            <div class="img-title">dls-icon-grid</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-grocery-filled" src="./img/Amex/dls-icon-grocery-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-grocery-filled.svg">SVG</a>
            <div class="img-title">dls-icon-grocery-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-grocery" src="./img/Amex/dls-icon-grocery.png" />
        <div>
            <a href="./img/Amex/dls-icon-grocery.svg">SVG</a>
            <div class="img-title">dls-icon-grocery</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-guide-filled" src="./img/Amex/dls-icon-guide-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-guide-filled.svg">SVG</a>
            <div class="img-title">dls-icon-guide-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-guide" src="./img/Amex/dls-icon-guide.png" />
        <div>
            <a href="./img/Amex/dls-icon-guide.svg">SVG</a>
            <div class="img-title">dls-icon-guide</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-hearing-impaired-filled" src="./img/Amex/dls-icon-hearing-impaired-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-hearing-impaired-filled.svg">SVG</a>
            <div class="img-title">dls-icon-hearing-impaired-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-hearing-impaired" src="./img/Amex/dls-icon-hearing-impaired.png" />
        <div>
            <a href="./img/Amex/dls-icon-hearing-impaired.svg">SVG</a>
            <div class="img-title">dls-icon-hearing-impaired</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-help-filled" src="./img/Amex/dls-icon-help-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-help-filled.svg">SVG</a>
            <div class="img-title">dls-icon-help-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-help" src="./img/Amex/dls-icon-help.png" />
        <div>
            <a href="./img/Amex/dls-icon-help.svg">SVG</a>
            <div class="img-title">dls-icon-help</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-hide-filled" src="./img/Amex/dls-icon-hide-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-hide-filled.svg">SVG</a>
            <div class="img-title">dls-icon-hide-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-hide" src="./img/Amex/dls-icon-hide.png" />
        <div>
            <a href="./img/Amex/dls-icon-hide.svg">SVG</a>
            <div class="img-title">dls-icon-hide</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-high-yield-filled" src="./img/Amex/dls-icon-high-yield-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-high-yield-filled.svg">SVG</a>
            <div class="img-title">dls-icon-high-yield-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-high-yield" src="./img/Amex/dls-icon-high-yield.png" />
        <div>
            <a href="./img/Amex/dls-icon-high-yield.svg">SVG</a>
            <div class="img-title">dls-icon-high-yield</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-home-filled" src="./img/Amex/dls-icon-home-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-home-filled.svg">SVG</a>
            <div class="img-title">dls-icon-home-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-home" src="./img/Amex/dls-icon-home.png" />
        <div>
            <a href="./img/Amex/dls-icon-home.svg">SVG</a>
            <div class="img-title">dls-icon-home</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-hotel-filled" src="./img/Amex/dls-icon-hotel-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-hotel-filled.svg">SVG</a>
            <div class="img-title">dls-icon-hotel-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-hotel" src="./img/Amex/dls-icon-hotel.png" />
        <div>
            <a href="./img/Amex/dls-icon-hotel.svg">SVG</a>
            <div class="img-title">dls-icon-hotel</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-infinity-filled" src="./img/Amex/dls-icon-infinity-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-infinity-filled.svg">SVG</a>
            <div class="img-title">dls-icon-infinity-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-infinity" src="./img/Amex/dls-icon-infinity.png" />
        <div>
            <a href="./img/Amex/dls-icon-infinity.svg">SVG</a>
            <div class="img-title">dls-icon-infinity</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-info-filled" src="./img/Amex/dls-icon-info-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-info-filled.svg">SVG</a>
            <div class="img-title">dls-icon-info-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-info" src="./img/Amex/dls-icon-info.png" />
        <div>
            <a href="./img/Amex/dls-icon-info.svg">SVG</a>
            <div class="img-title">dls-icon-info</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-instant-filled" src="./img/Amex/dls-icon-instant-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-instant-filled.svg">SVG</a>
            <div class="img-title">dls-icon-instant-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-instant" src="./img/Amex/dls-icon-instant.png" />
        <div>
            <a href="./img/Amex/dls-icon-instant.svg">SVG</a>
            <div class="img-title">dls-icon-instant</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-insurance-filled" src="./img/Amex/dls-icon-insurance-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-insurance-filled.svg">SVG</a>
            <div class="img-title">dls-icon-insurance-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-insurance" src="./img/Amex/dls-icon-insurance.png" />
        <div>
            <a href="./img/Amex/dls-icon-insurance.svg">SVG</a>
            <div class="img-title">dls-icon-insurance</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-krone-autopay-filled" src="./img/Amex/dls-icon-krone-autopay-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-krone-autopay-filled.svg">SVG</a>
            <div class="img-title">dls-icon-krone-autopay-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-krone-autopay" src="./img/Amex/dls-icon-krone-autopay.png" />
        <div>
            <a href="./img/Amex/dls-icon-krone-autopay.svg">SVG</a>
            <div class="img-title">dls-icon-krone-autopay</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-krone-cashback-filled" src="./img/Amex/dls-icon-krone-cashback-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-krone-cashback-filled.svg">SVG</a>
            <div class="img-title">dls-icon-krone-cashback-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-krone-cashback" src="./img/Amex/dls-icon-krone-cashback.png" />
        <div>
            <a href="./img/Amex/dls-icon-krone-cashback.svg">SVG</a>
            <div class="img-title">dls-icon-krone-cashback</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-krone-filled" src="./img/Amex/dls-icon-krone-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-krone-filled.svg">SVG</a>
            <div class="img-title">dls-icon-krone-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-krone" src="./img/Amex/dls-icon-krone.png" />
        <div>
            <a href="./img/Amex/dls-icon-krone.svg">SVG</a>
            <div class="img-title">dls-icon-krone</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-laptop-filled" src="./img/Amex/dls-icon-laptop-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-laptop-filled.svg">SVG</a>
            <div class="img-title">dls-icon-laptop-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-laptop" src="./img/Amex/dls-icon-laptop.png" />
        <div>
            <a href="./img/Amex/dls-icon-laptop.svg">SVG</a>
            <div class="img-title">dls-icon-laptop</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-launch-filled" src="./img/Amex/dls-icon-launch-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-launch-filled.svg">SVG</a>
            <div class="img-title">dls-icon-launch-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-launch" src="./img/Amex/dls-icon-launch.png" />
        <div>
            <a href="./img/Amex/dls-icon-launch.svg">SVG</a>
            <div class="img-title">dls-icon-launch</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-left-filled" src="./img/Amex/dls-icon-left-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-left-filled.svg">SVG</a>
            <div class="img-title">dls-icon-left-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-left" src="./img/Amex/dls-icon-left.png" />
        <div>
            <a href="./img/Amex/dls-icon-left.svg">SVG</a>
            <div class="img-title">dls-icon-left</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-line-graph-filled" src="./img/Amex/dls-icon-line-graph-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-line-graph-filled.svg">SVG</a>
            <div class="img-title">dls-icon-line-graph-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-line-graph" src="./img/Amex/dls-icon-line-graph.png" />
        <div>
            <a href="./img/Amex/dls-icon-line-graph.svg">SVG</a>
            <div class="img-title">dls-icon-line-graph</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-link-filled" src="./img/Amex/dls-icon-link-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-link-filled.svg">SVG</a>
            <div class="img-title">dls-icon-link-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-link" src="./img/Amex/dls-icon-link.png" />
        <div>
            <a href="./img/Amex/dls-icon-link.svg">SVG</a>
            <div class="img-title">dls-icon-link</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-list-filled" src="./img/Amex/dls-icon-list-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-list-filled.svg">SVG</a>
            <div class="img-title">dls-icon-list-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-list" src="./img/Amex/dls-icon-list.png" />
        <div>
            <a href="./img/Amex/dls-icon-list.svg">SVG</a>
            <div class="img-title">dls-icon-list</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-location-filled" src="./img/Amex/dls-icon-location-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-location-filled.svg">SVG</a>
            <div class="img-title">dls-icon-location-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-location-services-filled" src="./img/Amex/dls-icon-location-services-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-location-services-filled.svg">SVG</a>
            <div class="img-title">dls-icon-location-services-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-location-services" src="./img/Amex/dls-icon-location-services.png" />
        <div>
            <a href="./img/Amex/dls-icon-location-services.svg">SVG</a>
            <div class="img-title">dls-icon-location-services</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-location" src="./img/Amex/dls-icon-location.png" />
        <div>
            <a href="./img/Amex/dls-icon-location.svg">SVG</a>
            <div class="img-title">dls-icon-location</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-lock-card-filled" src="./img/Amex/dls-icon-lock-card-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-lock-card-filled.svg">SVG</a>
            <div class="img-title">dls-icon-lock-card-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-lock-card" src="./img/Amex/dls-icon-lock-card.png" />
        <div>
            <a href="./img/Amex/dls-icon-lock-card.svg">SVG</a>
            <div class="img-title">dls-icon-lock-card</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-lock-filled" src="./img/Amex/dls-icon-lock-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-lock-filled.svg">SVG</a>
            <div class="img-title">dls-icon-lock-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-lock" src="./img/Amex/dls-icon-lock.png" />
        <div>
            <a href="./img/Amex/dls-icon-lock.svg">SVG</a>
            <div class="img-title">dls-icon-lock</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-lounge-filled" src="./img/Amex/dls-icon-lounge-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-lounge-filled.svg">SVG</a>
            <div class="img-title">dls-icon-lounge-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-lounge" src="./img/Amex/dls-icon-lounge.png" />
        <div>
            <a href="./img/Amex/dls-icon-lounge.svg">SVG</a>
            <div class="img-title">dls-icon-lounge</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-medal-filled" src="./img/Amex/dls-icon-medal-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-medal-filled.svg">SVG</a>
            <div class="img-title">dls-icon-medal-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-medal" src="./img/Amex/dls-icon-medal.png" />
        <div>
            <a href="./img/Amex/dls-icon-medal.svg">SVG</a>
            <div class="img-title">dls-icon-medal</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-medical-filled" src="./img/Amex/dls-icon-medical-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-medical-filled.svg">SVG</a>
            <div class="img-title">dls-icon-medical-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-medical" src="./img/Amex/dls-icon-medical.png" />
        <div>
            <a href="./img/Amex/dls-icon-medical.svg">SVG</a>
            <div class="img-title">dls-icon-medical</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-membership-filled" src="./img/Amex/dls-icon-membership-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-membership-filled.svg">SVG</a>
            <div class="img-title">dls-icon-membership-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-membership" src="./img/Amex/dls-icon-membership.png" />
        <div>
            <a href="./img/Amex/dls-icon-membership.svg">SVG</a>
            <div class="img-title">dls-icon-membership</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-menu-filled" src="./img/Amex/dls-icon-menu-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-menu-filled.svg">SVG</a>
            <div class="img-title">dls-icon-menu-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-menu" src="./img/Amex/dls-icon-menu.png" />
        <div>
            <a href="./img/Amex/dls-icon-menu.svg">SVG</a>
            <div class="img-title">dls-icon-menu</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-merchandise-filled" src="./img/Amex/dls-icon-merchandise-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-merchandise-filled.svg">SVG</a>
            <div class="img-title">dls-icon-merchandise-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-merchandise" src="./img/Amex/dls-icon-merchandise.png" />
        <div>
            <a href="./img/Amex/dls-icon-merchandise.svg">SVG</a>
            <div class="img-title">dls-icon-merchandise</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-minus-circle-filled" src="./img/Amex/dls-icon-minus-circle-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-minus-circle-filled.svg">SVG</a>
            <div class="img-title">dls-icon-minus-circle-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-minus-circle" src="./img/Amex/dls-icon-minus-circle.png" />
        <div>
            <a href="./img/Amex/dls-icon-minus-circle.svg">SVG</a>
            <div class="img-title">dls-icon-minus-circle</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-minus-filled" src="./img/Amex/dls-icon-minus-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-minus-filled.svg">SVG</a>
            <div class="img-title">dls-icon-minus-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-minus" src="./img/Amex/dls-icon-minus.png" />
        <div>
            <a href="./img/Amex/dls-icon-minus.svg">SVG</a>
            <div class="img-title">dls-icon-minus</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-mobile-filled" src="./img/Amex/dls-icon-mobile-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-mobile-filled.svg">SVG</a>
            <div class="img-title">dls-icon-mobile-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-mobile" src="./img/Amex/dls-icon-mobile.png" />
        <div>
            <a href="./img/Amex/dls-icon-mobile.svg">SVG</a>
            <div class="img-title">dls-icon-mobile</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-more-filled" src="./img/Amex/dls-icon-more-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-more-filled.svg">SVG</a>
            <div class="img-title">dls-icon-more-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-more" src="./img/Amex/dls-icon-more.png" />
        <div>
            <a href="./img/Amex/dls-icon-more.svg">SVG</a>
            <div class="img-title">dls-icon-more</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-multi-channel-filled" src="./img/Amex/dls-icon-multi-channel-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-multi-channel-filled.svg">SVG</a>
            <div class="img-title">dls-icon-multi-channel-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-multi-channel" src="./img/Amex/dls-icon-multi-channel.png" />
        <div>
            <a href="./img/Amex/dls-icon-multi-channel.svg">SVG</a>
            <div class="img-title">dls-icon-multi-channel</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-neutral-filled" src="./img/Amex/dls-icon-neutral-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-neutral-filled.svg">SVG</a>
            <div class="img-title">dls-icon-neutral-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-neutral" src="./img/Amex/dls-icon-neutral.png" />
        <div>
            <a href="./img/Amex/dls-icon-neutral.svg">SVG</a>
            <div class="img-title">dls-icon-neutral</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-no-fee-filled" src="./img/Amex/dls-icon-no-fee-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-no-fee-filled.svg">SVG</a>
            <div class="img-title">dls-icon-no-fee-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-no-fee" src="./img/Amex/dls-icon-no-fee.png" />
        <div>
            <a href="./img/Amex/dls-icon-no-fee.svg">SVG</a>
            <div class="img-title">dls-icon-no-fee</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-offers-desktop-filled" src="./img/Amex/dls-icon-offers-desktop-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-offers-desktop-filled.svg">SVG</a>
            <div class="img-title">dls-icon-offers-desktop-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-offers-desktop" src="./img/Amex/dls-icon-offers-desktop.png" />
        <div>
            <a href="./img/Amex/dls-icon-offers-desktop.svg">SVG</a>
            <div class="img-title">dls-icon-offers-desktop</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-offers-mobile-filled" src="./img/Amex/dls-icon-offers-mobile-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-offers-mobile-filled.svg">SVG</a>
            <div class="img-title">dls-icon-offers-mobile-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-offers-mobile" src="./img/Amex/dls-icon-offers-mobile.png" />
        <div>
            <a href="./img/Amex/dls-icon-offers-mobile.svg">SVG</a>
            <div class="img-title">dls-icon-offers-mobile</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-open-banking-filled" src="./img/Amex/dls-icon-open-banking-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-open-banking-filled.svg">SVG</a>
            <div class="img-title">dls-icon-open-banking-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-open-banking" src="./img/Amex/dls-icon-open-banking.png" />
        <div>
            <a href="./img/Amex/dls-icon-open-banking.svg">SVG</a>
            <div class="img-title">dls-icon-open-banking</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-overdraft-protection-filled" src="./img/Amex/dls-icon-overdraft-protection-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-overdraft-protection-filled.svg">SVG</a>
            <div class="img-title">dls-icon-overdraft-protection-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-overdraft-protection" src="./img/Amex/dls-icon-overdraft-protection.png" />
        <div>
            <a href="./img/Amex/dls-icon-overdraft-protection.svg">SVG</a>
            <div class="img-title">dls-icon-overdraft-protection</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-oversize-bag-filled" src="./img/Amex/dls-icon-oversize-bag-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-oversize-bag-filled.svg">SVG</a>
            <div class="img-title">dls-icon-oversize-bag-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-oversize-bag" src="./img/Amex/dls-icon-oversize-bag.png" />
        <div>
            <a href="./img/Amex/dls-icon-oversize-bag.svg">SVG</a>
            <div class="img-title">dls-icon-oversize-bag</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-p2p-filled" src="./img/Amex/dls-icon-p2p-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-p2p-filled.svg">SVG</a>
            <div class="img-title">dls-icon-p2p-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-p2p" src="./img/Amex/dls-icon-p2p.png" />
        <div>
            <a href="./img/Amex/dls-icon-p2p.svg">SVG</a>
            <div class="img-title">dls-icon-p2p</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-paperless-filled" src="./img/Amex/dls-icon-paperless-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-paperless-filled.svg">SVG</a>
            <div class="img-title">dls-icon-paperless-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-paperless" src="./img/Amex/dls-icon-paperless.png" />
        <div>
            <a href="./img/Amex/dls-icon-paperless.svg">SVG</a>
            <div class="img-title">dls-icon-paperless</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-partnership-filled" src="./img/Amex/dls-icon-partnership-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-partnership-filled.svg">SVG</a>
            <div class="img-title">dls-icon-partnership-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-partnership" src="./img/Amex/dls-icon-partnership.png" />
        <div>
            <a href="./img/Amex/dls-icon-partnership.svg">SVG</a>
            <div class="img-title">dls-icon-partnership</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pause-circle-filled" src="./img/Amex/dls-icon-pause-circle-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-pause-circle-filled.svg">SVG</a>
            <div class="img-title">dls-icon-pause-circle-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pause-circle" src="./img/Amex/dls-icon-pause-circle.png" />
        <div>
            <a href="./img/Amex/dls-icon-pause-circle.svg">SVG</a>
            <div class="img-title">dls-icon-pause-circle</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pause-filled" src="./img/Amex/dls-icon-pause-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-pause-filled.svg">SVG</a>
            <div class="img-title">dls-icon-pause-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pause" src="./img/Amex/dls-icon-pause.png" />
        <div>
            <a href="./img/Amex/dls-icon-pause.svg">SVG</a>
            <div class="img-title">dls-icon-pause</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pay-over-time-filled" src="./img/Amex/dls-icon-pay-over-time-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-pay-over-time-filled.svg">SVG</a>
            <div class="img-title">dls-icon-pay-over-time-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pay-over-time" src="./img/Amex/dls-icon-pay-over-time.png" />
        <div>
            <a href="./img/Amex/dls-icon-pay-over-time.svg">SVG</a>
            <div class="img-title">dls-icon-pay-over-time</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-payment-due-filled" src="./img/Amex/dls-icon-payment-due-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-payment-due-filled.svg">SVG</a>
            <div class="img-title">dls-icon-payment-due-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-payment-due" src="./img/Amex/dls-icon-payment-due.png" />
        <div>
            <a href="./img/Amex/dls-icon-payment-due.svg">SVG</a>
            <div class="img-title">dls-icon-payment-due</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pdf-filled" src="./img/Amex/dls-icon-pdf-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-pdf-filled.svg">SVG</a>
            <div class="img-title">dls-icon-pdf-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pdf" src="./img/Amex/dls-icon-pdf.png" />
        <div>
            <a href="./img/Amex/dls-icon-pdf.svg">SVG</a>
            <div class="img-title">dls-icon-pdf</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pet-filled" src="./img/Amex/dls-icon-pet-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-pet-filled.svg">SVG</a>
            <div class="img-title">dls-icon-pet-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pet" src="./img/Amex/dls-icon-pet.png" />
        <div>
            <a href="./img/Amex/dls-icon-pet.svg">SVG</a>
            <div class="img-title">dls-icon-pet</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-picture-filled" src="./img/Amex/dls-icon-picture-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-picture-filled.svg">SVG</a>
            <div class="img-title">dls-icon-picture-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-picture-strikethrough-filled" src="./img/Amex/dls-icon-picture-strikethrough-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-picture-strikethrough-filled.svg">SVG</a>
            <div class="img-title">dls-icon-picture-strikethrough-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-picture-strikethrough" src="./img/Amex/dls-icon-picture-strikethrough.png" />
        <div>
            <a href="./img/Amex/dls-icon-picture-strikethrough.svg">SVG</a>
            <div class="img-title">dls-icon-picture-strikethrough</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-picture" src="./img/Amex/dls-icon-picture.png" />
        <div>
            <a href="./img/Amex/dls-icon-picture.svg">SVG</a>
            <div class="img-title">dls-icon-picture</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pie-chart-filled" src="./img/Amex/dls-icon-pie-chart-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-pie-chart-filled.svg">SVG</a>
            <div class="img-title">dls-icon-pie-chart-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pie-chart" src="./img/Amex/dls-icon-pie-chart.png" />
        <div>
            <a href="./img/Amex/dls-icon-pie-chart.svg">SVG</a>
            <div class="img-title">dls-icon-pie-chart</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-play-circle-filled" src="./img/Amex/dls-icon-play-circle-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-play-circle-filled.svg">SVG</a>
            <div class="img-title">dls-icon-play-circle-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-play-circle" src="./img/Amex/dls-icon-play-circle.png" />
        <div>
            <a href="./img/Amex/dls-icon-play-circle.svg">SVG</a>
            <div class="img-title">dls-icon-play-circle</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-play-filled" src="./img/Amex/dls-icon-play-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-play-filled.svg">SVG</a>
            <div class="img-title">dls-icon-play-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-play" src="./img/Amex/dls-icon-play.png" />
        <div>
            <a href="./img/Amex/dls-icon-play.svg">SVG</a>
            <div class="img-title">dls-icon-play</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-plus-circle-filled" src="./img/Amex/dls-icon-plus-circle-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-plus-circle-filled.svg">SVG</a>
            <div class="img-title">dls-icon-plus-circle-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-plus-circle" src="./img/Amex/dls-icon-plus-circle.png" />
        <div>
            <a href="./img/Amex/dls-icon-plus-circle.svg">SVG</a>
            <div class="img-title">dls-icon-plus-circle</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-plus-filled" src="./img/Amex/dls-icon-plus-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-plus-filled.svg">SVG</a>
            <div class="img-title">dls-icon-plus-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-plus" src="./img/Amex/dls-icon-plus.png" />
        <div>
            <a href="./img/Amex/dls-icon-plus.svg">SVG</a>
            <div class="img-title">dls-icon-plus</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-10k-filled" src="./img/Amex/dls-icon-point-10k-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-10k-filled.svg">SVG</a>
            <div class="img-title">dls-icon-point-10k-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-10k" src="./img/Amex/dls-icon-point-10k.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-10k.svg">SVG</a>
            <div class="img-title">dls-icon-point-10k</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-20k-filled" src="./img/Amex/dls-icon-point-20k-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-20k-filled.svg">SVG</a>
            <div class="img-title">dls-icon-point-20k-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-20k" src="./img/Amex/dls-icon-point-20k.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-20k.svg">SVG</a>
            <div class="img-title">dls-icon-point-20k</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-2x-filled" src="./img/Amex/dls-icon-point-2x-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-2x-filled.svg">SVG</a>
            <div class="img-title">dls-icon-point-2x-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-2x" src="./img/Amex/dls-icon-point-2x.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-2x.svg">SVG</a>
            <div class="img-title">dls-icon-point-2x</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-3x-filled" src="./img/Amex/dls-icon-point-3x-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-3x-filled.svg">SVG</a>
            <div class="img-title">dls-icon-point-3x-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-3x" src="./img/Amex/dls-icon-point-3x.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-3x.svg">SVG</a>
            <div class="img-title">dls-icon-point-3x</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-5x-filled" src="./img/Amex/dls-icon-point-5x-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-5x-filled.svg">SVG</a>
            <div class="img-title">dls-icon-point-5x-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-5x" src="./img/Amex/dls-icon-point-5x.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-5x.svg">SVG</a>
            <div class="img-title">dls-icon-point-5x</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-8x-filled" src="./img/Amex/dls-icon-point-8x-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-8x-filled.svg">SVG</a>
            <div class="img-title">dls-icon-point-8x-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-point-8x" src="./img/Amex/dls-icon-point-8x.png" />
        <div>
            <a href="./img/Amex/dls-icon-point-8x.svg">SVG</a>
            <div class="img-title">dls-icon-point-8x</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pound-autopay-filled" src="./img/Amex/dls-icon-pound-autopay-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-pound-autopay-filled.svg">SVG</a>
            <div class="img-title">dls-icon-pound-autopay-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pound-autopay" src="./img/Amex/dls-icon-pound-autopay.png" />
        <div>
            <a href="./img/Amex/dls-icon-pound-autopay.svg">SVG</a>
            <div class="img-title">dls-icon-pound-autopay</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pound-cashback-filled" src="./img/Amex/dls-icon-pound-cashback-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-pound-cashback-filled.svg">SVG</a>
            <div class="img-title">dls-icon-pound-cashback-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pound-cashback" src="./img/Amex/dls-icon-pound-cashback.png" />
        <div>
            <a href="./img/Amex/dls-icon-pound-cashback.svg">SVG</a>
            <div class="img-title">dls-icon-pound-cashback</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pound-filled" src="./img/Amex/dls-icon-pound-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-pound-filled.svg">SVG</a>
            <div class="img-title">dls-icon-pound-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pound-no-fee-filled" src="./img/Amex/dls-icon-pound-no-fee-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-pound-no-fee-filled.svg">SVG</a>
            <div class="img-title">dls-icon-pound-no-fee-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pound-no-fee" src="./img/Amex/dls-icon-pound-no-fee.png" />
        <div>
            <a href="./img/Amex/dls-icon-pound-no-fee.svg">SVG</a>
            <div class="img-title">dls-icon-pound-no-fee</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-pound" src="./img/Amex/dls-icon-pound.png" />
        <div>
            <a href="./img/Amex/dls-icon-pound.svg">SVG</a>
            <div class="img-title">dls-icon-pound</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-print-filled" src="./img/Amex/dls-icon-print-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-print-filled.svg">SVG</a>
            <div class="img-title">dls-icon-print-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-print" src="./img/Amex/dls-icon-print.png" />
        <div>
            <a href="./img/Amex/dls-icon-print.svg">SVG</a>
            <div class="img-title">dls-icon-print</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-processing-filled" src="./img/Amex/dls-icon-processing-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-processing-filled.svg">SVG</a>
            <div class="img-title">dls-icon-processing-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-processing" src="./img/Amex/dls-icon-processing.png" />
        <div>
            <a href="./img/Amex/dls-icon-processing.svg">SVG</a>
            <div class="img-title">dls-icon-processing</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-qr-scan-filled" src="./img/Amex/dls-icon-qr-scan-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-qr-scan-filled.svg">SVG</a>
            <div class="img-title">dls-icon-qr-scan-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-qr-scan" src="./img/Amex/dls-icon-qr-scan.png" />
        <div>
            <a href="./img/Amex/dls-icon-qr-scan.svg">SVG</a>
            <div class="img-title">dls-icon-qr-scan</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-quick-transfer-filled" src="./img/Amex/dls-icon-quick-transfer-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-quick-transfer-filled.svg">SVG</a>
            <div class="img-title">dls-icon-quick-transfer-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-quick-transfer" src="./img/Amex/dls-icon-quick-transfer.png" />
        <div>
            <a href="./img/Amex/dls-icon-quick-transfer.svg">SVG</a>
            <div class="img-title">dls-icon-quick-transfer</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-receipt-add-filled" src="./img/Amex/dls-icon-receipt-add-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-receipt-add-filled.svg">SVG</a>
            <div class="img-title">dls-icon-receipt-add-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-receipt-add" src="./img/Amex/dls-icon-receipt-add.png" />
        <div>
            <a href="./img/Amex/dls-icon-receipt-add.svg">SVG</a>
            <div class="img-title">dls-icon-receipt-add</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-receipt-filled" src="./img/Amex/dls-icon-receipt-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-receipt-filled.svg">SVG</a>
            <div class="img-title">dls-icon-receipt-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-receipt-view-filled" src="./img/Amex/dls-icon-receipt-view-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-receipt-view-filled.svg">SVG</a>
            <div class="img-title">dls-icon-receipt-view-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-receipt-view" src="./img/Amex/dls-icon-receipt-view.png" />
        <div>
            <a href="./img/Amex/dls-icon-receipt-view.svg">SVG</a>
            <div class="img-title">dls-icon-receipt-view</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-receipt" src="./img/Amex/dls-icon-receipt.png" />
        <div>
            <a href="./img/Amex/dls-icon-receipt.svg">SVG</a>
            <div class="img-title">dls-icon-receipt</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-recent-points-filled" src="./img/Amex/dls-icon-recent-points-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-recent-points-filled.svg">SVG</a>
            <div class="img-title">dls-icon-recent-points-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-recent-points" src="./img/Amex/dls-icon-recent-points.png" />
        <div>
            <a href="./img/Amex/dls-icon-recent-points.svg">SVG</a>
            <div class="img-title">dls-icon-recent-points</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-recurring-interest-filled" src="./img/Amex/dls-icon-recurring-interest-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-recurring-interest-filled.svg">SVG</a>
            <div class="img-title">dls-icon-recurring-interest-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-recurring-interest" src="./img/Amex/dls-icon-recurring-interest.png" />
        <div>
            <a href="./img/Amex/dls-icon-recurring-interest.svg">SVG</a>
            <div class="img-title">dls-icon-recurring-interest</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-refresh-filled" src="./img/Amex/dls-icon-refresh-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-refresh-filled.svg">SVG</a>
            <div class="img-title">dls-icon-refresh-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-refresh" src="./img/Amex/dls-icon-refresh.png" />
        <div>
            <a href="./img/Amex/dls-icon-refresh.svg">SVG</a>
            <div class="img-title">dls-icon-refresh</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-refreshment-filled" src="./img/Amex/dls-icon-refreshment-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-refreshment-filled.svg">SVG</a>
            <div class="img-title">dls-icon-refreshment-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-refreshment" src="./img/Amex/dls-icon-refreshment.png" />
        <div>
            <a href="./img/Amex/dls-icon-refreshment.svg">SVG</a>
            <div class="img-title">dls-icon-refreshment</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-retirement-filled" src="./img/Amex/dls-icon-retirement-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-retirement-filled.svg">SVG</a>
            <div class="img-title">dls-icon-retirement-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-retirement" src="./img/Amex/dls-icon-retirement.png" />
        <div>
            <a href="./img/Amex/dls-icon-retirement.svg">SVG</a>
            <div class="img-title">dls-icon-retirement</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-rewards-filled" src="./img/Amex/dls-icon-rewards-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-rewards-filled.svg">SVG</a>
            <div class="img-title">dls-icon-rewards-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-rewards" src="./img/Amex/dls-icon-rewards.png" />
        <div>
            <a href="./img/Amex/dls-icon-rewards.svg">SVG</a>
            <div class="img-title">dls-icon-rewards</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-right-filled" src="./img/Amex/dls-icon-right-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-right-filled.svg">SVG</a>
            <div class="img-title">dls-icon-right-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-right" src="./img/Amex/dls-icon-right.png" />
        <div>
            <a href="./img/Amex/dls-icon-right.svg">SVG</a>
            <div class="img-title">dls-icon-right</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-round-the-clock-filled" src="./img/Amex/dls-icon-round-the-clock-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-round-the-clock-filled.svg">SVG</a>
            <div class="img-title">dls-icon-round-the-clock-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-round-the-clock" src="./img/Amex/dls-icon-round-the-clock.png" />
        <div>
            <a href="./img/Amex/dls-icon-round-the-clock.svg">SVG</a>
            <div class="img-title">dls-icon-round-the-clock</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-rupee-autopay-filled" src="./img/Amex/dls-icon-rupee-autopay-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-rupee-autopay-filled.svg">SVG</a>
            <div class="img-title">dls-icon-rupee-autopay-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-rupee-autopay" src="./img/Amex/dls-icon-rupee-autopay.png" />
        <div>
            <a href="./img/Amex/dls-icon-rupee-autopay.svg">SVG</a>
            <div class="img-title">dls-icon-rupee-autopay</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-rupee-cashback-filled" src="./img/Amex/dls-icon-rupee-cashback-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-rupee-cashback-filled.svg">SVG</a>
            <div class="img-title">dls-icon-rupee-cashback-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-rupee-cashback" src="./img/Amex/dls-icon-rupee-cashback.png" />
        <div>
            <a href="./img/Amex/dls-icon-rupee-cashback.svg">SVG</a>
            <div class="img-title">dls-icon-rupee-cashback</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-rupee-filled" src="./img/Amex/dls-icon-rupee-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-rupee-filled.svg">SVG</a>
            <div class="img-title">dls-icon-rupee-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-rupee" src="./img/Amex/dls-icon-rupee.png" />
        <div>
            <a href="./img/Amex/dls-icon-rupee.svg">SVG</a>
            <div class="img-title">dls-icon-rupee</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-savings-filled" src="./img/Amex/dls-icon-savings-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-savings-filled.svg">SVG</a>
            <div class="img-title">dls-icon-savings-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-savings" src="./img/Amex/dls-icon-savings.png" />
        <div>
            <a href="./img/Amex/dls-icon-savings.svg">SVG</a>
            <div class="img-title">dls-icon-savings</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-search-filled" src="./img/Amex/dls-icon-search-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-search-filled.svg">SVG</a>
            <div class="img-title">dls-icon-search-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-search" src="./img/Amex/dls-icon-search.png" />
        <div>
            <a href="./img/Amex/dls-icon-search.svg">SVG</a>
            <div class="img-title">dls-icon-search</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-security-filled" src="./img/Amex/dls-icon-security-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-security-filled.svg">SVG</a>
            <div class="img-title">dls-icon-security-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-security" src="./img/Amex/dls-icon-security.png" />
        <div>
            <a href="./img/Amex/dls-icon-security.svg">SVG</a>
            <div class="img-title">dls-icon-security</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-send-and-split-filled" src="./img/Amex/dls-icon-send-and-split-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-send-and-split-filled.svg">SVG</a>
            <div class="img-title">dls-icon-send-and-split-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-send-and-split" src="./img/Amex/dls-icon-send-and-split.png" />
        <div>
            <a href="./img/Amex/dls-icon-send-and-split.svg">SVG</a>
            <div class="img-title">dls-icon-send-and-split</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-setting-filled" src="./img/Amex/dls-icon-setting-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-setting-filled.svg">SVG</a>
            <div class="img-title">dls-icon-setting-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-setting" src="./img/Amex/dls-icon-setting.png" />
        <div>
            <a href="./img/Amex/dls-icon-setting.svg">SVG</a>
            <div class="img-title">dls-icon-setting</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-share-filled" src="./img/Amex/dls-icon-share-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-share-filled.svg">SVG</a>
            <div class="img-title">dls-icon-share-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-share" src="./img/Amex/dls-icon-share.png" />
        <div>
            <a href="./img/Amex/dls-icon-share.svg">SVG</a>
            <div class="img-title">dls-icon-share</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-shipping-truck-filled" src="./img/Amex/dls-icon-shipping-truck-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-shipping-truck-filled.svg">SVG</a>
            <div class="img-title">dls-icon-shipping-truck-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-shipping-truck" src="./img/Amex/dls-icon-shipping-truck.png" />
        <div>
            <a href="./img/Amex/dls-icon-shipping-truck.svg">SVG</a>
            <div class="img-title">dls-icon-shipping-truck</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-show-filled" src="./img/Amex/dls-icon-show-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-show-filled.svg">SVG</a>
            <div class="img-title">dls-icon-show-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-show" src="./img/Amex/dls-icon-show.png" />
        <div>
            <a href="./img/Amex/dls-icon-show.svg">SVG</a>
            <div class="img-title">dls-icon-show</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-social-filled" src="./img/Amex/dls-icon-social-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-social-filled.svg">SVG</a>
            <div class="img-title">dls-icon-social-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-social" src="./img/Amex/dls-icon-social.png" />
        <div>
            <a href="./img/Amex/dls-icon-social.svg">SVG</a>
            <div class="img-title">dls-icon-social</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-sort-down" src="./img/Amex/dls-icon-sort-down.png" />
        <div>
            <a href="./img/Amex/dls-icon-sort-down.svg">SVG</a>
            <div class="img-title">dls-icon-sort-down</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-sort-up" src="./img/Amex/dls-icon-sort-up.png" />
        <div>
            <a href="./img/Amex/dls-icon-sort-up.svg">SVG</a>
            <div class="img-title">dls-icon-sort-up</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-sound-off-filled" src="./img/Amex/dls-icon-sound-off-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-sound-off-filled.svg">SVG</a>
            <div class="img-title">dls-icon-sound-off-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-sound-off" src="./img/Amex/dls-icon-sound-off.png" />
        <div>
            <a href="./img/Amex/dls-icon-sound-off.svg">SVG</a>
            <div class="img-title">dls-icon-sound-off</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-sound-on-filled" src="./img/Amex/dls-icon-sound-on-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-sound-on-filled.svg">SVG</a>
            <div class="img-title">dls-icon-sound-on-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-sound-on" src="./img/Amex/dls-icon-sound-on.png" />
        <div>
            <a href="./img/Amex/dls-icon-sound-on.svg">SVG</a>
            <div class="img-title">dls-icon-sound-on</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-source-filled" src="./img/Amex/dls-icon-source-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-source-filled.svg">SVG</a>
            <div class="img-title">dls-icon-source-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-source" src="./img/Amex/dls-icon-source.png" />
        <div>
            <a href="./img/Amex/dls-icon-source.svg">SVG</a>
            <div class="img-title">dls-icon-source</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-spa-filled" src="./img/Amex/dls-icon-spa-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-spa-filled.svg">SVG</a>
            <div class="img-title">dls-icon-spa-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-spa" src="./img/Amex/dls-icon-spa.png" />
        <div>
            <a href="./img/Amex/dls-icon-spa.svg">SVG</a>
            <div class="img-title">dls-icon-spa</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-split-filled" src="./img/Amex/dls-icon-split-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-split-filled.svg">SVG</a>
            <div class="img-title">dls-icon-split-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-split" src="./img/Amex/dls-icon-split.png" />
        <div>
            <a href="./img/Amex/dls-icon-split.svg">SVG</a>
            <div class="img-title">dls-icon-split</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-statement-paid-filled" src="./img/Amex/dls-icon-statement-paid-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-statement-paid-filled.svg">SVG</a>
            <div class="img-title">dls-icon-statement-paid-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-statement-paid" src="./img/Amex/dls-icon-statement-paid.png" />
        <div>
            <a href="./img/Amex/dls-icon-statement-paid.svg">SVG</a>
            <div class="img-title">dls-icon-statement-paid</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-statement-ready-filled" src="./img/Amex/dls-icon-statement-ready-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-statement-ready-filled.svg">SVG</a>
            <div class="img-title">dls-icon-statement-ready-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-statement-ready" src="./img/Amex/dls-icon-statement-ready.png" />
        <div>
            <a href="./img/Amex/dls-icon-statement-ready.svg">SVG</a>
            <div class="img-title">dls-icon-statement-ready</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-success-filled" src="./img/Amex/dls-icon-success-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-success-filled.svg">SVG</a>
            <div class="img-title">dls-icon-success-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-success" src="./img/Amex/dls-icon-success.png" />
        <div>
            <a href="./img/Amex/dls-icon-success.svg">SVG</a>
            <div class="img-title">dls-icon-success</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-tablet-filled" src="./img/Amex/dls-icon-tablet-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-tablet-filled.svg">SVG</a>
            <div class="img-title">dls-icon-tablet-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-tablet" src="./img/Amex/dls-icon-tablet.png" />
        <div>
            <a href="./img/Amex/dls-icon-tablet.svg">SVG</a>
            <div class="img-title">dls-icon-tablet</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-tag-filled" src="./img/Amex/dls-icon-tag-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-tag-filled.svg">SVG</a>
            <div class="img-title">dls-icon-tag-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-tag" src="./img/Amex/dls-icon-tag.png" />
        <div>
            <a href="./img/Amex/dls-icon-tag.svg">SVG</a>
            <div class="img-title">dls-icon-tag</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-tap-to-pay-filled" src="./img/Amex/dls-icon-tap-to-pay-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-tap-to-pay-filled.svg">SVG</a>
            <div class="img-title">dls-icon-tap-to-pay-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-tap-to-pay" src="./img/Amex/dls-icon-tap-to-pay.png" />
        <div>
            <a href="./img/Amex/dls-icon-tap-to-pay.svg">SVG</a>
            <div class="img-title">dls-icon-tap-to-pay</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-taxi-filled" src="./img/Amex/dls-icon-taxi-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-taxi-filled.svg">SVG</a>
            <div class="img-title">dls-icon-taxi-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-taxi" src="./img/Amex/dls-icon-taxi.png" />
        <div>
            <a href="./img/Amex/dls-icon-taxi.svg">SVG</a>
            <div class="img-title">dls-icon-taxi</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-telephone-filled" src="./img/Amex/dls-icon-telephone-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-telephone-filled.svg">SVG</a>
            <div class="img-title">dls-icon-telephone-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-telephone" src="./img/Amex/dls-icon-telephone.png" />
        <div>
            <a href="./img/Amex/dls-icon-telephone.svg">SVG</a>
            <div class="img-title">dls-icon-telephone</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-thumbs-down-filled" src="./img/Amex/dls-icon-thumbs-down-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-thumbs-down-filled.svg">SVG</a>
            <div class="img-title">dls-icon-thumbs-down-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-thumbs-down" src="./img/Amex/dls-icon-thumbs-down.png" />
        <div>
            <a href="./img/Amex/dls-icon-thumbs-down.svg">SVG</a>
            <div class="img-title">dls-icon-thumbs-down</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-thumbs-up-filled" src="./img/Amex/dls-icon-thumbs-up-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-thumbs-up-filled.svg">SVG</a>
            <div class="img-title">dls-icon-thumbs-up-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-thumbs-up" src="./img/Amex/dls-icon-thumbs-up.png" />
        <div>
            <a href="./img/Amex/dls-icon-thumbs-up.svg">SVG</a>
            <div class="img-title">dls-icon-thumbs-up</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-time-filled" src="./img/Amex/dls-icon-time-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-time-filled.svg">SVG</a>
            <div class="img-title">dls-icon-time-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-time" src="./img/Amex/dls-icon-time.png" />
        <div>
            <a href="./img/Amex/dls-icon-time.svg">SVG</a>
            <div class="img-title">dls-icon-time</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-train-filled" src="./img/Amex/dls-icon-train-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-train-filled.svg">SVG</a>
            <div class="img-title">dls-icon-train-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-train" src="./img/Amex/dls-icon-train.png" />
        <div>
            <a href="./img/Amex/dls-icon-train.svg">SVG</a>
            <div class="img-title">dls-icon-train</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-transfer-filled" src="./img/Amex/dls-icon-transfer-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-transfer-filled.svg">SVG</a>
            <div class="img-title">dls-icon-transfer-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-transfer" src="./img/Amex/dls-icon-transfer.png" />
        <div>
            <a href="./img/Amex/dls-icon-transfer.svg">SVG</a>
            <div class="img-title">dls-icon-transfer</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-trash-filled" src="./img/Amex/dls-icon-trash-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-trash-filled.svg">SVG</a>
            <div class="img-title">dls-icon-trash-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-trash" src="./img/Amex/dls-icon-trash.png" />
        <div>
            <a href="./img/Amex/dls-icon-trash.svg">SVG</a>
            <div class="img-title">dls-icon-trash</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-travel-bag-filled" src="./img/Amex/dls-icon-travel-bag-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-travel-bag-filled.svg">SVG</a>
            <div class="img-title">dls-icon-travel-bag-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-travel-bag" src="./img/Amex/dls-icon-travel-bag.png" />
        <div>
            <a href="./img/Amex/dls-icon-travel-bag.svg">SVG</a>
            <div class="img-title">dls-icon-travel-bag</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-trends-filled" src="./img/Amex/dls-icon-trends-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-trends-filled.svg">SVG</a>
            <div class="img-title">dls-icon-trends-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-trends" src="./img/Amex/dls-icon-trends.png" />
        <div>
            <a href="./img/Amex/dls-icon-trends.svg">SVG</a>
            <div class="img-title">dls-icon-trends</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-unlock-filled" src="./img/Amex/dls-icon-unlock-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-unlock-filled.svg">SVG</a>
            <div class="img-title">dls-icon-unlock-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-unlock" src="./img/Amex/dls-icon-unlock.png" />
        <div>
            <a href="./img/Amex/dls-icon-unlock.svg">SVG</a>
            <div class="img-title">dls-icon-unlock</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-up-filled" src="./img/Amex/dls-icon-up-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-up-filled.svg">SVG</a>
            <div class="img-title">dls-icon-up-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-up" src="./img/Amex/dls-icon-up.png" />
        <div>
            <a href="./img/Amex/dls-icon-up.svg">SVG</a>
            <div class="img-title">dls-icon-up</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-upload-filled" src="./img/Amex/dls-icon-upload-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-upload-filled.svg">SVG</a>
            <div class="img-title">dls-icon-upload-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-upload" src="./img/Amex/dls-icon-upload.png" />
        <div>
            <a href="./img/Amex/dls-icon-upload.svg">SVG</a>
            <div class="img-title">dls-icon-upload</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-warning-filled" src="./img/Amex/dls-icon-warning-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-warning-filled.svg">SVG</a>
            <div class="img-title">dls-icon-warning-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-warning" src="./img/Amex/dls-icon-warning.png" />
        <div>
            <a href="./img/Amex/dls-icon-warning.svg">SVG</a>
            <div class="img-title">dls-icon-warning</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-watch-filled" src="./img/Amex/dls-icon-watch-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-watch-filled.svg">SVG</a>
            <div class="img-title">dls-icon-watch-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-watch" src="./img/Amex/dls-icon-watch.png" />
        <div>
            <a href="./img/Amex/dls-icon-watch.svg">SVG</a>
            <div class="img-title">dls-icon-watch</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-wi-fi-filled" src="./img/Amex/dls-icon-wi-fi-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-wi-fi-filled.svg">SVG</a>
            <div class="img-title">dls-icon-wi-fi-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-wi-fi" src="./img/Amex/dls-icon-wi-fi.png" />
        <div>
            <a href="./img/Amex/dls-icon-wi-fi.svg">SVG</a>
            <div class="img-title">dls-icon-wi-fi</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-wifi-off-filled" src="./img/Amex/dls-icon-wifi-off-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-wifi-off-filled.svg">SVG</a>
            <div class="img-title">dls-icon-wifi-off-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-wifi-off" src="./img/Amex/dls-icon-wifi-off.png" />
        <div>
            <a href="./img/Amex/dls-icon-wifi-off.svg">SVG</a>
            <div class="img-title">dls-icon-wifi-off</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-wire-transfer-filled" src="./img/Amex/dls-icon-wire-transfer-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-wire-transfer-filled.svg">SVG</a>
            <div class="img-title">dls-icon-wire-transfer-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-wire-transfer" src="./img/Amex/dls-icon-wire-transfer.png" />
        <div>
            <a href="./img/Amex/dls-icon-wire-transfer.svg">SVG</a>
            <div class="img-title">dls-icon-wire-transfer</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-yen-autopay-filled" src="./img/Amex/dls-icon-yen-autopay-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-yen-autopay-filled.svg">SVG</a>
            <div class="img-title">dls-icon-yen-autopay-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-yen-autopay" src="./img/Amex/dls-icon-yen-autopay.png" />
        <div>
            <a href="./img/Amex/dls-icon-yen-autopay.svg">SVG</a>
            <div class="img-title">dls-icon-yen-autopay</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-yen-cashback-filled" src="./img/Amex/dls-icon-yen-cashback-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-yen-cashback-filled.svg">SVG</a>
            <div class="img-title">dls-icon-yen-cashback-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-yen-cashback" src="./img/Amex/dls-icon-yen-cashback.png" />
        <div>
            <a href="./img/Amex/dls-icon-yen-cashback.svg">SVG</a>
            <div class="img-title">dls-icon-yen-cashback</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-yen-filled" src="./img/Amex/dls-icon-yen-filled.png" />
        <div>
            <a href="./img/Amex/dls-icon-yen-filled.svg">SVG</a>
            <div class="img-title">dls-icon-yen-filled</div>
        </div>
    </div>
    <div>
        <img alt="dls-icon-yen" src="./img/Amex/dls-icon-yen.png" />
        <div>
            <a href="./img/Amex/dls-icon-yen.svg">SVG</a>
            <div class="img-title">dls-icon-yen</div>
        </div>
    </div>
</div>