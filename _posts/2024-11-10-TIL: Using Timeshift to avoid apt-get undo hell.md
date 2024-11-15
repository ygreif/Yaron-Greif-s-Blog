# TIL: Using Timeshift to avoid apt-get undo hell

*(tdlr: if you're going to do something complex with package managers use timeshift first)*

For every hour I spend actually programming, I spend god knows how much time finnagling development environments. It took a painful hour just to make sure Pytorch was picking up my gpu. Then one day I needed to upgrade my nvidia driver so I could run some other library I was trying out ([nougat](https://github.com/facebookresearch/nougat). 

I trusted my nifty pal ChatGPT with the commands needed for the upgrade. And poof, no upgraded nvidia driver, no nvidia driver at all. I was back to square one and had to spend another half hour restoring the previous configuration.

So when I needed to upgrade emacs I wanted to find a quick way to reset my latops settings if something went wrong. The tool for the job was *timeshift*. Timeshift is designd to backup system directories (like /usr, /bin, /etc) making it very easy to restore emacs if something went wrong.

Luckily, the upgrade went smoothly. But I'll update this blogpost if I ever use timeshift for real.
