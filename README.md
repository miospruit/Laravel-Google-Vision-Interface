
# Info

This is an interface for google vision API within Laravel.

## Installation

Use the package manager composer for the installation.

```bash
composer install google/cloud-vision
```
Next set up the Google Cloud CLI.



## Usage
Next, you only need to add this file to your project and use this code to use the Google Cloud Vision Api:
```php
$detectornator = new LabelDetection;
$labels = $detectornator::tags('$your_image');
#In the $labels variable are the created tags for the image.
```


## License
[MIT](https://choosealicense.com/licenses/mit/)
