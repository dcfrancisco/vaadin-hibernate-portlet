Vaadin Hibernate Portlet Example
=====

This is an attempt to port the [Vaadin hibernate example application][vhbn] to a Liferay portlet and ported to be built using Maven. For more info, see the [original project in Vaadin incubator][vhbn], [Developing Vaadin Applications as Liferay Portlets][vplt], and [Using Vaadin with Maven][vmvn].

This example now uses the [HbnContainer Vaadin Add-on][hbnpl]. 

*This portlet currently will deploy, but does nothing. Hope to have this fixed in the future, but please feel free to contribute.*

Feel free to contact me via GitHub about it/submit issues to this GitHub project or leave a note on [this Vaadin forum thread][forumthread].

### Build the Portlet

Install Maven and Java and build with:

    mvn clean install

### Deploy the Portlet

Copy the portlet war in target/vaadin-hibernate-portlet.war to your (Liferay)/deploy directory to deploy.

### License

All modifications to the [original application][vhbn] are released under the copyright (c) 2011 Gary S. Weaver, released under the [MIT license][lic]. The [original application][vhbn]'s license is unknown but is open source and probably falls under the [Apache 2.0 license][apache]. Vaadin is released under the [Apache 2.0 license][apache]. 

[vhbn]: http://dev.vaadin.com/svn/incubator/hbncontainer/
[vplt]: http://www.liferay.com/web/guest/community/wiki/-/wiki/Main/Developing+Vaadin+Applications+as+Liferay+Portlets
[vmvn]: http://vaadin.com/wiki/-/wiki/Main/Using%20Vaadin%20with%20Maven
[hbnpl]: http://vaadin.com/directory/-/directory/addon/hbncontainer
[lic]: http://github.com/garysweaver/vaadin-hibernate-portlet/blob/master/LICENSE
[apache]: http://www.apache.org/licenses/LICENSE-2.0
[forumthread]: http://vaadin.com/forum/-/message_boards/view_message/442390