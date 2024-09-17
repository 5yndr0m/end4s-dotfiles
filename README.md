<div align="center">
    <h1>end_4's Hyprland dotfiles with some tweaks.</h1>
    <h3>by me ofc. This is WIP btw</h3>
</div>

<div align="center">
    <h2>• overview •</h2>
    <h3>what's the difference between this fork and source?</h3>
</div>

 #### I only changed few minor things that I prefer having.

 - Changing to binaries instead of building from source
   - according to [wiki](https://end-4.github.io/dots-hyprland-wiki/en/i-i/05faq) building from source can help to mitigate some issues that "might" occur.
   - But... I want my system to be reliable; at least a bit. No one needs a computer that goes nuclear after a simple update. right? 
   - Not every thing is replaced as of now. There are some dependencies which can only be found on AUR as -git. So it should work fine for long-term. I will how ever look into others too.

 - Changing the theme to fit some oddball displays - WXGA - to be specific
   - to be specific my laptop and monitor, both have WXGA displays:
     - 1366x768 60Hz 14" 110.4 PPI 16:10 for laptop
     - 1366x768 60Hz 16" 80 something PPI for external monitor
   - If you have same type of displays and if you use the default ags theme provided, you might find some elements are not exactly fit to your screen.
   - Elements I had issues with are - both side bars, cheatsheet and Everything looks pretty big compared to other things in display.
   - What I did ? : I add a scale_factor variable to all the values that affects height and width in the `.config/ags/scss/main.scss` and provide a value for that in the `main.scss` file.
   - What does it do ? : exactly what it says. It is a scale variable that can used to scale down or up the default config. In my case I downscale the defaults to 0.75 of its original size, which perfectly fit my screens.

### !! there might be easy way to do this other than this very smooth brain approach. I'm not sure wether using hyprland scale same can be achieved or not. But its worth a shot?? Will look in to that too.

<div align="center">
    <h2>• screenshots •</h2>
    <h3></h3>
</div>

will be added soon. <br>
for not look at the [here](https://github.com/end-4/dots-hyprland) 

<div align="center">
    <h2>• thank you •</h2>
    <h3></h3>
</div>

 - [end4](https://github.com/end-4/dots-hyprland) for making an awesome theme
 - [@clsty](https://github.com/clsty) for making an actually good install script + many other stuff that I neglect
 - [@midn8hustlr](https://github.com/midn8hustlr) for greatly improving the color generation system
 - AGS: [Aylur's config](https://github.com/Aylur/dotfiles), [kotontrion's config](https://github.com/kotontrion/dotfiles)
 - EWW: [fufexan's config](https://github.com/fufexan/dotfiles) (he thanks more people there btw)
 - AI bots for providing useful examples
 - Open source contributors for their software and ricers for their insipration (would be a too long list to put here!)

<div align="center">
    <h2>• inspirations •</h2>
    <h3></h3>
</div>

