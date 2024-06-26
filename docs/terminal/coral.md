---
  title: Coral TCU
---

--8<-- "includes/abbreviations.md"

## Positions

| Name               | ID      | Callsign       | Frequency        | Login Identifier              |
| ------------------ | --------------| -------------- | ---------------- | ---------------------|
| Mackay Approach  | MKA | Coral Approach  | 125.650       | MK_APP    |
| Rockhampton Approach  | RKA | Coral Approach   | 123.750        | RK_APP                 |

## Airspace
The Coral TCU includes the airspace `SFC` to `F150` within the Mackay and Rockhampton keyholes (shown below).  
MK ADC own the Class D airspace within MK CTR `SFC` to `A010`.  
RK ADC own the Class D airspace within RK CTR `SFC` to `A010`.  

## Extending
MKA may extend to RKA and vice versa, callsigns remain the same. See [Controller Skills](../controller-skills/extending.md) for details.

!!! tip
    When setting up vatSys while providing coverage to RKA and MKA, it is recommended that you have seperate air displays open for MKA and RKA.
    <figure markdown>
    ![Coral Combined Airspace](img/coraltcusetup.png){ width="1000" }
    </figure>

## Coordination

### Enroute
#### Departures
Voiceless coordination is in place from MKA/RKA to ENR for aircraft:  

**Departing All Ports** - Assigned the lower of `F150` or `RFL`  

Any aircraft not meeting the above criteria must be prior coordinated to ENR.

!!! example
    <span class="hotline">**RKA** -> **KPL**</span>: "QFA114, with your concurrence, will be assigned F130, for my separation with ZYX"  
    <span class="hotline">**KPL** -> **RKA**</span>: "QFA114, concur F130"  

#### Arrivals
The Standard assignable level from INL(KPL) to RKA is `A070`, and assigned a STAR. All other aircraft must be prior coordinated.  
The Standard assignable level from KEN(SWY) to MKA is `A070`, and assigned a STAR. All other aircraft must be prior coordinated

### MK/RK ADC
#### Airspace
MK ADC is responsible for the Class D airspace in the MK CTR `SFC` to `A010`.

RK ADC is responsible for the Class D airspace in the RK CTR `SFC` to `A010`.

#### Auto Release
'Next' coordination is **not** required from MK/RK ADC for aircraft that are:   
  a) Departing from a runway nominated on the ATIS; and  
  b) Assigned the standard assignable level; and  
  c) Assigned a **Procedural** SID

!!! example
    <span class="hotline">**MK ADC** -> **MKA**</span>: "Next, ABC, runway 14"  
    <span class="hotline">**MKA** -> **MK ADC**</span>: "ABC, Heading 150 Visual, unrestricted"  
    <span class="hotline">**MK ADC** -> **MKA**</span>: "Heading 150 Visual unrestricted, ABC"

The TCU controller can suspend/resume Auto Release at any time, with the concurrence of **ADC**.

The Standard Assignable level from MK/RK ADC to MKA/RKA is the lower of `A060` or the `RFL`.

#### MK/RK SMC
The controller assuming responsibility of **SMC** shall give heads-up coordination to TCU controller prior to the issue of the following clearances:  

- VFR Departures  
- Aircraft using a runway not on the ATIS

#### Arrivals
COR TCU will coordinate all YBMK and YBRK arrivals to ADC prior to **5 mins** from the boundary. This coordination shall be as per [Standard Heads-up format](../../controller-skills/coordination/#heads-up), with the addition of:

- Runway, if other than duty runway  
- Approach type, unless specifically nominated on the ATIS  
- IFR Circuit joining instructions, if not on Straight-in instrument approach

!!! example
    <span class="hotline">**RKA** -> **RK ADC**</span>: "via ABVAS, DJU, for the VOR-A”  
    <span class="hotline">**RK ADC** -> **RKA**</span>: "DJU, VOR-A"