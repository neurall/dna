https://neurall.github.io/dna/
 I was curious how dna actually looks like as a raw data.
 
 So I thrown together simple short easily hackable DNA visualiser that downloads and shows in realtime line by line chromosome 1
 where all of 4 letters have unique 4 colors.
 
 I am mostly curious about what will I actually see.
 
 Will I see discern a patterns repetittions?
 
 Will I see color differences between different parts of DNA/chromosomes?
 
 Given how human eye and brain with it's incredible ability to spot patterns corelations repetitionshuman induction etc.
 
And Indeed ;)

So far top of chromosome 1 is reddish bottom greenish ;)
 
This is the most fascinating data I had ever chance to see.
Considering I am looking at source code of pretty much everything alive on earth.

As for fitting to gpu memory for latter comparsion shenanigans that I am definitely planing ;). 

What is super cool, was that each from 26 human chromosomes has around 60 m  letters but since they are in just 4 letter alphabet "acgt", you can store it to texture with just 2 bits per letter and decode it back via simple pixel shader thus you can sample and draw 16x4 rgb pixels from4x4 texture which this sample does ;D. sad thing is float precision uv starts flling apart at 16k wide textured triangle and there is visible jumping seam which was unexpected ;(

In next step I will try to simulate drawing folded dna while still showing colors. 

Will some colors aggregate on outside ?

I.E consider painting red circle on spaghety ball and then strighten spaghety up.

You will not see a circle anymore just bunch of random red stripes. 

So lets curle dna back and then observe whether we will see patterns with naked eye ;D

O boy this is exciting ;D
