# re::phrase 
re::phrase is a shorthand convention for writing plain text blocks as strings that are friendly to array value conversion.

The convention helps content and code collaborators work together with pre-decided project-based rules on how they will use the structure.

# The Convention
&#35;&#35; for text blocks<br>
:: for subtext items<br>
** to mark favourites<br>
all fields are optional<br>
whitespace is to be ignored 

# Structure

```
pretext
## text 1
## text 2**
## text 3
	:: subtext 1**
	:: subtext 2
	:: subtext 3
	:: subtext 4**
## text 4**
```

or, in single line

`pretext ## text 1 ## text 2** ## text 3 :: subtext 1** :: subtext 2 :: subtext 3 :: subtext 4** ## text 4**`

or, even shorter

`pretext##text 1##text 2**##text 3::subtext 1**::subtext 2::subtext 3::subtext 4**##text 4**`

## How is it different from JSON
The re::phrase convention is only for structuring values, and not key-value pairs, whereas JSON provides a robust convention for key-value pair structuring. Re::phrase can be quickly typed with less changes of mistakes, JSON is difficult to write without JSON validator.


## How is it different from Markdown
This is for plain text values - typically text or texarea input fields in HTML.


## Examples
In a typical scenario, this can replace the use of multi-input fields from CMS dashboards / form inputs, or add additional complexity handling to them.

![re::phrase examples](https://wildfiretech.co/uploads/2022/03-March/01-Tue/rephrase-examples.png)

## More info and contact
https://wildfiretech.co/page/our-approach<br>
https://github.com/wil-ldf-ire

![Wildfire logo](https://wildfiretech.co/theme/assets/img/logo-bg.png "Wildfire logo")