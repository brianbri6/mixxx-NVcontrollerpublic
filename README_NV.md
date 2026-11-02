# Raspberry Pi4 / original Numark NV integration

AI-generated documentation at the repository owner's request.

Our complete v0.5.8 Pi source project is in **[bitedj-nv/](bitedj-nv/)**. Start with [SOURCE_README.md](bitedj-nv/SOURCE_README.md) for source/build/test instructions and [CODEX_PROGRESS.md](CODEX_PROGRESS.md) for this fork's import status.

The project includes controller mappings, native exporter and mixed-folder patch, LCD metadata/waveform/browser renderer, bounded display transport, FX/pad feedback, SD MUSIC support, tests, protocol evidence and reversible-update build tools. The controller copies in res/controllers match bitedj-nv/controller byte-for-byte.

The Pi native code applies to TeamDeckshark/bitedj commit78074e05c8bf99ede6fedd755aa68bd222ba343c. The surrounding fresh Mixxx fork retains its current upstream sources and build system. This import does not establish native LCD support in a build of that newer root Mixxx application; such a port requires separate API/build work.

Preserve the original factory EQ order in [NV_EQ_FACTORY_MAPPING.md](bitedj-nv/docs/NV_EQ_FACTORY_MAPPING.md), the mixed parent/subfolder navigation fix, scratch sensitivity, VU clearing, FX/browser controls, audio settings and the disabled HDMI waveforms used on the smooth Pi4 setup.

D.VIEW outgoing commands, artwork/overlays and remaining physical behavior require the evidence/tests listed in [NV_INTEGRATION_V058.md](bitedj-nv/docs/NV_INTEGRATION_V058.md). Source import supplies no new SD image or physical hardware test.

End AI-generated documentation.
