---
author: Cory House
date: 2021-09-14
tags: ['react', 'state-management']
aliases: ['state management in react', 'state tips react']
createdAt: 2021-11-01
---
# 10 lessons handling React State
[](https://twitter.com/housecor/status/1437765667906854915)

[Thread Here](https://threadreaderapp.com/thread/1437765667906854915.html)

## Synopsis: 

### Ways to handle State in react
1. URL
2. Web Storage
3. Local State
4. Lifted State
5. Derived State
6. Refs
7. Context
8. Third Party Lib

### Tips
##### Normalize state by deriving on render
create stateful properties that are derived from existing state/props
- example: `hasErrors` stateful property based on length of an errors array

#### Understand when React renders
A state change
- avoid using `shouldComponentUpdate` or `React.Memo`

A prop change or parent renders
- avoid using `shouldComponentUpdate` or `React.Memo` or `PureComponent`

Context change

#### Use Enums to represent a set of states

``` typescript
enum STATUS {
	"IDLE",
	"SUBMITTING",
	"SUBMITTED",
	"COMPLETED"
}
```



#### Example Usecases using tips above
Form Management
![[Pasted image 20211101143825.png]]



















































