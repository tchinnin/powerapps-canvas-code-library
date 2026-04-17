# Sample YAML Snippet
![SampleCodeSnippet](/yaml-snippets/multi-steps/assets/multi-steps.jpeg)
## Description

Multi step progress indicateur with previous, current and futur step colors management.


## Usage instructions
Use a named formula : 
```
nfSteps = Sort(
    Table(
        {
            Label: "General informations",
            Code: "general",
            Order: 1
        },
        {
            Label: "Advanced informations",
            Code: "advanced",
            Order: 2
        }
    ),
    Order,
    SortOrder.Ascending
);
```

Use a global variable for current step :

`Set(glbCurrentStepOrder,1)`
