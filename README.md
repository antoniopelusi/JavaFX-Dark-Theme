# JavaFX-Dark-Theme :waning_crescent_moon:
A complete CSS stylesheet to set a dark theme in your JavaFX UI.

## How to use
- **Load via FXML:**


  Add `stylesheets="@style.css"` to the top-level FXML tag.
<br></br>

- **Load via Java:**
  Add the following code:
  ```
  File style = new File("relative-path/style.css");
  scene.getStylesheets().add(style.toURI().toURL().toExternalForm());
  ```
## CSS preview example
![image](https://user-images.githubusercontent.com/35381371/195473344-540e090e-da60-45d8-9cc4-f676db4b4523.png)
