# pixget
Handy CLI tool for generating placeholder Pixel Art.

Example usage:
```sh
pixget scenery, sand dunes, cactus, night, moon
```

Generates the pixel art and saves it as "scenery,_sand_dunes,_cactus,_night,_moon.png"

![example output](/scenery,_sand_dunes,_cactus,_night,_moon.png)

Uses this model: https://huggingface.co/nerijs/pixel-art-xl

Dependencies:
- curl
- imagemagik
- network access to huggingface.co

Features:
- Generates 124x124 pixel art in just a few seconds.
- No API key needed, just run it.

Limitations:
- Rate-limited, breaks if you run it too frequently.

## Roadmap
These features would be nice to add:
- Option to use API key.
- Better error messages for failed requests.
- Add a rate limiter, 2 per minute is a good default.

Submit a PR!
