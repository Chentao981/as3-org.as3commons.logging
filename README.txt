as3-commons logging API releases for use as Git submodules in ActionScript or 
Flex applications.

****************************
* IMPORTING AS A SUBMODULE *
****************************

The following instructions assume that you have a git repository set up on your
application directory.

To import this package into your application, run :

----------
 Commands 
 
$  git submodule add git@github.com:collectivecolors/as3-org.as3commons.logging.git
                     {SOURCE_DIR}/org/as3commons/logging
                     
$  git submodule init

----------

Where :

 {SOURCE_DIR} is your root source folder.  
    
    If your repository is at the root source path then just use the package
    name, org/as3commons/logging 

*********
* NOTES * 
*********

1. We did not create and are not the maintainers of the as3commons logging 
   API.  Thanks to Christophe Herreman and team at 
   http://www.as3commons.org/as3-commons-logging/team-list.html! 
   
2. Please see http://www.as3commons.org/as3-commons-logging/index.html for more 
   information about the as3commons logging API.

3. The official svn repository from which this git repo is based upon is 
   http://as3-commons.googlecode.com/svn.
   
4. We will try to update this repository as close to actual svn release as 
   possible.  If you notice that this repo is stale then send us a message 
   and we'll update it.