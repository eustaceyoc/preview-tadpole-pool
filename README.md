# Tadpole Pool Services: sample site

A one-page sample site I put together for Tadpole Pool Services (Carrollton, TX). It's a concept, not their official website, and it says so at the top of the page and in the footer.

Live preview: https://preview-tadpole-pool.vercel.app

The request form doesn't send anything to a server. It just opens your own email app with a message addressed to tadpolepoolservices@gmail.com, and the phone buttons dial (972) 662-6014. There's no tracking or analytics, and the fonts are self-hosted.

## What's on the page

Only details from Tadpole Pool Services's own website and public listings: business name, Carrollton address, phone, email, hours and service areas from tadpolepoolservices.com. Their site doesn't list specific services, so this sample doesn't either. Anything I couldn't confirm is left out or marked to be confirmed. There are no reviews, ratings, prices, years in business or team photos.

## Photos

Stock photos from Pexels, used under the Pexels License (https://www.pexels.com/license/). They're there for mood. None of them shows Tadpole Pool Services, its people or its work.

- `pool-handrails.jpg`: "Handrails in a Corner of a Swimming Pool" by Mihman Duğanlı on Pexels (https://www.pexels.com/photo/handrails-in-a-corner-of-a-swimming-pool-19281006/)
- `turf-ladder.jpg`: "Inviting Poolside Scene in Chefchaouen, Morocco" by A. on Pexels (https://www.pexels.com/photo/inviting-poolside-scene-in-chefchaouen-morocco-38987604/)
- `goggles.jpg`: "Photo of Slippers Beside Goggles" by Atlantic Ambience on Pexels (https://www.pexels.com/photo/photo-of-slippers-beside-goggles-12932253/)

Fonts: Fredoka, Nunito (Google Fonts, SIL Open Font License). Full details are in `assets/provenance.json`.

## Indexing

The page has `noindex, nofollow` in a meta tag and in the `X-Robots-Tag` header (`vercel.json`), and `robots.txt` disallows everything, so it shouldn't turn up in search.

Eustace Crentsil
