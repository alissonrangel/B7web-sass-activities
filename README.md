# B7web Sass Course Activities Repository

# Sass on the command line
- npm install -g sass
- sass assets/sass/styles.scss assets/css/styles.css --no-source-map
- sass assets/sass/styles.scss assets/css/styles.css --no-source-map --style compressed

## Monitoring specific file
- sass assets/sass/styles.scss assets/css/styles.css --no-source-map --style compressed --watch

## Monitoring all files in the folder
- sass --watch assets/sass:assets/css --no-source-map --style compressed
