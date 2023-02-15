# ridgewoodhs

#### Documentation on the RHS-TV and RHS Recording Studio.

# Introduction

Welcome to the RHS Recording and TV Studio. The following is an attempt to cover the most common functions with the equipment in the control room. Additional questions can be directed to:

## Behringer X32

### Scenes

Both RHS-TV and the RHS Recording Studio use the X32 as their mixer/routing console. By utilizing "scenes", all the parameters of the console can be recalled to the correct settings for each use case. The following is a quick description of each scene. 

#### Recalling a Scene

Press the small view button in the `SCENES` block on the console below the talk back section. The available scenes will be displayed on the console. Recalling a scene is done by using the left most select knob to browse to the desired scene, pressing that knob, and then pressing the `YES` on the `PAGE SELECT` (located on the bottom right of LCD unit).

#### Existing Scenes

```
music prod - originally the scene for having a recording session (overwritten by MAX)
TV PROD - used by RHS-TV for shoots, LOCAL INPUTS ACTIVE
IN STUDIO REC - ?
INSTUDIO2 - idk the difference, AES50A INPUTS ACTIVE
MAROON&WHITE - AES50B INPUTS ACTIVE
EDIT - created for RHS-TV students to have easy control over the two sets of speakers, and configured for
immediate playback from COMPUTER PLAYBACK
```

### I/O 

#### Analog

##### Input

```markdown
CH 1: RHS-TV Stage Box 1
CH 2: RHS-TV Stage Box 2
CH 3: RHS-TV Stage Box 3
CH 4: RHS-TV Stage Box 4
CH 5: RHS-TV Stage Box 5
CH 6: RHS-TV Stage Box 6
CH 7: RHS-TV Stage Box 7

...

CH 11: AJA RECORDER return L
CH 12: AJA RECORDER return R
CH 13: MUSIC PLAYBACK (mono)

...

CH 31: VOX BOX XLR 1
CH 32: VOX BOX XLR 2
AUX 1: L from COMPUTER PLAYBACK
AUX 2: R from COMPUTER PLAYBACK
```

##### Output

```markdown
AS OF 2/15/23 XLR OUTPUT SECTION FAILURE
CH 14: TB 1 (not active)
CH 15: TB 2 (not active)

AUX 1: VOX BOX TRS 1
AUX 2: VOX BOX TRS 2
AUX 3: TB 1
AUX 4: TB 2
```

#### Digital

```markdown
AES50A: S32 Stage Box
AES50B: S8 Stage Box (library drop)
EBU: TO RHS-TV (recorder)
```

---

### A Note On Routing:

The X32 utilizes two different I/O sources (either `LOCAL` or `AES50`) depending on the configuration. The current routing configuration can be viewed from the `ROUTING` page, accessible by the buttons next to the LCD screen. 

Routing works in groups of 8, with the added ability to make a custom routings to overcome that limitation. 

Only 32 channels can be connected to the console at one time, whether it be analog digital.

### Typical Setup

The AES50(A/B) connection(s) are utilized when using a remote digital stage box.  

## Computer Playback

### General Info

The playback computer is powered by a Intel NUC. Both playback and editing are possible.
