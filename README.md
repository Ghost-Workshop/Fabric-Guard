# Fabric Guard

Fabric Guard is a lightweight region-protection mod made specifically for dedicated Fabric servers. It allows server administrators to select areas of the world, turn them into protected regions, and control what players or entities can do inside those regions.

Using WorldEdit for area selection and familiar `/rg`-style commands for management, Fabric Guard provides a straightforward way to protect important locations without switching your server to a Bukkit- or Paper-based platform.

## What Does Fabric Guard Add?

Fabric Guard adds configurable regions to your server. Each region can have its own rules, allowing different parts of the same world to behave differently.

Region settings can be used to control:

- Player building
- Block breaking
- PvP combat
- Mob spawning
- Player access and interaction rules
- Greeting messages shown when entering a region
- Healing-related region settings
- Other behavior through configurable state, text, and number flags

These settings make it possible to protect an area without applying the same restrictions to the entire world.

## What Can It Be Used For?

Fabric Guard is useful for survival servers, SMPs, community servers, event servers, and other multiplayer environments where certain locations need additional protection.

For example, administrators can use Fabric Guard to:

- Protect a spawn area from griefing
- Prevent players from breaking blocks inside important builds
- Disable PvP in towns while allowing it elsewhere
- Create dedicated PvP or event zones
- Prevent mobs from spawning in selected locations
- Protect staff areas, shops, hubs, and community projects
- Display a custom message when players enter a region
- Configure areas with their own special rules

Instead of relying on one global ruleset, administrators can configure each region separately.

## How Does It Work?

Fabric Guard uses WorldEdit selections to define region boundaries.

A typical setup works like this:

1. Select an area using WorldEdit.
2. Use a Fabric Guard `/rg` command to define the region.
3. Configure the region's flags and behavior.
4. Manage or update the region whenever necessary.

Commands can be run by administrators in-game or directly through the server console. The familiar `/rg` command style is intended to make the mod approachable for administrators who have previously used region-management plugins.

## Why Use Fabric Guard?

Fabric Guard is designed for Fabric server owners who want focused region-protection features without moving their server to another mod loader or server platform.

It provides:

- Region protection designed specifically for Fabric
- WorldEdit-based region selection
- Familiar `/rg`-style commands
- Separate rules for different areas
- In-game administrative commands
- Full server-console command support
- Configurable state, text, and number-based flags
- Protection for spawns, towns, builds, arenas, and other important locations

The mod focuses on giving administrators practical control over their world while keeping region creation and management straightforward.

## Requirements

Fabric Guard requires **WorldEdit for Fabric**.

WorldEdit provides the selection tools used to mark the boundaries of each region. Install a WorldEdit version that is compatible with your Minecraft and Fabric versions.

Fabric Guard is intended for dedicated servers and currently supports Minecraft **1.20.1 through 1.20.6**.

## Disclaimer

Fabric Guard is an independent and unofficial Fabric mod inspired by region-protection concepts commonly associated with WorldGuard.

It is not affiliated with, endorsed by, or maintained by the official WorldGuard project.
