# midstone.cc

The Midstone landing page: one static page, served by GitHub Pages at https://midstone.cc.
Built by the Product: Platform chat from Marketing's copy and Brand's kit (Midstone repo: `marketing/website/`, `brand/`).
Nothing here is private. No trackers, no cookies, no forms on the page: the buttons link out to the forms.

## Contact address

The contact email appears in index.html (footer, structured data, sign-up note), privacy/index.html and terms/index.html. To change it everywhere at once:

    sed -i "s/OLD@example.com/NEW@example.com/g" index.html privacy/index.html terms/index.html

privacy/ and terms/ are built from the CMO's markdown (thientheman/midstone, business/legal/site/); rebuild them after a text change.
