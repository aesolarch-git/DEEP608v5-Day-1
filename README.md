# DEEP608v5-Day-1

 - [ ] Next, we will add a trigger for our workflow
    ```yaml
	on:
		push:
			branches: [ main ]
			paths:
			- 'infrastructure/**'
		pull_request:
			paths:
			- 'infrastructure/**'
	```
  --- my fix
 ```yaml
  on:
    push:
      branches: [ main ]
      paths:
      - 'infrastructure/**'
    pull_request:
      paths:
      - 'infrastructure/**'
```
  
   - [ ] Next, we will add a trigger for our workflow
```
&nbsp; ONE
	 Tab Space
> Arrow
> > Two Arrow

* one
	+Two Plus
	 One Tab Space
	 	 Two Tab Space
	  One Tab Two Space

	 One Tab Space
	 	 Two Tab Space
	  One Tab Two Space
--- my pasted fix
 on:
   push:
     branches: [ main ]
     paths:
     - 'infrastructure/**'
   pull_request:
     paths:
     - 'infrastructure/**'
