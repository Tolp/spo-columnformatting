# JSON for Column Formatting to Customise SharePoint Online Columns

### Project Management RYAG Status


`{
    "elmType": "div",
    "txtContent": "@currentField",
    "style": {
        "color": "#fff",
        "padding-left": "14px",
        "background-color": {
            "operator": "?",
            "operands": [
                {
                    "operator": "==",
                    "operands": [
                        "@currentField",
                        "Red"
                    ]
                },
                "#e81123",
                {
                    "operator": "?",
                    "operands": [
                        {
                            "operator": "==",
                            "operands": [
                                "@currentField",
                                "Green"
                            ]
                        },
                        "#00B294",
                        {
                            "operator": "?",
                            "operands": [
                                {
                                    "operator": "==",
                                    "operands": [
                                        "@currentField",
                                        "Amber"
                                    ]
                                },
                                "#ff8c00",
                                {
                                    "operator": "?",
                                    "operands": [
                                        {
                                            "operator": "==",
                                            "operands": [
                                                "@currentField",
                                                "Yellow"
                                            ]
                                        },
                                        "#fff100",
                                        ""
                                    ]
                                }
                            ]
                        }
                    ]
                }
            ]
        }
    }
}`
