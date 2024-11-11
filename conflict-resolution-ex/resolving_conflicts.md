### Cascading Algorithm - What style to apply?

#### Four Key Concepts:
1. Origin
    - Use this rule when two declarations are in conflict (specify same property for same target)
    - The last declaration is used
        - Recall HTML is processed sequentially, top to bottom
        - Note that external CSS is declared at the spot where it is linked to
2. Merge
    - Use this rule when two different CSS declarations target the same element, but specify different properties
        - Here we just use the properties from both. The element will get both properties
3. Inheritance
    - Use this rule if a parent element has a style
        - All children have that style unless overriden due to origin
4. Specificity
    - Most specific targeting is the style attribute on an element
    - Next most specific is an id attribute and then using the #sign
    - Using a class (the . syntax), a pseudo-class like :link, or attribute
    - Then we use the # of elements as a tie breaker