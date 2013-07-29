gridlover-less
==============

xy-grid from http://www.gridlover.net/

inspired by https://github.com/sevenupcan/gridlover-mixin

config
------
```
// import mixin
@import 'rhythm'
// rhythm config
@body-font-size : 16px;
@body-line-height : 1.5;
@scale-factor : 1.680;
```

mixins
------
Default rhythm
 
```
.rhythm(@font-scale, @margin-before, @margin-after)
 ```
 
Size element height to vertical-rhythm
 
```
.rhythm-height(@font-scale)
 ```
 
Size element square (height & width) to vertical-rhythm
 
```
.rhythm-square(@font-scale)
 ```