# Mac Playbook

How to get a macbook for development setup

## Manual Steps

* Ensure Apple's command line tools are installed:
xcode-select --install

* Run the following command to add Python 3 to your 
export PATH="$HOME/Library/Python/3.9/bin:/opt/homebrew/bin:$PATH"
sudo pip3 install --upgrade pip
pip3 install ansible

* Start Synchronization tasks:
    * Open Photos and make sure iCloud sync options are correct
    * Open Music, make sure computer is authorized, and set Library sync options
* Make sure you signed into App Store

## TODO
- [ ] get `mas` working
- [ ] Add npm installations? i.e. `mermaid-js/mermaid-cli`
