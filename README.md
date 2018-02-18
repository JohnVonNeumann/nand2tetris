# Nand2tetris files

* this'll probably just end up being a collection of hdl files ill end up writing on my way through Nand2tetris, got some notes ill keep in here as well. i'm just running symlinks from the project files so as i go each week ill add the weeks files and whatnot.

* made an edit to the strucutre so id have .tst files and .cmp files here as well and also in dirs effectively, figured itd get messy as the course went on and also that the course creators probably had a reason they set the dirs out how they did

## Tips
* Keep it symmetric, if you have inverse units, ie youve taken the NOT of say, a, so nota, dont put them on separate ends of the gates, keep them same end, ie, if you use them in an AND, put both of them at the a= or both of them at the b=, dont split, it will skew results.

* Type out the truth table yourself before going forward, it helps

* read the book high level descriptions of the chips, they help provide a better level of understanding rather than trying to simply brute force the answer, it may work at the start but as the amount of moving parts goes up, youll suffer. in particular, focus on the chip function provided, as it will ususally explain the options that can be output fairly cleanly

* I halfway expected there to be a cleaner syntax for building mutlibit buses to be fair, I was wondering why they called the implementations of them "tedious", now I know! At least my vim skills get better and I learn the implementation of the gates well too.

#### for future modules and symlinking them
> ln -fP ~/programs/nand2tetris/projects/01/* ~/code/learn/nand2tetris/01
