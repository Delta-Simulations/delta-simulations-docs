# Bambi Bucket and Helitak Tank

The H-60 has two firefighting configurations. The **Bambi bucket** hangs below the aircraft. The **Helitak tank** is built into the belly of the dedicated civilian Helitak variant. Both use the **WATER SYSTEM** panel on the aircraft tablet.

## Select the equipment

| To use | In the simulator | Tablet indication |
| --- | --- | --- |
| Bambi bucket | Select a model without the fixed tank. On **Aircraft → CONFIGURATION**, select **BAMBI BUCKET**. | **BAMBI** and a water-level bar. |
| Helitak tank | Choose **S70i Civilian Helitak N60HD** in the aircraft selector. | **HELITAK** and a water-level bar. The bucket selector is disabled on this model. |
| Neither | On a model without the fixed tank, turn **BAMBI BUCKET** off. | **NO WATER EQUIPMENT**. |

On the Helitak, the bucket button can look selected even though there is no hanging bucket. Check the **HELITAK** label on the right. The belly tank already occupies the water-equipment position.

## Fill and release

1. With the equipment selected, press **FORCE FILL**. The blue bar and percentage should rise to **100%**. This is a convenient way to set up a practice flight or confirm that you have the intended equipment.
2. Once airborne in the simulator, select **DROP**. Watch the water percentage fall. Select **DROP** again to end a partial release. The add-on inhibits discharge while the simulator reports the aircraft is on the ground.
3. You can also refill over water. The simulation checks the underlying surface, radio height and true airspeed. The bucket and tank have different pickup heights. Crossing a shoreline at cruise speed won't refill either one.
4. To put the release on your hardware, find **DECREASE MAC CREADY** in the MSFS controls menu. This is the binding labeled **Release Water** on the tablet. In the project keybind list the event appears as `MAC_CREADY_SETTING_DEC`.

If you get the drop control but no effect, check the water percentage first, then confirm that the aircraft is airborne in the sim. If the panel only reads **NO WATER EQUIPMENT**, return to **CONFIGURATION** and select the bucket, or reload with the Helitak variant.
