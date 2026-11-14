# Apps on both macOS and Linux (from common-config.nix and common-home.nix).
# Install: brew bundle --file=Brewfile
# Then the OS file: Brewfile.macos or Brewfile.linux
# GUI apps install as casks on macOS and as Flatpaks on Linux.

# General
brew "btop"
brew "gh"
brew "kubectl"
cask "obsidian"
cask "localsend"
cask "zed"
cask "zoom"
cask "zen"
cask "font-fira-code-nerd-font"
brew "neovim"

# Shell (programs.fish, programs.starship)
brew "fish"
brew "starship"

# AI
cask "claude-code"
brew "rtk"
brew "openspec"

# Dev tools (programs.mise)
brew "mise"
brew "graphviz"
cask "android-platform-tools"

if OS.mac?
  brew "git"
  brew "wget"
  brew "cocoapods" # Flutter iOS simulation
  cask "utm"
  cask "iterm2"
  cask "affinity"
  cask "balenaetcher"
  cask "leader-key"
  cask "tailscale-app"
  cask "hermes-desktop"
  cask "docker-desktop"
  cask "sweet-home3d"
elsif OS.linux?
  # brew "tailscale" # services.tailscale; start tailscaled yourself
  cask "onlyoffice"
  flatpak "org.gnome.Podcasts"
  flatpak "org.videolan.VLC"
  flatpak "org.gnome.Geary"
  # Not installable with Homebrew or Flatpak. Get these from extensions.gnome.org:
  #   PaperWM, Tailscale QS, Dash to Dock
end
