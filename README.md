# finger-to-key-data
Cubic Finger-to-Key Preference and Reachability

## Dataset
A user study was conducted to identify and measure the preferred and reachable key areas from the fingers when the users hold a cubic-shaped device in a diagonal position. The participants (N=22) voluntarily gave their informed consent that their anonymized data will be collected, published and used for research purposes.

![Alt text](img/position_diagonal.jpg?raw=true "Drawing of the diagonal position")

More information about the user study (participants, materials, procedure and results) are present on the paper `Supporting Mobility and Posture Diversity in Virtual Workspaces: Text Input with a Keycube`.

**The datasets are released for scientific use.**

## Details
Both preferences and reachability dataset are released in `comma-separated values` (CSV) format and include the `handedness` (self-reported) as well as hands measurements (`circumference`, `length` and `span` in millimeters) of the participants.

![Alt text](img/hand_measurement.png?raw=true "Drawings of the hand measurement process")

**Refer to the figures of the paper to know the codes of the keys (R1 to Y16).**

### Preferences
[preferences.csv](preferences.csv)

Preferred finger for each key (80).
Code `1` to `10` are mapped to the little finger from the left hand to the little finger of the right hand.

![Alt text](img/finger_preference_code.png?raw=true "Drawing of the finger preference code")

### Reachability
[reachability.csv](reachability.csv)

Reachability score of each finger to each key (10 x 80).
Each finger is coded with the initial of the corresponding hand followed by that of the finger (for example, `LT` for left thumb).
Reachability score:

0. unreachable
1. reachable with effort
2. easily reachable

![Alt text](img/finger_reachability_code.png?raw=true "Drawing of the finger reachability code")

## Contact
For questions and further information, please contact:

- **Damien Brun**, 
damien.brun (at) ulapland.fi
