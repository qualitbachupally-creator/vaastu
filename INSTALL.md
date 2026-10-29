# వాస్తు దిక్సూచి – ఫోన్‌లో ఎలా పెట్టుకోవాలి
# Vastu Dikshuchi – how to put it on your phone

The compass sensor only works when the app is opened from an **https://** link. So the app has to go on a free website once. After that, every Android phone can install it from that link.

దిక్సూచి సెన్సార్ **https://** లింక్ ద్వారా తెరిస్తేనే పని చేస్తుంది. అందుకే ఒక్కసారి ఉచిత వెబ్‌సైట్‌లో పెట్టాలి. ఆ తర్వాత ఆ లింక్‌తో ఏ ఆండ్రాయిడ్ ఫోన్‌లోనైనా ఇన్‌స్టాల్ చేసుకోవచ్చు.

The files to upload are everything inside the `VastuCompass` folder:

```
index.html
manifest.webmanifest
sw.js
icons/  (4 images)
```

---

## Step 1: Put it online (one time, about 10 minutes)

### Option A: GitHub Pages (free and permanent, recommended)

1. On your computer, sign up or log in at **github.com**.
2. Click **+** at the top right, then **New repository**. Name it `vastu-compass`, choose **Public**, and click **Create repository**.
3. On the new page, click **uploading an existing file**. Drag in all the files from the `VastuCompass` folder, including the `icons` folder, and click **Commit changes**.
4. Open **Settings**, then **Pages**. Under *Branch*, pick **main** and **/(root)**, then click **Save**.
5. Wait 1–2 minutes. Your link will be:
   `https://YOUR-GITHUB-NAME.github.io/vastu-compass/`

### Option B: Netlify Drop (quickest)

1. Go to **app.netlify.com/drop** on your computer.
2. Drag the whole `VastuCompass` folder onto the page.
3. You get an https link straight away. **Sign up for a free account and claim the site**, otherwise Netlify deletes it after a while.

---

## Step 2: Install on each Android phone

1. Open the link in **Chrome** on the phone.
2. Tap the **⋮** menu (top right), then **Install app** or **Add to Home screen**, then **Install**.
3. The **వాస్తు దిక్సూచి** icon appears on your home screen. It opens full screen like a normal app and works offline afterwards.

To give it to family members, just send them the same link on WhatsApp.

ఫోన్‌లో Chrome లో లింక్ తెరిచి, ⋮ మెనూ → **Install app / Add to Home screen** నొక్కండి. హోమ్ స్క్రీన్‌పై యాప్ ఐకాన్ వస్తుంది. కుటుంబ సభ్యులకు అదే లింక్ వాట్సాప్‌లో పంపండి.

---

## Step 3: Using it

| Tab | What it does |
|---|---|
| **దిక్సూచి / Compass** | Live compass with the 8 Telugu directions. Shows the deity and planet of the direction you're facing, and what should and should not be there. **Hold** freezes the reading. |
| **ముఖ దిశ / Facing** | Stand inside at the main door, look out, and tap **Record**. It tells you the house or flat facing, checks whether the main door is in an ఉచ్చ or నీచ position, and checks for వీధిపోటు (houses only). |
| **తనిఖీ / Check** | For each room and item (kitchen, master bedroom, pooja, toilets, borewell, sump, septic tank and more), stand at the centre of the home, point the phone at it, and tap **Use**. Or pick the zone on the grid. You get a score out of 100 and a list of fixes. **Share report** sends it on WhatsApp. |
| **నియమాలు / Guide** | Rules for all 8 directions and the centre (బ్రహ్మస్థానం), plus tips for buying, apartments, kitchen, sleep, the pooja room, and accurate readings. |

**For accurate readings:** hold the phone flat. First wave it in a figure-8 three or four times. Stay away from steel grills, almirahs, fridges, speakers and magnetic phone covers.

Your answers are saved on the phone. **Start over** clears them.

---

## Updating the app later

If you change any file, upload it again to the same place. Also open `sw.js` and change `vastu-dikshuchi-v1` to `v2`, `v3` and so on, so phones pick up the new version.

---

*Vastu is traditional guidance. Before any structural change, consult an experienced Vastu expert and a civil engineer.*
