This fork has a single modification to the **omnipod-testing** branch in line 410 of **Omnikit/Pumpmanager/PodCommsSession.swift**:

``` let bolusExtraCommand = BolusExtraCommand(acknowledgementBeep: true, completionBeep: true, units: units) ```

This modification makes the pump beep at the start and the end of each bolus.
