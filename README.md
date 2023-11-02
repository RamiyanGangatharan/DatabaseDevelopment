# DatabaseDevelopment
School Work from Database Development

## Introduction
this is a part of a github tutorial in Database Development I class where we are learning about branches.
- Database Model
- Normalization
- Functional Dependencies

  This is a code block
  ``` C#
  public void ClearControls(Control[] controls)
  {
      for (int controller = 0; controller < controls.Length; controller++)
      {
          var control = controls[controller];
          if (control.GetType() == typeof(CheckBox))
          {
              ((CheckBox)control).Checked = false;
          }
          else if (control.GetType() == typeof(ComboBox))
          {
              ((ComboBox)control).SelectedIndex = defaultIndex;
          }
          else if (control.GetType() == typeof(RichTextBox))
          {
              ((RichTextBox)control).Clear();
          }
      }
  }
  ```

  ```SQL
  SELECT * FROM users WHERE AGE >= 19;
  ```
