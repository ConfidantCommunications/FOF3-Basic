# FOF3 Basic
A hello world type example for Akeeba FOF3  as a walkthrough for building a Joomla! conponent from the ground up.

**Note:** This step in the tutorial assumes you have FOF3 installed. If not, you can get an FOF3 install package from http://Akeebabackup.com

**Note2:** This step in the tutorial also assumes you have set up your component on a development site (local recommended). That means your Joomla development site needs your component installed with the database tables. You could also set up your tables, copy the files to the site, and add a record to the #__extensions table so you could browse directly to the component via [yoursite url or local url]/administrator/index.php?option=com_[your component's name i.e. fof3basic]... (but an install is easier since you have a menu item to work with)

## Step 5 - Code Clean-Up and Customization
Congratulations, we have now created a vary bare bones Joomla component with FOF3. What's next? Well, we still need to clean up the Language strings since the Scaffolding feature's autogenerated strings are not perfect constructs. With this component frame in place, we can move on to implementing our specific application code and any additional views we may want. Since these items are specific to each project we'll stop here for now. 

### For details see the following FOF3 documentation links
- [Getting started with an FOF component](https://github.com/akeeba/fof/wiki/Getting-started-with-a-FOF-component)
- [The fof XML configuration file](https://github.com/akeeba/fof/wiki/The-XML-configuration-file)
- [FOF3's Dependency injection container and HMVC](https://github.com/akeeba/fof/wiki/The-Container)
- [Choosing your Factory or how much "magic" you want](https://github.com/akeeba/fof/wiki/The-Factory)
- [The Controller or the DataController](https://github.com/akeeba/fof/wiki/The-Controller)
- [Model, DataModel or TreeModel](https://github.com/akeeba/fof/wiki/The-Model)
- [View or DataViewInterface](https://github.com/akeeba/fof/wiki/The-View)
