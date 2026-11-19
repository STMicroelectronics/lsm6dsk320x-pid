---
pagetitle: Release Notes for LSM6DSK320X Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for LSM6DSK320X Component Driver
Copyright &copy; 2026 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the LSM6DSK320X component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section2" checked aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V2.0.0 / 19-Nov-2026</label>
<div>

## Main changes

- Fix MISRA issues

  **Breaking change: API renaming**

  API names have been updated to comply with **MISRA C:2012 Rule 5.1**, ensuring that
  external identifiers are distinguishable within their first 31 characters.

  This change breaks source and binary compatibility with previous driver versions.
  Applications must update all references to the renamed APIs and be rebuilt against the
  updated driver.

- Fix timestamp_raw_get() API
- reviewed indentation and doxygen doc

##

</div>

<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 07-Sep-2026</label>
<div>

## Main changes

### First release

- First official release [ref. DS v1.0]

##

</div>

:::


:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on LSM6DSK320X,
visit:
[LSM6DSK320X](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dsk320x.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 1.0">Info</abbr>
:::
:::
</footer>
