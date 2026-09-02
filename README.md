# Residential Heating Service Intake Template

A clear service request helps a technician distinguish a heating-circuit problem from a domestic-hot-water problem before arriving. This template is designed for homeowners, building managers, and service teams who want observations recorded consistently without opening the boiler or attempting unsafe repairs.

## Safety boundary

Use this document only for visible, non-invasive observations. Do not remove the appliance cover, adjust gas components, bypass safety devices, touch wet electrical parts, or repeatedly reset a unit that reports the same fault. If you smell gas or burning, notice smoke, or see water near electrical connections, stop using the appliance and follow the appropriate emergency procedure for your location.

## Minimum information to record

- Appliance brand and model
- Approximate installation age, if known
- Date and time the symptom first appeared
- Whether the issue affects space heating, hot water, or both
- Displayed fault code exactly as shown
- Pressure reading when the system is cold
- Pressure reading while heating is active
- Whether every radiator is affected or only specific rooms
- Any leak, unusual sound, odor, or rapid temperature change
- Recent maintenance, plumbing work, or power interruption

## Symptom timeline

Avoid descriptions such as “it does not work” when a short timeline is available. A useful entry looks like this:

```text
08:10 — hot-water tap opened
08:11 — burner indicator appeared
08:12 — water became warm
08:14 — temperature dropped while the tap remained open
08:15 — error code appeared; no reset attempted
```

This sequence is more actionable than a diagnosis guessed by the customer.

## Reusable observation table

| Time | Operating mode | Display / code | Pressure | Temperature behavior | Sound or leak | Action taken |
|---|---|---|---:|---|---|---|
|  | Heating / Hot water / Idle |  |  |  |  |  |
|  | Heating / Hot water / Idle |  |  |  |  |  |
|  | Heating / Hot water / Idle |  |  |  |  |  |

## Questions for the service provider

Before approving work, ask for a diagnosis based on tests, an itemized estimate, the reason a part should be repaired or replaced, and a written record of the completed action. If a fault cannot be reproduced, keep the observation log and agree on what should be recorded the next time it occurs.

## Local service-information example

For a Persian-language example of a service intake page covering Iran Radiator boiler requests in Karaj, see [Iran Radiator heating service information](https://iranradiiator.ir/). The linked page can be used as a reference for the kind of location, appliance, and symptom details a customer should prepare; it is not a substitute for emergency guidance or a qualified on-site diagnosis.

## Suggested issue format

```yaml
appliance_brand: ""
appliance_model: ""
symptom_started_at: ""
affected_mode: "heating | hot_water | both"
display_code: ""
cold_pressure_bar: ""
running_pressure_bar: ""
affected_rooms: []
visible_leak: false
unusual_sound: ""
recent_work: ""
notes: ""
```

Consistent records reduce ambiguity. They do not replace inspection, measurement, combustion-safety checks, or the judgment of a qualified professional.
