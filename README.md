# sublime_settings

### Enable emmet in jsx:
```
{ "keys": ["tab"], "command": "expand_abbreviation_by_tab", "context":
    [
        { "operand": "source.js", "operator": "equal", "match_all": true, "key": "selector" },
        { "match_all": true, "key": "selection_empty" },
        { "operator": "equal", "operand": false, "match_all": true, "key": "has_next_field" },
        { "operand": false, "operator": "equal", "match_all": true, "key": "auto_complete_visible" },
        { "match_all": true, "key": "is_abbreviation" }
    ]
}
```
