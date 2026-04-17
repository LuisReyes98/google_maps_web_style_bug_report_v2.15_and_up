# Reproducable MRE for Google Maps Web Style Bug

# Steps to run 

1. Update with a valid API key the google maps link on the index.html file

```html
<script
    src="https://maps.googleapis.com/maps/api/js?key=[GCP_API_KEY]&libraries=drawing,marker,visualization"></script>
```

Replace `[GCP_API_KEY]` with a valid key

2. Running the app on web on `google_maps_flutter: 2.14.2` will show the map with the dark mode custom colors, and if run with any version above for example `google_maps_flutter: 2.15.0` will show the map with the default colors. 

This bug is still happening in the latest version as of writing this which is `google_maps_flutter: 2.17.0`
