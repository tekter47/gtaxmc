# Mod Log

- 2026-10-10: Elytra flight now starts armed in user-steering mode. Space launches directly without requiring the hidden director `armdrive` command; the director command remains available for custom launch settings.
- 2026-10-10: Elytra ground safety probes from above the host player and catches a player already below the streamed surface. Ender-pearl teleports are emitted only after Minecraft accepts them and reset the host's in-flight position sample to prevent a snap-back.
- 2026-10-10: Flight now requires an actually equipped Elytra and a double Space tap; setup supplies an Elytra to inventory instead of equipping it automatically. Sword clicks explicitly swing the Minecraft arm, damage nearby GTA peds/cars, and gain extra damage/knockback while the GTA player is falling.
- Verification pending: run the Windows MSVC/Java 25 workflow, then test wearing/not wearing Elytra, single/double Space, sword swing/impact, and falling critical hits in Story Mode.
- Verification pending: compile the ASI and Fabric JAR in the Windows MSVC/Java 25 workflow, then test landing and ender pearls in GTA V Story Mode.
