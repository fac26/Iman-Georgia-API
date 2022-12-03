# Iman and Georgia's HTTP Project

---

## Marvel and Films hackesque site

### Aims

We decided to combine the Marvel API and the TMDB API to create a site that you 'hack' into to access the data. 

From here you can 'fetch' the data of all your favourite Marvel characters, as well as the movies and then their feature character films. 

### Progress

The Marvel API is complex to work with without a backend, so we have explored the use of Md5 to keep keys secure. 

As a buffer, we created a generic films and television fetch using the TMDB API in a section called 'Moving Pictures'.

We are currently working on better connecting the two, as the Moving Pictures site works on switching between one page that renders the display on and off for searching to create a more seamless experience for the user. However, this has posed problems in connecting the two APIs more seamlessly. 

---

## How to explore the files

To view a live deplyment of the moving pictures element go [here](https://fac26.github.io/Iman-Georgia-API/)

The files which are working are currently in the <code>main</code> branch. 

1. Clone the repo
2. Select the <code>moving-pictures</code> folder
3. The live view is of <code>index.html</code> from within this folder. 

### How Moving Pictures works

1. Enter a film or tv programme to search
2. Click search or press Enter on your keyboard to reveal the results
3. Select a film to open a panel revealing more detail

---

## Notes on Accessibility

The site is not yet as accessible as we would like. There are improvements to be made on navigation and explorations to made on rendering alt-text for a plethora of unknown results. 


