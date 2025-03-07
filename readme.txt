=== Plugin Name: OC Smart Table (free)  ===
Contributors: toshiyuki
Tags: block editor,table,responsive 
Requires at least: 5.0
Tested up to: 5.9 
Stable Tag: 0.1.6
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

It swaps list for table, if a viewer opens your page with small width display.

== Description ==

This plugin swaps list for table, if a viewer opens a your page with small width display.
The list for small width display is made from the table which you put in a page with table block editor. You do not need to write list having same contents in table. You can enable this plugin with a simple operation.
The plugin creates list on browser dynamically. So the list is not exists in your Wordpress database. You will edit the table being enabled this plugin, even after you uninstall this plugin. 

= Table structure and List structure =


Table has header which each cells are in row towards horizontally. The table body's each cells related with header cells are in row towards horizontally.

The informations is in row towards horizontally even if you see them with small width device. But other information tends to be in row towards vertically. 
You visit a page, see contents from top to down. It's natural way to scroll the display vertically. You encounter a table having long rows while scrolling, you have to stop scrolling vertically and, scroll display horizontally. At end of table row, you have to back to the start of row with scrolling and then scroll down again.

It originated in table having horizontal categorized cells arrangement.
It is not proper for me to keep table structure and show the data vertically.
It is nice for me to arrange data with list. The list data structure has the kind to arrange data vertically.

= OC Smart Table in background =

OC Smart Table creates list from table on browser side dynamically at opening the page. But list is not visible if the display width is enough to show table.
If the display width is not enough to show table, swap list for table.

== Usage ==

= Enable OC Smart Table (free) =

You put "oc-smart-table" in  Additional CSS class(es) at Advanced section on Settings sidebar. You need this operation only when you make editting table active. For example, You put a table with table block editor or click a table block which you put before. 

= Enable OC Smart Table =

If you have OC Smart Table standard edition, You click "Enable Smart Table" from other toolbar item in table block editor, then You make the editing table be enabled Smart Table.

You can buy standard edition from [here](https://ocsoft.base.shop/items/62050748).


= Inherit colors and styles =

You can make the list which the plugin create having table's colors and styles. To enable the inheritance, You need to enable option "inherit colors and styles" in Smart table setting in Setting sidebar.

== ChangeLog ==

= 0.1 =
* first release

Please see changelog.txt in the plugin directory.


== Screenshots ==

1. Enabling Smart Table
2. Smart Table enabled page (small display)
3. Smart Table enabled page (large display)
4. Inherit colors and styles
5. Other toolbar option(standard edition only)

