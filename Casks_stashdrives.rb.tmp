cask "stashdrives" do
  version "1.0.0"
  sha256 "4cd305626d5bd189f5ed25abb9ac9ab4c6060750d26e9b3c280cff27f7215249"

  url "https://stashdrives.com/releases/StashDrives-1.0.0-unsigned.dmg"
  name "StashDrives"
  desc "Reclaim disk space on your Mac"
  homepage "https://stashdrives.com"

  app "StashDrives.app"

  depends_on macos: ">= :sonoma"

  zap trash: [
    "~/.stashdrives",
    "~/Library/Application Support/StashDrives",
    "~/Library/Preferences/com.stashdrives.app.plist",
    "~/Library/Caches/com.stashdrives.app",
    "~/Library/Saved Application State/com.stashdrives.app.savedState",
  ]
end
