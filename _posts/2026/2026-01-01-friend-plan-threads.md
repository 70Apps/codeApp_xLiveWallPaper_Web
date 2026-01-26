---
layout: post
category: Guide
title: Friend Plan Threads
description: Share our app on Threads to get free vip code
keyword: xLiveWallpaper
tags: [appstore]
---
# Friend Plan Threads
## 🎉 Snag Free VIP Like a Boss! 🎉

Wanna level-up your wallpaper game without dropping a dime? Just shout us out on Threads (or any social hangout you love) and we’ll slide a shiny VIP redeem code straight into your DMs. Easy, breezy, totally free! 🚀

# How to hop on the hype train 🚂

1️⃣ Snap a screenshot of your fave live wallpaper, hit “Share” and tag @xLiveWallpaper on Threads.  
   Pro-tip: drop a 🔥 emoji so we know you’re legit!  
2️⃣ Kick back, sip your coffee, and let our tiny review elves do their thing (usually under 24 hrs).  
3️⃣ Boom—check your inbox for a VIP code that unlocks every single premium pack. No cap. 🦄

# Freebies & swag 🤳

## Download link (one tap, zero regrets)

- [Apple App Store](https://apps.apple.com/app/apple-store/id6747997192?pt=611621&ct=xlivewallpaper&mt=8) 📱✨

## Eye-candy Share Preview and Random Share Button

<div class="button-share">
<div class="button-share-preview">
</div>
<a href="javascript:return false;" class="button-share-link">Share Now</a>
<a href="javascript:return false;" class="button-share-random">Random Share</a>
 </div>

<script>
    const share_post_url = "https://www.threads.net/intent/post?"
    const share_post_link = "{{site:app_link}}"
    const share_texts = ["欸！看我分享的xLiveWallpaper，免费获取VIP码！", "免费获取VIP码，点击链接即可获取"]
    var share_link = ""
function init(){
// random select a text
const share_text = share_texts[Math.floor(Math.random() * share_texts.length)]
// add text to preview
document.querySelector(".button-share-preview").textContent = share_text
share_link = share_post_url + "text=" + encodeURIComponent(share_text) + "&url=" + encodeURIComponent(share_post_link)
// add link to share button
document.querySelector(".button-share-link").href = share_link
}
init()
// add event listener to random share button
document.querySelector(".button-share-random").addEventListener("click", function(){
    init()
})


</script>
