# Google-charts-utils
Its not straightforwad preparing data to work with Google Charts, effort at a few utility classes to bend it into a more usable form

## The problem
your data is probably not in a format that you can export straight into Google Charts - Google charts require the data to in a specific JSON format which generally takes some massaging to achieve. You can get a long way with databases/SQL, pivot tables and the like, but it still needs JSON'ing appropriately.

## The solution
some utility classes for data formatting - a conveniant 2 or 3 dimensional collection which will output its contents in google-charts compatible JSON format
