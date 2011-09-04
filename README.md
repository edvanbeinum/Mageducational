# Magento Admin Module Boilerplate Thing

An educational Magento Module commented the way you wish the Core was.

## Using the Ant Buildfile

* Install [Ant](http://ant.apache.org/manual/install.html)
* Copy <code>build.default.properties.example</code> to <code>build.default.properties</code> and then edit the <code>deploy.dir</code> to point to the root folder of a  Magento installation on your local machine.
* Then from the same directory as <code>build.default.properties</code> run <code>ant build</code>. This will copy all the module files into your Magento installation and enables them.
* Clear Magento cache and refresh the page