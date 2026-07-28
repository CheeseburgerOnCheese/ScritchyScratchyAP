##### Credit to the Slimipelago text file for helping me to figure it out and explaining Protontricks that was already all setup for me.

# Installing Protontricks (not needed for SteamOS/Bazzite and not tested, but should work)

Open your terminal and write this command: `sudo apt install protontricks`

If you are using another distribution of Linux like Fedora or Arch, you'll need to use your distribution's package manager. For Fedora it should be `sudo dnf install protontricks` and for Arch `yay -S protontricks`.

# Use Steam Play (yes, I did take it from Slimipelago since it's the same)

Steam Play is what allows Windows games to run on Linux. You need to enable it globally so that all your games can use Proton.

Open Steam and click on Steam in the top left corner. From the dropdown menu, select Settings. In the Settings window, look for the Compatibility section in the left sidebar and click on it.

You'll see a checkbox that says "Enable Steam Play for all other titles". Check this box. Below that, there's a dropdown menu where you can select which version of Proton to use. Choose either `Proton Experimental` or the latest numbered version like `Proton 9.0`. `Proton Experimental` usually has the newest features and fixes.

Click OK to save your changes. Steam will ask you to restart. Go ahead and fully close Steam and then open it again.

# Setting up Scritchy Scratchy to use Protontricks

Even though you activated Proton globally, you'll want to make sure it boots on Proton.

On Steam, either right-click or press the gear in Scritchy Scratchy and select Properties. From there you should be able to get on the Compatibility Tab and make it use Proton (I recommend `Proton Experimental` or `Proton 9.0`).

# Installing the AP mod

Install `BepInEx-Unity.Mono-win-x64-6.0.0-be.755+3fab71a.zip` (yes, the Windows one) and place its content inside the Scritchy Scratchy game folder (...steamapps/common/Scritchy Scratchy).

Extract a release's Scritchy Scratchy AP zip folder into it (not the `.apworld`) and Overwrite/Write Into all files when prompted.

Lastly, go back to the Scritchy Scratchy Properties (in Steam) and add this line `WINEDLLOVERRIDES="winhttp.dll=n,b %command%` in the Launch Options box.

# End

If you have any more questions, feel free to ask in the [discord channel](https://discord.com/channels/731205301247803413/1490574506337505385) (and anything wrong/unexplained in this text is on the fault of @CoCoColin12).

Thanks again for the Slimipelago text file for explaining Protontricks and the BepInEx Linux setup guide.
