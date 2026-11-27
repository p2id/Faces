component_inventory:
- app_shell: default, loading, error, empty, success
- navigation_item: default, hover, focus-visible, active, disabled
- button: default, hover, focus-visible, active, disabled, loading, success, error
- text_input: empty, filled, hover, focus-visible, disabled, loading, error, success
- select: closed, open, hover, focus-visible, disabled, loading, error
- checkbox: unchecked, checked, indeterminate, hover, focus-visible, disabled, error
- tab: inactive, hover, focus-visible, active, disabled
- card: default, hover, focus-visible, selected, disabled, loading, error
- table: default, loading, empty, error
- pagination: default, hover, focus-visible, active, disabled
- toast: info, success, warning, error, dismissed
- modal: closed, open, loading, error, success

state_rules:
- default: normal emphasis and available interaction
- hover: subtle surface or border change; never the sole status signal
- focus-visible: visible 2px focus ring with offset
- active: pressed treatment during activation
- disabled: reduced emphasis and no action
- loading: preserve geometry, expose progress, prevent duplicate activation
- error: semantic color plus text or icon label
- empty: explain absence and provide a relevant next action
- success: confirm completion with persistent inline text or status message
- selected, checked, indeterminate: visible mark plus programmatic state