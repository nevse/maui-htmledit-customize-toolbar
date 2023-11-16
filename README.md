# DevExpress .NET MAUI HTML Edit - Replicate a Built-In Toolbar

The DevExpress **HTML Edit** control for .NET MAUI includes the built-in [DXToolbar Control](https://docs.devexpress.com/MAUI/404604/dialogs-menu-and-navigation/toolbar/toolbar-overview?v=23.2) that you can use to manipulate the displayed content. This repository replicates the **HTML Edit**'s built-in toolbar in XAML including the [SafeKeyboardAreaView](https://docs.devexpress.com/MAUI/DevExpress.Maui.Core.SafeKeyboardAreaView?v=23.2&) class. You can use this class to achieve the following:
* Decrease the height of HTML Edit when you open the device keyboard and keeps the toolbar visible. It allows to avoid the device keyboard and the toolbar overlap.
* Display custom content in the keyboard area to add more space for UI elements.

![DevExpress .NET MAUI HTML Edit - Custom Panel in the Keyboard Area](https://docs.devexpress.com/MAUI/images/core/safekeyboardareaview.png?v=23.2)

## Files to Review

- [MainPage.xaml](CS/MainPage.xaml)
- [MainPage.xaml.cs](CS/MainPage.xaml.cs)
- [EmbedImageSettingsView.xaml](CS/Views/EmbedImageSettingsView.xaml)
- [EmbedImageSettingsViewModel.cs](CS/ViewModels/EmbedImageSettingsViewModel.cs)
- [FontFamilySettingsView.xaml](CS/Views/FontFamilySettingsView.xaml)
- [FontFamilySettingsViewModel.cs](CS/ViewModels/FontFamilySettingsViewModel.cs)
- [HyperlinkSettingsView.xaml](CS/Views/HyperlinkSettingsView.xaml)
- [HyperlinkSettingsViewModel.cs](CS/ViewModels/HyperlinkSettingsViewModel.cs)
- [TextFormatView.xaml](CS/Views/TextFormatView.xaml)
- [TextFormatViewModel.cs](CS/ViewModels/TextFormatViewModel.cs)

## Documentation

- [SafeKeyboardAreaView](https://docs.devexpress.com/MAUI/DevExpress.Maui.Core.SafeKeyboardAreaView?v=23.2)
- [DXToolbar Control](https://docs.devexpress.com/MAUI/404604/dialogs-menu-and-navigation/toolbar/toolbar-overview?v=23.2)
- [HTML Edit - Create a Custom Toolbar](https://docs.devexpress.com/MAUI/404639/html-edit/toolbar?v=23.2)

## More Examples

* [DevExpress .NET MAUI Demo Center](https://github.com/DevExpress-Examples/maui-demo-app)
* [Stocks App](https://github.com/DevExpress-Examples/maui-stocks-mini)
* [Data Grid](https://github.com/DevExpress-Examples/maui-data-grid-get-started)
* [Data Form](https://github.com/DevExpress-Examples/maui-data-form-get-started)
* [Data Editors](https://github.com/DevExpress-Examples/maui-editors-get-started)
* [Charts](https://github.com/DevExpress-Examples/maui-charts)
* [Scheduler](https://github.com/DevExpress-Examples/maui-scheduler-get-started)
* [Tab Page](https://github.com/DevExpress-Examples/maui-tab-page-get-started)
* [Tab View](https://github.com/DevExpress-Examples/maui-tab-view-get-started)
* [Drawer Page](https://github.com/DevExpress-Examples/maui-drawer-page-get-started)
* [Drawer View](https://github.com/DevExpress-Examples/maui-drawer-view-get-started)
* [Collection View](https://github.com/DevExpress-Examples/maui-collection-view-get-started)
* [Popup](https://github.com/DevExpress-Examples/maui-popup-get-started)
