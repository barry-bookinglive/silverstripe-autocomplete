silverstripe-autocomplete
=========================

## Description
Autocomplete text field for Silverstripe

## Example usage
AutoCompleteField::create('MyDataObject','MyDataObject')
			 ->setSourceClass('MyDataObject')
			 ->setSourceFields('MyDataObjectFieldName')//this can be an array of different fields o nthe same object
			 ->setLimit(10);//limits the number of suggests returned at once
