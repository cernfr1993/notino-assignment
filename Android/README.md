![Notino](https://www.notino.cz/fotocache/gallery/loga/notino_pozitiv_800.png "Notino")

### Android Assignment
Your assignment is to create a native Android application for displaying a couple of Notino products as seen in the provided [Figma](https://www.figma.com/file/RKnYLbexOQOEMwZQzvarO5/%5BAndroid%5D-Test-handoff?node-id=0%3A1) design (you need to sign in to introspect the design with more detail).
Fetch products using a simple **GET** request at URL – https://my-json-server.typicode.com/cernfr1993/notino-assignment/db
Prefix URL for downloading product images – https://i.notino.com/detail_zoom/{IMAGE_ID}

---

**Requirements**
- Create **native Android** application in **Android Studio** (Android Studio 4.0 or higher).
- Use [Figma](https://www.figma.com/file/RKnYLbexOQOEMwZQzvarO5/%5BAndroid%5D-Test-handoff?node-id=0%3A1) for designing (you need to sign in to introspect the design with more detail).
- Get products from simple get request located at url
[https://my-json-server.typicode.com/cernfr1993/notino-assignment/db](https://my-json-server.typicode.com/cernfr1993/notino-assignment/db)
- Use prefix url for downloading product images **https:// i.notino.com/detail_zoom/**
- Clicking on heart button changes its empty heart to filled heart and vice versa.
- State of the favourite products (state of the heart) must be stored persistently.
- Keep in mind that products count can be much higher than provided in example request.
- Use score property in reviewSummary for displaying product rating.

![Screen](https://github.com/cernfr1993/notino-assignment/raw/main/Android/screen_android.png)
