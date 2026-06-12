# dealer-assets

Central static assets (vehicle images + compiled feed JSON) for the dealer websites,
served via jsDelivr CDN: `https://cdn.jsdelivr.net/gh/LukeInMyEyes/dealer-assets@main/...`

- `/toyota/<model>/` — official Toyota jellybeans + MotorPress lifestyle
- `/baic/<model>/` — official baic.co.za imagery
- `/feed/<brand>.json` — compiled per-brand feed (prices, specs, image URLs)

Produced by the `sa_new_car_feed` pipeline. Images are optimized (≤1600px).
