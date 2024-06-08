# PDF Redactor Example
## Description

The CSS snippet for PDF Redactor excludes specific information from PDF exports on the fly. This method is convenient for generating documents or sharing information while preserving the base markdown.

## Use:

To utilize the function, use a combination of a hashtag to select the redactor function and flag the text that should be omitted.

```
#r/function ==Text Goes Here==
```
---

- “#r/obscure”
	- Omits text within using a black box
- "#r/hide"
	- Hides text entirely with no style
- "#r/replace"
	- Replaces text with preconfigured text
- “#r/blur”
	- Omits text using a blur
## Examples

#r/obscure ==Obscure this text==

#r/blur ==Blur this text==

#r/hide  ==Hide this text==

#r/replace ==Replace this text==
