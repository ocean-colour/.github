<!--
  RECOMMENDED GRAPHIC: a global ocean-colour / chlorophyll-a map from a NASA
  ocean-colour mission (PACE/OCI or MODIS-Aqua) makes an ideal banner here.
  A good public-domain option is a NASA Earth Observatory / PACE chlorophyll
  image. Download it into this `profile/` folder (e.g. `profile/banner.png`)
  and uncomment the block below so the image is served from the repo rather
  than hot-linked:

  <p align="center">
    <img src="banner.png" alt="Global ocean chlorophyll from satellite ocean colour" width="800"/>
  </p>
-->

<h1 align="center">🌊 ocean-colour</h1>

<p align="center"><i>Open tools and analyses for ocean-colour remote sensing — for the community, hopefully by the community.</i></p>

## About

**ocean-colour** is a collection of open-source Python packages and analysis
notebooks for **ocean-colour remote sensing**: turning satellite measurements of
the light leaving the ocean into estimates of its bio-optical state — inherent
optical properties (IOPs), chlorophyll, and related biogeochemistry.

The repositories here span the full ocean-colour workflow: atmospheric
correction of top-of-atmosphere radiances, retrieval and inversion algorithms
for inherent optical properties, validation against in-situ data
(e.g. BGC-Argo), and applications such as harmful-algal-bloom detection. Much of
the work targets data from NASA's **PACE** mission and complementary sensors
(MODIS, etc.).

## Repositories

| Repository | Description |
|---|---|
| [**ocpy**](https://github.com/ocean-colour/ocpy) | Core Python utilities and notebooks for ocean-colour analyses. |
| [**IOPtics**](https://github.com/ocean-colour/IOPtics) | Analysis and comparison of inherent-optical-property (IOP) algorithms — for, and hopefully by, the community. |
| [**xqaa**](https://github.com/ocean-colour/xqaa) | An algorithm for inherent-optical-property retrievals (a Quasi-Analytical Algorithm variant). |
| [**bing**](https://github.com/ocean-colour/bing) | Bayesian INferences with Gordon coefficients — bio-optical parameter retrieval via Bayesian inference. |
| [**retrieve-or-bust**](https://github.com/ocean-colour/retrieve-or-bust) | Our last, best effort at IOP retrievals. |
| [**correct-atmosphere**](https://github.com/ocean-colour/correct-atmosphere) | Python code to perform atmospheric corrections for ocean colour. |
| [**PAB**](https://github.com/ocean-colour/PAB) | PACE and BGC-Argo matchup analyses for validation. |
| [**habs**](https://github.com/ocean-colour/habs) | Tools and analyses for harmful algal blooms (HABs). |

## Getting started

Most repositories are Python packages or Jupyter notebooks — clone the one you
need and follow its own README for installation and usage. Issues, questions,
and contributions are welcome on the individual repositories.

## Contributing

These projects are built in the open and meant to be community resources. If you
work in ocean-colour remote sensing, we'd love your contributions — open an
issue or a pull request on any of the repositories above.
