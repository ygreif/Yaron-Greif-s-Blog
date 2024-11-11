# TIL: Using Timeshift to avoid apt-get undo hell

(short tdlr use timeshift).

For every hour I spend actually programming, I spend god knows how much time finnagling development environments. It took me ages to setup my Ubuntu environment to have PyTorch use my nvidia drivers GPU. Luckily, whatever setting I lucked into worked well enough that I didn't have to think about it again.

That is until I needed to upgrade my nvidia driver so I could run some other library I was trying out ([nougat](https://github.com/facebookresearch/nougat). And of course I trusted my nifty pal ChatGPT with the commands needed for the upgrade. And poof, no upgraded nvidia driver, no nvidia driver at all. I was back to square one and had to spend another half hour restoring the previous configuration.

So when I needed to upgrade emacs I wanted to find a quick way to reset my latops settings if something went wrong. The tool for the job was *timeshift*. Timeshift is designd to backup system directories (like /usr, /bin, /etc) making it very easy to restore emacs if something went wrong.

Luckily, the upgrade went smoothly. But I'll update this blogpost if I ever use timeshift for real.
