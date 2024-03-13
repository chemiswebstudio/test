# Decorators

Decorators are functions that can be used to declaratively annotate and modify the behavior of classes. Within this context, several built-in decorators play pivotal roles in extending the capabilities of components.

## Built-in decorators <a href="#built-in-decorators" id="built-in-decorators"></a>

<table><thead><tr><th width="169">Decorator</th><th>Summary</th></tr></thead><tbody><tr><td><a href="component.md">@component</a></td><td>Defines and register components.</td></tr><tr><td><a href="command.md">@command</a></td><td>Define commands in the Floating Command Bar of the component.</td></tr><tr><td><a href="slot.md">@slot</a></td><td>Defines slots in the Floating Slot of the component.</td></tr><tr><td><a href="attributes.md">@attributes</a></td><td>Defines attributes for the component in the Node Inspector.</td></tr><tr><td><a href="events.md">@events</a></td><td>Defines events for the component in the Node Inspector.</td></tr></tbody></table>

## Enabling decorators <a href="#enabling-decorators" id="enabling-decorators"></a>

To use decorators, you need to build your code with a compiler compiler profile that have the `RollupPluginBabel` configured with the `js-decorators` preset. You can set it up in a new Rollup build profile, or add the configuration manually to the file.

{% code title="rollup.config.js" %}
```javascript
import RollupPluginBabel from "/@studio/modules/rollup-plugin-babel"

plugins: [
    RollupPluginBabel({
        presets: [
            "js-decorators"
        ]
    }),
]
```
{% endcode %}
