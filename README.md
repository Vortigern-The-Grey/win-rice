# My Windows rice settings!

## Wallpapers
Use my [wallpapers repo](https://github.com/Vortigern-The-Grey/wallpapers), set on 1 hour rotation.

## Rainmeter
Set up an on login task in task scheduler to reliably start on boot.

I use [https://github.com/modkavartini/catppuccin](https://github.com/modkavartini/catppuccin) for my top statusbar. 

## Windhawk
### Taskbar Clock Customization
```
{"ShowSeconds":0,"TimeFormat":"HH':'mm'","DateFormat":"ddd',' dd MMM yyyy","WeekdayFormat":"dddd","TopLine":"","BottomLine":"%date% | %time%","MiddleLine":"%weekday%","TooltipLine":"%web1_full%","Width":180,"Height":80,"TextSpacing":1,"WebContentsItems[0].Url":"https://feeds.bbci.co.uk/news/world/rss.xml","WebContentsItems[0].BlockStart":"<item>","WebContentsItems[0].Start":"<title><![CDATA[","WebContentsItems[0].End":"]]></title>","WebContentsItems[0].MaxLength":28,"WebContentsUpdateInterval":10,"TimeStyle.Visible":0,"TimeStyle.TextColor":"","TimeStyle.TextAlignment":"Center","TimeStyle.FontSize":0,"TimeStyle.FontFamily":"CaskaydiaCove Nerd Font","TimeStyle.FontWeight":"Thin","TimeStyle.FontStyle":"Normal","TimeStyle.FontStretch":"","TimeStyle.CharacterSpacing":0,"DateStyle.TextColor":"#cdd6f4","DateStyle.TextAlignment":"Center","DateStyle.FontSize":0,"DateStyle.FontFamily":"CaskaydiaCove Nerd Font","DateStyle.FontWeight":"Thin","DateStyle.FontStyle":"","DateStyle.FontStretch":"","DateStyle.CharacterSpacing":0,"oldTaskbarOnWin11":0}
```

### Taskbar height and icon size
```
{"IconSize":22,"TaskbarHeight":48,"TaskbarButtonWidth":48}
```

### Taskbar Labels for Windows 11
```
{"taskbarItemWidth":0,"minimumTaskbarItemWidth":0,"maximumTaskbarItemWidth":114,"runningIndicatorStyle":"fullWidth","progressIndicatorStyle":"fullWidth","fontSize":12,"leftAndRightPaddingSize":15,"spaceBetweenIconAndLabel":15,"labelForSingleItem":"%name%","labelForMultipleItems":"[%amount%] %name%","mode":"labelsWithoutCombining","excludedPrograms[0]":"excluded1.exe"}
```

### Windows 11 Start Menu Styler
```
{"theme":"SideBySide2","controlStyles[0].target":"Windows.UI.Xaml.Controls.Grid#UndockedRoot","controlStyles[0].styles[0]":"Visibility=Visible","resourceVariables[0].variableKey":"","resourceVariables[0].value":"","controlStyles[0].styles[1]":"Width=348","controlStyles[0].styles[2]":"Transform3D:=<CompositeTransform3D TranslateX=\\\"178\\\" />","controlStyles[0].styles[3]":"Margin=-80,-20,0,0","controlStyles[0].styles[4]":"Padding=0,0,0,0","controlStyles[1].target":"Windows.UI.Xaml.Controls.Grid#AllAppsRoot","controlStyles[1].styles[0]":"Visibility=Visible","controlStyles[1].styles[1]":"Width=320","controlStyles[1].styles[2]":"Transform3D:=<CompositeTransform3D TranslateX=\\\"-800\\\" />","controlStyles[1].styles[3]":"Margin=-30,-20,0,0","controlStyles[2].target":"Windows.UI.Xaml.Controls.Grid#ShowMoreSuggestions","controlStyles[2].styles[0]":"Visibility=Collapsed","controlStyles[3].target":"Windows.UI.Xaml.Controls.Grid#SuggestionsParentContainer","controlStyles[3].styles[0]":"Visibility=Collapsed","controlStyles[4].target":"Windows.UI.Xaml.Controls.Grid#TopLevelSuggestionsListHeader","controlStyles[4].styles[0]":"Visibility=Collapsed","controlStyles[5].target":"Windows.UI.Xaml.Controls.Grid#TopLevelRoot > Windows.UI.Xaml.Controls.Border","controlStyles[5].styles[0]":"Visibility=Collapsed","controlStyles[6].target":"Windows.UI.Xaml.Controls.Button#CloseAllAppsButton","controlStyles[6].styles[0]":"Visibility=Collapsed","controlStyles[7].target":"StartMenu.PinnedList","controlStyles[7].styles[0]":"Height=504","controlStyles[8].target":"Border#AcrylicBorder","controlStyles[8].styles[0]":"Background:=<AcrylicBrush TintColor=\\\"#1e1e2e\\\" TintLuminosityOpacity=\\\"0.8\\\" TintOpacity=\\\"0.5\\\" Opacity=\\\"1\\\" FallbackColor=\\\"#1e1e2e\\\"/>","controlStyles[9].target":"StartDocked.NavigationPaneView#Margin","controlStyles[9].styles[0]":"Margin=210,0,210,0"}
```

### Windows 11 Taskbar Styler
```
{"theme":"RosePine","controlStyles[0].target":"Taskbar.TaskListButton","controlStyles[0].styles[0]":"CornerRadius=34","resourceVariables[0].variableKey":"","resourceVariables[0].value":"","controlStyles[1].target":"SystemTray.TextIconContent > Grid#ContainerGrid > SystemTray.AdaptiveTextBlock#Base > TextBlock#InnerTextBlock","controlStyles[1].styles[0]":"FontSize=18","controlStyles[2].target":"SystemTray.NotifyIconView#NotifyItemIcon","controlStyles[2].styles[0]":"MinWidth=25","controlStyles[3].target":"SystemTray.OmniButton#ControlCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter[1] > SystemTray.IconView > Grid > Grid","controlStyles[3].styles[0]":"Visibility=Visible","controlStyles[4].target":"SystemTray.TextIconContent > Grid#ContainerGrid","controlStyles[4].styles[0]":"Padding=2","controlStyles[5].target":"SystemTray.ChevronIconView","controlStyles[5].styles[0]":"MinWidth=27","controlStyles[6].target":"SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > SystemTray.IconView#SystemTrayIcon > Grid > Grid > SystemTray.TextIconContent","controlStyles[6].styles[0]":"Visibility=Collapsed","controlStyles[7].target":"Taskbar.TaskListLabeledButtonPanel > Border#BackgroundElement","controlStyles[7].styles[0]":"Background:=#11111b","controlStyles[8].target":"Grid#SystemTrayFrameGrid","controlStyles[8].styles[0]":"Background:=#11111b","controlStyles[8].styles[1]":"CornerRadius=8","controlStyles[8].styles[2]":"Margin=0,5,4,5","controlStyles[8].styles[3]":"Padding=2,0,-8,0","controlStyles[7].styles[1]":"CornerRadius=10","controlStyles[9].target":"Taskbar.TaskListLabeledButtonPanel@CommonStates > Rectangle#RunningIndicator","controlStyles[9].styles[0]":"Height=40","controlStyles[9].styles[1]":"RadiusX=6","controlStyles[9].styles[2]":"RadiusY=6","controlStyles[9].styles[3]":"StrokeThickness=2.5","controlStyles[9].styles[4]":"Stroke@InactivePointerOver=#89b4fa","controlStyles[9].styles[5]":"Stroke@InactivePressed=#89b4fa","controlStyles[9].styles[6]":"Stroke@ActiveNormal=#89b4fa","controlStyles[9].styles[7]":"Stroke@ActivePointerOver=#89b4fa","controlStyles[9].styles[8]":"Stroke@ActivePressed=#89b4fa","controlStyles[9].styles[9]":"Fill=Transparent","controlStyles[10].target":"SystemTray.ImageIconContent > Grid#ContainerGrid > Image","controlStyles[10].styles[0]":"Width=13","controlStyles[11].target":"SystemTray.TextIconContent > Grid#ContainerGrid > SystemTray.AdaptiveTextBlock#Base > TextBlock#InnerTextBlock","controlStyles[11].styles[0]":"FontSize=12","controlStyles[12].target":"TextBlock#LabelControl","controlStyles[12].styles[0]":"FontFamily=CaskaydiaCove Nerd Font","controlStyles[12].styles[1]":"Foreground=#cdd6f4","controlStyles[12].styles[2]":"FontSize=10","controlStyles[11].styles[1]":"Foreground=#cdd6f4"}
```
