---
layout: post
title: Type Casting in ET Programming Language
---

Some programming language does not require explicit type definition in the variable declaration.

That is to say, if an integer value is assigned to the variable $value, $value becomes an integer.
If a string value is then assigned to $value, it becomes a string.

a variable's type is determined by the context in which the variable is used. (automatic)

#### An example:


```
main()
{
	age=5+1+2+4*2
	
	ab=5*4+4*1
	ab=4+100-5*2*4.6
	
	an=4.6

	ab=5*(4-1)
	ab=5*4-1
}
```


In the code above, it is noteworthy that there is a possibility to change the value of the variable.

And when changing the value, its type may also change.
This is done in the code above.

So Compiler can be expected to display an error(not warning). Or does it automatically perform conversion work?

Deciding which one is the best option... It's not easy.
And there are certainly discussions between the Compiler specialists.
Because each person makes a claim to a good one for reasons of the benefits.

