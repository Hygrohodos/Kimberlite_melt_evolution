# Kimberlite melt evolution

Fractional crystallisation (FC) and digestion-fractional crystallisation (DFC) of olivine for the kimberlite melt, from source to surface.

The calculation is in `olivine-fc-dfc.ts`. It is the browser port of the SD2 spreadsheet (Greene et al.).

- `runFc` traces MgO–FeO–Ni and the equilibrium olivine along an FC path (Matzen DNi, T in °C).
- `runDfc` / `runDfcFromFc` grow an olivine rim while assimilating orthopyroxene (Pilbeam-style grain growth + AFC).
- `PROTO_PARENTAL_DEFAULTS` is the reduced protokimberlite starting melt that feeds the DFC sheet.
- `meltFromOlivineMargin` rebuilds the DFC starting melt from the FC olivine at a chosen F.

Used by the Hygrohodos workshop (Kimberlite → Fractional Crystallization / Digestion-Fractional Crystallization).
