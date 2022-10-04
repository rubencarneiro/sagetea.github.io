# Progress Schema

```txt
v3/schema/action.schema.yml#/properties/operating_systems/items/properties/steps/items/properties/actions/items/oneOf/1/properties/core:info/properties/progress
```

Progress bar (omit to hide)

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                          |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [device.schema.json*](../device.schema.json "open original schema") |

## progress Type

`number` ([Progress](device-properties-operating-systems-operating-system-properties-steps-step-properties-group-step-action-oneof-coreinfo-action-properties-coreinfo-action-properties-progress.md))

## progress Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`
