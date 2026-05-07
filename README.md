# Your Life in Weeks

**Live at: <https://alicommit-malp.github.io/life-in-weeks/>**

A free, single-page web app that generates a printable A4 poster of a life,
one week at a time. Every week already lived is filled in as a solid circle;
every week ahead is empty. The result is a quiet, useful way to look at time.

Pick **Human**, **Dog**, or **Cat** and the grid scales to the right lifespan.

No signup. No backend. No analytics. Your name and birthdate never leave your
device.

## Use it

1. Open the page.
2. Type a name and a birthdate, then pick the species.
3. Click **Generate** to see a live preview, then **Download PDF**.

The PDF is A4 portrait — print it on plain paper at home, or send it to a
print shop.

## What you get

| Option | Grid                  | Roughly      |
|--------|-----------------------|--------------|
| Human  | 100 rows × 52 columns | ~5,200 weeks |
| Dog    | 20 rows × 52 columns  | ~1,040 weeks |
| Cat    | 25 rows × 52 columns  | ~1,300 weeks |

Each row is one year. Each circle is one week.

## Privacy

Everything runs in your browser. There is no server, no tracking, no cookies,
no `localStorage`. The only network requests are to load the fonts (Google
Fonts) and the PDF library (jsPDF, from cdnjs) — neither receives your name
or birthdate.

## Run it locally

It's a single file. There's no build step, no package manager, no framework.

```sh
git clone https://github.com/alicommit-malp/life-in-weeks.git
cd life-in-weeks
# Open index.html in a browser — that's it.
```

## Deploy

The live version is hosted free on **GitHub Pages**: repo settings → Pages →
*Deploy from a branch* → `main` / root. Push to `main` and the site rebuilds
within a minute. No CI, no staging.

## Inspired by

The "life in weeks" idea is widely associated with Tim Urban's 2014
*Wait But Why* post. The design here — type, layout, copy — is original.

## License

MIT — see [LICENSE](LICENSE). Fork it, share it, print it, gift it.
