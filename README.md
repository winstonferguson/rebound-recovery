# Rebound Recovery 

Shopify theme built off Dawn reference theme: https://github.com/Shopify/dawn.

## Customizations 

Theme specific files are prepended with "rr-" to avoild name clashes.

### Settings

### Styles 

Overrides take place in the original declaration locations. 

Theme specific sections have specific stylesheets.

### Sections

Header

Has been revised to facilitate full image landings on the homepage.

rr_capsule_details

Section designed for capsules, adhering to the Figma design specifications. This segment is utilized on product pages.

rr-feature

This section is rendered beneath the landing image on the homepage, integrating a product form with badges and images.

### Snippets

rr-grid-styles

Displays the style settings for a section's RR grid layout. RR grid layout settings enable a multi-column layout that can include sections within each column.


rr-multipack-qty-selector

If multipacks is activated through Product metadata, this code snippet manages the quantity input. 

Note: multipack ordering was originally developed to streamline batch orders while ensuring accurate inventory management (as opposed to using variants for product bundles). However, this feature is now obsolete, as the store utilizes an app to synchronize inventories across variants.
