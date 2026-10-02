# Royal English Bulldogs

Static, single-page website. The entry point is `index.html` in the repository
root.

## Deploy to Render

This repository includes a `render.yaml` Blueprint for a Render Static Site.
In Render, choose **New > Blueprint**, connect this repository, and deploy the
Blueprint. Render publishes the repository root, where `index.html` is located,
and rewrites direct page requests to that file.

To create the site manually instead, choose **New > Static Site**, connect this
repository, leave the root directory blank, use `echo "Static site ready"` as
the build command, and set the publish directory to `.`.
