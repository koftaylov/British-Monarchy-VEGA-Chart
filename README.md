# British-Monarchy-VEGA-Chart

[English & British Monarchy Timeline](https://app.powerbi.com/view?r=eyJrIjoiNWMyMTkxYjktMWI2OS00ZjJiLWE0MGEtN2NlNjFlNzFlZjFiIiwidCI6IjRjNDFkY2ZjLTRkOWMtNGZiMi1iNGZmLWQ3YTZkNWM5NDM0YiJ9) chart built with VEGA, presented in Power BI Deneb visual

The chart primarily visualizes historical figures such as Monarchs, Regents, and others. Their lifetimes are depicted as white rectangles, with reign periods highlighted using colored rectangles inside. The color coding corresponds to the country they ruled—e.g., red for England, green for Ireland. Marriages are indicated by grey rectangles, while regents' reigns are shown in light green.

![image 8](https://github.com/user-attachments/assets/aaf6e702-ba60-4511-8969-c3685dd62bf4)



## Filters

The chart supports multiple filtering options to customize data visualization. Below are the available filters:

### Years (Between)

Allows filtering data based on a specific range of years.

![image 1](https://github.com/user-attachments/assets/1a954bd2-4b0d-4a91-87b3-e472f63abaef)


### Monarch’s Timeframe

Filters monarch-related data from 20 years before a monarch’s birth to 50 years after their death.

![image 2](https://github.com/user-attachments/assets/f9f29229-e893-4db2-b58a-9638d293986a)
![image 3](https://github.com/user-attachments/assets/a9818a23-fd46-4a74-8d8d-b7f6bb2c9b0e)


### Reign House

Displays data within the timeframe of a ruling house, starting from the birth of the first monarch to the death of the last monarch in the house.

![image 4](https://github.com/user-attachments/assets/17b6e8f2-d6c7-4674-8073-a9f6d9b1e930)
![image 5](https://github.com/user-attachments/assets/67e06983-c7d9-4c40-bad7-300c3e35210d)


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
![image 7](https://github.com/user-attachments/assets/a7b069bf-28ab-4372-af0c-0a33606acae0)

### Show Birth Lines

Displays relationships between parents and children.
![image 8](https://github.com/user-attachments/assets/4c15b827-9b73-402c-9736-73ba1d99c163)

### Show Succession Lines

Shows the connection between predecessors and successors.
![image 9](https://github.com/user-attachments/assets/efe5df2c-d1a1-4e86-b853-5ef62d8a5a04)

### Show Spouse Connections

Highlights relationships between married individuals.
![image 10](https://github.com/user-attachments/assets/10cb03d1-1a98-4017-9127-604572651bd0)

### Show Reign Houses

Marks the reign periods of monarch houses in the background.
![image 11](https://github.com/user-attachments/assets/718176a0-b8f6-4ea1-b6e8-1e5fa22c424b)

### Show Death Marks

Indicates the type of death with specific icons.
![image 12](https://github.com/user-attachments/assets/071061ab-015e-4417-9f1c-82ae97af27bc)


### Show Legend

Displays a legend beneath the chart for reference.
![image 13](https://github.com/user-attachments/assets/9e47a9ed-0417-4add-88a1-b714fbcdb1ed)


### Fit Selected Years

Zooms into the selected years, ensuring that only those years appear on the screen. Persons whose lifetimes partially fall within the selected years remain visible.
![image 14](https://github.com/user-attachments/assets/09455ee5-7cbf-4b2d-96aa-0f637cd1b564)
![image 15](https://github.com/user-attachments/assets/7dcdfbea-dcb5-44bf-8309-673671821823)


### Cut Off by Life Years

Hides individuals who do not fully fit into the selected years. Only those whose entire lifetime falls within the specified period remain visible.
![image 16](https://github.com/user-attachments/assets/0397cb70-1db6-42ac-8e20-8838efcbb12a)
![image 17](https://github.com/user-attachments/assets/ed0380dc-6082-4abc-8a1e-d2368b7bf6d0)


### Use Hyperlinks on Click

Enables hyperlink mode, allowing users to open Wikipedia articles by clicking on a person or event.
![image 18](https://github.com/user-attachments/assets/28bc8a5c-aec3-40d1-804a-c0f77f9ce4db)


### Show Tooltips

Displays additional information when hovering over persons or events.
![image 19](https://github.com/user-attachments/assets/e08094d5-6a9c-4192-ad08-9741c99081a2)


## Behavior of Time Filtering Options

### Fit Selected Years

By default, persons are displayed if any part of their lifetime falls within the selected period. Selected years are marked with dotted lines. This option zooms in to display only the selected years while keeping partially fitting individuals visible.

### Cut Off by Life Years

This option hides individuals whose lifetimes only partially fall within the selected period, ensuring only those fully within the period remain visible.

## Selection Behavior

If **Use Hyperlinks on Click** is disabled, clicking on a person selects them, filling their area with dark grey.
![image 20](https://github.com/user-attachments/assets/db9e2963-dc07-4bf6-af48-e9454976c1f5)
