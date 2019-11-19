# GIT Best Practices

Best practices for making great commit messages

## Documentation

### First Line

[Identifier] #Labels 'Specification'

### Second Line

<Task-ID>

### Third Line

{Comment}

#### Informations

* [Identifier]
	* The function ID

* #Labels
	* #INIT – Initializes a repository or a new release
		* repro: documentation / configuration …
		* archetype: jar / war / ear / pom / zip …
		* version: version
	* #IMPLEMENT – Implement a new feature
		* function: clazz
	* #CHANGE – Change an existing function
		* function: clazz
	* #EXTEND – Extend an existing feature
		* function: clazz
		* attach: clazz
	* #BUGFIX – Error correction
		* priority: critical / medium / low / design
	* #REVIEW – Quality control
		* refactor: function
		* analyze: quality
		* migrate: function
		* format: source
	* #RELEASE – Completion of an artifact for delivery
		* version: version
	* #REVERT – Withdrawal of a revision
		* commit: id
	* #BRANCH – Create a branch
		* create: name
		* stash: branch
	* #MERGE – Merging a branch
		* from: branch
		* to: branch
	* #CLOSE – Close a development branch
		* branch: name

* 'Specification'
	* function
	* attach
	* priority
	* reactor
	* analyze
	* migrate
	* format
	* version
	* commit
	* create
	* from
	* to
	* branch

* Task-ID
	* Alphanumeric characters

* {Comment}
	* The comment of this task

## Example

```bash
git commit -m "[CORE-0001] #INIT 'repro' <Core-00001> {Initial the repository.}"
```
