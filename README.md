# British-Monarchy-VEGA-Chart
British Monarchy chart built with VEGA, presented in Power BI Deneb visual


The chart primarily visualizes historical figures such as Monarchs, Regents, and others. Their lifetimes are depicted as white rectangles, with reign periods highlighted using colored rectangles inside. The color coding corresponds to the country they ruled—e.g., red for England, green for Ireland. Marriages are indicated by grey rectangles, while regents' reigns are shown in light green.


## Filters

The chart supports multiple filtering options to customize data visualization. Below are the available filters:

### Years (Between)

Allows filtering data based on a specific range of years.

### Monarch’s Timeframe

Filters monarch-related data from 20 years before a monarch’s birth to 50 years after their death.

### Reign House

Displays data within the timeframe of a ruling house, starting from the birth of the first monarch to the death of the last monarch in the house.


### Types of Person

Filters the types of persons displayed in the chart:

- Monarch
- Regent
- Spouse
- Parents
- Children


## Options

The following options control the display of additional data elements and relationships:

### Show Events

Displays major historical events in the background, spanning from the top to bottom of the chart. Events are color-coded by sentiment.

### Show Birth Lines

Displays relationships between parents and children.

### Show Succession Lines

Shows the connection between predecessors and successors.

### Show Spouse Connections

Highlights relationships between married individuals.

### Show Reign Houses

Marks the reign periods of monarch houses in the background.

### Show Death Marks

Indicates the type of death with specific icons:


### Show Legend

Displays a legend beneath the chart for reference.


### Fit Selected Years

Zooms into the selected years, ensuring that only those years appear on the screen. Persons whose lifetimes partially fall within the selected years remain visible.


### Cut Off by Life Years

Hides individuals who do not fully fit into the selected years. Only those whose entire lifetime falls within the specified period remain visible.


### Use Hyperlinks on Click

Enables hyperlink mode, allowing users to open Wikipedia articles by clicking on a person or event.


### Show Tooltips

Displays additional information when hovering over persons or events.


## Behavior of Time Filtering Options

### Fit Selected Years

By default, persons are displayed if any part of their lifetime falls within the selected period. Selected years are marked with dotted lines. This option zooms in to display only the selected years while keeping partially fitting individuals visible.

### Cut Off by Life Years

This option hides individuals whose lifetimes only partially fall within the selected period, ensuring only those fully within the period remain visible.

## Selection Behavior

If **Use Hyperlinks on Click** is disabled, clicking on a person selects them, filling their area with dark grey.
