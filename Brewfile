# To install: brew bundle --file=Brewfile

## TERMINAL
cask "iterm2" if OS.mac?

## DOT FILES
brew "chezmoi"

## BROWSER
cask "brave-browser" if OS.mac?
flatpak "com.brave.Browser" if OS.linux?

## LAUNCHER
cask "leader-key" if OS.mac?

## NOTES
cask "obsidian" if OS.mac?
flatpak "md.obsidian.Obsidian" if OS.linux?

## SHARING
cask "localsend" if OS.mac?
flatpak "org.localsend.localsend_app" if OS.linux?

## CODE EDITOR
cask "zed"
brew "neovim"

## VIDEO CONFERENCE
cask "zoom" if OS.mac?
flatpak "us.zoom.Zoom" if OS.linux?

## FONTS
cask "font-fira-code-nerd-font"

## SHELL
brew "fish"
brew "starship"

## AI
cask "claude-code"
brew "rtk"
brew "openspec"
cask "hermes-desktop" if OS.mac?

## DEV TOOLS
brew "mise"
# brew "graphviz"
cask "android-platform-tools"

## VIDEO PLAYER
cask "vlc" if OS.mac?
flatpak "org.videolan.VLC" if OS.linux?

## OFFICE SUITE
cask "onlyoffice" if OS.linux?

## EMAIL
flatpak "org.gnome.Geary" if OS.linux?

## PODCASTS
flatpak "org.gnome.Podcasts" if OS.linux?

## VPN
cask "tailscale-app" if OS.mac?
brew "tailscale" if OS.linux? # add Tailscale QS for UI

## VIRTUALIZATION
cask "utm" if OS.mac?

## ISO FLASHER
cask "balenaetcher" if OS.mac?

## IMAGE EDITOR
cask "affinity" if OS.mac?

## 3D MODELING
cask "sweet-home3d" if OS.mac?
flatpak "com.sweethome3d.Sweethome3d" if OS.linux?

## OTHER TOOLS
brew "btop"
brew "gh"
brew "kubectl"

if OS.mac?
  brew "git"
  brew "wget"
  brew "cocoapods" # Flutter iOS simulation
  cask "docker-desktop"
end
