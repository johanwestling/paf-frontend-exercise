# Paf frontend exercise

Translate the provided [designs (for small & large viewports)](#designs) into a working solution with HTML, CSS and JavaScript.

## Requirements

- Use HTML introduces meaning to the elements.
- Use JavaScript to load JSON-data & render the lists.
- Layout with support for viewport widths ranging from (at least) 320-1920px.
- Works in modern browsers.

_You are allowed to make adjustments to the design/layout if needed._

## File structure

```bash
src/index.html      # The place to author your HTML.
src/styles.css      # The place to author your CSS.
src/scripts.js      # The place to author your JavaScript.
dist/data.js        # The JSON-data to load & use in your JavaScript.
```

## Loading data

The JSON-data is requested from the following url:
```
./data.json
```

<br>

---

<br id="designs">

## Designs

### Small viewports

![Small viewports](./design/small-viewports.png)

### Large viewports

![Large viewports](./design/large-viewports.png)

<br>

---

<br id="development-setup">

## Development setup

Start coding directly on [codesandbox.io](https://codesandbox.io/s/github/johanwestling/paf-frontend-exercise) or use the provided localhost setup to develop your solution.

_**Note:** You'll nee to have **Git** & **Node.js** v10 (or higher) installed for the provided localhost setup._

```bash
# Clone paf-frontend-exercise.
git clone https://github.com/johanwestling/paf-frontend-exercise.git

# Change directory to where you cloned paf-frontend-exercise.
cd paf-frontend-exercise

# Start the localhost server.
npm start
```

