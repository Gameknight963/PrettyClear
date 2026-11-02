## PrettyClear
modified version of [Translucence](https://github.com/CapnKitten/Translucence) that looks less gamery

you may want to use the included remove-titlebar.css theme to remove 
discord's custom titlebar if you intend on using the native one.

if you want the window to be resizable with native titlebar on, consider installing my windhawk mod
<br>
[Discord Transparency Resize Fix](https://windhawk.net/mods/resizable-discord)

shown with [DWMBlurGlass](https://github.com/Maplespe/DWMBlurGlass) and [Aero11](https://github.com/Sand216/Aero11) msstyle

### screenshots

<img width="964" height="633" alt="image" src="https://github.com/user-attachments/assets/916da8b6-d906-465a-962c-ca28a3eb64d4" />

<img width="712" height="386" alt="image" src="https://github.com/user-attachments/assets/7b6ee3c6-93b5-477a-828b-e0e9239624a1" />

<img width="249" height="480" alt="image" src="https://github.com/user-attachments/assets/f2841b27-f8de-4288-97b6-c53bff70be79" />

(free promo for msz lol)

## important

all browsers seem to have this composition issue when backdrop filter blur
is used on a transparent background. ~~not much i can do about it~~ actually there is something I can do about it! install [bedrock](https://github.com/Gameknight963/Bedrock) and use the Backdrop Blur Fix plugin

<img width="356" height="86" alt="image" src="https://github.com/user-attachments/assets/856b8e20-462c-438b-8613-6e6ab051bb0d" />

~~## why is the commit history screwed??
I learned too late that you're supposed to use a noreply on github. Why doesn't anyone tell you ts~~
nevermind its fixed now thank you codex

## build

```
sass --no-source-map --style=expanded main.scss PrettyClear.theme.css
```