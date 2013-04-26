bootstrap-checkbox
==================

A checkbox component based on bootstrap framework

## Author
[Roberto Montresor](https://github.com/montrezorro)

## Documentation
You can find demo and documentation [here](http://montrezorro.github.io/bootstrap-checkbox).

## Usage

Create your `<input type="checkbox">` with the `.checkbox` class.

    <input type="checkbox" class="chekbox" />
    <input type="checkbox" class="chekbox" checked="checked"/>
    <input type="checkbox" class="chekbox" disabled="disabled"/>
    <input type="checkbox" class="chekbox" checked="checked" disabled="disabled"/>
	
    
Enable Bootstrap-checkbox via JavaScript:

    $('.checkbox').checkbox();

Or just

    $('input[type="checkbox"]').checkbox();

## Options

Options can be passed via data attributes or JavaScript.

    $('input[type="checkbox"]').checkbox({
      buttonStyle: 'btn-link',
      buttonStyleChecked: 'btn-inverse',
      checkedClass: 'icon-check',
      uncheckedClass: 'icon-check-empty',
	  
      checked: false,
      enabled: true
    });

You can append or prepend a label via the `data-label` or `data-label-prepend` attribute.

## Methods

    $('input[type="checkbox"]').checkbox('click'); // change input's state
    $('input[type="checkbox"]').checkbox('toggleEnabled'); // change input's enabled
    
## Copyright and license

Copyright (C) 2013 Roberto Montresor

Licensed under the MIT license.
