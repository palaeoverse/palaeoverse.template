This is a template package used in `pkgdown` websites for all Palaeoverse packages.

### Use in other Palaeoverse packages

Install this template locally:

```r
remotes::install_github("palaeoverse/palaeoverse.template")
```

Then, in the Palaeoverse package for which you want to render the website, all calls to `pkgdown` (e.g. `pkgdown::build_site()`) will automatically use this template.

### Update the brand file

The brand file in this repository needs to be updated when `_brand.yml` in `palaeoverse/resources` changes. In bash:

```
> cd inst/pkgdown/BS5/assets/
> quarto use brand palaeoverse/resources
```