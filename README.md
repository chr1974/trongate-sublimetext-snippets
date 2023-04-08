# trongate-sublimetext-snippets
Some simple Trongate Framework Snippets for sublime text 4 based of off
[Jakecastelli's trongate-vscode snippets](https://github.com/jakecastelli/trongate-vscode "jakecastelli\trongate-vscode Github")

Contributions Welcome!

####Triggers used currently:
+ **tgc**         - Creates a class that extends Trongate
+ **tg:submit**   - Creates a submit function
+ **tg:for**      - Creates a foreach loop in a Viewfile
+ **tg:if**       - Creates a if condition in a Viefile
+ **tg:ifelse**   - Creates a if else condition in a Viewfile

to use the snippets navigate to: **C:\Users\<your_username>\AppData\Roaming\Sublime Text\Packages\User**
and add the trongate-snippets folder into that folder.

#### example snippet

```
<!-- your snippet goes here, tab positions should be marked ${1}, ${2} and so on... $0 marks where last tabstop ends -->
<!-- before php variables $var we must put a single \ in fron for var to show \$var -->
<snippet>
   <content><![CDATA[
      if (${1}) {
        ${2}// do suff if here
      } else {
        ${3} // do other stuff here
      }
   ]]></content>
   <description>Add a description for the snippet, will show in dropdown list</description> <!-- optional (filename as default description if not used) -->
  
   <tabTrigger>add the keyword that triggers the snippet on TAB (us tg:) as prefix and check that it is not in use by the other snippets first.</tabTrigger>
    
   <!-- <scope>source.php</scope> -->
   <!-- optional use source.php if the file already starts with <?php and only php is used in source file, or commet it out if you want it to show in all places --> 
</snippet>
```

