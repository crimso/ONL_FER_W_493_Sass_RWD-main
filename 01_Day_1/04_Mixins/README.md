![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)


> ### Setup
> Modify `package.json` so that the `source` variable points to:
> -  `01_Day_1/04_Mixins/01_Exercise_1`
>
> **Remember that after each change in `package.json` you should stop Parcel (`CTRL+C`) and run it again (`npm start`).**

## Exercise 1 - done with the lecturer

Create a mixin called `headerFont` that will set font size for the `header` element based on the `$font` parameter passed to it. Additionally, it should set `border-radius` to `5px`.


> ### Setup
> Modify `package.json` so that the `source` variable points to:
> -  `01_Day_1/04_Mixins/02_Exercise_2`
>
> **Remember that after each change in `package.json` you should stop Parcel (`CTRL+C`) and run it again (`npm start`).**


## Exercise 2

Create a mixin named `dialogBox` that will take two parameters - color ($backgroundColor) and box width ($width). Its task will be to set styles for the element with `dialog` class.

```
  width: $width;
  padding: 10px;
  background: $backgroundColor;
  border: 1px solid black;
  margin: 40px auto;
```

In the mixin, add a `:after` pseudo-element that will create a 10x10px square that decorates the box. The final effect should be the following:

![Dialog](images/dialog.png)

Test your code for `green` and `lightgray` background, and also test it with random widths.


ï»¿> ### Setup
> Modify `package.json` so that the `source` variable points to:
> -  `01_Day_1/04_Mixins/03_Exercise_3`
>
> **Remember that after each change in `package.json` you should stop Parcel (`CTRL+C`) and run it again (`npm start`).**

## Exercise 3

Create a mixin named `disabledHover`. It should use the `@content` directive to style a button with a `hover` state. The button is inactive (it has a `disabled` attribute).
