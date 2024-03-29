<!-- Reference-style links to make tables & lists more readable -->
[Eaton-Info]: <https://tripplite.eaton.com/products/ethernet-cable-types>
[PCGamer-Info]: <https://www.pcgamer.com/what-are-the-differences-between-cat5-cat6-and-cat7-ethernet-cables/>
[CableMatters-CAT7]: https://www.cablematters.com/Blog/Networking/what-is-cat7-and-why-you-don-t-need-it
[PowerCert-Video]: <https://www.youtube.com/watch?v=_NX99ad2FUA>
[InfiniteCables-ConStd]: <https://www.infinitecables.com/products/rj45-1-piece-cat6-plug-for-round-cable-solid-or-stranded-8p-8c>
[InfiniteCables-ConInsert]: <https://www.infinitecables.com/products/rj45-cat6a-plug-w-insert-solid-or-stranded-8p-8c-pack-of-50>
[InfiniteCables-ConThru]: <https://www.infinitecables.com/products/rj45-cat5e-cat6-pass-through-plug-solid-or-stranded-8p-8c-pack-of-50>
[InfiniteCables-Crimp]: <https://www.infinitecables.com/products/professional-crimp-tool-for-modular-pass-through-plugs-rj45-strip-and-cut>
[InfiniteCables-Strip]: <https://www.infinitecables.com/products/adjustable-cable-jacket-strip-tool-for-networking-and-data-cable-cat3-cat5e-cat6-cat6a-cat7>
[VCELiNK-AmazonHome]: <https://www.amazon.ca/stores/page/65E06D4E-0D0B-4780-9022-EF7AA39D27A1>
[VCELiNK-PunchStand]: <https://www.amazon.ca/VCE-Keystone-Stripper-180Degree-Modular/dp/B07X24YZX1>
[VCELiNK-PunchTool]: <https://www.amazon.ca/VCELINK-Keystone-Terminal-Insertion-Stripper/dp/B08XK752YK>
[VCELiNK-Keystone]: <https://www.amazon.ca/stores/page/76F89957-8DA8-4230-91C8-5E17D49C24AA>
[VCELiNK-Connector101]: <https://www.vcelink.com/blogs/focus/rj45-connector-101>
[VCELiNK-ThruOrNo]: <https://www.vcelink.com/blogs/focus/pass-through-vs-non-pass-through-rj45-connector>
[Digiflex-CAT]: <https://digiflexcables.com/products/ldmx-cat>
[Radial-CAT]: <https://www.radialeng.com/product/catapult>
[Stellar-CAT]: <https://canada.newark.com/stellar-labs/24-16312/3-pin-male-xlr-to-rj45-dmx-adapter/dp/98Y0114>
[LINESO-CAT]: <https://www.amazon.ca/LINESO-3-5mm-Stereo-White-Extender/dp/B01HHO8382>

## Networking connectors
<!----------------------------------------------------------------------------->

# RJ-45 connectors/cables
The ubiquitous connector:
- XLR over CATx (typ. shielded): [Digiflex-CAT], [Radial-CAT], [Stellar-CAT]
- HDMI over CATx
- USB over CATx
- RCA/TRS over CATx: [LINESO-CAT]

Multiple "Categories":
- CAT5, CAT5e, CAT6, CAT6e, CAT7, CAT8, ..
- Basic introduction: \< [PCGamer-Info], 🎞️[PowerCert-Video] \>
- More detailed info \< [Eaton-Info], [CableMatters-CAT7] \>

Multiple connector types:
- [VCELiNK-Connector101]
- Shielded/unshielded
- 2-pronged contacts: Stranded wires only. 3-pronged contacts: Either Stranded or Solid conductors.
- CAT6+ RJ-45 connectors have more room for cable/jacket itself. Integrated cable clamp might be loose on CAT5 cables.
- 3 "Types": [standard][InfiniteCables-ConStd] / [pass-through][InfiniteCables-ConThru] / [with insert][InfiniteCables-ConInsert]
  <br>Tradeoffs/info: \< [VCELiNK-ThruOrNo] \>
- ⚠️Warning: Each connectors has its acceptable range of wire gauges/thickness.
  Compatibility appears to get more complicated in the CAT6 range and above (more variants?).

## RJ-45 tools & connectors:
- RJ-45 crimper ("pass-through" capable): \< [InfiniteCables-Crimp] \>
- Jacket stripper: \< [InfiniteCables-Strip] \>
  <br>NOTE: Jacket strippers can accidentally nick cables. Preferable to have an
  adjustable blade depth. [This one][InfiniteCables-Strip] has good control but
  has a large opening for typical CAT5 (must compensate for opening).
- VCELink Misc tools (good quality) \< [VCELiNK-AmazonHome] \>
  - Punch-down stand: \< [VCELiNK-PunchStand] \>
  - Punch-down tool: \< [VCELiNK-PunchTool] (not tried) \>
  - RJ-45 keystone jacks: \< [VCELiNK-Keystone] \>
    <br>==> CAT6: Higher quality. Backwards compatible with CAT5 (typical cabling)
