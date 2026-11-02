# Exact continuation prompt

AI-generated continuation instructions.

Continue the Pi4/original Numark NV project in brianbri6/mixxx-NVcontrollerpublic. Inspect status, diff, history and root CODEX_PROGRESS.md first. The restored v058 source under bitedj-nv comes from prior branch a6c18f4836f5c6937765c98db757e31d259077c4. Preserve its113 imported files and the byte-identical res/controllers mapping mirrors; preserve original factory EQ order and all existing Pi fixes. Read bitedj-nv/SOURCE_README.md and bitedj-nv/NEXT_TASK.md for build instructions and pending binary/hardware work. Do not mistake this for the Android app or claim the Pi native code has been ported to the current root Mixxx API.

The v0.5.8 source import is now published on main as820b40c46634220f31dedb77e0cc6bf0f2acfc02, based on fresh upstreambc49961fd3e5a46cd46588090c652a0d7ec44e18. The previous GitHub403 restriction is resolved. All113 source blob hashes and both controller copies match;78 Python and33 JavaScript tests pass. Source synchronization is complete. Do not reapply the old import patch. Check the latest root progress receipt and continue remaining installable-image recovery/hardware acceptance or explicitly requested new development. Preserve remote changes and fast-forward history; no upstream PR/issues or force-push.

Exact tests: cd bitedj-nv; node tests/test_controller.js; python3 -m unittest discover -s tests -v; sh -n runtime/launch.sh. Restore pinned vendor/bitedj at78074e05c8bf99ede6fedd755aa68bd222ba343c and run scripts/apply_native.py first for the native-browser source tests. Root git diff --check must pass except explicitly documented pre-existing trailing blank lines imported exactly for native provenance. Root README_NV.md explains layout. Keep audio/HDMI/native sources unchanged for the synchronization task.

End AI-generated continuation instructions.
