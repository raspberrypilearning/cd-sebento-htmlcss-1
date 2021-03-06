## Making a list

Now you will learn how to turn a list of items, such as "unicorns, robots, cats", into a nicer-looking list that you can do cool things with later.
  
- In the `index.html` file, add the following code just above the line with `</main>` on it:

```html
    <ul>
        <li>Barn owl</li>
        <li>Hen harrier</li>
        <li>Yellowhammer</li>
        <li>Curlew</li>
    </ul>
```

The result should be a nice list like this: 

![Unordered list](images/egUnorderedList.png)

Notice that there is a separate pair of `<li> </li>` tags around each item in the list. 

This is a list of some protected birds in Ireland. You can change the items on the list to things that make sense for your website, and add a paragraph above the list to describe what it's a list of, if you like!

How about if you wanted a numbered list? It's almost the same, but instead of `<ul>`, you use `<ol>`. A numbered list is also called an **ordered** list. 

- Add the following code below the code you just wrote — make sure it's **below** the `</ul>` tag!

```html
    <p>
        Threats to birds:
    </p>
    <ol>
        <li>Habitat destruction</li>
        <li>Pollution</li>
        <li>Climate change</li>
    </ol>
```

Here's what it should look like now:

![Ordered list](images/egOrderedList.png)

--- challenge ---

## Challenge: add style to your lists

- See if you can add **CSS rules** to your stylesheet to change how your lists look.

--- /challenge ---
