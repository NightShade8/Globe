# Globe-Terminal-Simulation
A lightweight Bash script that streams an animated globe simulation in your terminal for a visually engaging experience.

## 🚀 Features

Fetches and displays the globe simulation using curl.

Smooth animation with controlled speed using the pv command for a cinematic effect.

## 🛠 Prerequisites Ensure you have the following installed:

`curl` (for fetching the animation file).

`pv` (for controlling playback speed).

You can install them using:

```
# Debian/Ubuntu
sudo apt install curl pv

# RHEL/CentOS
sudo yum install curl pv

# macOS
brew install curl pv
```

## 📌 Usage
Clone the repository and run the script:

```
git clone https://github.com/NighShade8/Globe-Terminal-Simulation.git
cd Globe-Terminal-Simulation
chmod +x globe_sim.sh  # Make the script executable
./globe_sim.sh
```

## ⚡ Alias for Quick Access 
To run the script from anywhere, create a shell alias. Add this line to your `~/.bashrc` or `~/.zshrc` file:

```
alias globesim="~/Globe-Terminal-Simulation/globe_sim.sh"
```
Then, reload your shell configuration:
```
# For Bash
source ~/.bashrc

# For Zsh
source ~/.zshrc
```
Now, you can start the globe simulation with a simple command:

```
globesim
```

## 🌟 Customizations
 Feel free to adjust the speed by modifying the -L value in the pv command within the script. You can also experiment with other vt100 animations for variety!
