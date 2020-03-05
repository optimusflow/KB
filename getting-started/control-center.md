---
description: >-
  Get to know how to use and manage the Control center which is the starting
  panel of Optimus Flow.
---

# Control center

**Control center** — is the main starting point of all terminal, used as a launcher and informer simultaneously. The main functions of the Control center \(CC\) are:

* Launcher for panels
* Workspaces holder
* Connections monitor
* General settings access point

![Control Center Toolbar](../.gitbook/assets/image%20%289%29.png)

CC technically is a panel, but behaves something differently: it can be dragged among your screens \(if you have more than one\) and it will be always stuck at the top of the screen. It adapts own width up to the screen width and it participates in the workspace, meaning, that other panels can be stuck to it.

Due to the fact that CC is the main controlling panel it has an ability to collapse all terminal’s interface by clicking the “_**Collapse**_” icon. This action makes all application panels to collapse to the taskbar and literally disappear from your screens; it affects all panels on all screens. If you press the CC icon on the taskbar after the collapse, you will get all of the interfaces appear again.

![Global interface collapser](../.gitbook/assets/cclogoicon.png)

The “_**Close**_” icon just closes the terminal. You may set up “_not to ask to confirm the closing_” setting in the pop-up screen while the first closing.

## Customization of Control Center

For optimal use of the space on Control center, we have added the ability to display/hide some controls. For example, to hide the Timezones, Workspaces, Connections, etc., right-click on the context menu and go to View section. By clicking on the ticks, the controls will appear at the control center.

![Right click on the control center will bring up the additional settings window.](../.gitbook/assets/image%20%286%29.png)

We have also added the ability to quickly call the controls without displaying them on the control center.

![Additional settings of Control Center](../.gitbook/assets/customization-of-control-center2.png)

## Sidebar

All of the panels are placed in so-called _**“Sidebar”**_ screen, that is popping out once you click the Logo icon on CC.

![Control Center sidebar \(Main Menu\)](../.gitbook/assets/image%20%283%29.png)

The Sidebar consists of panels icons, grouped by the functionality. Each group can be collapsed in order to make the panels list cleaner. From this place, you can open any panel by left-clicking on its icon. Each group has its color to help you determine the functional assignment of each panel.

The footer of Sidebar contains several functions:

* “**About**” link: opens a screen with information about terminal \(version, rollback, updates checker etc.\). If the system detects the new version of OptimusFLOW, the “NEW VERSION” button appears instead of this link;
* “**Exit**” button: closes the application.

{% hint style="info" %}
The list of links in footer can contain more or fewer items, depending on current application requirements.
{% endhint %}

## Favorite panels

You might already have seen the Star icon in the right top corners of some panels tiles in Sidebar. This is the “Favorite panels” functionality, allowing you to select the most usable panels and place their icons on the Favorites bar on Control center.

![Favorites Panel](../.gitbook/assets/favorites-panel.gif)

The way to use it very simple — hover over the right top corner of any panel tile in Sidebar and click the Star icon appeared. You can also right click an icon and choose the **Pin On Toolbar** option. That is all: panel appears in Favorite panels bar in Control center. To remove from favorites just click the activated Star icon on Panel's tile or right-click on the icon in Favorites panel and select “_**Hide from toolbar**_”.

## Lock trading

If you would like to prevent the manual trading operations occur, you may use the “_**Lock trading**_” button on Control center. Once clicked it displays the confirmation message that trading being locked and all of the functions, related to opening or closing orders and positions will be disabled. Unlock trading can be done the vice-versa way.

![Lock trading icon](../.gitbook/assets/cclocktrading.png)

This feature is useful in case you would like to only analyze the market or while editing your workspace \(mostly to avoid misclicks\).

## Workspaces manager

**Workspaces manager** allows you to see, create, edit and delete your working environments as well as lock their modification. It is represented with the special icon, that opens the list of available Workspaces once being clicked.

{% embed url="https://www.youtube.com/watch?v=lMHq6-v8OL8&t=" caption="How to manage, edit, and create new workspaces." %}



![Workspaces manager](../.gitbook/assets/ccworkspacesmanager.png)

The currently active workspace is marked with the color and has a blue dot on the left side of its name. You can switch the current workspace by left-clicking any of available item from the list. The bottom part of the list \(after separator\) consists of actions, referred to the currently active workspace and allows to:

* **Lock**: disables an ability to add, remove, move or resize any panel in current workspace;
* **Rename...** : invokes a pop-up screen where you can set up a new name for the current workspace;
* **Create new**: opens a pop-up screen with the new workspace creation form.

![New workspace creation window](../.gitbook/assets/ccnewworkspace.png)

When creating the new workspace, you have an ability to specify its future name and select whether it should be Blank, once created, or should contain some predefined panels set.

{% hint style="success" %}
The list of Workspace templates will be constantly growing.
{% endhint %}

You can also Remove any of Workspaces by clicking the “_**Trash**_” icon on the right side from Workspace name \(icon appears while hovering the name\).

## Favorite connections

The list of active connections can be seen on Control center in Favorite connections block. By default, you will see several items here, each representing one of the available connections. The [Connection manager](../connections/connections-manager.md) screen will be opened by clicking any of items in Favorite connections block.

![](../.gitbook/assets/image%20%281%29.png)

In order to show some connection on this bar, you need to click a “_**Star**_” icon at the right side of connection name in Connections manager panel. Click once more, and the connection will be removed from Favorites bar.

Being added to Favorites bar, each connection will be displayed as a tile, containing some vital info:

* **Connection name**
* **Status text** \(can be a status message or Ping time in ms when the connection is active\)
* **Status Dot**, a visual representation of connection status. Can be grey \(disconnected\), yellow \(connecting\), green \(active\). If connected, the Dot blinks periodically.

You can Remove connection from Favorites by right-clicking on it and selecting “_**Hide from toolbar**_” item. Here you can also ask to connect or disconnect.

## Notifications center

The most actions during the platform use generate various notifications. There can be system notification \(some connection problems or errors\) and Deal tickets. The Deal tickets — are the notifications about the trading operations. Each time you create an order or opening a new position — we will create a deal ticket for this.

While some trading actions may be done in one click at the first sight, they usually consist of several related operations, each of them will be displayed via the Deal tickets. That is why you can see much more items in Notifications center than you did actions.

![The Deal ticket and Notifications center icon](../.gitbook/assets/ccdealticket.png)

The Notifications center — is the place where all notifications are stored in one list. You can open that list by clicking the Notifications icon in Control center.

![Notifications center](../.gitbook/assets/ccnotificationcenter.png)

When you have a set of new notifications, the small number will appear in the left top corner of Notification center icon. It displays how many unread notifications you have. Once you open the list — it understands that you have read them and the number will disappear.

You will see all notifications just from the platform start. You may also clear this list by clicking the “_**Clear all**_” link. This action will hide all of the currently seen notifications from this list \(but they will be still available in Event Log panel\).

By clicking one of the notifications you will see the window with the detailed info.

## General settings

The “_**Gear**_” icon opens a general settings screen, where you can setup the most common parameters of our terminal. [More details about the **Settings**](general-settings.md) screen is available in the corresponding section of this documentation.

## Time & Time zones

The Time bar is also displayed on the Control center toolbar showing you time in selected timezone. By default, your local timezone is used. You can change the time zones list by clicking the "_**Gear**_" icon and then select the required ones in [**General settings screen**](general-settings.md). You may also select several time zones and they will appear as a list in a drop-down panel, allowing you to switch among them quickly.

![Switch between your favorite timezones](../.gitbook/assets/timezones.png)

