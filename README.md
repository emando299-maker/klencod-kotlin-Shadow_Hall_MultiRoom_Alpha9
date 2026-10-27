# Shadow Hall - Alpha 8

Android Kotlin/OpenGL ES 2.0 prototype. Import the `ShadowHallKotlin` project into KlencodIDE.

## Alpha 7 update
- Adds short audio cues when the danger status changes to nearby/very nearby.
- Repeats a restrained warning beep while the monster is very close, with an 1.8-second cooldown.
- Adds a separate short cue while the monster is actively chasing the player, with a 3.5-second cooldown.
- Existing two-finger movement/look controls, sprint button, hiding, flashlight, keys, doors and enemy AI are preserved.

Audio cues use Android `ToneGenerator` tones; they are simple prototype cues, not recorded footsteps or spatial 3D audio.

## Build note
This source archive has not been built or run in KlencodIDE during this update. Please build on-device and share the complete error text or screenshot if Gradle/Kotlin reports a problem.


## Alpha 8 update
- Adds short generated WAV footstep sounds while the player moves; running steps are faster and louder than walking steps.
- Adds a short creaking-door/interaction sound on the Interact button.
- Uses a short suspense sting during an active chase, while retaining the existing proximity warning tones.
- Audio is lightweight and uses bundled mono WAV files under `app/src/main/res/raw`.

## Build note
This source archive has not been built or run in KlencodIDE during this update. Please build on-device and share the complete error text or screenshot if Gradle/Kotlin reports a problem.

## Alpha 9 update
- Interior storage/side-room doors now require at least one key, and the inner rusty lock requires two keys.
- Hiding gives a distinct Arabic location label (under the bed, inside the wardrobe, or behind furniture); leaving the hiding spot resets discovery progress.
- Monster chase speed increases slightly as keys are collected, adding adaptive pressure without expensive pathfinding.
- Adds a very subtle camera shake when the monster is close and a small red/green scene tint for loss/escape feedback.
- The multi-room layout, existing three-key escape gate, fuse puzzle, flashlight battery, touch movement/look, and sound assets remain in the project.

## Alpha 9 build status
- Source archive and ZIP integrity were checked in this environment.
- Android Gradle build and on-device gameplay were **not** run here. Build in KlencodIDE before replacing your working copy.
