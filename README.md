[![Netlify Status](https://api.netlify.com/api/v1/badges/e55b8400-46c3-44b0-96d1-cb101549dd1a/deploy-status)](https://app.netlify.com/sites/create-groups/deploys) [website](https://create-groups.netlify.app/)
# Create Groups

This projects helps people create groups based on the items provided.


# What Are some of the Task 

1. Groups based on items 

```javascript
// Example

const grouping = (items, noPerGroup) => {
    // group the items[] by the number per group
}
```

2. Allow CSV Upload 

```javascript
// Example

const upload = (file, columnName, noPerGroup) => {
    // columnName -> the colunm we are pulling the numbers from -> can advance this in the future
    // check the type of file, for now allow - Array, JSON, CSV and xls
    // convert JSON, then Array -> or direcly to array.
    // Call the grouping function to perform grouping.
    const items = file // data after pulling from file
    const results = grouping(items, noPerGroup)
    return results
}

```

3. Allow Spreadsheet Upload 

```javascript
// Make sure can upload spreadsheet 
// Make use of upload function shown above

```

4. Save in computer/phone local storage

```javascript
// Save to local storage for sometime. (and display)
// localStorage.setItem(), etc methods

```


5. Other ideas 
    a. Allow multiple selection using other characters e.g gender balance groups
    b. Think of other metrics

# Example 


Take for instance, `[student1, student2, student3, student4, student5, student6]` and group them into groups of `2 students`, example of result might be:
```
Group 1 - [student1, student3]
Group 2 - [student2, student6]
Group 3 - [student4, student5]
```

# Contributors 

<a href="https://github.com/momi-foundation-coding/create-groups/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=momi-foundation-coding/create-groups" width="30" />
</a>
