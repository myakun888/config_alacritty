# bismillah

ini berisi config untuk alacrity

file utama , `.alacritty.toml`
folder warna , berisi kode kode warna berdasar tema

alacritty adalah terminal emulator yang berfokus dengan kecepatan dan efisiensi

kekurangan nya
tidak bisa rendiring gambar, tidak ada default tab dan window
tapi untuk tab dan windows bisa kita combinasi dengan tmux

untuk shell terminal nya alacritty dapat dikombinasikan dengan berbagai terminal shell
seperti

- bash
- zsh
  dan lainya

secara default config alacrity berada pada path home dari user
`~/.alacritty.toml`

jadi jangan lupa buat simlink pada path
~/.alacritty.toml

contoh

```cmd
ln -l .alacrity.tom ~/.config/alacritty/alacritty.toml
```

karena pada path ~/.config/alacritty/alacritty.toml
di buat agar ada file git nya
