+++
title = 'Mac terminal'
date = 2023-12-02T10:43:42+05:30
tags = [ "Mac", "Technical", ]
+++


Let’s talk about mac terminal. So, generally Mac comes with basic and boring terminal(zsh).

For a long time I didn’t know the power we can leverage using zsh. I looked in to youtube for terminal setup found few amazing tutorials to make my terminal flexible as well as aesthetic.

Almost all of the tutorials explained the same thing:

- Installing Iterm2 and oh my zsh framework
- A powerlevel10k theme
- Configure .zshrc file to your own needs such as auto completions & few aliases….

Then I made my terminal mildly transparent to make it look more charming.

![Image](/images/s1.jpg)



So, since I’m addicted to aesthetics of my terminal I wanted learn vim so that I can stick with it while coding and jotting down ideas.

Initially it seemed worthless effort. But after few weeks of “trying and leaving”, one fine day I determined to learn vim. The basic idea here is you should be able to finish your entire time in vim without lifting your fingers on your keyboard. I wanted to list out the commands that I use, but it’s pretty useless, you can find better documentation [here](https://vim.rtorr.com/). 

Apart from using :vsp to vertically split screen to compare 2 files at the same time, I configured (aliased) few plugins that I use often.
To access nerdtree press F1, you can toggle using ctrl+w or you can also use mouse.
If you add #!/usr/bin/env python3 at the beginning of python file you can click F2 to run it or else you should run with :! command.

I recently need to download my telegram chat history. When I’ve downloaded it gave me all these html files. But I really don’t wanna store every file. I want one single html file with all the data. So run a python command to get me the names as I desired. Then I use cat command on my mac terminal to concatenate all the files.


{{< notice example>}} 

~ cat messages0.html messages.html messages2.html messages3.html messages4.html messages5.html messages6.html messages7.html messages8.html messages9.html messages10.html messages11.html messages12.html messages13.html messages14.html messages15.html messages16.html messages17.html messages18.html messages19.html messages20.html messages21.html messages22.html messages23.html messages24.html messages25.html messages26.html messages27.html messages28.html messages29.html messages30.html messages31.html messages32.html messages33.html messages34.html messages35.html messages36.html messages37.html messages38.html messages39.html messages40.html messages41.html messages42.html messages43.html messages44.html messages45.html messages46.html messages47.html messages48.html messages49.html messages50.html messages51.html messages52.html messages53.html messages54.html messages55.html messages56.html messages57.html messages58.html messages59.html messages60.html messages61.html messages62.html messages63.html messages64.html messages65.html messages66.html messages67.html messages68.html messages69.html messages70.html messages71.html messages72.html messages73.html messages74.html messages75.html messages76.html messages77.html messages78.html messages79.html messages80.html messages81.html messages82.html messages83.html messages84.html messages85.html messages86.html messages87.html messages88.html messages89.html messages90.html messages91.html messages92.html messages93.html messages94.html messages95.html messages96.html messages97.html messages98.html messages99.html messages100.html messages101.html messages102.html messages103.html messages104.html messages105.html messages106.html messages107.html messages108.html messages109.html messages110.html messages111.html messages112.html messages113.html messages114.html messages115.html messages116.html messages117.html messages118.html messages119.html messages120.html messages121.html messages122.html messages123.html messages124.html messages125.html messages126.html messages127.html messages128.html messages129.html messages130.html messages131.html messages132.html messages133.html messages134.html messages135.html messages136.html messages137.html messages138.html messages139.html > 2022.html

{{< /notice >}}

I know it is very basic thing that anyone could do without any proper coding knowledge. But I’m just saying you can’t search for better tool to combine 100s of html files at once.
