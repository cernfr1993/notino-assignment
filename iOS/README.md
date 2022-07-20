![Notino](https://www.notino.cz/fotocache/gallery/loga/notino_pozitiv_800.png "Notino")

### iOS App Task
Your assignment is to create a **native iOS** application for displaying a couple of Notino products as seen in the provided [Figma design](https://www.figma.com/file/4ROi8fBsIH51vmAx2o6WAl/%5BiOS%5D-Test-handoff?node-id=1%3A1340) (you need to sign in to introspect the design with more detail).
Fetch products using a simple **GET** request at URL – https://my-json-server.typicode.com/cernfr1993/notino-assignment/db
Prefix URL for downloading product images – https://i.notino.com/detail_zoom/{IMAGE_ID}

---

**Requirements**:
- The application must be written in UIKit, no storyboards nor xibs.
- Use the necessary vector assets exported from Figma.
- Use `score` property in `reviewSummary` for displaying correct product rating (you can round the value to the nearest integer).
- Clicking on the heart button should **toggle between empty and filled heart** assets (export these from Figma).
- Any built-in iOS library is fair game, that includes `Combine` for reactive programming.
- You may use 3rd party libraries to make development easier, but try to keep it to a minimum.

---

**Optional**:
- Persist wishlisted products (those with a red heart) across app launches.
- Implement "add to cart" button states as proposed in the design.

**NOTE**: Keep complexity of the project in mind. Since this is a small single-screen app, the project should be easy to navigate and the code fairly simple to read.

![Screen](https://github.com/cernfr1993/notino-assignment/raw/main/iOS/screen_ios.png)
