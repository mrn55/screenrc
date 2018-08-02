# screenrc
my screenrc preferences 
<pre>
 $ cd ~
 $ git clone https://github.com/nbla/screenrc.git
 $ ln -s screenrc/.screenrc .screenrc
</pre>
the one-liner (same commands as above, just one one easy copy line):
<pre>
cd ~; git clone https://github.com/nbla/screenrc.git; ln -s screenrc/.screenrc .screenrc; echo "alias screenx='screen -RaAd -S x'" >> ~/.bashrc; source ~/.bashrc
</pre>
I also suggest adding the following line to your .bashrc to give you easy access to a named screen everytime you connect:
<pre>
echo "alias screenx='screen -RaAd -S x'" >> ~/.bashrc
</pre>
