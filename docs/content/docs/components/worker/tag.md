---
title: "tag"
notitle: true
notoc: true
---
# worker tag

`worker tag key=value key=value`

## Synopsis


On the workflow view, the sidebar on the left displays a select box to filter on CDS Tags.

So, what's a tag? A tag is a CDS Variable, exported as a tag. There are default tags as git.branch, git.hash, tiggered_by and environment.

Inside a job, you can add a Tag with the worker command:

	# worker tag <key>=<value> <key>=<value>
	worker tag tagKey=tagValue anotherTagKey=anotherTagValue


Tags are useful to add indication on the sidebar about the context of a Run.

You can select the tags displayed on the sidebar Workflow → Advanced → "Tags to display in the sidebar".

![Tag](/images/worker.commands.tag.png)
		

```
worker tag
```

## SEE ALSO

* [worker](/docs/components/worker/worker/)	 - CDS Worker

