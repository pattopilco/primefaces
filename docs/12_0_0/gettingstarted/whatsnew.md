# What is new?

This page contains a list of big features. Please check the GitHub issues for all changes.

## 12.0.0

### PrimeFaces

* AccordionPanel
  * Added support for `options` and `actions` facets of contained `Tab` components.
  * Added `ui-state-error` class to tabs that contain invalid inputs.
* AutoComplete:
  * Added `lazyModel` attribute for fetching autocomplete-suggestions (instead of completeMethod).
  * Added Ajax load indicator (spinner) within the component while the component is querying.
* BreadCrumb: added `seo` attribute for creating JSON Link Data for better SEO.
* CommandButton:
  * Added `disableOnAjax` attribute to disable the button during Ajax requests triggered by it.
  * Added Ajax load indicator (spinner) within the button during Ajax requests triggered by it.
* CommandLink
  * Now has a widget and can be enabled and disabled by its widget.
  * Added `disableOnAjax` attribute to disable the link during Ajax requests triggered by it.
* Exporter: added new options for `visibleOnly`, `exportHeader` and `exportFooter` to give better control over output.
* FileUpload: added `clear()` widget method in SkinSimple mode to clear out selected file.
* InputMask: added new options for `showMaskOnFocus` and `showMaskOnHover` to give better control over mask.
* MenuButton
  * Now can be enabled and disabled by its widget.
  * Added `disableOnAjax` attribute to disable the button during Ajax requests triggered by its menu items.
  * Added Ajax load indicator (spinner) within the button during Ajax requests triggered by its menu items.
* Printer: added `configuration` attribute for passing custom JSON options to PrintJS.
* Schedule: added `selectable` property and `rangeSelect` AJAX event
* SelectOneRadio: improved accessibility of custom layout via `custom` facet.
* Spinner: added `modifyValueOnWheel` to increment or decrement the element value with the mouse wheel.
* SplitButton
  * Now can be enabled and disabled by its widget.
  * Added `disableOnAjax` attribute to disable the button during Ajax requests triggered by it or its menu items.
  * Added Ajax load indicator (spinner) within the button during Ajax requests triggered by it.
* TabView: added `ui-state-error` class to tabs that contain invalid inputs.
* Tree: added `filterFunction` attribute for custom filtering.
* ToggleSwitch: added `onIcon` and `offIcon` attributes
* Tooltip: added `autoHide` attribute when set to false will keep the tooltip showing while focused.
* OverlayPanel: added `autoHide` attribute when set to false will keep the overlay showing while focused.

Look into [migration guide](https://primefaces.github.io/primefaces/12_0_0/#/../migrationguide/12_0_0) for more enhancements and changes.

### PrimeFaces Selenium 

* Switched from Selenium 3.x to Selenium 4.x
  * Most adaptions are done by PrimeFaces Selenium behind the scenes.
  * For usecases where you directly interact with Selenium without PrimeFaces Selenium abstraction look into https://www.selenium.dev/documentation/webdriver/getting_started/upgrade_to_selenium_4/ for details.
  * New Components `MenuBar`, `BlockUI`, `SelectCheckboxMenu`
