# JavaFX-Dark-Theme :waning_crescent_moon:
A complete CSS stylesheet to set a dark theme in your JavaFX UI.

Built on top of the default JavaFX theme (Modena)

<br>

## How to use
- **Load via FXML:**


  Add `stylesheets="@style.css"` to the top-level FXML tag.
  
<br>

- **Load via Java:**
  Add the following code:
  ```
  File style = new File("relative-path/style.css");
  scene.getStylesheets().add(style.toURI().toURL().toExternalForm());
  ```
  
<br>

## CSS preview example
See this theme in action [**here**](https://github.com/antoniopelusi/KeyHolder-desktop)!

  
<br>

## List of JavaFX recolored elements
- Label
- Pane
- GridPane
- TextField
- ComboBox
- ListCell
- ListView
- Button
- CheckBox
- TextArea
- ScrollBar
- Menu
- ProgressBar
- Slider
- TreeView
- Tab
- TitledPane
- TableView
- Tooltip
