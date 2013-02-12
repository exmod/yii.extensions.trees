yii.extensions.trees
====================

Provides a necessary functionality for dataful operation of type "nested sets", based on the Yii platform.

Logic installation for remote tree
----------------------------------
This module shall be child in relation to that module in which widget of remote tree is caused.

~~~php
//paste this in the "modules" section
'exmRemTree'=>array(
  //attention, model shall contain behavior of NestedSetBehavior
  'modelClass'=>'SomeModel',
)
~~~
