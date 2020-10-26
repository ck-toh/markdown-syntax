# Welcome to the markdown-syntax wiki!
[GitHub Extended Markdown](https://github.github.com/gfm/)

[Wiki](../../wiki/Markdown-Sytanx)

# Heading1
## Heading2
### Heading3
```markdown
# Heading1
## Heading2
### Heading3
```

## Text Formatting
*italic1*
**bold1**
~~strikethrough~~
_italic2_
__bold2__
```markdown
*italic1*
**bold1**
~~strikethrough~~
_italic2_
__bold2__
```
## Quotes
> _**Love your job but don't love your company, because you may not know when your company stop loving you.**_
>                
> Dr. APJ Abdul Kalam
```
> _**Love your job but don't love your company, because you may not know when your company stop loving you.**_
>                
> Dr. APJ Abdul Kalam
```


## List
- list1
  - list1a
     - list1a1
   
1. item1
   - item1a
      - item1a1

- [`release-0.13.5`](https://releases.hashicorp.com/terraform/0.13.5/): 0.13 series
* [`release-0.12.29`](https://releases.hashicorp.com/terraform/0.12.29/): 0.12 series
```
- list1
  - list1a
     - list1a1
   
1. item1
   - item1a
      - item1a1

- [`release-0.13.5`](https://releases.hashicorp.com/terraform/0.13.5/): 0.13 series
* [`release-0.12.29`](https://releases.hashicorp.com/terraform/0.12.29/): 0.12 series
```

## Tables
|table|heading|
|---|---|
|item1|value1
|item2|value2

### Table alignment uses `:`
|left|center|right|
|:---|:---:|---:|
|item1|value1|valuea|
|item2|value2|valueb|
```
|table|heading|
|---|---|
|item1|value1
|item2|value2

### Table alignment uses `:`
|left|center|right|
|:---|:---:|---:|
|item1|value1|valuea|
|item2|value2|valueb|
```

## Adding Icons, Pictures and Badges
```
https://github.com/simple-icons/simple-icons
https://github.com/badges/shields
https://github.com/Naereen/badges
https://github.com/badges/shields/blob/master/doc/logos.md
https://github.com/codeSTACKr/codeSTACKr/readme.md

basic
![](url-to-images)
[text](link-to-url)

nested
[![]()](url-linked-to-image)
```
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)


[![Terraform](https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terraform/terraform.png)](https://www.terraform.io/)


![](https://techcrunch.com/wp-content/uploads/2020/10/Google-Workspace-Icons-bad.png?w=400)

## Hyerlinks
[ask Google1](https://www.google.com)


[ask Google2][askgoogle]

[askgoogle]:https://www.google.com

### Emoji
```
https://gist.github.com/rxaviers/7360908
:warning: :construction: :information_source:
```
:warning: :construction: :information_source:
---
### footnote

amazon.co.uk <sup id="a1">[1](#f1)</sup>

<b id="f1">1</b> Check out [amazon](https://www.amazon.co.uk)

```
Git don't support this style
Some long sentence. [^footnote]
[^footnote]: Test, [Link](https://google.com).
```
