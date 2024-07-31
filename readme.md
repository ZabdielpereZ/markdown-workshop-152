# Markdown workshop Lecture


---

#Basic Markdown Syntax 

##1. Headers

there are 6 sizes of headers denoted by 1-6 consecutive # symbols

**Examples:**

> # header size 1 
> ## header size 2
> ### header size 3
> #### header size 4
> ##### header size 5
> ###### header size 6

**syntax**
```md
# header size 1 
## header size 2
### header size 3
#### header size 4
##### header size 5
###### header size 6
```
## 2. Emphasis

we can make things **bold**
```md
**bold**
```

we can make things *italic*
```md
*italic*
```


we can also strike ~~through text~~
```md
~~through text~~
```


~~***we can also do this***~~
```md
~~***we can also do this***~~
```

we can also make things ***bold and italic***
```md
***bold and italic***
```

## 3. Lists

ordered lists

1. first thing
    - this is important 
    - another important thing
        - important about this other thing
            - another thing?!
2. second thing
3. third thing

unordered lists

- one thing
- another thing
- last thing


## 4. Links and Images

### Inserting Links
[Back to the top](#markdown-workshop-lecture)


[pokeAPI](https://pokeapi.co/ "Link to the PokeAPI website")

### Inserting Images

[an image if ditto]
(![alt text](https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/132.svg)

![](132.svg)

--------

## Advanced Features 

### Tables 

**Syntax**
```md
| parameter | Type | Description |
|---|-----|-----|
|`first_name` |`string` | Required |
|`email` |   `string`| Required |
```

| parameter | Type | Description |
|---|-----|-----|
|`first_name` |`string` | Required |
|`email` |   `string`| Required |

### Code `Blocks`

```
simple code block
pip install this
```
```python
def solution():
    this = "that"
    for i in range(0, 20, 2):
        print(i)
    return this
```
```bash
git init 
git add .
git commit -m "first commit"
git remote add origin <link>
git push -u origin main
```



### Block Qoutes

> A block qoute could be a side note, futher info about a certain step, prehaps a definition for something.

### Definitions

What is an ORM?
: An ORM is an Object Relational Mapper that helps us relate a coding language like python into SQL queries

What is an ORM?
> An ORM is an Object Relational Mapper that helps us relate a coding language like python into SQL queries

