
```dataview 
	TABLE without id
	file.outlinks AS "OUTGOING", 
	file.inlinks AS "BACKLINKS"
	WHERE file.name = this.file.name 
```
#meeting
- [ ]  =={{title}}== (@{{date}} {{time}})


# Links


# Attendees

# Agenda
%%  Write down the nain topic to discuss %%


# Notes
%%  Cover any key information disscused in the neeting %%


# Todo List
> [!todo] Active
> ```dataview
>  task
>  from [[]]
>  where !completed
> sort file.ctime desc
> ```

> [!todo] Completed
> ```dataview
>  task
> from [[]]
>  where completed
>   sort file.ctime desc
>   limit 10
> ```

