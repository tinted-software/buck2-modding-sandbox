load("//minecraft_version.bzl", "minecraft_version")
load("//minecraft_assets.bzl", "minecraft_assets")

export_file(
    name = 'version_manifest_v2.json',
)

minecraft_version(
    name = "1.21.3",
    version_manifest = ":version_manifest_v2.json",
    requested_version = "1.21.3",
)

minecraft_assets(
    name = "1.21.3-assets",
    minecraft_version = ":1.21.3",
)
