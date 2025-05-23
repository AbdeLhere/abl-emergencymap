# ⚠️ No Support Provided
This project is fully open source and provided as-is.
Feel free to explore, modify, and use it however you like, but please note that I do not offer any support for it. Thank you !

# Overview
This is a custom minimap script made for emergency services RP servers. It includes different map versions (Cayo Perico, Roxwood County, and bridges) with road icons for Interstates, Rural (US Routes), and Urban (State Routes). Plus, it has modern zone names for even better navigation and realism.
# [Documentation ✨](https://abdelemporium-docs.gitbook.io/abdelemporium-docs/emergency-minimap-style)
# Installation

## <mark style="color:yellow;">**Remove Old Minimap Script**</mark>

* Remove any old minimap script from your resources.

## <mark style="color:yellow;">**Cleanup**</mark>&#x20;

* Open **Visual Studio Code**.
* Press `CTRL + K + O` to open a folder.
* Select your server folder and press `Open`.
* Press `CTRL + SHIFT + F` to search for the following lines:
  * `SetMapZoomDataLevel`
  * `SetRadarZoom`

*❗Remove these lines if found, **but do not remove them from the new script!**


## <mark style="color:yellow;">**Ensuring**</mark>&#x20;

* Drag and drop the new resource into your resources folder.
* Open your `server.cfg` file and add the following line after your framework, replacing `"script-name"` with your actual script name (e.g., `abl-emap-t1`):

<pre class="language-systemd"><code class="lang-systemd"><strong>ensure ox_lib ## my lib
</strong><strong>ensure qb-core ## my framework
</strong>
<strong>ensure "abl-emap-t1"
</strong></code></pre>

* Restart your server.

## <mark style="color:yellow;">Styles</mark>

❗I**f you want to use Cayo Bridge or Roxwood County styles, follow this guide.**

#### <mark style="color:yellow;">How to Change the Default Map</mark>

The default map used is **abl-emap-t1**. However, you can easily switch to a different map by replacing the contents of the **abl-emergencymap/stream/ytd** folder with the files from a new map.

**Example: Switching to the Los Santos + Cayo Perico Map (Without Zone Names)**

1. **Locate the Default Map:**
   * Go to the `abl-emergencymap/stream/ytd` folder in your current installation.
2. **Select Your Desired Map:**
   * Navigate to the **abl-emergencymap/INSTALLATION/Other Styles/abl-emap-t2/ytd** folder (this is the folder that contains the Los Santos + Cayo Perico map without zone names).
3. **Replace the Files:**
   * Drag and drop all the contents from the **abl-emap-t2/ytd** folder into the **abl-emap-t1/stream/ytd** folder, and when prompted, **replace the existing files**.

***

* <mark style="color:yellow;">**`abl-emap-t1`**</mark>**: Los Santos + Cayo Perico (&#x20;**<mark style="color:green;">**+**</mark>**&#x20;Zone Names)**
* <mark style="color:yellow;">**`abl-emap-t2`**</mark>**: Los Santos + Cayo Perico (**<mark style="color:red;">**Without**</mark>**&#x20;Zone Names)**
* <mark style="color:yellow;">**`abl-emap-t3`**</mark>**: Los Santos + Cayo Perico +&#x20;**<mark style="color:green;">**Roxwood County**</mark>**&#x20;V1 (**<mark style="color:green;">**+**</mark>**&#x20;Zone Names)**
* <mark style="color:yellow;">**`abl-emap-t4`**</mark>**: Los Santos + Cayo Perico +&#x20;**<mark style="color:green;">**Roxwood County**</mark>**&#x20;V1 +&#x20;**<mark style="color:green;">**Cayo Bridge**</mark>**&#x20;**<mark style="color:orange;">**V2**</mark>**&#x20;(**<mark style="color:green;">**+**</mark>**&#x20;Zone Names)**
* <mark style="color:yellow;">**`abl-emap-t5`**</mark>**: Los Santos + Cayo Perico +&#x20;**<mark style="color:green;">**Roxwood County**</mark>**&#x20;V1 +&#x20;**<mark style="color:green;">**Cayo Bridge**</mark>**&#x20;**<mark style="color:orange;">**V1**</mark>**&#x20;(**<mark style="color:green;">**+**</mark>**&#x20;Zone Names)**
* <mark style="color:yellow;">**`abl-emap-t6`**</mark>**: Los Santos + Cayo Perico +&#x20;**<mark style="color:green;">**Cayo Bridge**</mark>**&#x20;**<mark style="color:orange;">**V1**</mark> **(**<mark style="color:green;">**+**</mark>**&#x20;Zone Names)**
* <mark style="color:yellow;">**`abl-emap-t7`**</mark>**: Los Santos + Cayo Perico +&#x20;**<mark style="color:green;">**Cayo Bridge**</mark>**&#x20;**<mark style="color:orange;">**V2**</mark> **(**<mark style="color:green;">**+**</mark>**&#x20;Zone Names)**
* <mark style="color:yellow;">**`abl-emap-t8`**</mark>**: Los Santos + Cayo Perico +&#x20;**<mark style="color:green;">**Roxwood County**</mark> <mark style="color:red;">**Last Update**</mark>**&#x20;(**<mark style="color:green;">**+**</mark>**&#x20;Zone Names)**
* <mark style="color:yellow;">**`abl-emap-t9`**</mark>**: Los Santos + Cayo Perico +&#x20;**<mark style="color:green;">**Roxwood County**</mark> <mark style="color:red;">**Last Update**</mark>**&#x20;+&#x20;**<mark style="color:green;">**Cayo Bridge**</mark>**&#x20;**<mark style="color:orange;">**V2**</mark>**&#x20;(**<mark style="color:green;">**+**</mark>**&#x20;Zone Names)**
* <mark style="color:yellow;">**`abl-emap-t10`**</mark>**: Los Santos + Cayo Perico +&#x20;**<mark style="color:green;">**Roxwood County**</mark> <mark style="color:red;">**Last Update**</mark>**&#x20;+&#x20;**<mark style="color:green;">**Cayo Bridge**</mark>**&#x20;**<mark style="color:orange;">**V1**</mark>**&#x20;(**<mark style="color:green;">**+**</mark>**&#x20;Zone Names)**

