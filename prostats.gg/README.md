# Player Stats Comparison Dash App


![Dashoard ](https://user-images.githubusercontent.com/99633856/224131846-bead34d2-9f90-4876-be28-d29250187ba4.png)

## Description

This is a simple Dash app that allows you to compare the stats of different players based on a selected statistic. The app shows the comparison on a bar graph.

## Requirements

  1. Python 3.6 or later
  2. Dash 2.0 or later

## Installation

Clone the repository or download the source code.

```bash
git clone https://github.com/DSCKGEC/CS-GO-Professionals.git
```

Change into the project directory.

```bash
cd CS-GO-Professionals/prostats.gg
```

To run this.

```bash
pip install dash
pip install plotly
```

## Usage

1. Run the app.

```bash
python Players performance analysis .ipynb
```

2. Open the html file. 
Select the names of the players and the statistic to compare from the dropdown menus.
Click the "Compare" button to see the bar graph showing the comparison.

### Embedding in HTML
To embed the app in an HTML page, you can use an iframe. 
Here are the steps:

1. Create an HTML file and open it in a text editor.

2. Add an iframe element to the HTML file.

  html
  ```bash
  <iframe src="http://localhost:8050"></iframe>
  ```
3. Save the HTML file.

4. Open the HTML file in a web browser. You should see the Dash app embedded in the HTML page.


## License
This project is licensed under the MIT License. See the LICENSE file for details.



