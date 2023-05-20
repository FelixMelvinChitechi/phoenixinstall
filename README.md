# phoenixinstall

sudo apt install curl git 
git clone https://github.com/asdf-vm/asdf.git ~/.asdf
. $HOME/.asdf/asdf.sh
asdf plugin add erlang
asdf plugin add elixir
asdf list-all elixir  
asdf install elixir 1.13.0-otp-25
mix archive.install hex phx_new 1.6.0
mix phx.new hello         
cd hello 
code .  
mix phx.server 
