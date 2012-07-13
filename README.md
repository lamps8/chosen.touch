# Chosen.touch

Chosen.touch is a fork of the [Chosen](https://github.com/harvesthq/chosen/) library that allows you to optionally trigger native UI select pickers on touch based devices while maintaining Chosen styles and typical Chosen behavior on non-touch devices. 

- jQuery support: 1.4+
- Prototype support: 1.7+

I have also included a retina friendly version of the sprite for extra hotness on high density displays. The retina image is triggered by media queries, so there is no setup required.

### Usage

jQuery:

```
$(".chzn-select").chosen({touch:true})
```

Prototype:

```
new Chosen(some_form_field,{touch:true});
```

### Credits

- Built by [Harvest](http://www.getharvest.com/). 
- Concept and development by [Patrick Filler](http://www.patrickfiller.com/)
- Design and CSS by [Matthew Lettini](http://matthewlettini.com/)
- Chosen.touch fork by [Ben Markowitz](http://www.benmarkowitz.com)

### Other Forks

- [Chosen for MooTools](https://github.com/julesjanssen/chosen), by Jules Janssen
- [Chosen Drupal 7 Module](http://drupal.org/project/chosen), by Pol Dell'Aiera, Arshad Chummun, Bart Feenstra, Kálmán Hosszu, etc.
- [Chosen CakePHP Plugin](https://github.com/paulredmond/chosen-cakephp), by Paul Redmond
