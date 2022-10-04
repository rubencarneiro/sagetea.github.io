# fastboot:flash action Schema

```txt
v3/schema/action.schema.yml#/properties/operating_systems/items/properties/steps/items/properties/actions/items/oneOf/15/properties/fastboot:flash
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                          |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [device.schema.json*](../device.schema.json "open original schema") |

## fastboot:flash Type

`object` ([fastboot:flash action](device-properties-operating-systems-operating-system-properties-steps-step-properties-group-step-action-oneof-fastbootflash-action-properties-fastbootflash-action.md))

# fastboot:flash Properties

| Property                  | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                       |
| :------------------------ | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [partitions](#partitions) | `array` | Optional | cannot be null | [Device](device-properties-operating-systems-operating-system-properties-steps-step-properties-group-step-action-oneof-fastbootflash-action-properties-fastbootflash-action-properties-partitions.md "v3/schema/action.schema.yml#/properties/operating_systems/items/properties/steps/items/properties/actions/items/oneOf/15/properties/fastboot:flash/properties/partitions") |

## partitions

Partitions to flash

`partitions`

*   is optional

*   Type: `object[]` ([Partition](device-properties-operating-systems-operating-system-properties-steps-step-properties-group-step-action-oneof-fastbootflash-action-properties-fastbootflash-action-properties-partitions-partition.md))

*   cannot be null

*   defined in: [Device](device-properties-operating-systems-operating-system-properties-steps-step-properties-group-step-action-oneof-fastbootflash-action-properties-fastbootflash-action-properties-partitions.md "v3/schema/action.schema.yml#/properties/operating_systems/items/properties/steps/items/properties/actions/items/oneOf/15/properties/fastboot:flash/properties/partitions")

### partitions Type

`object[]` ([Partition](device-properties-operating-systems-operating-system-properties-steps-step-properties-group-step-action-oneof-fastbootflash-action-properties-fastbootflash-action-properties-partitions-partition.md))
