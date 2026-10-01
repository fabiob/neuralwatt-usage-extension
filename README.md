# Neuralwatt Usage Gnome Extension
![GNOME Shell 46+](https://img.shields.io/badge/GNOME%20Shell-46%2B-blue)   

A Gnome shell extension that displays your Neuralwatt usage and account stats in the top panel.

<img src="assets/screen.png" width="440"  alt="Screenshot of extension panel"/>

## Important Note                                                                                                                                                                                                
                                                                                                                                                                                                                   
I am not affiliated with Neuralwatt in any way, I just really needed a way to see my usage, and I use Gnome.... so....

## Features                                                                                                                                                                                                      
                                                                                                                                                                                                                   
- **Near-realtime** usage display
- **Account stats** including total usage for the subscription period, total usage for current day, and available credits
- **Pacing indicator** on the usage bar showing how far through the billing cycle you are, with under/over pace status — just like the web dashboard
- **Configurable refresh rate** to adjust how often the usage is updated
- **Multiple accounts** support for users with multiple Neuralwatt accounts
                                                                                                                                                                                                            
## Requirements                                                                                                                                                                                                  
                                                                                                                                                                                                                   
- GNOME Shell 46 or later

## Installation                                                                                                                                                                                                  

Manual:

```bash
git clone https://github.com/nickgermaine/neuralwatt-usage-extension
cp -r neuralwatt-usage-extension ~/.local/share/gnome-shell/extensions/neuralwatt-usage-extension@nickgermaine.com 
cd ~/.local/share/gnome-shell/extensions/neuralwatt-usage-extension@nickgermaine.com/schemas                                                                                                                                        
glib-compile-schemas .

## Restart Gnome Shell by logging out and logging back in
## Then enable the extension
```
