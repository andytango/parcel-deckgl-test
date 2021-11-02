# ParcelJS and deck.gl Issue - Demo Repo

This repo uses one of the examples from the deck.gl website to highlight a current bug affecting parcel production builds with this library (appears to relate to upstream dependencies luma.gl and probe.gl).

To recreate the issue:

Install deps: ```yarn```

Build and run local server: ```yarn build && npx serve ./dist```

Open `localhost:5000` in your browser and observe error:

![CleanShot 2021-11-02 at 20 06 58@2x](https://user-images.githubusercontent.com/8215152/139944546-dcfdadef-f4aa-44a8-8699-849758eceeaa.png)
