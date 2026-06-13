# arushjasuja.github.io

My personal portfolio. Live at **[arushjasuja.github.io](https://arushjasuja.github.io)**.

I'm Arush Jasuja, an ML systems engineer in New York: GPU performance, distributed training, and ML infrastructure, with an MS in Computer Science from NYU and five peer-reviewed ML publications. The site lays out the work behind that, with the derivation under every number.

## What's here

A single static page, no framework and no build step. `index.html` holds the markup, styles, and the small bit of JavaScript that drives the scroll reveals and the timeline. The design treats the page like a profiler trace: a dark slate ground, colored career spans on a 2021–2026 ruler, and a roofline chart in the Method section plotting two real workloads from the experience below.

```
.
├── index.html                 # the entire site
├── Arush_Jasuja_Resume.pdf    # linked from the header (add before publishing)
└── README.md
```

## Running it locally

No dependencies. Open the file directly, or serve it so relative links behave like they do in production:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploying

GitHub Pages serves from this repo. Push to the default branch and the live site updates within a minute or two. Settings → Pages controls the source branch if it ever needs changing.

## Notes

- Built mobile-first with fluid type and spacing, so it reflows continuously from phone to laptop. The career timeline becomes swipeable on narrow screens.
- Keyboard focus is visible throughout and reduced-motion preferences are respected.
- Primary contact is arushjasuja@gmail.com.

## License

Code is free to reuse. The written content, the work history, and the metrics are mine, so please don't pass them off as your own.
