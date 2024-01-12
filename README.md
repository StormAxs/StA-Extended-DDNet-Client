[![DDraceNetwork](https://cdn.discordapp.com/attachments/1056897504211370004/1176966640504676486/gui_logo.png?ex=6570ca9a&is=655e559a&hm=0d179414b9c0859fe17bd1d34279119cb1145fc47f490c2f333c1b49b344cf76&)](https://ddnet.org) [![](https://github.com/ddnet/ddnet/workflows/Build/badge.svg)](https://github.com/ddnet/ddnet/actions?query=workflow%3ABuild+event%3Apush+branch%3Amaster) [![](https://codecov.io/gh/ddnet/ddnet/branch/master/graph/badge.svg)](https://codecov.io/gh/ddnet/ddnet/branch/master)

![StA](https://cdn.discordapp.com/attachments/1141459005395435692/1182843102864613446/gui_logo.png?ex=65862b7b&is=6573b67b&hm=dc7a2bd1b5b33cc503dbcbfff79c30fd5e36416eef959131be912637e712b0f2&)

### What is StA?

StA client is an extended version of the DDNet client that includes new ingame features, custom color and more
![FUTURES](https://cdn.discordapp.com/attachments/1056897504211370004/1182862820619059280/FEATURES.png?ex=65863dd8&is=6573c8d8&hm=c4c6dcb8fdde981a0c0f8d1cb7f04b47f64535a167f1f885371321bfe4712020&)

- ✅Auto login on specific DDNet and KoG Servers (GER10 for DDNet | GER3 for KoG)
- ✅Better Animation using LERP
- ✅Custom Console settings

  ![png](https://i.imgur.com/wGpbSo6.png)
- ![png](https://i.imgur.com/B0tQqm8.png)

- ✅Custom colors in the TAB Player View

  ![png](https://i.imgur.com/ccn2vA8.png)
- ✅PlayerAssets(Profiles from T-Client)
  ![png](https://i.imgur.com/agtBLGU.jpeg)
- ✅BindWheel allows to bind multiple commands and use them

  ![png](https://i.imgur.com/VZ0htwS.png)
  ![png](https://i.imgur.com/yUMwSMe.png)
  ![png](https://i.imgur.com/WP5ksYI.png)

- ✅Frozen Tee Display, allows to frozen/unfrozen teammates

  ![png](https://i.imgur.com/Ml3TyBZ.png)
  ![png](https://i.imgur.com/FoVW4Ho.png)

### ✅ Some old features that was removed from game

- ✅ Old freeze - bring back katana to tees 


- ✅ Custom StA Binds (more to come soon!)

 ![png](https://i.imgur.com/yxNsmd7.png)

![install](https://cdn.discordapp.com/attachments/1056897504211370004/1182862820161892403/INSTALL.png?ex=65863dd8&is=6573c8d8&hm=584ca3907f28a8c792267748108e4c8fcd78c530b4c3a9aa80b993c37c30aa73&)

Download the Client here: [Release](https://github.com/StormAxs/StA-Extended-DDNet-Client/releases)

![SourseCode](https://cdn.discordapp.com/attachments/1056897504211370004/1182861395306479766/SC.png?ex=65863c85&is=6573c785&hm=de8d52675f98e4be84eb1784734f8f950bbecea0acc63649b585a2be1c7c0b16&)
## If you wish to get the source code, you can do it by following these steps:
add me on [Discord](https://discordapp.com/users/479926515908214795) or join my [Discord-Server](https://discord.gg/MratBSWsMP) <br />
you can also just write me a DM: **stormaxd**

Telegram - @StormArq

# DOCUMENTATION ABOUT EXEC FILES
In client Setting->Controls you might see a keybinding type exec:DeepFly etc.

if you want them to work, open client folder and go to data->StA->ConfigDir. You can see some .cfg files in it, before make exactly bind in controls make sure that you have all keys are prepared  to bind.

For exaple we have a deepfly.cfg file, and i want to bind it for T key on my keyboard, so we are going on client files and going to data/StA/ConfigDir. Then opens file that we want to bind

bind <span style="color:red">**x**</span> "bind mouse1 \"+fire; +toggle cl_dummy_hammer 1 0\";cl_message_client_color green; echo Deep Fly ON; bind <span style="color:red">**x**</span>. \"bind mouse1 +fire; cl_dummy_hammer 0; cl_message_client_color red; echo Deep Fly OFF; exec StA/ConfigDir/deepfly.cfg\""

Overwrite all <span style="color:red">**x**</span> key to any you want to bind (my case is <span style="color:green">**T**</span> Key)























