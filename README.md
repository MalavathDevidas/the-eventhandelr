# the-eventhandelr
When handle() is called directly, this refers to the global window object. When the button is clicked, this refers to the button element. This happens because this behaves differently in direct calls vs. event-triggered calls.
