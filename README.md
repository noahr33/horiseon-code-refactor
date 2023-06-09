# Horiseon Code Refactor Description

In this project I refactored the code in the following ways:

* **Added a proper title description** 
* **Added the missing anchor element destination**
* **Added alt attributes for correct accessibility practices**
* **Simplified CSS code by combining selectors that share the same attributes**

***

# Link

https://noahr33.github.io/horiseon-code-refactor/

***

# Screenshot

<img src="assets/README-assets/Screenshot 2023-06-05 at 5.56.18 PM.png" width="80%">

***

## DRYing up the code example

By combining the selectors that share the same attributes, the code becomes less cluttered and easier to read.

### Before

<img src="assets/README-assets/Screenshot-2023-05-30%20at%2010.36.43%20PM.png" width="40%">

### After

![CSS code after](assets/README-assets/Screenshot-2023-05-30%20at%2010.42.05%20PM.png)

****

## Using the anchor element to quickly navigate to a specific page loaction.

```
<a href="#search-engine-optimization">Search Engine Optimization</a>
```
By adding the id of the element as the anchor destination, the user will be brought to that elements location when clicked.