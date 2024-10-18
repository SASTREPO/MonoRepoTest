# MonoRepoTest

This repository consist from publicly available:
* https://github.com/bitcoin/bitcoin
* https://github.com/cocos2d/cocos2d-x
* https://github.com/OpenPrinting/cups
* https://github.com/electron/electron
* https://github.com/emscripten-core/emscripten
* https://github.com/envoyproxy/envoy
* https://github.com/google-ai-edge/mediapipe
* https://github.com/oatpp/oatpp
* https://github.com/redpanda-data/redpanda
* https://github.com/trustwallet/wallet-core

# Configuration
* export MEND_SAST_TIMEOUT_FILE=60
* export MEND_SAST_TIMEOUT_TOTAL=4320
* export MEND_SAST_TIMEOUT_LANGUAGE=4320

# Exclusions:
* envoy/third_party/android/ifaddrs-android.h
* emscripten/system/lib/libc/musl/src/passwd/getpwent.c
* emscripten/system/lib/libc/musl/src/passwd/getpw_r.c
* emscripten/system/lib/libc/musl/src/passwd/pwf.h
* redpanda/src/v/cloud_storage/async_manifest_view.cc
* emscripten/system/lib/libc/musl/src/passwd/getgr_r.c
* emscripten/system/lib/libc/musl/src/passwd/getgrent.c
