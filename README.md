// Place your key bindings in this file to override the defaults
[
    { "key": "ctrl+`", "command": "workbench.action.terminal.focus" },
    {
        "key": "ctrl+`",
        "command": "workbench.action.focusActiveEditorGroup",
        "when": "terminalFocus"
    },
    {
        "key": "shift+alt+f",
        "command": "editor.action.formatDocument.none",
        "when": "editorTextFocus && !editorHasDocumentFormattingProvider && !editorReadonly"
    },
    {
        "key": "shift+alt+f",
        "command": "-editor.action.formatDocument.none",
        "when": "editorTextFocus && !editorHasDocumentFormattingProvider && !editorReadonly"
    },
    {
        "key": "shift+alt+f",
        "command": "notebook.format",
        "when": "notebookEditable && !editorTextFocus && activeEditor == 'workbench.editor.notebook'"
    },
    {
        "key": "shift+alt+f",
        "command": "-notebook.format",
        "when": "notebookEditable && !editorTextFocus && activeEditor == 'workbench.editor.notebook'"
    },
    {
        "key": "shift+alt+l",
        "command": "cursorRightSelect",
        "when": "textInputFocus"
    },
    {
        "key": "shift+right",
        "command": "-cursorRightSelect",
        "when": "textInputFocus"
    },
    {
        "key": "alt+l",
        "command": "cursorRight",
        "when": "textInputFocus"
    },
    {
        "key": "right",
        "command": "-cursorRight",
        "when": "textInputFocus"
    },
    {
        "key": "alt+h",
        "command": "cursorLeft",
        "when": "textInputFocus"
    },
    {
        "key": "left",
        "command": "-cursorLeft",
        "when": "textInputFocus"
    },
    {
        "key": "shift+alt+h",
        "command": "cursorLeftSelect",
        "when": "textInputFocus"
    },
    {
        "key": "shift+left",
        "command": "-cursorLeftSelect",
        "when": "textInputFocus"
    },
    {
        "key": "alt+j",
        "command": "cursorDown",
        "when": "textInputFocus"
    },
    {
        "key": "down",
        "command": "-cursorDown",
        "when": "textInputFocus"
    },
    {
        "key": "shift+alt+j",
        "command": "cursorDownSelect",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+shift+down",
        "command": "-cursorDownSelect",
        "when": "textInputFocus"
    },
    {
        "key": "alt+k",
        "command": "cursorUp",
        "when": "textInputFocus"
    },
    {
        "key": "up",
        "command": "-cursorUp",
        "when": "textInputFocus"
    },
    {
        "key": "shift+alt+k",
        "command": "cursorUpSelect",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+shift+up",
        "command": "-cursorUpSelect",
        "when": "textInputFocus"
    },
    {
        "key": "alt+;",
        "command": "cursorEnd",
        "when": "textInputFocus"
    },
    {
        "key": "end",
        "command": "-cursorEnd",
        "when": "textInputFocus"
    },
    {
        "key": "shift+alt+;",
        "command": "cursorEndSelect",
        "when": "textInputFocus"
    },
    {
        "key": "shift+end",
        "command": "-cursorEndSelect",
        "when": "textInputFocus"
    },
    {
        "key": "alt+a",
        "command": "cursorHome",
        "when": "textInputFocus"
    },
    {
        "key": "home",
        "command": "-cursorHome",
        "when": "textInputFocus"
    },
    {
        "key": "alt+n",
        "command": "code-runner.run"
    },
    {
        "key": "ctrl+alt+n",
        "command": "-code-runner.run"
    },
    {
        "key": "alt+i",
        "command": "scrollLineDown",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+down",
        "command": "-scrollLineDown",
        "when": "textInputFocus"
    },
    {
        "key": "alt+,",
        "command": "scrollLineUp",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+up",
        "command": "-scrollLineUp",
        "when": "textInputFocus"
    },
    {
        "key": "down",
        "command": "cursorDown",
        "when": "textInputFocus"
    },
    {
        "key": "up",
        "command": "cursorUp",
        "when": "textInputFocus"
    },
    {
        "key": "left",
        "command": "cursorLeft",
        "when": "textInputFocus"
    },
    {
        "key": "right",
        "command": "cursorRight",
        "when": "textInputFocus"
    }
]
