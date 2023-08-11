# game-cfg

## CS:GO Setup
1. **Locate Your CS:GO Installation Folder**:
   - Open your Steam client and go to the Library.
   - Right-click on "Counter-Strike: Global Offensive" and select "Properties."
   - Go to the "Local Files" tab and click "Browse Local Files." This will open the installation folder.

2. **Create or Edit Your `autoexec.cfg` File**:
   - Inside the CS:GO installation folder, navigate to the "csgo" folder.
   - If you don't already have an `autoexec.cfg` file, create a new text document using a text editor like Notepad.
   - Add your desired commands and key bindings to this file.

3. **Save the `autoexec.cfg` File**:
   - After editing the file, save it.

4. **Add Launch Option**:
   - Right-click on "Counter-Strike: Global Offensive" in your Steam Library.
   - Select "Properties."
   - In the "General" tab, click on the "Set Launch Options" button.

5. **Specify Autoexec Execution**:
   - In the launch options field, add the following command:
     ```
     +exec autoexec.cfg
     ```
   - Click "OK" to save the launch options.

6. **Launch CS:GO**:
   - When you launch CS:GO from Steam, the game will automatically execute the commands and key bindings from your `autoexec.cfg` file.

7. **Verify Execution**:
   - While in-game, you can test whether your `autoexec.cfg` commands are working as intended. You should see the effects of the commands you've added.commands to ensure they're working as intended.
