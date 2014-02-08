hmt-app-skin
============

Configuration files to skin CITE-Servlet for the Homer Multitext Project.

This package consists of:

- A custom `build.gradle` file.
- Custom `conf.gradle` and `links.gradle` files
- A custom `home` file.
- A custom `svcforms` file.

These will be applied to the [CITE Servlet](https://github.com/neelsmith/citeservlet) package at build time.

**N.b.** For proper skinning, the file `cite-core.css` (from [the `hmt-core-css` repo](https://github.com/Eumaeus/hmt-css-core) should be copied into `/src/main/webapp/css/` in the servlet.
