# merge_tiff
short notebook to merge tiffs from s2p run


### First quickly set up environment

Open terminal in a directory where you want to have the scripts saved and run:

```
conda create --name merge_tiff
conda activate merge_tiff
git clone https://github.com/juremaj/merge_tiff
conda install -c conda-forge jupyter
pip install tifftools
```

Now the environment is set up you can just run jupyter from the `merge_tiff` folder, open the `merge_tiff.npynb` notebook and follow the instructions there:

```
cd /path/on/your/pc/to/merge_tiff 
jupyter
```

### If already 'installed'

Just run:

```
conda activate merge_tiff
cd /path/on/your/pc/to/merge_tiff
jupyter
```

And then follow instructions in the notebook `merge_tiff.npynb`
