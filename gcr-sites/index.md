---
title: GCR Sites
has_children: true
nav_order: 2
---
# Geological Conservation Review Sites

<div style = "height: 250px" id="map"></div>
<script>

	const map = L.map('map').setView([51.505, -0.09], 13);

	const tiles = L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
		maxZoom: 19,
		attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
	}).addTo(map);
 </script>

The Geological Conservation Review (GCR) is the register of known nationally and internationally important Earth science (geological and geomorphological) sites in Great Britain. The GCR underpins designation of Earth science features in Sites of Special Scientific Interest (SSSIs). The majority of GCR sites, therefore, now have statutory protection through designation as notified features in SSSIs.

Some GCR sites, however, remain unnotified and are known as unnotified GCR sites. National Park Authorities and some Local Authorities treat these as candidate SSSIs and afford them the same protection as SSSIs.

Some unnotified GCR sites are also Local Geological Sites (LGS), and as such they are afforded levels of protection appropriate to locally important sites (though they are, themselves, considered to be of national or international importance).

The remaining unnotified GCR sites have no statutory protection, although they are considered to be sites of national or international importance.

Initially developed between 1977 and 1990, the GCR network is periodically updated and this dataset is subject to change. Boundaries of GCR sites are often not co-incident with SSSIs.
