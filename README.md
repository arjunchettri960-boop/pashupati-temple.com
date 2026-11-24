# पशुपति मन्दिर धादिङ — वेबसाइट अपडेट

यो अपडेटमा मूल वेबसाइटको डिजाइन कायम राख्दै **भजन तथा आरती** र **YouTube/Facebook Live** का लागि नयाँ खण्ड थपिएको छ।

## GitHub Pages मा अपडेट गर्ने
1. आफ्नो `pashupati-temple-dhading` repository खोल्नुहोस्।
2. नयाँ `index.html` upload गरेर पुरानो फाइल replace गर्नुहोस्।
3. Commit changes गर्नुहोस्।
4. केही मिनेटपछि वेबसाइट refresh गर्नुहोस्।

## Live भिडियो जोड्ने
अहिले Live का ठाउँमा placeholder देखिन्छ। वास्तविक प्रसारण जोड्न YouTube Live को embed URL/Video ID र Facebook Live को आधिकारिक embed URL चाहिन्छ। ती लिंक पाएपछि HTML मा जोड्न सकिन्छ।

## भजन/आरती अडियो जोड्ने
Repository मा `audio` नामको folder बनाउनुहोस् र यी MP3 फाइलहरू upload गर्नुहोस्:
- `pashupati-bhajan.mp3`
- `shiva-aarti.mp3`

फाइलको नाम फरक भए `index.html` भित्रको `audio/...` path पनि सोहीअनुसार बदल्नुहोस्।

## तस्बिर
मूल डिजाइनले `images/temple.jpg` खोज्छ। आफ्नो मन्दिरको फोटो `images` folder भित्र यही नाममा राख्नुहोस्।


## थपिएको भजन
तपाईंले पठाउनुभएको `रामकै सनिसार` MP3 फाइललाई `audio/pashupati-bhajan.mp3` नाममा राखिएको छ। वेबसाइटको भजन प्लेयरले यही फाइल चलाउँछ।
