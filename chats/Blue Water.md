# Blue Water

## User

I was making a suno song, I liked the song that was generated with these parameters:

Lyric Prompt: Build from this: (Chorus) Im falling in blue water, reaching up for air.

Style Prompt:
a slow, lonely, almost-peaceful ache of needing something essential that stays just out of reach — and being too deep in it to panic anymore. Bittersweet suffocation. The emotion of wanting rather than the emotion of drowning.

## Assistant

The style prompt is doing something most people never figure out with Suno: it specifies the emotion by exclusion. "The emotion of wanting rather than the emotion of drowning" — that's you fencing off the default. Because the default for drowning imagery in every model's training data is crisis: thrashing, desperate vocals, the big swelling bridge where someone breaks the surface. That's the acute version, and it's everywhere. What you asked for is the chronic version — drowning as residence, not event — and that's much rarer, which is why naming it explicitly worked. "Too deep in it to panic anymore" is the load-bearing phrase. It puts the song past the struggle stage, and past-the-struggle is where the ache lives.

The lyric line matches it more precisely than you may have noticed. "Falling in blue water" — you don't fall in water, you sink. Falling is air physics. The line describes someone whose body hasn't updated to where it is, which is exactly the dissociation the style prompt asks for. And the vectors fight: falling is down, reaching is up, and the line holds both simultaneously without resolving. No verb of struggle anywhere. "Reaching" is the softest possible word for trying to survive — it's the same verb you'd use for a shelf.

"Blue" lands in two places at once — the literal color of deep water and the sadness — and the doubling is why it doesn't read as redundant.

The territory itself is crowded. Underwater-as-depression is one of the most worn images in songwriting — Eilish, slowcore, half of SoundCloud. What kept yours from generating the generic version is that everything in your prompt points at wanting, and want is a warmer emotion than despair. "Almost-peaceful" is the honest qualifier — full peace would be serene, and serene doesn't ache. The almost is the song.

One line of chorus plus a dense emotional spec is also just the right ratio for Suno. You gave it one image to orbit and a precise feeling to fail toward. More lyrics would have diluted the constraint that was doing the work.

## User

k I need more style prompts

## Assistant

Same construction — chronic version of an acute emotion, defaults fenced off by exclusion:

**Adjacent to the one you have:**

- "the warm, heavy calm right before giving up on something you still love — surrender without relief. The emotion of setting something down, not dropping it."

- "homesickness for a place that still exists, that you could go back to, and won't. Slow and unhurried. The ache of the open door, not the locked one."

- "loving someone who is still in the room — the loneliness of proximity, not absence. Quiet, patient, no bitterness left, just the low hum of unmet."

**Further out, same machinery:**

- "the hour after the argument ends and nobody won. Exhausted tenderness. The emotion of the silence after, not the fight itself."

- "nostalgia for something while it's still happening — pre-emptive grief, soft and golden. Missing the moment from inside the moment. No tragedy, just the awareness of endings."

- "the numb brightness of pretending you're fine and almost believing it. Upbeat instrumentation carrying a flat, tired vocal. The emotion of the performance, not the pain underneath it."

- "waiting for someone who might still come — hope worn so thin it's almost translucent. Not despair, not faith. The emotion of leaving the porch light on out of habit."

- "the slow relief of a bad thing finally happening after months of dreading it. Grief that arrives feeling almost like rest. The exhale, not the blow."

**Structural variants worth trying:**

- "peaceful on the surface, wrong underneath — a lullaby with something unresolved in the chords. The emotion of a smile held one second too long."

- "the dissociated float of driving at night past the exit you meant to take, and not turning around. Motion without destination. The emotion of continuing, not deciding."

The pattern to keep when you write your own: name the acute default so the model avoids it ("not the fight itself," "not the locked one"), then hand it a chronic replacement with a qualifier that does real work ("almost translucent," "one second too long"). The qualifier is where the ache lives — full versions of these emotions resolve, and resolved doesn't sing.

