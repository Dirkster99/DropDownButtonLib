[![Release](https://img.shields.io/github/release/Dirkster99/DropDownButtonLib.svg)](https://github.com/Dirkster99/DropDownButtonLib/releases/latest)
[![NuGet](https://img.shields.io/nuget/dt/Dirkster.DropDownButtonLib.svg)](http://nuget.org/packages/Dirkster.DropDownButtonLib)
<h1><img src="https://github.com/Dirkster99/Docu/blob/master/DropDownButtonLib/DropDownButtonLibLogo.png" height="64"/>&nbsp;Overview</h1>
The DropDownButtonLib project supplies MVVM/WPF drop down controls that are based on a button. 

There are sample screenshot on the Codeplex site from were this project is migrated from:
https://dropdownbuttonlib.codeplex.com/

This project is based on the drop down control contained in the
Extended WPF Toolkit™ Community Edition:https://wpftoolkit.codeplex.com/ from Xceed.
It includes some bugfixes to the original implementation and extends the original controls with a:

- DropDownButton, SplitButton

with:

- DropDownItemsButton, SplitItemsButton

controls. The original implementation (DropDownButton, SplitButton) can be used to drop down and interact with single drop down items, while the extended controls (DropDownItemsButton, SplittItemsButton) are based on an ItemsControl and can thus be with multiple drop down items (in a similar fashion as a standard WPF ComboBox or ListBox control).

## DropDownButton
<img src="https://github.com/Dirkster99/Docu/blob/master/DropDownButtonLib/DropDownButton.png"/>

## SplitButton
<img src="https://github.com/Dirkster99/Docu/blob/master/DropDownButtonLib/SplitButton.png"/>

## DropDownItemsButton
<img src="https://github.com/Dirkster99/Docu/blob/master/DropDownButtonLib/DropDownItemsButton.png"/>

## SplitItemsButton
<img src="https://github.com/Dirkster99/Docu/blob/master/DropDownButtonLib/SplitItemsButton.png"/>

## Theming

Load *Light* or *Dark* brush resources in you resource dictionary to take advantage of existing definitions.

```XAML
    <ResourceDictionary.MergedDictionaries>
        <ResourceDictionary Source="/DropDownButtonLib;component/Themes/MetroDark.xaml" />
    </ResourceDictionary.MergedDictionaries>
```

```XAML
    <ResourceDictionary.MergedDictionaries>
        <ResourceDictionary Source="/DropDownButtonLib;component/Themes/MetroLight.xaml" />
    </ResourceDictionary.MergedDictionaries>
```

These definitions do not theme all controls used within this library. You should use a standard theming library, such as:
- [MahApps.Metro](https://github.com/MahApps/MahApps.Metro),
- [MLib](https://github.com/Dirkster99/MLib), or
- [MUI](https://github.com/firstfloorsoftware/mui)

to also theme standard elements, such as, button and textblock etc.
