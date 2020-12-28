# MATLAB App Designer Password Edit Field

[![View App Designer Password Edit Field on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/84852-app-designer-password-edit-field)

Insert protected password field to your App Designer App

![App-Designer-Password-Edit](/sample/app-designer-password-edit.png)


## How to use

1. Copy `passwordEdit.html` file to your App's folder

2. Insert HTML Component to your App. Rename it to 'PasswordHTML'

3. Setup PasswordHTML component to use `passwordEdit.html` file

4. Create for PasswordHTML component DataChanged callback:

```MATLAB
function PasswordHTMLDataChanged(app, event)
    password = app.PasswordHTML.Data;
    disp(password);
end
```


## Example

Examine `PasswordEditExample.mlapp`
