
#Raspberry Pi
Account Information:
1) user:   root
   passwd: metran123
2) user:   metran
   passwd: metran123

# How to run Compressor Application
    +) Option 1: Double click to file name "compressor.sh" , then click "excute"
    +) Option 2: Open terminal then type "./compressor.sh" Enter.

# How to update software:
#At the first time update:
#Open terminal:
   rm -rf Compressor compressor.sh compressor/
   rm -rf /home/metran/Compressor /home/metran/compressor.sh
   git clone https://github.com/Hoangvietcuong/Compressor.git 
   cd Compressor/
   cp -f compressor compressor.sh update.sh /home/metran/Desktop/
   
#In the next time update:
  Just double click in to file name "update.sh" and choose "excute"
