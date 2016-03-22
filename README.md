# Internet Explorer View Mode

A simple Drupal module to add the X-UA-Compatible HTTP header to all pages
regardless of theme or area.

## Requirements

* Drupal 7.x

## Configuration

The module starts working as soon as it is enabled. You can verify the module
is working by inspecting the headers of the page and looking for the
X-UA-Compatible header. By default, it is set to 'IE=edge,chrome=1'.

The module also supports other Internet Explorer modes if there is a need for
them. Configuration of the module is found in Configuration -> User interface.

The available options are currently limited to Internet Explorer 7, 8, 9, and
Edge. These modes set the HTTP header record to something like "IE=EmulateIE9".
While it is unlikely these modes will be needed, they are available.
