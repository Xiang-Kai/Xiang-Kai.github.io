# November 2026 Homepage Update

The homepage source is `_pages/about.md`; navigation is in
`_data/navigation.yml`, the Scholar URL is in `_config.yml`, and the timeline
and publication-thumbnail styles are in `assets/css/main.scss`.

## Papers And Figures

The four PDFs in `files/` are unchanged copies supplied by the author:

| Website file | Original file |
| --- | --- |
| `demus-infocom2026.pdf` | `2026-Hanzhang-infocom2026-DEMUS.pdf` |
| `timesbook-mm2026.pdf` | `2026-JunjieWang-MM2026.pdf` |
| `pilot.pdf` | `pilot.pdf` |
| `robodemo.pdf` | `robodemo.pdf` |

The local PDF is authoritative for each new paper's title and author list.
In particular, the supplied PILOT manuscript uses "Visual Appearance"; its
project page still uses "Visual Representations". TimesBook's author order
follows the PDF's ACM Reference Format, not the order returned by extraction
of the multi-column author block.

Framework figures were imported into SVG with Inkscape 1.4.3's Poppler
importer. Cropping is defined by the SVG viewBox; the original vector paths
and embedded photographic evidence are retained. Do not redraw these assets
with a raster or Python plotting workflow.

| SVG asset | PDF page | Figure | ViewBox |
| --- | --- | --- | --- |
| `images/timesbook-framework.svg` | 3 | 2 | `64 81 484 268` |
| `images/pilot-framework.svg` | 4 | 3 | `107 44 398 220` |
| `images/robodemo-framework.svg` | 3 | 2 | `58 52 496 306` |

PNG thumbnails are exported from the SVGs at 1600 px wide on white.
The thumbnails link to their full-resolution vector sources. Status badges
are HTML overlays in a reserved strip above the figure, not burned into it.

Example export:

```sh
inkscape images/pilot-framework.svg --export-area-page \
  --export-background=white --export-width=1600 \
  --export-filename=images/pilot-framework.png
```

## Institutional Marks

- NJU: https://www.nju.edu.cn/en/images/logoft.svg
- NJU Computer Science: https://cs.nju.edu.cn/_upload/site/00/42/66/logo.png
- UESTC: https://en.uestc.edu.cn/images/logo.png
- Yingcai: https://www.yingcai.uestc.edu.cn/images/icon/logo.png
- JD: https://shengxu.net/images/jd-logo.png

`images/institutions/nju.svg` preserves the official white vector emblem on
an NJU-purple background. `images/institutions/uestc.svg` crops the UESTC wordmark to its
emblem and places the original white artwork on a blue background.
The Yingcai mark uses the same blue background in CSS for legibility.
`images/institutions/nju-cs.svg` embeds the official school header artwork
and crops its right-hand school emblem with an SVG viewBox. Both NJU
department names link to https://cs.nju.edu.cn/ because they identify the
same unit in different periods.
These marks identify the institutions; they do not imply endorsement.

## Biography Notes

- The Ph.D. start date is September 2024.
- The 2022-2024 entry describes graduate study and selection for the
  integrated master's-to-Ph.D. program; it does not claim a master's degree.
- The undergraduate honors wording preserves the existing biography.
- The JD entry says Research Intern, not Talent Program.
- The JD internship runs from April 2026 to the present.
- Education and Internship appear directly after the biography, before News.
- Institution marks sit next to the institution names rather than at the
  far edge of the page, with larger desktop and mobile sizes.
- RoboDemo's equal-contribution note and author asterisks are removed at
  the author's request; the uploaded original PDF remains unchanged.
- November 2026 news announces the PILOT and RoboDemo preprints, complete
  project code, and trained model weights. TimesBook acceptance uses only
  the year 2026 because an acceptance month was not supplied.

## Preview

Use the repository's Jekyll/GitHub Pages environment:

```sh
bundle install
bundle exec jekyll serve
```

Check the education and internship anchors, timeline alignment, full-size
figure links, four local PDF downloads, and phone-width layout before
publishing. Existing inbound `#-educations` and `#-internships` fragments are
retained as aliases.
