# EzCustomScheduleBlockTemplateBundle

This Bundle is using and extending the same example demonstrated in [Create a Schedule Block for Featured Articles]( https://doc.ez.no/display/DEVELOPER/Step+3+-+Using+existing+blocks) 

Important: This bundle is using article **with image as Content relation (single)** (aka ezobjectrelation). This is the article default ContetType delivered with the eZ Platform Enterprise Edition clean Installation. 

PS: The tutorial example (see link above) is using a simple **image** FieldType.


## Prerequisites
* **eZ Platform Enterprise Edition (clean installation)**

But using eZ Platform Open Source you can re-use the article and image Twig Templates (more infos in ezplatform.yml) to display different views of article having image as content relation. 

## Features
* Customizing the **article** schedule block template
* Understanding the workflow to access the content added with ezobjectrelation FieldType
* Quickly re-use this out-of-the-box bundle in different projects without changing or adding yaml files in app/config folder as well as Templates in Resources/view
* Using the same logic to extend schedule blocks for other articles or different ContentTypes 

## Installation
Clone or download the bundle in your src folder

Then add it to your application:

```php
// app/AppKernel.php

    public function registerBundles()
    {   
        $bundles = array(  
        // ...
        new EzCustomScheduleBlockTemplateBundle\EzCustomScheduleBlockTemplateBundle(),
        // ...
    );
}
```


## Usage
Please refer to the end of [Create a Schedule Block for Featured Articles]( https://doc.ez.no/display/DEVELOPER/Step+3+-+Using+existing+blocks) section.

## Screenshots
Inside the doc folder delivered with this bundle.