# unused

```
tlt: tap_layer_toggle {
            compatible = "zmk,behavior-hold-tap";
            label = "TAP_LAYER_TOGGLE";
            #binding-cells = <2>;
            tapping-term-ms = <150>;
            quick_tap_ms = <125>;
            flavor = "tap-preferred";
            retro-tap; // tap beahavior is triggered if no other key is pressed
            bindings = <&kp>, <&to>;
        };
        hm: homerow_mods {
            compatible = "zmk,behavior-hold-tap";
            label = "HOMEROW_MODS";
            #binding-cells = <2>;
            tapping-term-ms = <200>;
            quick_tap_ms = <0>;
            flavor = "tap-preferred";
            bindings = <&kp>, <&kp>;
        };
        hs: homerow_shifts {
            compatible = "zmk,behavior-hold-tap";
            label = "HOMEROW_SHIFTS";
            #binding-cells = <2>;
            tapping-term-ms = <150>;
            quick_tap_ms = <0>;
            flavor = "balanced";
            bindings = <&kp>, <&kp>;
        };
        tl: taplayer {
            compatible = "zmk,behavior-hold-tap";
            label = "TAP_LAYER";
            #binding-cells = <2>;
            tapping-term-ms = <150>;
            quick_tap_ms = <0>;
            flavor = "balanced";
            bindings = <&kp>, <&to>;
        };
        tln: taplayernone {
            compatible = "zmk,behavior-hold-tap";
            label = "TAP_LAYER_NONE";
            #binding-cells = <2>;
            tapping-term-ms = <150>;
            quick_tap_ms = <0>;
            flavor = "balanced";
            bindings = <&none>, <&to>;
        };
	    td: tapdance {
            compatible = "zmk,behavior-hold-tap";
            label = "TAP_DANCE";
            #binding-cells = <2>;
            tapping-term-ms = <150>;
            quick_tap_ms = <0>;
            flavor = "tap-preferred";
            bindings = <&kp>, <&kp>;
        };
	    bl: layertap {
            compatible = "zmk,behavior-hold-tap";
            label = "LAYERTAP";
            #binding-cells = <2>;
            tapping-term-ms = <150>;
            quick_tap_ms = <0>;
            flavor = "tap-preferred";
            bindings = <&to>, <&kp>;
        };
```
