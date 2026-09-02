# CognitiveAssist Architecture

## High-level flow

1. **Sensing** — camera and wearable sensors collect environmental and user-context signals.
2. **Preprocessing** — raw sensor/media data is prepared for downstream analysis.
3. **Context analysis** — activity and contextual signals are identified.
4. **Memory representation** — relevant events can be represented as connected entities/events.
5. **Assistance** — the interface presents context-aware information to the user.

## Current implementation boundary

The current repository contains the frontend prototype and camera pin definitions. AI inference, complete sensor fusion, persistent episodic memory, and production wearable integration remain future implementation areas.
