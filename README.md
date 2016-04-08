# Tasty Backend Article

The Tasty Backend Article content type.

This module adds a "Tasty Backend" Article if one does not already exist. It checks for the content type machine name **article**if it is found it does not create a "Tasty Backend" version of the Article.

#### Options for using this module on a Drupal installation that already has a content type with the machine name **article**.

If you are using this module without the Tasty Backend Installation Profile you will find that it does not change the current Article into a Tasty Backend one. Here are a few options on how to remedy this.

* Change the machine name of the current content type to something other than **article** then install.
* Delete the content type with the machine name **article** then install.
* Change the machine name of the content type to be createdd to something other than **article**. To do this fork this project and replace the four instances of **'article'** with you new machine name, maybe **'tasty_article'**. You may also want to change the name of the content type to something other than **'Basic article'**. Just replace the one instance of **'Basic article'** with something else, maybe **'Tasty Backend article'**

### RDF module
If the RDF module is not a dependency but if it is installed RDF mappings will be create during the installation.

### Views module
