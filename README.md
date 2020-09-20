![Demo](https://github.com/cecton/blueprint-rs/blob/main/demo.mp4?raw=true)

blueprint-rs
============

It's [Blueprint](https://blueprintjs.com), but for
[Yew](https://github.com/yewstack/yew) in [Rust](https://www.rust-lang.org/).

This is in early development and it is possible it won't be finished if there
is no interest. Don't use this in production! Please help or at least leave it
a star to let me know you are interested in this project.

Installation
------------

### Prerequisites

 *  wasm-pack
 *  cargo-watch
 *  Rust nightly

### Use as a library

```toml
blueprint-rs = { git = "https://github.com/cecton/blueprint-rs.git", branch = "main" }
```

### Development server

```
rustup override set nightly
./dev.sh
```

Roadmap
-------

 -  [ ] Doc web-site designed with the library itself (like https://blueprintjs.com) including link to the Yew library
 -  [ ] [FocusStyleManager](https://blueprintjs.com/docs/#core/accessibility.focus-management)
 -  [ ] [Classes & Typography (and bp3- prefix)](https://blueprintjs.com/docs/#core/classes)
     -  [HTML elements](https://blueprintjs.com/docs/#core/components/html)
     -  [HTML table](https://blueprintjs.com/docs/#core/components/html-table)
     -  [Non-ideal state](https://blueprintjs.com/docs/#core/components/non-ideal-state)
     -  [HTML select](https://blueprintjs.com/docs/#core/components/html-select)
     -  [HTML input](https://blueprintjs.com/docs/#core/components/text-inputs.html-input)
     -  [Search field](https://blueprintjs.com/docs/#core/components/text-inputs.search-field)
 -  [ ] [Breadcrumbs](https://blueprintjs.com/docs/#core/components/breadcrumbs)
 -  [x] [Button](https://blueprintjs.com/docs/#core/components/button)
     -  [ ] Complete Button API
     -  [ ] AnchorButton
 -  [ ] [ButtonGroup](https://blueprintjs.com/docs/#core/components/button-group)
 -  [ ] [Callout](https://blueprintjs.com/docs/#core/components/callout)
 -  [ ] [Card](https://blueprintjs.com/docs/#core/components/card)
 -  [x] [Collapse](https://blueprintjs.com/docs/#core/components/collapse)
 -  [ ] [CollapsibleList](https://blueprintjs.com/docs/#core/components/collapsible-list)
 -  [ ] [Divider](https://blueprintjs.com/docs/#core/components/divider)
 -  [ ] [EditableText](https://blueprintjs.com/docs/#core/components/editable-text)
 -  [ ] [Hotkeys](https://blueprintjs.com/docs/#core/components/hotkeys)
 -  [x] [Icon](https://blueprintjs.com/docs/#core/components/icon)
 -  [ ] [Menu](https://blueprintjs.com/docs/#core/components/menu)
 -  [ ] [Popover](https://blueprintjs.com/docs/#core/components/menu.dropdowns) (dropdowns)
     -  depends on: Menu
 -  [ ] [Navbar](https://blueprintjs.com/docs/#core/components/navbar)
 -  [ ] [OverflowList](https://blueprintjs.com/docs/#core/components/overflow-list)
 -  [ ] [PanelStack](https://blueprintjs.com/docs/#core/components/panel-stack)
 -  [ ] [ProgressBar](https://blueprintjs.com/docs/#core/components/progress-bar)
 -  [ ] [ResizeSensor](https://blueprintjs.com/docs/#core/components/resize-sensor)
 -  [ ] [Skeleton](https://blueprintjs.com/docs/#core/components/skeleton)
 -  [ ] [Spinner](https://blueprintjs.com/docs/#core/components/spinner)
 -  [ ] [Tabs](https://blueprintjs.com/docs/#core/components/tabs)
 -  [ ] [Tag](https://blueprintjs.com/docs/#core/components/tag)
 -  [ ] [Text](https://blueprintjs.com/docs/#core/components/text)
 -  [x] [Tree](https://blueprintjs.com/docs/#core/components/tree)
     -  depends on: Collapse, Icon
 -  [ ] [FormGroup](https://blueprintjs.com/docs/#core/components/form-group)
 -  [ ] [ControlGroup](https://blueprintjs.com/docs/#core/components/control-group)
 -  [ ] [Label](https://blueprintjs.com/docs/#core/components/label)
 -  [ ] [Checkbox](https://blueprintjs.com/docs/#core/components/checkbox)
 -  [ ] [RadioGroup](https://blueprintjs.com/docs/#core/components/radio)
 -  [ ] [Sliders](https://blueprintjs.com/docs/#core/components/sliders)
 -  [ ] [RangeSlider](https://blueprintjs.com/docs/#core/components/sliders.range-slider)
 -  [ ] [MultiSlider](https://blueprintjs.com/docs/#core/components/sliders.multi-slider)
 -  [x] [Switch](https://blueprintjs.com/docs/#core/components/switch)
 -  [ ] [FileInput](https://blueprintjs.com/docs/#core/components/file-input)
 -  [ ] [NumericInput](https://blueprintjs.com/docs/#core/components/numeric-input)
 -  [ ] [InputGroup](https://blueprintjs.com/docs/#core/components/text-inputs.input-group)
 -  [ ] [TextArea](https://blueprintjs.com/docs/#core/components/text-inputs.text-area)
 -  [ ] [TagInput](https://blueprintjs.com/docs/#core/components/tag-input)
 -  [ ] [Overlay](https://blueprintjs.com/docs/#core/components/overlay)
     -  depends on: Portal
 -  [ ] [Portal](https://blueprintjs.com/docs/#core/components/portal)
 -  [ ] [Alert](https://blueprintjs.com/docs/#core/components/alert)
     -  depends on: Button, Dialog
 -  [ ] [Context menu](https://blueprintjs.com/docs/#core/components/context-menu)
     -  depends on: Popover
 -  [ ] [Dialog](https://blueprintjs.com/docs/#core/components/dialog)
     -  depends on: Icon, Overlay, Button
 -  [ ] [Drawer](https://blueprintjs.com/docs/#core/components/drawer)
     -  depends on: Icon, Overlay, Button
 -  [ ] [Popover](https://blueprintjs.com/docs/#core/components/popover)
     -  depends on: ResizeSensor, Tooltip, Overlay
 -  [ ] [Toast](https://blueprintjs.com/docs/#core/components/toast)
     -  depends on: Button, ButtonGroup, Icon, AnchorButton
 -  [ ] [Tooltip](https://blueprintjs.com/docs/#core/components/tooltip)
     -  depends on: Popover
 -  [ ] [DatePicker](https://blueprintjs.com/docs/#datetime/datepicker)
 -  [ ] [DateRangePicker](https://blueprintjs.com/docs/#datetime/daterangepicker)
 -  [ ] [TimePicker](https://blueprintjs.com/docs/#datetime/timepicker)
 -  [ ] [DateTimePicker](https://blueprintjs.com/docs/#datetime/datetimepicker)
 -  [ ] [DateInput](https://blueprintjs.com/docs/#datetime/dateinput)
 -  [ ] [DateRangeInput](https://blueprintjs.com/docs/#datetime/daterangeinput)
 -  [ ] [Select](https://blueprintjs.com/docs/#select/select-component)
 -  [ ] [Suggest](https://blueprintjs.com/docs/#select/suggest)
 -  [ ] [MultiSelect](https://blueprintjs.com/docs/#select/multi-select)
 -  [ ] [Omnibar](https://blueprintjs.com/docs/#select/omnibar)
 -  [ ] [QueryList](https://blueprintjs.com/docs/#select/query-list)
 -  [ ] [Table](https://blueprintjs.com/docs/#select/query-list)
 -  [ ] [TimezonePicker](https://blueprintjs.com/docs/#timezone)
